# PRODIGY_GA_01 - Task-01: Text Generation with GPT-2

## Overview
This repository contains Task-01 from my Generative AI Internship at Prodigy InfoTech.  
The goal of this task is to train/fine-tune a GPT-2 model to generate coherent and contextually relevant text based on a given prompt. The focus is on **learning the theory and understanding GPT-2 architecture and text generation**.

## About GPT-2
GPT-2 is a transformer-based language model developed by OpenAI that predicts the next token in a sequence.  
It can generate human-like text when prompted and can be fine-tuned on custom datasets to adapt to specific styles or domains.

## Dataset
For this task, the dataset contains:
- Information about Prodigy InfoTech, their mission, internships, and offerings
- Basic AI and GPT-2 descriptions for context

The dataset is used to fine-tune GPT-2 so it can generate text relevant to the company and generative AI concepts.

## Implementation
- Environment: Google Colab
- Libraries: `transformers`, `torch`, `gradio`
- Model: `GPT2LMHeadModel` from Hugging Face
- Tokenizer: `GPT2Tokenizer`

### Features
- Generates text completions based on prompt input
- Demonstrates fine-tuning concepts
- Frontend implemented with Gradio for interactive demonstration

## Demo
You can see the demo video here: `demo_video.mp4` (or link to LinkedIn post if uploaded)

## Learnings
- GPT-2 architecture and working mechanism
- Fine-tuning workflow on custom datasets
- Prompt engineering for text generation
- Building an interactive frontend with Gradio

## How to Run
1. Open `gpt2_text_generation.ipynb` in Google Colab
2. Run all cells sequentially
3. Use Gradio interface to enter prompts and generate text
4.  You can open this notebook in Google Colab for execution:
[Open in Colab](https://colab.research.google.com/github/ShaikArfaAnjum/PRODIGY_GA_01/blob/main/Task_01_GPT2_Text_Generation.ipynb)

