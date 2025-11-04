# ACL_EMR_LLM  

This repository contains the PyTorch implementation of the following paper:
> **ACL_EMR_LLM:  S**<be>
><br>
> Authors: Shuak Bakytnur<br>
> **Paper Link**: [http://arxiv.org/abs/xxx](http://arxiv.org/abs/xxx)

## Introduction
ACL_EMR_LLM, a lightweight audio–video
multimodal LLM.
<!-- <div align="center"><img width="90%" src="image.png?raw=true" /></div> -->

### Step 0. Environment Setup
- Python version >= 3.10
```bash
conda create -n av-emr-llm python=3.10 -y
conda activate av-emr-llm
git clone https://github.com/Shuaque/AV-EMR-LLM.git
cd AV-EMR-LLM
```
```bash
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu126
pip3 install torchaudio --index-url https://download.pytorch.org/whl/cu126
pip install transformers opencv-python accelerate

# If your pip version > 24.1, please run "python3 -m pip install --upgrade pip==24.0"

cd fairseq
pip install --editable ./
```