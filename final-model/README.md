# Final Model

This folder contains the fully assembled GPT model built throughout the book.

## Contents

- `scripts/gpt_model.py` — Model architecture (assembled from all chapters)
- `scripts/train.py` — Pretraining script
- `scripts/generate.py` — Text generation script
- `scripts/finetune_classification.py` — Classification finetuning
- `scripts/finetune_instructions.py` — Instruction finetuning
- `checkpoints/` — Saved model weights

## Running

```bash
# Pretrain
python scripts/train.py

# Generate text
python scripts/generate.py --checkpoint checkpoints/model.pt --prompt "Once upon a time"

# Finetune (classification)
python scripts/finetune_classification.py
```
