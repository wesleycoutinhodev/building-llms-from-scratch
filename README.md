# 📖 Build an LLM From Scratch — Study Repository

> Personal study repository following **"Build a Large Language Model (From Scratch)"** by Sebastian Raschka.
>
> 📚 Book repo: [rasbt/LLMs-from-scratch](https://github.com/rasbt/LLMs-from-scratch)
> 🎬 Author's lecture: [YouTube](https://www.youtube.com/watch?v=kPGTx4wcm_w)

---

## 🗺️ Repository Structure

```
llms-from-scratch-study/
│
├── ch01/               # Chapter 1 — Understanding Large Language Models
├── ch02/               # Chapter 2 — Working with Text Data
├── ch03/               # Chapter 3 — Coding Attention Mechanisms
├── ch04/               # Chapter 4 — Implementing a GPT Model from Scratch
├── ch05/               # Chapter 5 — Pretraining on Unlabeled Data
├── ch06/               # Chapter 6 — Finetuning for Text Classification
├── ch07/               # Chapter 7 — Finetuning to Follow Instructions
│
├── appendix-A/         # Appendix A — Introduction to PyTorch
├── appendix-D/         # Appendix D — Adding Bells & Whistles to Training Loop
├── appendix-E/         # Appendix E — Parameter-efficient Finetuning with LoRA
│
├── final-model/        # Final assembled GPT model (end goal)
│   ├── checkpoints/    # Saved model weights
│   └── scripts/        # Training & inference scripts
│
├── resources/          # Papers, links, extra references
└── assets/             # Diagrams, images
```

Each chapter folder follows the same layout:
```
chXX/
├── notebooks/          # Code-along notebooks (replicate & experiment)
├── exercises/          # Chapter exercise solutions
└── notes/              # Personal notes and key concepts (Markdown)
```

---

## 📋 Progress Tracker

| # | Chapter | Status | Notes |
|---|---------|--------|-------|
| — | Appendix A: PyTorch Intro | ⬜ Not started | Pre-req if needed |
| 1 | Understanding Large Language Models | ⬜ Not started | Conceptual, no code |
| 2 | Working with Text Data | ⬜ Not started | Tokenization, BPE |
| 3 | Coding Attention Mechanisms | ⬜ Not started | Self-attention, MHA |
| 4 | Implementing a GPT Model from Scratch | ⬜ Not started | Full GPT architecture |
| 5 | Pretraining on Unlabeled Data | ⬜ Not started | Training loop |
| 6 | Finetuning for Text Classification | ⬜ Not started | Classification head |
| 7 | Finetuning to Follow Instructions | ⬜ Not started | Instruction tuning |
| — | Appendix D: Training Loop Extras | ⬜ Not started | LR schedulers, etc. |
| — | Appendix E: LoRA Finetuning | ⬜ Not started | Parameter-efficient |

**Legend:** ⬜ Not started · 🔄 In progress · ✅ Done

---

## 🎯 Goal

By the end of this study, I will have built a fully functional GPT-like language model from scratch in PyTorch — covering architecture, pretraining, and finetuning.

---

## 🛠️ Setup

```bash
# Clone the official repo for reference
git clone --depth 1 https://github.com/rasbt/LLMs-from-scratch.git

# Install dependencies
pip install torch tiktoken matplotlib numpy
```

See the official [setup guide](https://github.com/rasbt/LLMs-from-scratch/blob/main/setup/README.md) for full instructions.

---

## 📚 Key Concepts by Chapter

- **Ch 1** — LLM overview, transformer architecture big picture
- **Ch 2** — Tokenization, BPE, embeddings, data loaders
- **Ch 3** — Scaled dot-product attention, causal masking, multi-head attention
- **Ch 4** — Layer norm, feed-forward, residual connections, GPT-2 config
- **Ch 5** — Text generation, perplexity, weight loading from OpenAI
- **Ch 6** — Classification head, transfer learning, spam detection
- **Ch 7** — Instruction datasets, SFT, Alpaca-style finetuning
