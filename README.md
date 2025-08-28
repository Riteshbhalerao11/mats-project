# Fragile Beliefs

Exploring the fragility of incepted beliefs in hybrid reasoning model (Qwen3) via fine-tuning with corrupted data.

This repository contains code and experiments that combine **behavioral evaluation** (MCQs, perturbations) with **mechanistic interpretability** tools (crosscoders, patching) to study counterfactual reasoning.

---

## Repository Structure

* **crosscoder/** — Training and analysis of CrossCoders to identify latents/features acquired through fine-tuning.
* **datagen/** — Synthetic data generation with controlled corruptions for counterfactual inception.
* **eval\_qna\_plots/** — Behavioral evaluation plots (MCQs).
* **patching/** — Exploratory and unfinished patching experiments to probe circuits.

---

## Important Links

* [Project writeup](https://docs.google.com/document/d/1bRGN_LGHJcwbkWnSAT1lyNGf0xfOOa52cINZWspRats/edit?usp=sharing)
* [Generated data for facts](https://huggingface.co/datasets/Bhalewow/MATS_dataset_qwen)
* [Generated data for counterfactuals (corrupted data)](https://huggingface.co/datasets/Bhalewow/MATS_dataset)
* [Fine-tuned models](https://huggingface.co/collections/Bhalewow/mats-project-68ae115e63ae2d03c37e744e)
* [Latent examples](https://drive.google.com/drive/folders/1EKJfB8dE8KjoXYzUxTSPnOn8g2sqwv13?usp=sharing)

