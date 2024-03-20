<div align="center">

## A Tool to Gather A Selection of Large Multimodal Models for Image Captioning


[![python](https://img.shields.io/badge/-Python%203.9-blue?logo=python&logoColor=white)](https://github.com/pre-commit/pre-commit)
[![pytorch](https://img.shields.io/badge/PyTorch-ee4c2c?logo=pytorch&logoColor=white)](https://pytorch.org/get-started/locally/)
[![license](https://img.shields.io/badge/license-Apache%202.0-gray.svg)](#license)

</div>

<br>

### Overview

>Large Multimodal Models (LMMs) are being used for many purposes, and image captioning is one of them. In order to understand the captioning performance and runtime of some known models, I wrote a notebook with a Gradio interface. If you have some domain specific images and want to know how they will be captioned, give it a try! 
### 📌 Important note
The models used here belong to their authors, please refer to their respective works: 
* [MoonDream](https://github.com/vikhyat/moondream)
* [DeepSeek-VL](https://github.com/deepseek-ai/DeepSeek-VL)

### Installation
Consider creating an environment like below (recommended, optional):
```
conda create -n lmm python=3.9
conda activate lmm
```
Clone the repository, then install dependencies 
```
git clone https://github.com/IceTea42/caption-with-llms
cd caption-with-llms
pip install -r requirements.txt
```
Next to this repository, install DeepSeek-VL as such:
```
git clone https://github.com/deepseek-ai/DeepSeek-VL
cd DeepSeek-VL
pip install -e .
```

### Acknowledgement
By its comparative nature, this repository builds upon [MoonDream](https://github.com/vikhyat/moondream) and [DeepSeek-VL](https://github.com/deepseek-ai/DeepSeek-VL)
