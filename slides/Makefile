# ── Usage ─────────────────────────────────────────────────────────────────────
#   make lec=lec01-overview        # compile one lecture
#   make all                       # compile all lectures
#   make clean lec=lec01-overview  # clean one lecture
#   make cleanall                  # clean all

LECTURES := $(wildcard */main.tex)
DIRS     := $(patsubst %/main.tex,%,$(LECTURES))

.PHONY: all clean cleanall

# Compile a single lecture: make lec=lec01-overview
ifdef lec
build:
	cd $(lec) && latexmk -pdf -interaction=nonstopmode main.tex
	@echo "✓ PDF: slides/$(lec)/main.pdf"

clean:
	cd $(lec) && latexmk -C main.tex
	cd $(lec) && rm -f *.nav *.snm *.vrb
else
build:
	@echo "Usage: make lec=<lecture-dir>  (e.g. make lec=lec01-overview)"
endif

# Compile all lectures
all:
	@for dir in $(DIRS); do \
		echo "── Building $$dir ──"; \
		(cd $$dir && latexmk -pdf -interaction=nonstopmode main.tex); \
	done

cleanall:
	@for dir in $(DIRS); do \
		(cd $$dir && latexmk -C main.tex && rm -f *.nav *.snm *.vrb); \
	done
