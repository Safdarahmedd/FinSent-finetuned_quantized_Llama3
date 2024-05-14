# Fine-Tuning LLMs with Quantization for Financial Sentiment Analysis
In this project, we delve into a comparative analysis of various Large Language Models (LLMs) such as LLaMA2, LLaMA3, Ladybird, Jupiter-k-7B-slerp,  and Facebook's OPT, specifically focusing on their capabilities in Financial Sentiment Analysis.  And we use the FinancialPhraseBank dataset which is a polar sentiment dataset consisting of 4,840 sentences from English language financial news.


---

# Contributors

* **Syed Ahzam Tariq (sat10045@nyu.edu)**
* **Safdar Ahmed (sa8237@nyu.edu)**
* **Ran Xu (rx523@nyu.edu)**

---

### Abstract
In this project, we embark on a comparative analysis of various Large Language Models (LLMs) to evaluate their efficacy in Financial Sentiment Analysis. With the rapid advancements in artificial intelligence, LLMs have become pivotal in extracting and interpreting sentiment from vast amounts of financial data. This capability is crucial for stakeholders in the finance sector, as it aids in decision-making processes by providing insights into market sentiment. Through this study, we aim to identify which models are most effective in accurately analyzing sentiments expressed in financial texts, thus providing a clearer understanding of their practical applications and limitations within the finance industry.

### Requirements
The following python packages are required to run the Jupyter notebooks:
* numpy
* pandas
* os
* tqdm
* bitsandbytes
* torch
* transformers
* datasets
* peft
* trl
* sklearn

Install them manually or use add this command in your python notebook:
`!pip install accelerate peft bitsandbytes transformers trl`

---
### Results
## Model Performance Overview

**Pre-Finetuned Models**

| Models             | Accuracy |
| ------------------ | -------- |
| **Llama 3 - 8B**   | 37%      |
| Jupiter-k-7B-slerp | 78%      |
| OPT 13B            | 34%      |
| Ladybird Base 7B   | 80%      |
| Llama 2 7B         | 37%      |
| Llama 2 13B        | 40%      |

**Finetuned Models**

| Models             | Accuracy |
| ------------------ | -------- |
| **Llama 3 - 8B**   | 85%      |
| Jupiter-k-7B-slerp | 88%      |
| OPT 13B            | 86%      |
| Ladybird Base 7B   | 89%      |
| Llama 2 7B         | 86%      |
| Llama 2 13B        | 87%      |

### System Specification

* NYU Greene HPC Jupyter Environmrnt
* CPU: 8 Virtualized Cores of Intel Xeon-Platinum 8286
* GPU: Nvidia Tesla v100
* System Memory: 96 GB
* Python Version: 3.11
* CUDA version: v11.1.74
* Torch Version: 2.0.0

---
