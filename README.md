# Awesome-LLM-for-Chart [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of papers and resources on using **Large Language Models (LLMs) for Chart Understanding**, including chart data extraction, visual reasoning, chart-based QA, and chart-to-knowledge generation.

Large Language Models (LLMs) have demonstrated impressive capabilities in natural language processing, vision, and multimodal tasks. Among these, understanding and reasoning over **Data Visualizations**—such as charts, plots, and graphs—is emerging as a critical research direction.
This repository aims to bridge the gap between **Chart Understanding** and **Large Language Models** by collecting high-quality research papers and resources that explore how LLMs can be applied to **extract**, **interpret**, and **reason** about visual data representations in charts.

## Table of Contents

- [Awesome-LLM-for-Chart ](#awesome-llm-for-chart-)
  - [Table of Contents](#table-of-contents)
  - [Chart Understanding](#chart-understanding)
  - [Chart Data Extraction and Structuring](#chart-data-extraction-and-structuring)
  - [Visual Question Answering over Charts (ChartQA)](#visual-question-answering-over-charts-chartqa)
  - [Chart Captioning (Summarization)](#chart-captioning-summarization)
  - [Benchmarks, Evaluation \& Surveys](#benchmarks-evaluation--surveys)
  - [Contributing](#contributing)

## Chart Understanding
- *Liu, Fuxiao, Xiaoyang Wang, Wenlin Yao, Jianshu Chen, Kaiqiang Song, Sangwoo Cho, Yaser Yacoob, and Dong Yu.* **MMC: Advancing Multimodal Chart Understanding with Large-scale Instruction Tuning** <img src='https://img.shields.io/badge/NAACL-2024-yellow'> <a href='https://arxiv.org/abs/2311.10774'><img src='https://img.shields.io/badge/Paper-purple'></a>
  <a href='https://github.com/FuxiaoLiu/MMC'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Wang, Zirui, Mengzhou Xia, Luxi He, Howard Chen, Yitao Liu, Richard Zhu, Kaiqu Liang et al.* **CharXiv: Charting Gaps in Realistic Chart Understanding in Multimodal LLMs** <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/pdf/2406.18521'><img src='https://img.shields.io/badge/Paper-purple'></a>  <a href='https://huggingface.co/datasets/princeton-nlp/CharXiv'><img src='https://img.shields.io/badge/Dataset-red'></a>


## Chart Data Extraction and Structuring
- *Zhou, Zhiguang, Haoxuan Wang, Zhengqing Zhao, Fengling Zheng, Yongheng Wang, Wei Chen, and Yong Wang.* **ChartKG: A Knowledge-Graph-Based Representation for Chart Images** <img src='https://img.shields.io/badge/TVCG-2024-yellow'> <a href='https://ieeexplore.ieee.org/document/10711251/'><img src='https://img.shields.io/badge/Paper-purple'></a>
  
- *Lu, Pan, Hritik Bansal, Tony Xia, Jiacheng Liu, Chunyuan Li, Hannaneh Hajishirzi, Hao Cheng, Kai-Wei Chang, Michel Galley, and Jianfeng Gao.* **MathVista: Evaluating Math Reasoning in Visual Contexts with GPT-4V, Bard, and Other Large Multimodal Models** <img src='https://img.shields.io/badge/ICLR-2024-yellow'> <a href='https://arxiv.org/abs/2310.02255'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://huggingface.co/datasets/AI4Math/MathVista'><img src='https://img.shields.io/badge/Dataset-red'></a>


## Visual Question Answering over Charts (ChartQA)
- *Masry, Ahmed, Do Xuan Long, Jia Qing Tan, Shafiq Joty, and Enamul Hoque.* **ChartQA: A Benchmark for Question Answering about Charts with Visual and Logical Reasoning** <img src='https://img.shields.io/badge/ACL_Findings-2022-yellow'> <a href='https://aclanthology.org/2022.findings-acl.177/'><img src='https://img.shields.io/badge/Paper-purple'></a><a href='https://github.com/vis-nlp/ChartQA'><img src='https://img.shields.io/badge/Dataset-red'></a> <img src='https://img.shields.io/badge/Benchmark-green'>

- *Kim, Dae Hyun, Enamul Hoque, and Maneesh Agrawala.* **Answering Questions about Charts and Generating Visual Explanations** <img src='https://img.shields.io/badge/CHI-2020-yellow'> <a href='https://dl.acm.org/doi/10.1145/3313831.3376467/'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Singh, Hrituraj, and Sumit Shekhar. "STL-CQA: Structure-based transformers with localization and encoding for chart question answering.* **STL-CQA: Structure-based Transformers with Localization and Encoding for Chart Question Answering** <img src='https://img.shields.io/badge/EMNLP-2020-yellow'> <a href='https://aclanthology.org/2020.emnlp-main.264/'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Chaudhry, Ritwick, Sumit Shekhar, Utkarsh Gupta, Pranav Maneriker, Prann Bansal, and Ajay Joshi.* **LEAF-QA: Locate, Encode & Attend for Figure Question Answering** <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://openaccess.thecvf.com/content_WACV_2020/papers/Chaudhry_LEAF-QA_Locate_Encode__Attend_for_Figure_Question_Answering_WACV_2020_paper.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Methani, Nitesh, Pritha Ganguly, Mitesh M. Khapra, and Pratyush Kumar.* **PlotQA: Reasoning over Scientific Plots**
  <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://arxiv.org/abs/1909.00997'><img src='https://img.shields.io/badge/Paper-purple'></a><a href='https://github.com/NiteshMethani/PlotQA'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Kafle, Kushal, Brian Price, Scott Cohen, and Christopher Kanan.* **DVQA: Understanding Data Visualizations via Question Answering** <img src='https://img.shields.io/badge/CVPR-2018-yellow'> <a href='https://openaccess.thecvf.com/content_cvpr_2018/papers/Kafle_DVQA_Understanding_Data_CVPR_2018_paper.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>
  <a href='https://github.com/kushalkafle/DVQA_dataset'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Kahou, Samira Ebrahimi, Vincent Michalski, Adam Atkinson, Ákos Kádár, Adam Trischler, and Yoshua Bengio.* **FigureQA: An Annotated Figure Dataset for Visual Reasoning** <img src='https://img.shields.io/badge/ICLR_Workshop-2018-yellow'> <a href='https://arxiv.org/abs/1710.07300'><img src='https://img.shields.io/badge/Paper-purple'></a><a href='https://www.microsoft.com/en-us/research/project/figureqa-dataset/'><img src='https://img.shields.io/badge/Dataset-red'></a>




## Chart Captioning (Summarization)
- *Chen, Charles, Ruiyi Zhang, Eunyee Koh, Sungchul Kim, Scott Cohen, and Ryan Rossi.* **Figure Captioning with Relation Maps for Reasoning** <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://openaccess.thecvf.com/content_WACV_2020/papers/Chen_Figure_Captioning_with_Relation_Maps_for_Reasoning_WACV_2020_paper.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>



## Benchmarks, Evaluation & Surveys
- *Xu, Zhengzhuo, Sinan Du, Yiyan Qi, Chengjin Xu, Chun Yuan, and Jian Guo.* **ChartBench: A Benchmark for Complex Visual Reasoning in Charts** <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2312.15915'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://huggingface.co/datasets/SincereX/ChartBench'><img src='https://img.shields.io/badge/Dataset-red'></a>



## Contributing
👍 Contributions to this repository are welcome! 

If you have come across relevant resources, feel free to open an issue or submit a pull request.

📌 示例格式：

```
- *Author1, Author2, Author3, ...*  **Paper Title (bolded)** <img src='https://img.shields.io/badge/Conference_Journal_Name-Year-Color'><a href='PDF_Link'><img src='https://img.shields.io/badge/Paper-purple'></a><a href='Code_Link'><img src='https://img.shields.io/badge/Code-orange'></a><a href='Dataset_Link'><img src='https://img.shields.io/badge/Dataset-red'></a><img src='https://img.shields.io/badge/Benchmark-green'>

```

[#contributing]: #-contributing
[#benchmarks--surveys]: #-benchmarks--surveys
