## Jumpstart Generative AI Examples
This repository contains code examples for **SageMaker Jumpstart** Generative AI, a tutorial series designed to help users get started with generative AI using Python and PyTorch.

### Module 1: Stable Diffusion with Small Dataset of Cat Images
This repository showcases the Stable Diffusion technique, a powerful generative modeling technique that allows for the creation of high-quality images from small datasets. The repository consists of three Jupyter notebooks.

The first notebook, `_Lab 1 - Text to Image.ipynb`, demonstrates how to easily create a SageMaker endpoint for the pre-trained Stable Diffusion model and generate images based on user text prompts. Users can input fun scenarios and prompts to generate various images, such as these cats.

<div>
    <img src="./img/cat-3.png" alt="Image 3" width="400" style="display:inline-block">
    <img src="./img/cat-4.png" alt="Image 4" width="400" style="display:inline-block">
</div>
<br>
The second notebook, `_Lab 2- Text to Image Inpainting.ipynb`, showcases the process of taking an exsisting image and inpainting.  Inpainting in Generative AI images is the process of filling in missing or corrupted parts of an image.  This will take an original image of a dog and inpaint it with that of a cat.  

The third notebook '_Lab 3 - Finetune a Stable Diffusion Model; showcases the process of fine-tuning the Stable Diffusion model with a small set of images. This approach involves using images of cats from specific breeds or your own pet cats to teach the model how to recreate these images and incorporate them into various creative scenarios. This technique can be adapted to work with any set of images containing fewer than ten examples, such as images of pet dogs or other entities.

By following the steps outlined in the notebook, you can collect a few images of your chosen entity from Google Images and utilize the fine-tuning process to train the Stable Diffusion model to create new and unique compositions. This approach offers a broad range of creative possibilities, allowing you to experiment with various scenarios and unleash your imagination.

<div>
    <img src="./img/cat-1.png" alt="Image 1" width="400" style="display:inline-block">
    <img src="./img/cat-2.png" alt="Image 2" width="400" style="display:inline-block">
</div>

This repository provides users with a powerful tool for generating high-quality images, even with limited datasets. The Stable Diffusion technique offers a versatile and efficient way to create customized and imaginative images.

### Module 2: FLAN-T5-XL In-Context Learning via Prompt Engineering
This module focuses on utilizing the FLAN-T5-XL Large Language Model (LLM) to achieve N-shot learning via in-context learning. This involves leveraging the model's natural language understanding (NLU) capabilities to personalize virtual assistant responses and improve their performance for users.

<div style="text-align:center">
    <img src="./img/flan-t5.png" alt="flan-t5" width="600" style="display:inline-block">
</div>

In this module, you will learn step-by-step how to perform NLU tasks using FLAN-T5-XL. Specifically, you will learn how to read and understand multi-turn customer support chat transcripts, and engineer prompts that enable FLAN-T5-XL to learn in-context and improve its performance in N-shot learning. This will enhance the model's ability to infer context and answer questions derived from the chat transcripts.

Overall, this module provides an excellent opportunity to explore the capabilities of FLAN-T5-XL in solving NLU tasks, such as text summarization, abstractive question answering, sentiment analysis, and sentiment phrase extraction.

### Usage
Each module has its own subdirectory containing code examples and instructions for use. Simply navigate to the module you are interested in and follow the instructions in the README file.

### Amazon Internal Reference
This workshop uses :
Workshop ID : 80ae1ed2-f415-4d3d-9eb0-e9118c147bd4 
Repository name : implementing-generative-ai-on-aws
