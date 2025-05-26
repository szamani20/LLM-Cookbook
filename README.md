# LLM-Cookbook

**A collection of ready-to-run notebooks and practical guides for training and fine-tuning large language models (LLMs) in 2025.**

---

# Core Techniques Covered

## Supervised Fine-Tuning (SFT)
Train models on labeled input-output pairs using Teacher Forcing.

## Direct Preference Optimization (DPO)
Align models with human preferences using pairwise comparisons.

## Quantization
Reduce memory and compute requirements using 8-bit and 4-bit model formats via `BitsAndBytes`.

## Parameter-Efficient Fine-Tuning (PEFT) with LoRA
Fine-tune models efficiently by injecting low-rank adapters, using the `peft` library.

## Signal-to-Noise Ratio (SNR) Analysis
Understand layer-wise learning dynamics with the `spectrum` library.

## Evaluation Metrics
Assess performance with metrics like `Accuracy`, `BLEU`, `ROUGE`, `BERTScore`, and `Levenshtein distance`.

---

# Dataset Creation

## [Dataset-Creation-DPO.ipynb](https://github.com/szamani20/LLM-Cookbook/blob/main/Dataset-Creation-DPO.ipynb)

## [Dataset-Creation-SFT.ipynb](https://github.com/szamani20/LLM-Cookbook/blob/main/Dataset-Creation-SFT.ipynb)

---

# Training

## [FineTune-LLM-using-DPO.ipynb](https://github.com/szamani20/LLM-Cookbook/blob/main/FineTune-LLM-using-DPO.ipynb)

## [FineTune-LLM-using-SFT.ipynb](https://github.com/szamani20/LLM-Cookbook/blob/main/FineTune-LLM-using-SFT.ipynb)

> ⚠️ These notebooks are optimized for demonstration and may use small datasets and short training times.

