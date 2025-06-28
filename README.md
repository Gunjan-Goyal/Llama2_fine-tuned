# Llama2_fine-tuned
## Project Pending:
This repository will contain a Jupyter Notebook focused on fine-tuning the LLaMA2 model using Hugging Face's transformers, peft, and trl libraries.

This project fine-tunes the "NousResearch/Llama-2-7b-chat-hf" model using LoRA (Low-Rank Adaptation) for efficient parameter tuning and BitsAndBytes 4-bit quantization for reduced memory usage. It utilizes transformers, peft, and trl libraries to implement supervised fine-tuning on custom instruction-response datasets.

The notebook includes:
- Setting up a 4-bit quantized model using bitsandbytes.
- Loading and formatting datasets for supervised instruction tuning.
- Configuring and applying LoRA adapters.
- Training with SFTTrainer from trl.
- Saving and merging the fine-tuned LoRA weights back into the base model.
- This setup allows fine-tuning of large models like LLaMA 2 on limited hardware (e.g., single GPU with 16GB VRAM), making it highly accessible for research and experimentation.

## Current Status:
The notebook is complete but not yet functional due to following issues:
- Token access or model download errors from Hugging Face (NousResearch/Llama-2-7b-chat-hf).
- Compatibility issues between PyTorch, CUDA, and bitsandbytes.

## Note
This repo and code will be made public once setup is stable and reproducible across systems. Until then, feel free to watch this repo for updates.
