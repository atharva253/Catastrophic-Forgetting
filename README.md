# Catastrophic-Forgetting

This study investigates Multi-Task Learning (MTL) and Elastic Weight Consolidation
(EWC) as strategies to mitigate this issue and compares it with Vanilla Sequential Finetuning (SFT).

### Branch Info

- master: code to run multitask learning 
- sequential: code to run sequential finetuning and elastic weight consolidation 


### Dependencies

`pip install` the following packages:
- `torch`
- `numpy`
- `transformers`
- `datasets`
- `tiktoken`
- `wandb`
- `tqdm`
- `pytorch-ignite`

### Data

1. Run prepare.py in data/squad
2. Run prepare.py in data/cnn_dailymail
