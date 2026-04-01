---
layout: page
title: Project
permalink: /project/
---

Please see a sampled project report from [here](https://ml-graph.github.io/winter-2025/static_files/Federated_Learning_for_Document_Classification.pdf) 

The project may be completed either individually or as a team; both approaches are acceptable. For team-based projects, only one team member should submit the final report and clearly specify all contributing teammates. Bonus Points will apply if you consider doing projects in the following fields with (*) or any domain beyond the following:


### 1. Background and Problem Formulation - 10%
- **Background - 5%**: 
  - What is the general background of the problem you are working on?
    - I want to build a generative AI system that can produce realistic and diverse images of natural scenes conditioned on text descriptions.
- **Problem Formulation - 5%**: 
  - Under the general topic, what specific problem is your project addressing?
    - I want to develop a diffusion-based generative model that takes a text prompt as input and outputs a high-fidelity image, targeting a specific domain such as medical imaging or satellite imagery.

### 2. Data Mining and Machine Learning Stage - 40%
- **Data Collection and Store - 10%**: 
  - What data are you looking to kick off your project? How do you collect them? What data structure do you use to represent them?
    - I collect image-text paired data from a publicly available dataset (e.g., LAION, MS-COCO, or a domain-specific dataset from Hugging Face), and I store images as tensors with their corresponding text captions in a structured dataset class.
- **Data Mining - 10%**: 
  - What kind of data analysis do you need to do and why? 
    - I need to analyze the distribution of the image data and the alignment between text and image pairs, since understanding this helps me design a better conditioning mechanism for the generative model.
  - How do you do it?
    - I compute CLIP similarity scores between image-text pairs to quantify alignment quality, and visualize the latent space using t-SNE to understand how different categories cluster in the embedding space.
  - What kind of pattern do you find? How do you present your findings/analysis?
    - I find that certain text descriptors (e.g., "photorealistic", "aerial view") strongly cluster the latent representations. I present findings using similarity histograms and 2D embedding plots.
- **Machine Learning Model Design - 20%**: 
  - Based on your targeted problem, what kind of generative model do you want to build and why?
    - I want to build a latent diffusion model conditioned on text embeddings to leverage the discovered structure in the CLIP latent space.
  - How do you build your model, and what is the key design?
    - The key design is a U-Net denoising network operating in latent space, with cross-attention layers to incorporate text conditioning; I use the Diffusers library and fine-tune a pretrained checkpoint on my target domain.
  - What kind of experiments do you run to evaluate your model?
    - I evaluate generation quality using FID score and CLIP similarity on a held-out test set, and conduct ablations on the number of diffusion steps and classifier-free guidance scale.

### 3. Demo - 40%
- **Demo - 40%**:
  - Build a runnable demonstration of your project — this can be a Jupyter notebook walkthrough, a Gradio/Streamlit web app, or a short recorded screen-capture video (≤ 3 min).
  - The demo should show your model working end-to-end on at least one real example: provide an input, run your model, and display or visualise the output.
  - Example: a text-conditioned image generator where a user types a prompt and the generated image appears in the app, with side-by-side comparison against a baseline.

### 4. Discussion - 10%
- **Discussion - 5%**: 
  - Any further discussion on your exploration of this project?
    - I compare the fine-tuned model against the base pretrained model and find a clear improvement in domain-specific fidelity while maintaining diversity.
  - Any further thinking and interesting questions you can ask about this project?
    - How does the model behave when given out-of-distribution prompts? Could the generative model be used adversarially to synthesize misleading domain imagery (e.g., fake satellite data)?
- **Feeling of this class - 5%**: 
  - Feeling of this class.


