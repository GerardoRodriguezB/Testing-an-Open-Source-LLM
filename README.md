# Testing-a-LLM

In this repository `Phi-3-mini-4k-instruct` is set and tested. 

## Environment Setup

Create an Anaconda environment using `python=3.10`. Navigate to the root folder of the project and install requeriments

```bash
pip install -r requeriments.txt
```

## Install PyTORCH

If your machine has a CUDA compatible GPU, install:

```bash
pip install torch==2.8.0 torchvision==0.23.0 torchaudio==2.8.0 --index-url https://download.pytorch.org/whl/cu126
```
Otherwise, install the versions for CPU

```bash
pip install torch==2.8.0 torchvision==0.23.0 torchaudio==2.8.0
```
