# Gemma2-Hindi-Finetune

This project was developed as part of a Kaggle competition hosted by Google. 

This project explores the fine-tuning of Google’s **Gemma 2B** large language model for creating a bilingual conversational assistant capable of understanding and responding in both Hindi and Hinglish.

I fine-tuned Google’s **Gemma 2B** language model on a custom Hindi and Hinglish dataset using **LoRA (Low-Rank Adaptation)** and **4-bit quantization** to enable efficient training on limited hardware.

This repository walks through the complete fine-tuning pipeline from data preprocessing to model training and outlines best practices that you can apply to fine-tune any other large language model (LLM) using the PEFT framework.

> 📌 If you're interested in multilingual GenAI or fine-tuning LLMs on resource-constrained systems, this guide is for you.

