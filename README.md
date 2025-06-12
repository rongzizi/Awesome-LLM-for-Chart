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
  - [Chart Reverse Engineering](#chart-reverse-engineering)
  - [Benchmarks, Evaluation \& Surveys](#benchmarks-evaluation--surveys)
  - [Contributing](#contributing)

## Chart Understanding
- *Xu, Zhengzhuo, Bowen Qu, Yiyan Qi, Sinan Du, Chengjin Xu, Chun Yuan, and Jian Guo.* **ChartMoE: Mixture of Expert Connector for Advanced Chart Understanding** <img src='https://img.shields.io/badge/ICLR-2025-yellow'> <a href='https://openreview.net/pdf?id=o5TsWTUSeF'> <img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/IDEA-FinAI/ChartMoE'><img src='https://img.shields.io/badge/Code-orange'></a> <a href='https://huggingface.co/datasets/Coobiw/ChartMoE-Data'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Liu, Fuxiao, Xiaoyang Wang, Wenlin Yao, Jianshu Chen, Kaiqiang Song, Sangwoo Cho, Yaser Yacoob, and Dong Yu.* **MMC: Advancing Multimodal Chart Understanding with Large-scale Instruction Tuning** <img src='https://img.shields.io/badge/NAACL-2024-yellow'> <a href='https://arxiv.org/abs/2311.10774'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/FuxiaoLiu/MMC'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Masry, Ahmed, Parsa Kavehzadeh, Xuan Long Do, Enamul Hoque, and Shafiq Joty.* **UniChart: A Universal Vision-language Pretrained Model for Chart Comprehension and Reasoning** <img src='https://img.shields.io/badge/EMNLP-2023-yellow'> <a href='https://aclanthology.org/2023.emnlp-main.906/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/vis-nlp/UniChart'><img src='https://img.shields.io/badge/Code-orange'></a>

- *Lee, Kenton, Mandar Joshi, Iulia Raluca Turc, Hexiang Hu, Fangyu Liu, Julian Martin Eisenschlos, Urvashi Khandelwal, Peter Shaw, Ming-Wei Chang, and Kristina Toutanova.* **Pix2Struct: Screenshot Parsing as Pretraining for Visual Language Understanding** <img src='https://img.shields.io/badge/ICML-2023-yellow'> <a href='https://proceedings.mlr.press/v202/lee23g/lee23g.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://huggingface.co/google/pix2struct-base'><img src='https://img.shields.io/badge/Code-orange'></a>

- *Zhou, Mingyang, Yi R. Fung, Long Chen, Christopher Thomas, Heng Ji, and Shih-Fu Chang.* **Enhanced Chart Understanding via Visual Language Pre-training on Plot Table Pairs** <img src='https://img.shields.io/badge/ACL_Findings-2023-yellow'> <a href='https://aclanthology.org/2023.findings-acl.85/'><img src='https://img.shields.io/badge/Paper-purple'></a>
  <a href='https://github.com/zmykevin/ACL2023_ChartT5'><img src='https://img.shields.io/badge/Code-orange'></a>

- *Wang, Zirui, Mengzhou Xia, Luxi He, Howard Chen, Yitao Liu, Richard Zhu, Kaiqu Liang et al.* **CharXiv: Charting Gaps in Realistic Chart Understanding in Multimodal LLMs** <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/pdf/2406.18521'><img src='https://img.shields.io/badge/Paper-purple'></a>  <a href='https://huggingface.co/datasets/princeton-nlp/CharXiv'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Han, Yucheng, Chi Zhang, Xin Chen, Xu Yang, Zhibin Wang, Gang Yu, Bin Fu, and Hanwang Zhang.* **ChartLlama: A Multimodal LLM for Chart Understanding and Generation** <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2311.16483'> <img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/tingxueronghua/ChartLlama-code'><img src='https://img.shields.io/badge/Code-orange'></a> <a href='https://huggingface.co/datasets/listen2you002/ChartLlama-Dataset'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Han, Yucheng, Chi Zhang, Xin Chen, Xu Yang, Zhibin Wang, Gang Yu, Bin Fu, and Hanwang Zhang.* **StructChart: Perception, Structuring, Reasoning for Visual Chart Understanding** <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2309.11268'><img src='https://img.shields.io/badge/Paper-purple'></a>


## Chart Data Extraction and Structuring
- *Zhou, Zhiguang, Haoxuan Wang, Zhengqing Zhao, Fengling Zheng, Yongheng Wang, Wei Chen, and Yong Wang.* **ChartKG: A Knowledge-Graph-Based Representation for Chart Images** <img src='https://img.shields.io/badge/NAACL-Findings-2025-yellow'> <a href='https://aclanthology.org/2025.findings-naacl.35.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>
  
- *Lu, Pan, Hritik Bansal, Tony Xia, Jiacheng Liu, Chunyuan Li, Hannaneh Hajishirzi, Hao Cheng, Kai-Wei Chang, Michel Galley, and Jianfeng Gao.* **MathVista: Evaluating Math Reasoning in Visual Contexts with GPT-4V, Bard, and Other Large Multimodal Models** <img src='https://img.shields.io/badge/ICLR-2024-yellow'> <a href='https://arxiv.org/abs/2310.02255'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://huggingface.co/datasets/AI4Math/MathVista'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Chen, Jinyue, Lingyu Kong, Haoran Wei, Chenglong Liu, Zheng Ge, Liang Zhao, Jianjian Sun, Chunrui Han, and Xiangyu Zhang.* **OneChart: Purify the Chart Structural Extraction via One Auxiliary Token** <img src='https://img.shields.io/badge/ACM_MM-Oral-2024-yellow'> <a href='https://arxiv.org/abs/2404.09987'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/LingyvKong/OneChart'><img src='https://img.shields.io/badge/Code-orange'></a> <a href='https://drive.google.com/drive/folders/1YmOvxq0DfOA9YKoyCZDjpnTIkPNoyegQ'><img src='https://img.shields.io/badge/Dataset-red'></a>


## Visual Question Answering over Charts (ChartQA)
- *Wonjoong Kim, Sangwu Park, Yeonjun In, Seokwon Han, and Chanyoung Park.* **SIMPLOT: Enhancing Chart Question Answering by Distilling Essentials** <img src='https://img.shields.io/badge/TVCG-2024-yellow'> <a href='https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10670526'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Zeng, Xingchen, Lin Haichuan, Ye Yilin, and Zeng Wei.* **Advancing Multimodal Large Language Models in Chart Question Answering with Visualization-Referenced Instruction Tuning** <img src='https://img.shields.io/badge/TVCG-2024-yellow'> <a href='https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10670526'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/zengxingchen/ChartQA-MLLM'><img src='https://img.shields.io/badge/Code-orange'></a>

- *Li, Zhuowan, Bhavan Jasani, Peng Tang, and Shabnam Ghadar.* **Synthesize Step-by-Step: Tools, Templates and LLMs as Data Generators for Reasoning-Based Chart VQA** <img src='https://img.shields.io/badge/CVPR-2024-yellow'> <a href='https://openaccess.thecvf.com/content/CVPR2024/papers/Li_Synthesize_Step-by-Step_Tools_Templates_and_LLMs_as_Data_Generators_for_CVPR_2024_paper.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>


- *Masry, Ahmed, Do Xuan Long, Jia Qing Tan, Shafiq Joty, and Enamul Hoque.* **ChartQA: A Benchmark for Question Answering about Charts with Visual and Logical Reasoning** <img src='https://img.shields.io/badge/ACL_Findings-2022-yellow'> <a href='https://aclanthology.org/2022.findings-acl.177/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/vis-nlp/ChartQA'><img src='https://img.shields.io/badge/Dataset-red'></a> <img src='https://img.shields.io/badge/Benchmark-green'>

- *Kantharaj, Shankar, Xuan Long Do, Rixie Tiffany Ko Leong, Jia Qing Tan, Enamul Hoque, and Shafiq Joty.* **OpenCQA: Open-ended Question Answering with Charts** <img src='https://img.shields.io/badge/EMNLP-2022-yellow'> <a href='https://aclanthology.org/2022.emnlp-main.811/'><img src='https://img.shields.io/badge/Paper-purple'></a>  <a href='https://github.com/vis-nlp/OpenCQA'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Kim, Dae Hyun, Enamul Hoque, and Maneesh Agrawala.* **Answering Questions about Charts and Generating Visual Explanations** <img src='https://img.shields.io/badge/CHI-2020-yellow'> <a href='https://dl.acm.org/doi/10.1145/3313831.3376467/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/dhkim16/VisQA-release'><img src='https://img.shields.io/badge/Code-orange'></a> <a href='https://github.com/dhkim16/VisQA-release'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Singh, Hrituraj, and Sumit Shekhar.* **STL-CQA: Structure-based Transformers with Localization and Encoding for Chart Question Answering** <img src='https://img.shields.io/badge/EMNLP-2020-yellow'> <a href='https://aclanthology.org/2020.emnlp-main.264/'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Chaudhry, Ritwick, Sumit Shekhar, Utkarsh Gupta, Pranav Maneriker, Prann Bansal, and Ajay Joshi.* **LEAF-QA: Locate, Encode & Attend for Figure Question Answering** <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://openaccess.thecvf.com/content_WACV_2020/papers/Chaudhry_LEAF-QA_Locate_Encode__Attend_for_Figure_Question_Answering_WACV_2020_paper.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Methani, Nitesh, Pritha Ganguly, Mitesh M. Khapra, and Pratyush Kumar.* **PlotQA: Reasoning over Scientific Plots**
  <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://arxiv.org/abs/1909.00997'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/NiteshMethani/PlotQA'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Kafle, Kushal, Robik Shrestha, Scott Cohen, Brian Price, and Christopher Kanan.* **Answering Questions about Data Visualizations using Efficient Bimodal Fusion** <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://openaccess.thecvf.com/content_WACV_2020/papers/Kafle_Answering_Questions_about_Data_Visualizations_using_Efficient_Bimodal_Fusion_WACV_2020_paper.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/kushalkafle/PReFIL'><img src='https://img.shields.io/badge/Code-orange'></a>

- *Kafle, Kushal, Brian Price, Scott Cohen, and Christopher Kanan.* **DVQA: Understanding Data Visualizations via Question Answering** <img src='https://img.shields.io/badge/CVPR-2018-yellow'> <a href='https://openaccess.thecvf.com/content_cvpr_2018/papers/Kafle_DVQA_Understanding_Data_CVPR_2018_paper.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>
  <a href='https://github.com/kushalkafle/DVQA_dataset'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Kahou, Samira Ebrahimi, Vincent Michalski, Adam Atkinson, Ákos Kádár, Adam Trischler, and Yoshua Bengio.* **FigureQA: An Annotated Figure Dataset for Visual Reasoning** <img src='https://img.shields.io/badge/ICLR_Workshop-2018-yellow'> <a href='https://arxiv.org/abs/1710.07300'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://www.microsoft.com/en-us/research/project/figureqa-dataset/'><img src='https://img.shields.io/badge/Dataset-red'></a>

## Chart Captioning (Summarization)
- *Huang, Kung-Hsiang, Mingyang Zhou, Hou Pong Chan, Yi R. Fung, Zhenhailong Wang, Lingyu Zhang, Shih-Fu Chang, and Heng Ji.* **Do LVLMs Understand Charts? Analyzing and Correcting Factual Errors in Chart Captioning** <img src='https://img.shields.io/badge/ACL_Findings-2024-yellow'> <a href='Do LVLMs Understand Charts? Analyzing and Correcting Factual Errors in Chart Captioning'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://huggingface.co/datasets/khhuang/CHOCOLATE'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Tang, Benny J., Angie Boggust, and Arvind Satyanarayan.* **VisText: A Benchmark for Semantically Rich Chart Captioning** <img src='https://img.shields.io/badge/ACL-2023-yellow'> <a href='https://aclanthology.org/2023.acl-long.401/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/mitvis/vistext'><img src='https://img.shields.io/badge/Dataset-red'></a> <img src='https://img.shields.io/badge/Benchmark-green'>

- *Islam, Saad Obaid Ul, Iza Škrjanec, Ondřej Dušek, and Vera Demberg.* **Tackling Hallucinations in Neural Chart Summarization** <img src='https://img.shields.io/badge/INLG-2023-yellow'> <a href='https://aclanthology.org/2023.inlg-main.30/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='[https://github.com/JasonObeid/Chart2Text](https://github.com/WorldHellow/Hallucinations-C2T)'><img src='https://img.shields.io/badge/Code-orange'></a>

- *Rahman, Raian, Rizvi Hasan, Abdullah Al Farhad, Md Tahmid Rahman Laskar, Md Hamjajul Ashmafee, and Abu Raihan Mostofa Kamal.* **ChartSumm: A Comprehensive Benchmark for Automatic Chart Summarization of Long and Short Summaries** <img src='https://img.shields.io/badge/CANAI-2023-yellow'> <a href='https://caiac.pubpub.org/pub/ujhjycsw/release/1'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/pranonrahman/ChartSumm'><img src='https://img.shields.io/badge/Dataset-red'></a> <img src='https://img.shields.io/badge/Benchmark-green'>

- *Singh, Ashish, Prateek Agarwal, Zixuan Huang, Arpita Singh, Tong Yu, Sungchul Kim, Victor Bursztyn, Nikos Vlassis, and Ryan A. Rossi.* **FigCaps-HF: A Figure-to-Caption Generative Framework and Benchmark with Human Feedback** <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2307.10867'><img src='https://img.shields.io/badge/Paper-purple'></a>
  <a href='https://figcapshf.github.io/'><img src='https://img.shields.io/badge/Dataset-red'></a> <img src='https://img.shields.io/badge/Benchmark-green'>

- *Mahinpei, Anita, Zona Kostic, and Chris Tanner.* **LineCap: Line Charts for Data Visualization Captioning Models** <img src='https://img.shields.io/badge/IEEE_VIS-2022-yellow'> <a href='https://ieeexplore.ieee.org/abstract/document/9973197'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/anita76/LineCapDataset'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Hsu, Ting-Yao, C. Lee Giles, and Ting-Hao'Kenneth Huang.* **Scicap:Generating captions for scientific Figures** <img src='https://img.shields.io/badge/EMNLP-2021-yellow'> <a href='https://aclanthology.org/2021.findings-emnlp.277/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/tingyaohsu/scicap'><img src='https://img.shields.io/badge/Code-orange'></a> <a href='https://paperswithcode.com/dataset/scicap'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Seweryn, Karolina, Katarzyna Lorenc, Anna Wróblewska, and Sylwia Sysko-Romańczuk.* **What Will You Tell Me About the Chart? – Automated Description of Charts** <img src='https://img.shields.io/badge/ICONIP-2021-yellow'> <a href='https://link.springer.com/chapter/10.1007/978-3-030-92307-5_2'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Kantharaj, Shankar, Rixie Tiffany Ko Leong, Xiang Lin, Ahmed Masry, Megh Thakkar, Enamul Hoque, and Shafiq Joty.* **Chart-to-Text: A Large-Scale Benchmark for Chart Summarization** <img src='https://img.shields.io/badge/ACL-2022-yellow'> <a href='https://aclanthology.org/2022.acl-long.277/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/vis-nlp/Chart-to-text'><img src='https://img.shields.io/badge/Dataset-red'></a> <img src='https://img.shields.io/badge/Benchmark-green'>

- *Obeid, Jason, and Enamul Hoque.* **Chart-to-Text: Generating Natural Language Descriptions for Charts by Adapting the Transformer Model** <img src='https://img.shields.io/badge/INLG-2020-yellow'> <a href='https://aclanthology.org/2020.inlg-1.20/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/JasonObeid/Chart2Text'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Chen, Charles, Ruiyi Zhang, Eunyee Koh, Sungchul Kim, Scott Cohen, and Ryan Rossi.* **Figure Captioning with Relation Maps for Reasoning** <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://openaccess.thecvf.com/content_WACV_2020/papers/Chen_Figure_Captioning_with_Relation_Maps_for_Reasoning_WACV_2020_paper.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Obeid, Jason, and Enamul Hoque.* **Chart-to-Text: Generating Natural Language Descriptions for Charts by Adapting the Transformer Model** <img src='https://img.shields.io/badge/INLG-2020-yellow'> <a href='https://aclanthology.org/2020.inlg-1.20/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/JasonObeid/Chart2Text'><img src='https://img.shields.io/badge/Dataset-red'></a>


## Chart Reverse Engineering



## Benchmarks, Evaluation & Surveys
- *Wu, Yifan, Lutao Yan, Yuyu Luo, Yunhai Wang, and Nan Tang.* **Evaluating Task-based Effectiveness of MLLMs on Charts** <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2405.07001'><img src='https://img.shields.io/badge/Paper-purple'></a>  <a href='https://anonymous.4open.science/r/ChartInsights-D43E'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Xu, Zhengzhuo, Sinan Du, Yiyan Qi, Chengjin Xu, Chun Yuan, and Jian Guo.* **ChartBench: A Benchmark for Complex Visual Reasoning in Charts** <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2312.15915'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://huggingface.co/datasets/SincereX/ChartBench'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Singh, Ashish, Prateek Agarwal, Zixuan Huang, Arpita Singh, Tong Yu, Sungchul Kim, Victor Bursztyn, Nikos Vlassis, and Ryan A. Rossi.* **FigCaps-HF: A Figure-to-Caption Generative Framework and Benchmark with Human Feedback** <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2307.10867'><img src='https://img.shields.io/badge/Paper-purple'></a>
  <a href='https://figcapshf.github.io/'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Kantharaj, Shankar, Rixie Tiffany Ko Leong, Xiang Lin, Ahmed Masry, Megh Thakkar, Enamul Hoque, and Shafiq Joty.* **Chart-to-Text: A Large-Scale Benchmark for Chart Summarization** <img src='https://img.shields.io/badge/ACL-2022-yellow'> <a href='https://aclanthology.org/2022.acl-long.277/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/vis-nlp/Chart-to-text'><img src='https://img.shields.io/badge/Dataset-red'></a>




## Contributing
👍 Contributions to this repository are welcome! 

If you have come across relevant resources, feel free to open an issue or submit a pull request.

📌 For example：

```
- *Author1, Author2, Author3, ...*  **Paper Title (bolded)** <img src='https://img.shields.io/badge/Conference_Journal_Name-Year-Color'><a href='PDF_Link'><img src='https://img.shields.io/badge/Paper-purple'></a><a href='Code_Link'><img src='https://img.shields.io/badge/Code-orange'></a><a href='Dataset_Link'><img src='https://img.shields.io/badge/Dataset-red'></a><img src='https://img.shields.io/badge/Benchmark-green'>

```

[#contributing]: #-contributing
[#benchmarks--surveys]: #-benchmarks--surveys
