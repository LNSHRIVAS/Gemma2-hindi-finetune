# Gemma2-Hindi-Finetune

This project was developed as part of a Kaggle competition hosted by Google. 

This project explores the fine-tuning of Google’s **Gemma 2B** large language model for creating a bilingual conversational assistant capable of understanding and responding in both Hindi and Hinglish.

I fine-tuned Google’s **Gemma 2B** language model on a custom Hindi and Hinglish dataset using **LoRA (Low-Rank Adaptation)** and **4-bit quantization** to enable efficient training on limited hardware.

This repository walks through the complete fine-tuning pipeline from data preprocessing to model training and outlines best practices that you can apply to fine-tune any other large language model (LLM) using the PEFT framework.

> 📌 If you're interested in multilingual GenAI or fine-tuning LLMs on resource-constrained systems, this guide is for you.

## What You'll Learn from This Project

- How to fine-tune a large-scale open-source LLM (Gemma2-2B) on a multilingual instruction-following dataset.
- Key parameters in **LoRA (Low-Rank Adaptation)** and how to configure them for **knowledge injection** vs **task adaptation**.
- How to manage model saving and inference to avoid common deployment pitfalls.
- Tips for saving compute and optimizing fine-tuning runs with limited resources.


## Datasets Used

This model was fine-tuned on a diverse and instructional dataset mix:

-  **GPT-4 Alpaca** (instruction-tuned data)
-  **Wikipedia Hindi corpus**
-  **Cognitive Lab’s Hindi Instruct**
-  **Databricks Dolly**
-  **Hindi Maths Quest**
-  **Alpaca-Inspired Hindi Data for Gemma**
