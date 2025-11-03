# Persian News Title Generation

This project applies prompt-based learning and SFT fine-tuning to generate concise Persian news titles from full news articles. It leverages **Mistral-7B-Instruct** and **Qwen2.5-7B-Instruct** models using **Hugging Face Transformers** and the **TRL (Transformer Reinforcement Learning)** library.

## Dataset

A Persian news dataset is preprocessed for training and evaluation.

## Methods

- **Fine-tuning** performed efficiently using **QLoRA**
- **Prompting strategies** explored:
  - Zero-shot
  - Few-shot
  - Chain-of-thought (CoT)

## Evaluation

Model performance is evaluated using:
- **BLEU**
- **ROUGE-L**
- **METEOR**
