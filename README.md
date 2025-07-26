# 🎨 PRODiGY_GA_02 – Text-to-Image Generation with Diffusion Models

This project explores **text-to-image generation** using state-of-the-art **pretrained diffusion models** such as **Stable Diffusion**. Given a textual prompt, the model generates high-quality, realistic images that reflect the semantic content of the input text.

---

## 🎯 Project Objectives

- Understand the principles of diffusion models for generative tasks.
- Use pre-trained text-to-image models (like Stable Diffusion) to generate images from text prompts.
- Experiment with prompt engineering to optimize image outputs.
- Build a pipeline to input prompts and save generated images.

---

## 🧰 Tech Stack & Tools

- **Model:** Stable Diffusion (via Hugging Face / CompVis / Diffusers)
- **Library:** 🤗 Hugging Face `diffusers`, `transformers`, `torch`
- **Platform:** Google Colab / Jupyter Notebook
- **Image Generation Techniques:** Latent diffusion, prompt embeddings

---

## 🧠 How It Works

1. **Load Pre-trained Stable Diffusion Model**  
   Use Hugging Face’s `diffusers` library to access and load the model.

2. **Input Text Prompt**  
   Provide descriptive text (e.g., "a futuristic city under the stars").

3. **Generate Image**  
   The model processes the prompt and produces an image reflecting the content.

4. **Save / Visualize Output**  
   Images are saved locally or displayed inline in Colab.

---
