# baby_gpt_hongloumeng
train baby gpt with hongloumeng text for karpathy nanoGPT repo from https://github.com/karpathy/nanoGPT

# steps

1. env
- python3.11
- GPU A800
- ubuntu 12.04
- CUDA 12.4
- `pip install torch numpy transformers datasets tiktoken wandb tqdm`

2. prepare data

```
python data/hongloumeng_char_local/prepare.py
```

output:

```
vocab size: 4,435
train has 791,045 tokens
val has 87,894 tokens

```

3. train model

```
python train.py config/train_hongloumeng_char_local.py
```

4. generate output

```

```

