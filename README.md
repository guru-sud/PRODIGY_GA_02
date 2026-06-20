# PRODIGY_GA_02 — Image Generation with Pre-trained Models

## Task
Utilize pre-trained generative models (Stable Diffusion) to create images from text prompts.

## Overview
This project uses **Stable Diffusion v1.5** (via Hugging Face's `diffusers` library) to generate images from text prompts. It covers:

- Loading a pre-trained text-to-image diffusion model
- Generating images from custom prompts
- Exploring varied artistic styles (oil painting, digital art, photorealism, anime, watercolor)
- Comparing the effect of `guidance_scale` on output quality and prompt adherence
- Saving generated images and image grids

## Model Used
- **Model:** `runwayml/stable-diffusion-v1-5`
- **Library:** Hugging Face `diffusers`
- **Hardware:** GPU (CUDA) via Google Colab

## How to Run
1. Open `PRODIGY_GA_02.ipynb` in Google Colab
2. Set runtime to GPU: **Runtime → Change runtime type → GPU**
3. Run all cells in order: **Runtime → Run all**

## Dependencies
```
diffusers
transformers
accelerate
torch
```

## Results
The notebook generates:
- A grid of images from varied text prompts
- A grid comparing different artistic styles
- A grid comparing different `guidance_scale` values on the same prompt

## Reference
- [TensorFlow Stable Diffusion Tutorial](https://www.tensorflow.org/tutorials/generative/generate_images_with_stable_diffusion)
- [Hugging Face Diffusers Documentation](https://huggingface.co/docs/diffusers)

## Author
guru-sud — Prodigy InfoTech Generative AI Internship, Task-02
