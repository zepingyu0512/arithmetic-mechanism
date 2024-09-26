# EMNLP 2024: Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis

## Introduction

This repo is for the EMNLP 2024 paper: [Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis](https://arxiv.org/pdf/2409.14144)

This work explores the mechanism of arithmetic tasks. This work introduces the comparable neuron analysis (CNA) method to identify the important neurons.

This work uses the findings and insights in [this repo](https://github.com/zepingyu0512/neuron-attribution/tree/main) in [this EMNLP 2024 paper](https://arxiv.org/pdf/2312.12141)

## running code

First, please use modeling_llama.py to replace the original file in the transformers path, which is usually in anaconda3/envs/YOUR_ENV_NAME/lib/python3.8/site-packages/transformers/models/llama. This modified file is useful for extracting the internal vectors during inference time. **Please remember to save the original file.** 

Then, run the code in Llama_view_arithmetic.ipynb using jupyter notebook. This introduces how to identify and analyze the important heads/neurons in an arithmetic case.

transformers version: 4.37.1

torch version: 2.1.2+cu121

## cite us: 

```
@article{yu2024interpreting,
  title={Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis},
  author={Yu, Zeping and Ananiadou, Sophia},
  journal={arXiv preprint arXiv:2409.14144},
  year={2024}
}
```
