# EMNLP 2024: Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis

## Introduction

This repo is for the EMNLP 2024 paper: [Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis](https://zepingyu0512.github.io/arithmetic-mechanism.github.io/)

This work explores the mechanism of arithmetic tasks. This work introduces the comparable neuron analysis (CNA) method to identify the important neurons.

This work also uses the findings and insights in [this repo](https://github.com/zepingyu0512/neuron-attribution/tree/main) in [this EMNLP 2024 paper](https://zepingyu0512.github.io/neuron-attribution.github.io/)

## running code

Environment versions: please see **environment.yml**

First, please use modeling_llama.py to replace the original file in the transformers path, which is usually in anaconda3/envs/YOUR_ENV_NAME/lib/python3.8/site-packages/transformers/models/llama. This modified file is useful for extracting the internal vectors during inference time. **Please remember to save the original file.** 

Then, run the code in Llama_view_arithmetic_head.ipynb and Llama_view_arithmetic_CNA.ipynb using jupyter notebook. This introduces how to identify and analyze the important heads/neurons in an arithmetic case.

Llama_view_arithmetic_head.ipynb: identifying the important heads.

Llama_view_arithmetic_CNA.ipynb: identifying the important neurons in deep FFN layers and shallow FFN layers.

## cite us: 

```
@inproceedings{yu2024interpreting,
  title={Interpreting Arithmetic Mechanism in Large Language Models through Comparative Neuron Analysis},
  author={Yu, Zeping and Ananiadou, Sophia},
  booktitle={Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing},
  pages={3293--3306},
  year={2024}
}
```
