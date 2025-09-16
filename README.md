# Testing-an-Open-Source-LLM

In this repository we set and test `Phi-3-mini-4k-instruct`, a Microsoft's relatively small LLM. This model was released under the open source MIT license, allowing to free use, modify and integration in comercial software.

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
