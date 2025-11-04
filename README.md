# Fine-tuning-Llama-3.2-3B-Model

Tools & Libraries: Unsloth, Transformers, TRL, PyTorch, Hugging Face Datasets

Description:
Fine-tuned the Llama 3.2–3B Instruct model using parameter-efficient fine-tuning (PEFT) techniques on the FineTome-100k dataset.
Implemented supervised fine-tuning (SFT) using the SFTTrainer from Hugging Face’s TRL library with LoRA adapters for efficient memory usage.
Evaluated the fine-tuned model through prompt-based inference for domain-specific question answering tasks.
