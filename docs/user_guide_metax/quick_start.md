# MetaX Quick Start

## Introduction
This guide walks you through running a GRPO training job with verl on the MetaX platform. Make sure you have completed the [Installation Guide](./install_guidance.md) first.

## Running a Training Script

Metax provides verl example training scripts under `/workspace/verl/examples`. 

Launch the training (example for Qwen3-8B on 8 GPUs):

```bash
cd /workspace/verl/examples/grpo_trainer/
bash train_qwen3-8b-8gpus.sh
```

Training is running successfully if you see step-level progress output in the logs.

> Adjust environment variables in the script (model path, data path, batch size, etc.) to match your setup before running.

## Next Steps

- See the [FAQ](./faq.md) for troubleshooting common issues.
