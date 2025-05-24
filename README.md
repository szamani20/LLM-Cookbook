# LLM-Cookbook

A collection of practical guides and runnable examples for training and fine-tuning large language models (LLMs).

This repository covers core techniques such as:

- **Supervised Fine-Tuning (SFT)** – train models on labeled input-output pairs using Teacher Forcing.
- **Direct Preference Optimization (DPO)** – align models with human preferences using pairwise comparisons.
- **Quantization** – reduce memory and compute requirements using 8-bit and 4-bit model formats via `BitsAndBytes`.
- **Parameter-Efficient Fine-Tuning (PEFT)** with **LoRA** – fine-tune models efficiently by injecting low-rank adapters, using the `peft` library.
- **Signal-to-Noise Ratio (SNR)** analysis – understand layer-wise learning dynamics with the `spectrum` library.
- **Evaluation Metrics** – assess performance with metrics like Accuracy, BLEU, ROUGE, BERTScore, and Levenshtein distance.

All examples are built for clarity, reproducibility, and quick iteration—even on limited hardware. Perfect for learners, researchers, and developers exploring LLM tuning techniques.

> ⚠️ These notebooks are optimized for demonstration and may use small datasets and short training times.

## Files
A list of files in this repository with short description.

### Dataset Creation

**A notebook to create datasets suitable for DPOTrainer**:

[Dataset-Creation-DPO.ipynb](https://github.com/szamani20/LLM-Cookbook/blob/main/Dataset-Creation-DPO.ipynb)

---

**A notebook to create datasets suitable for SFTTrainer**:

[Dataset-Creation-SFT.ipynb](https://github.com/szamani20/LLM-Cookbook/blob/main/Dataset-Creation-SFT.ipynb)

### Training

**Notebook to fine tune Llama with DPOTrainer**:

[FineTune-LLM-using-DPO.ipynb](https://github.com/szamani20/LLM-Cookbook/blob/main/FineTune-LLM-using-DPO.ipynb)

---

**Notebook to fine tune Llama with SFTTrainer**:

[FineTune-LLM-using-SFT.ipynb](https://github.com/szamani20/LLM-Cookbook/blob/main/FineTune-LLM-using-SFT.ipynb)
