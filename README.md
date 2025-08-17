# Awesome-LLM-for-Chart [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated collection of papers and resources on applying **Large Language Models** (LLMs) to various aspects of Chart Understanding, including **chart-based question answering, chart captioning, reverse engineering, and evaluation benchmarks**.

Recent advances in LLMs have showcased remarkable capabilities across language, vision, and multimodal tasks. Among them, interpreting and reasoning over data visualizations—such as charts, plots, and graphs—has emerged as a vital frontier. This repository bridges the domains of LLMs and Chart Understanding by organizing state-of-the-art research across multiple topics, including: Chart Understanding, Chart Question Answering, Chart Captioning for summarizing chart content, Chart Reverse Engineering for recovering underlying data and structure, Benchmarks, Evaluation, and Surveys for assessing model performance and research trends.

## Table of Contents

- [Awesome-LLM-for-Chart ](#awesome-llm-for-chart-)
  - [Table of Contents](#table-of-contents)
  - [Chart Understanding](#chart-understanding)
  - [Visual Question Answering over Charts (ChartQA)](#visual-question-answering-over-charts-chartqa)
  - [Chart Captioning (Summarization)](#chart-captioning-summarization)
  - [Chart Reverse Engineering](#chart-reverse-engineering)
  - [Benchmarks, Evaluation \& Surveys](#benchmarks-evaluation--surveys)
    - [Benchmarks](#benchmarks)
    - [Evaluation](#evaluation)
    - [Surveys](#surveys)
  - [Contributing](#contributing)


## Chart Understanding

- *Wang, Huichen Will, Jane Hoffswell, Victor S. Bursztyn, and Cindy Xiong Bearfield.* **How Aligned are Human Chart Takeaways and LLM Predictions? A Case Study on Bar Charts with Varying Layouts** <img src='https://img.shields.io/badge/TVCG-2025-yellow'> <a href='https://ieeexplore.ieee.org/document/10681139'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Xu, Zhengzhuo, Bowen Qu, Yiyan Qi, Sinan Du, Chengjin Xu, Chun Yuan, and Jian Guo.* **ChartMoE: Mixture of Expert Connector for Advanced Chart Understanding** <img src='https://img.shields.io/badge/ICLR-2025-yellow'> <a href='https://openreview.net/pdf?id=o5TsWTUSeF'> <img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/IDEA-FinAI/ChartMoE'><img src='https://img.shields.io/badge/Code-orange'></a> <a href='https://huggingface.co/datasets/Coobiw/ChartMoE-Data'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Huang, Kung-Hsiang, Can Qin, Haoyi Qiu, Philippe Laban, Shafiq Joty, Caiming Xiong, and Chien-Sheng Wu.* **Why Vision Language Models Struggle with Visual Arithmetic? Towards Enhanced Chart and Geometry Understanding** <img src='https://img.shields.io/badge/ACL_Findings-2025-yellow'> <a href='https://arxiv.org/abs/2502.11492'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://huggingface.co/Salesforce/cogalign-internvl2_5-mpo-4b'><img src='https://img.shields.io/badge/Model-orange'></a> <a href='https://huggingface.co/datasets/Salesforce/CogAlign'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Liu, Junteng, Weihao Zeng, Xiwen Zhang, Yijun Wang, Zifei Shan, and Junxian He.* **On the Perception Bottleneck of VLMs for Chart Understanding** <img src='https://img.shields.io/badge/Arxiv-2025-yellow'> <a href='https://arxiv.org/pdf/2503.18435'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Hu, Linmei, Duokang Wang, Yiming Pan, Jifan Yu, Yingxia Shao, Chong Feng, and Liqiang Nie.* **NovaChart: A Large-scale Dataset towards Chart Understanding and Generation of Multimodal Large Language Models** <img src='https://img.shields.io/badge/ACM_MM-2024-yellow'> <a href='https://dl.acm.org/doi/10.1145/3664647.3680790'> <img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/Elucidator-V/NovaChart'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Zhang, Liang, Anwen Hu, Haiyang Xu, Ming Yan, Yichen Xu, Qin Jin, Ji Zhang, and Fei Huang.* **TinyChart: Efficient Chart Understanding with Visual Token Merging and Program-of-Thoughts Learning** <img src='https://img.shields.io/badge/EMNLP-2024-yellow'> <a href='https://aclanthology.org/2024.emnlp-main.112.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/X-PLUG/mPLUG-DocOwl/tree/main/TinyChart'><img src='https://img.shields.io/badge/Model-orange'></a>

- *Liu, Fuxiao, Xiaoyang Wang, Wenlin Yao, Jianshu Chen, Kaiqiang Song, Sangwoo Cho, Yaser Yacoob, and Dong Yu.* **MMC: Advancing Multimodal Chart Understanding with Large-scale Instruction Tuning** <img src='https://img.shields.io/badge/NAACL-2024-yellow'> <a href='https://arxiv.org/abs/2311.10774'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/FuxiaoLiu/MMC'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Fan, Wan-Cyuan, Yen-Chun Chen, Mengchen Liu, Lu Yuan, and Leonid Sigal.* **On Pre-training of Multimodal Language Models Customized for Chart Understanding** <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2407.14506'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Masry, Ahmed, Parsa Kavehzadeh, Xuan Long Do, Enamul Hoque, and Shafiq Joty.* **UniChart: A Universal Vision-language Pretrained Model for Chart Comprehension and Reasoning** <img src='https://img.shields.io/badge/EMNLP-2023-yellow'> <a href='https://aclanthology.org/2023.emnlp-main.906/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/vis-nlp/UniChart'><img src='https://img.shields.io/badge/Code-orange'></a>

- *Lee, Kenton, Mandar Joshi, Iulia Raluca Turc, Hexiang Hu, Fangyu Liu, Julian Martin Eisenschlos, Urvashi Khandelwal, Peter Shaw, Ming-Wei Chang, and Kristina Toutanova.* **Pix2Struct: Screenshot Parsing as Pretraining for Visual Language Understanding** <img src='https://img.shields.io/badge/ICML-2023-yellow'> <a href='https://proceedings.mlr.press/v202/lee23g/lee23g.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://huggingface.co/google/pix2struct-base'><img src='https://img.shields.io/badge/Code-orange'></a>

- *Zhou, Mingyang, Yi R. Fung, Long Chen, Christopher Thomas, Heng Ji, and Shih-Fu Chang.* **Enhanced Chart Understanding via Visual Language Pre-training on Plot Table Pairs** <img src='https://img.shields.io/badge/ACL_Findings-2023-yellow'> <a href='https://aclanthology.org/2023.findings-acl.85/'><img src='https://img.shields.io/badge/Paper-purple'></a>
  <a href='https://github.com/zmykevin/ACL2023_ChartT5'><img src='https://img.shields.io/badge/Code-orange'></a>

- *Wang, Zirui, Mengzhou Xia, Luxi He, Howard Chen, Yitao Liu, Richard Zhu, Kaiqu Liang et al.* **CharXiv: Charting Gaps in Realistic Chart Understanding in Multimodal LLMs** <img src='https://img.shields.io/badge/NIPS-2024-yellow'> <a href='https://proceedings.neurips.cc/paper_files/paper/2024/file/cdf6f8e9fd9aeaf79b6024caec24f15b-Paper-Datasets_and_Benchmarks_Track.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>  <a href='https://huggingface.co/datasets/princeton-nlp/CharXiv'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Han, Yucheng, Chi Zhang, Xin Chen, Xu Yang, Zhibin Wang, Gang Yu, Bin Fu, and Hanwang Zhang.* **ChartLlama: A Multimodal LLM for Chart Understanding and Generation** <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2311.16483'> <img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/tingxueronghua/ChartLlama-code'><img src='https://img.shields.io/badge/Code-orange'></a> <a href='https://huggingface.co/datasets/listen2you002/ChartLlama-Dataset'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Xia, Renqiu, Bo Zhang, Haoyang Peng, Hancheng Ye, Xiangchao Yan, Peng Ye, Botian Shi, Yu Qiao, and Junchi Yan.* **StructChart: On the Schema, Metric, and Augmentation for Visual Chart Understanding** <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2309.11268'><img src='https://img.shields.io/badge/Paper-purple'></a>



## Visual Question Answering over Charts (ChartQA)

- *Huang, Muye, Lingling Zhang, Han Lai, Wenjun Wu, Xinyu Zhang, and Jun Liu.* **VProChart: Answering Chart Question through Visual Perception Alignment Agent and Programmatic Solution Reasoning** <img src='https://img.shields.io/badge/AAAI-2025-yellow'> <a href='https://ojs.aaai.org/index.php/AAAI/article/view/32384'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/MuyeHuang/VProChart'><img src='https://img.shields.io/badge/Model-orange'></a>

- *Ford, James, Xingmeng Zhao, Dan Schumacher, and Anthony Rios.* **Charting the Future: Using Chart Question-Answering for Scalable Evaluation of LLM-Driven Data Visualizations** <img src='https://img.shields.io/badge/COLING-2025-yellow'> <a href='https://aclanthology.org/2025.coling-main.501.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Masry, Ahmed, Megh Thakkar, Aayush Bajaj, Aaryaman Kartha, Enamul Hoque, and Shafiq Joty.* **ChartGemma: Visual Instruction-tuning for Chart Reasoning in the Wild** <img src='https://img.shields.io/badge/COLING-2025-yellow'> <a href='https://aclanthology.org/2025.coling-industry.54.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://huggingface.co/ahmed-masry/chartgemma'><img src='https://img.shields.io/badge/Model-orange'></a> <a href='https://huggingface.co/datasets/ahmed-masry/ChartGemma'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Masry, Ahmed, Do Xuan Long, Jia Qing Tan, Shafiq Joty, and Enamul Hoque.* **ChartQAPro: A More Diverse and Challenging Benchmark for Chart Question Answering** <img src='https://img.shields.io/badge/Arxiv_2025-yellow'> <a href='https://arxiv.org/abs/2504.05506v2'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/vis-nlp/ChartQAPro'><img src='https://img.shields.io/badge/Code-orange'></a> <a href='https://huggingface.co/datasets/ahmed-masry/ChartQAPro'><img src='https://img.shields.io/badge/Dataset-red'></a> <img src='https://img.shields.io/badge/Benchmark-green'>

- *Wonjoong Kim, Sangwu Park, Yeonjun In, Seokwon Han, and Chanyoung Park.* **SIMPLOT: Enhancing Chart Question Answering by Distilling Essentials** <img src='https://img.shields.io/badge/TVCG-2024-yellow'> <a href='https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10670526'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Zeng, Xingchen, Lin Haichuan, Ye Yilin, and Zeng Wei.* **Advancing Multimodal Large Language Models in Chart Question Answering with Visualization-Referenced Instruction Tuning** <img src='https://img.shields.io/badge/TVCG-2024-yellow'> <a href='https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10670526'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/zengxingchen/ChartQA-MLLM'><img src='https://img.shields.io/badge/Code-orange'></a>

- *Li, Zhuowan, Bhavan Jasani, Peng Tang, and Shabnam Ghadar.* **Synthesize Step-by-Step: Tools, Templates and LLMs as Data Generators for Reasoning-Based Chart VQA** <img src='https://img.shields.io/badge/CVPR-2024-yellow'> <a href='https://openaccess.thecvf.com/content/CVPR2024/papers/Li_Synthesize_Step-by-Step_Tools_Templates_and_LLMs_as_Data_Generators_for_CVPR_2024_paper.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Bursztyn, Victor Soares, Jane Hoffswell, Eunyee Koh, and Shunan Guo.* **Representing Charts as Text for Language Models: An In-Depth Study of Question Answering for Bar Charts** <img src='https://img.shields.io/badge/VIS_Short_Paper-2024-yellow'> <a href='https://ieeexplore.ieee.org/document/10771151'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Masry, Ahmed, Mehrad Shahmohammadi, Md Rizwan Parvez, Enamul Hoque, and Shafiq Joty.* **ChartInstruct: Instruction Tuning for Chart Comprehension and Reasoning** <img src='https://img.shields.io/badge/ACL Findings-2024-yellow'> <a href='https://aclanthology.org/2024.findings-acl.619.pdf'> <img src='https://img.shields.io/badge/Paper-purple'></a>  <a href='https://github.com/vis-nlp/ChartInstruct'><img src='https://img.shields.io/badge/Model-orange'></a>

- *Wu, Yifan, Lutao Yan, Leixian Shen, Yunhai Wang, Nan Tang, and Yuyu Luo.* **ChartInsights: Evaluating Multimodal Large Language Models for Low-Level Chart Question Answering** <img src='https://img.shields.io/badge/EMNLP-2024-yellow'> <a href='https://aclanthology.org/2024.findings-emnlp.710/'> <img src='https://img.shields.io/badge/Paper-purple'></a>  <a href='https://github.com/ChartInsight'><img src='https://img.shields.io/badge/Code-orange'></a> <a href='https://github.com/ChartInsight/chartinsight/tree/main/Dataset'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Zhang, Wenqi, Zhenglin Cheng, Yuanyu He, Mengna Wang, Yongliang Shen, Zeqi Tan, Guiyang Hou et al.* **Multimodal Self-Instruct: Synthetic Abstract Image and Visual Reasoning Instruction Using Language Model** <img src='https://img.shields.io/badge/EMNLP-2024-yellow'> <a href='https://aclanthology.org/2024.emnlp-main.1072.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/zwq2018/Multi-modal-Self-instruct'><img src='https://img.shields.io/badge/Code-orange'></a> <a href='https://huggingface.co/datasets/zwq2018/Multi-modal-Self-instruct'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Carbune, Victor, Hassan Mansoor, Fangyu Liu, Rahul Aralikatte, Gilles Baechler, Jindong Chen, and Abhanshu Sharma.* **Chart-based Reasoning: Transferring Capabilities from LLMs to VLMs** <img src='https://img.shields.io/badge/NAACL Findings-2024-yellow'> <a href='https://aclanthology.org/2024.findings-naacl.62.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Liu, Fuxiao, Xiaoyang Wang, Wenlin Yao, Jianshu Chen, Kaiqiang Song, Sangwoo Cho, Yaser Yacoob, and Dong Yu.* **MMC: Advancing Multimodal Chart Understanding with Large-scale Instruction Tuning** <img src='https://img.shields.io/badge/NAACL-2024-yellow'> <a href='https://arxiv.org/abs/2311.10774'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/FuxiaoLiu/MMC'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Yang, Xudong, Yifan Wu, Yizhang Zhu, Nan Tang, and Yuyu Luo.* **AskChart: Universal Chart Understanding through Textual Enhancement** <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2412.19146'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Fan, Wan-Cyuan, Yen-Chun Chen, Mengchen Liu, Lu Yuan, and Leonid Sigal.* **On Pre-training of Multimodal Language Models Customized for Chart Understanding** <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2407.14506'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *He, Wei, Zhiheng Xi, Wanxu Zhao, Xiaoran Fan, Yiwen Ding, Zifei Shan, Tao Gui, Qi Zhang, and Xuanjing Huang.* **Distill Visual Chart Reasoning Ability from LLMs to MLLMs** <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2410.18798'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/hewei2001/ReachQA'><img src='https://img.shields.io/badge/Code-orange'></a> <a href='https://huggingface.co/datasets/hewei2001/ReachQA'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Liu, Fangyu, Francesco Piccinno, Syrine Krichene, Chenxi Pang, Kenton Lee, Mandar Joshi, Yasemin Altun, Nigel Collier, and Julian Martin Eisenschlos.* **MatCha: Enhancing Visual Language Pretraining with Math Reasoning and Chart Derendering** <img src='https://img.shields.io/badge/ACL-2023-yellow'> <a href='https://aclanthology.org/2023.acl-long.714.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Liu, Fangyu, Julian Martin Eisenschlos, Francesco Piccinno, Syrine Krichene, Chenxi Pang, Kenton Lee, Mandar Joshi, Wenhu Chen, Nigel Collier, and Yasemin Altun.* **Deplot: One-shot visual language reasoning by plot-to-table translation** <img src='https://img.shields.io/badge/ACL_Findings-2023-yellow'> <a href='https://aclanthology.org/2023.findings-acl.660.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/google-research/google-research/tree/master/deplot'><img src='https://img.shields.io/badge/Code-orange'></a>

- *Masry, Ahmed, Do Xuan Long, Jia Qing Tan, Shafiq Joty, and Enamul Hoque.* **ChartQA: A Benchmark for Question Answering about Charts with Visual and Logical Reasoning** <img src='https://img.shields.io/badge/ACL_Findings-2022-yellow'> <a href='https://aclanthology.org/2022.findings-acl.177/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/vis-nlp/ChartQA'><img src='https://img.shields.io/badge/Dataset-red'></a> <img src='https://img.shields.io/badge/Benchmark-green'>

- *Kantharaj, Shankar, Xuan Long Do, Rixie Tiffany Ko Leong, Jia Qing Tan, Enamul Hoque, and Shafiq Joty.* **OpenCQA: Open-ended Question Answering with Charts** <img src='https://img.shields.io/badge/EMNLP-2022-yellow'> <a href='https://aclanthology.org/2022.emnlp-main.811/'><img src='https://img.shields.io/badge/Paper-purple'></a>  <a href='https://github.com/vis-nlp/OpenCQA'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Hoque, Enamul, Parsa Kavehzadeh, and Ahmed Masry.* **Chart Question Answering: State of the Art and Future Directions** <img src='https://img.shields.io/badge/CGF-2022-yellow'> <a href='https://arxiv.org/pdf/2205.03966'><img src='https://img.shields.io/badge/Paper-purple'></a>

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
- *Lim, Junyoung, Jaewoo Ahn, and Gunhee Kim.* **ChartCap: Mitigating Hallucination of Dense Chart Captioning** <img src='https://img.shields.io/badge/ICCV-2025-yellow'> <a href='https://arxiv.org/pdf/2508.03164'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Ko, Hyung-Kwon, Hyeon Jeon, Gwanmo Park, Dae Hyun Kim, Nam Wook Kim, Juho Kim, and Jinwook Seo.* **Natural Language Dataset Generation Framework for Visualizations Powered by Large Language Models** <img src='https://img.shields.io/badge/CHI-2024-yellow'> <a href='https://dl.acm.org/doi/pdf/10.1145/3613904.3642943'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/hyungkwonko/chart-llm'><img src='https://img.shields.io/badge/Code-orange'></a> <a href='https://dl.acm.org/doi/10.1145/3613904.3642943'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Huang, Kung-Hsiang, Mingyang Zhou, Hou Pong Chan, Yi R. Fung, Zhenhailong Wang, Lingyu Zhang, Shih-Fu Chang, and Heng Ji.* **Do LVLMs Understand Charts? Analyzing and Correcting Factual Errors in Chart Captioning** <img src='https://img.shields.io/badge/ACL_Findings-2024-yellow'> <a href='Do LVLMs Understand Charts? Analyzing and Correcting Factual Errors in Chart Captioning'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://huggingface.co/datasets/khhuang/CHOCOLATE'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Masry, Ahmed, Mehrad Shahmohammadi, Md Rizwan Parvez, Enamul Hoque, and Shafiq Joty.* **ChartInstruct: Instruction Tuning for Chart Comprehension and Reasoning** <img src='https://img.shields.io/badge/ACL Findings-2024-yellow'> <a href='https://aclanthology.org/2024.findings-acl.619.pdf'> <img src='https://img.shields.io/badge/Paper-purple'></a>  <a href='https://github.com/vis-nlp/ChartInstruct'><img src='https://img.shields.io/badge/Model-orange'></a>

- *Liu, Mengsha, Daoyuan Chen, Yaliang Li, Guian Fang, and Ying Shen.* **ChartThinker: A Contextual Chain-of-Thought Approach to Optimized Chart Summarization** <img src='https://img.shields.io/badge/LREC COLING-2024-yellow'> <a href='https://aclanthology.org/2024.lrec-main.273.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/Notonion/ChartThinker'><img src='https://img.shields.io/badge/Code-orange'></a> <a href='https://huggingface.co/datasets/ChartThinker/Chart-Sum-QA'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Xu, Peixin, Yujuan Ding, and Wenqi Fan.* **ChartAdapter: Large Vision-Language Model for Chart Summarization** <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2412.20715'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Tang, Benny J., Angie Boggust, and Arvind Satyanarayan.* **VisText: A Benchmark for Semantically Rich Chart Captioning** <img src='https://img.shields.io/badge/ACL-2023-yellow'> <a href='https://aclanthology.org/2023.acl-long.401/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/mitvis/vistext'><img src='https://img.shields.io/badge/Dataset-red'></a> <img src='https://img.shields.io/badge/Benchmark-green'>

- *Islam, Saad Obaid Ul, Iza Škrjanec, Ondřej Dušek, and Vera Demberg.* **Tackling Hallucinations in Neural Chart Summarization** <img src='https://img.shields.io/badge/INLG_SIGDIAL-2023-yellow'> <a href='https://aclanthology.org/2023.inlg-main.30/'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Rahman, Raian, Rizvi Hasan, Abdullah Al Farhad, Md Tahmid Rahman Laskar, Md Hamjajul Ashmafee, and Abu Raihan Mostofa Kamal.* **ChartSumm: A Comprehensive Benchmark for Automatic Chart Summarization of Long and Short Summaries** <img src='https://img.shields.io/badge/CANAI-2023-yellow'> <a href='https://caiac.pubpub.org/pub/ujhjycsw/release/1'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/pranonrahman/ChartSumm'><img src='https://img.shields.io/badge/Dataset-red'></a> <img src='https://img.shields.io/badge/Benchmark-green'>

- *Singh, Ashish, Prateek Agarwal, Zixuan Huang, Arpita Singh, Tong Yu, Sungchul Kim, Victor Bursztyn, Nikos Vlassis, and Ryan A. Rossi.* **FigCaps-HF: A Figure-to-Caption Generative Framework and Benchmark with Human Feedback** <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2307.10867'><img src='https://img.shields.io/badge/Paper-purple'></a>
  <a href='https://figcapshf.github.io/'><img src='https://img.shields.io/badge/Dataset-red'></a> <img src='https://img.shields.io/badge/Benchmark-green'>

- *Mahinpei, Anita, Zona Kostic, and Chris Tanner.* **LineCap: Line Charts for Data Visualization Captioning Models** <img src='https://img.shields.io/badge/IEEE_VIS-2022-yellow'> <a href='https://ieeexplore.ieee.org/abstract/document/9973197'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/anita76/LineCapDataset'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Kantharaj, Shankar, Rixie Tiffany Ko Leong, Xiang Lin, Ahmed Masry, Megh Thakkar, Enamul Hoque, and Shafiq Joty.* **Chart-to-Text: A Large-Scale Benchmark for Chart Summarization** <img src='https://img.shields.io/badge/ACL-2022-yellow'> <a href='https://aclanthology.org/2022.acl-long.277/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/vis-nlp/Chart-to-text'><img src='https://img.shields.io/badge/Dataset-red'></a> <img src='https://img.shields.io/badge/Benchmark-green'>

- *Hsu, Ting-Yao, C. Lee Giles, and Ting-Hao'Kenneth Huang.* **Scicap:Generating captions for scientific Figures** <img src='https://img.shields.io/badge/EMNLP-2021-yellow'> <a href='https://aclanthology.org/2021.findings-emnlp.277/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/tingyaohsu/scicap'><img src='https://img.shields.io/badge/Code-orange'></a> <a href='https://paperswithcode.com/dataset/scicap'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Seweryn, Karolina, Katarzyna Lorenc, Anna Wróblewska, and Sylwia Sysko-Romańczuk.* **What Will You Tell Me About the Chart? – Automated Description of Charts** <img src='https://img.shields.io/badge/ICONIP-2021-yellow'> <a href='https://link.springer.com/chapter/10.1007/978-3-030-92307-5_2'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Obeid, Jason, and Enamul Hoque.* **Chart-to-Text: Generating Natural Language Descriptions for Charts by Adapting the Transformer Model** <img src='https://img.shields.io/badge/INLG-2020-yellow'> <a href='https://aclanthology.org/2020.inlg-1.20/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/JasonObeid/Chart2Text'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Chen, Charles, Ruiyi Zhang, Eunyee Koh, Sungchul Kim, Scott Cohen, and Ryan Rossi.* **Figure Captioning with Relation Maps for Reasoning** <img src='https://img.shields.io/badge/WACV-2020-yellow'> <a href='https://openaccess.thecvf.com/content_WACV_2020/papers/Chen_Figure_Captioning_with_Relation_Maps_for_Reasoning_WACV_2020_paper.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>



## Chart Reverse Engineering
- *Zhou, Zhiguang, Haoxuan Wang, Zhengqing Zhao, Fengling Zheng, Yongheng Wang, Wei Chen, and Yong Wang.* **ChartKG: A Knowledge-Graph-Based Representation for Chart Images** <img src='https://img.shields.io/badge/TVCG_2024-yellow'> <a href='https://ieeexplore.ieee.org/document/10711251'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Ying, Lu, Yun Wang, Haotian Li, Shuguang Dou, Haidong Zhang, Xinyang Jiang, Huamin Qu, and Yingcai Wu.* **Reviving Static Charts into Live Charts** <img src='https://img.shields.io/badge/TVCG_2024-yellow'> <a href='https://ieeexplore.ieee.org/document/10530507'><img src='https://img.shields.io/badge/Paper-purple'></a>
  
- *Lu, Pan, Hritik Bansal, Tony Xia, Jiacheng Liu, Chunyuan Li, Hannaneh Hajishirzi, Hao Cheng, Kai-Wei Chang, Michel Galley, and Jianfeng Gao.* **MathVista: Evaluating Math Reasoning in Visual Contexts with GPT-4V, Bard, and Other Large Multimodal Models** <img src='https://img.shields.io/badge/ICLR-2024-yellow'> <a href='https://arxiv.org/abs/2310.02255'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://huggingface.co/datasets/AI4Math/MathVista'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Meng, Fanqing, Wenqi Shao, Quanfeng Lu, Peng Gao, Kaipeng Zhang, Yu Qiao, and Ping Luo.* **ChartAssistant: A Universal Chart Multimodal Language Model via Chart-to-Table Pre-training and Multitask Instruction Tuning** <img src='https://img.shields.io/badge/ACL Findings-2024-yellow'> <a href='https://aclanthology.org/2024.findings-acl.463.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/OpenGVLab/ChartAst'><img src='https://img.shields.io/badge/Code-orange'></a> <a href='https://huggingface.co/datasets/FanqingM/ChartAssistant'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Chen, Jinyue, Lingyu Kong, Haoran Wei, Chenglong Liu, Zheng Ge, Liang Zhao, Jianjian Sun, Chunrui Han, and Xiangyu Zhang.* **OneChart: Purify the Chart Structural Extraction via One Auxiliary Token** <img src='https://img.shields.io/badge/ACM_MM_Oral-2024-yellow'> <a href='https://arxiv.org/abs/2404.09987'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/LingyvKong/OneChart'><img src='https://img.shields.io/badge/Code-orange'></a> <a href='https://drive.google.com/drive/folders/1YmOvxq0DfOA9YKoyCZDjpnTIkPNoyegQ'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Ye, Huayuan, Chenhui Li, Yang Li, and Changbo Wang.* **InvVis: Large-scale data embedding for invertible visualization** <img src='https://img.shields.io/badge/TVCG-2024-yellow'> <a href='https://ieeexplore.ieee.org/document/10290968'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/huayuan4396/InvVis'><img src='https://img.shields.io/badge/Code-orange'></a>

- *Liu, Fangyu, Julian Martin Eisenschlos, Francesco Piccinno, Syrine Krichene, Chenxi Pang, Kenton Lee, Mandar Joshi, Wenhu Chen, Nigel Collier, and Yasemin Altun.* **Deplot: One-shot visual language reasoning by plot-to-table translation** <img src='https://img.shields.io/badge/ACL_Findings-2023-yellow'> <a href='https://aclanthology.org/2023.findings-acl.660.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/google-research/google-research/tree/master/deplot'><img src='https://img.shields.io/badge/Code-orange'></a>

- *Yan, Pengyu, Saleem Ahmed, and David Doermann.* **CACHED: Context-Aware Chart Element Detection** <img src='https://img.shields.io/badge/ICDAR-2023-yellow'> <a href='https://arxiv.org/pdf/2410.12268'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/pengyu965/ChartDete'><img src='https://img.shields.io/badge/Code-orange'></a>

- *Yuan, Lin-Ping, Wei Zeng, Siwei Fu, Zhiliang Zeng, Haotian Li, Chi-Wing Fu, and Huamin Qu.* **Deep colormap extraction from visualizations** <img src='https://img.shields.io/badge/TVCG-2022-yellow'> <a href='https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9395231'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Luo, Junyu, Zekun Li, Jinpeng Wang, and Chin-Yew Lin.* **ChartOCR: Data Extraction From Charts Images via a Deep Hybrid Framework** <img src='https://img.shields.io/badge/WACV-2021-yellow'> <a href='https://openaccess.thecvf.com/content/WACV2021/papers/Luo_ChartOCR_Data_Extraction_From_Charts_Images_via_a_Deep_Hybrid_WACV_2021_paper.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>



## Benchmarks, Evaluation & Surveys

### Benchmarks

- *Masry, Ahmed, Mohammed Saidul Islam, Mahir Ahmed, Aayush Bajaj, Firoz Kabir, Aaryaman Kartha, Md Tahmid Rahman Laskar et al.* **ChartQAPro: A More Diverse and Challenging Benchmark for Chart Question Answering** <img src='https://img.shields.io/badge/Aarxiv_-2025-yellow'> <a href='https://arxiv.org/abs/2504.05506v2'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/vis-nlp/ChartQAPro'><img src='https://img.shields.io/badge/Code-orange'></a> <a href='https://huggingface.co/datasets/ahmed-masry/ChartQAPro'><img src='https://img.shields.io/badge/Dataset-red'></a> <img src='https://img.shields.io/badge/Benchmark-green'>

- *Xu, Zhengzhuo, Sinan Du, Yiyan Qi, Chengjin Xu, Chun Yuan, and Jian Guo.* **ChartBench: A Benchmark for Complex Visual Reasoning in Charts** <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2312.15915'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://huggingface.co/datasets/SincereX/ChartBench'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Singh, Ashish, Prateek Agarwal, Zixuan Huang, Arpita Singh, Tong Yu, Sungchul Kim, Victor Bursztyn, Nikos Vlassis, and Ryan A. Rossi.* **FigCaps-HF: A Figure-to-Caption Generative Framework and Benchmark with Human Feedback** <img src='https://img.shields.io/badge/Arxiv-2023-yellow'> <a href='https://arxiv.org/abs/2307.10867'><img src='https://img.shields.io/badge/Paper-purple'></a>
  <a href='https://figcapshf.github.io/'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Kantharaj, Shankar, Rixie Tiffany Ko Leong, Xiang Lin, Ahmed Masry, Megh Thakkar, Enamul Hoque, and Shafiq Joty.* **Chart-to-Text: A Large-Scale Benchmark for Chart Summarization** <img src='https://img.shields.io/badge/ACL-2022-yellow'> <a href='https://aclanthology.org/2022.acl-long.277/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/vis-nlp/Chart-to-text'><img src='https://img.shields.io/badge/Dataset-red'></a>
  
- *Masry, Ahmed, Do Xuan Long, Jia Qing Tan, Shafiq Joty, and Enamul Hoque.* **ChartQA: A Benchmark for Question Answering about Charts with Visual and Logical Reasoning** <img src='https://img.shields.io/badge/ACL_Findings-2022-yellow'> <a href='https://aclanthology.org/2022.findings-acl.177/'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/vis-nlp/ChartQA'><img src='https://img.shields.io/badge/Dataset-red'></a> <img src='https://img.shields.io/badge/Benchmark-green'>

### Evaluation

- *Ford, James, Xingmeng Zhao, Dan Schumacher, and Anthony Rios.* **Charting the Future: Using Chart Question-Answering for Scalable Evaluation of LLM-Driven Data Visualizations** <img src='https://img.shields.io/badge/COLING-2025-yellow'> <a href='https://aclanthology.org/2025.coling-main.501.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Bendeck, Alexander, and John Stasko.* **An Empirical Evaluation of the GPT-4 Multimodal Language Model on Visualization Literacy Tasks** <img src='https://img.shields.io/badge/VIS-2024-yellow'> <a href='https://ieeexplore.ieee.org/abstract/document/10670574'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Choe, Kiroong, Chaerin Lee, Soohyun Lee, Jiwon Song, Aeri Cho, Nam Wook Kim, and Jinwook Seo. * **Enhancing Data Literacy On-demand: LLMs as Guides for Novices in Chart Interpretation** <img src='https://img.shields.io/badge/VIS-2024-yellow'> <a href='https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10555321'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Lo, Leo Yu-Ho, and Huamin Qu.* **How Good (Or Bad) Are LLMs at Detecting Misleading Visualizations?** <img src='https://img.shields.io/badge/VIS-2024-yellow'> <a href='https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10679256'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Xu, Zhongzheng, and Emily Wall.* **Exploring the Capability of LLMs in Performing Low-Level Visual Analytic Tasks on SVG Data Visualizations** <img src='https://img.shields.io/badge/VIS_Short_Paper-2024-yellow'> <a href='https://arxiv.org/pdf/2404.19097'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *XBako, Hannah K., Arshnoor Bhutani, Xinyi Liu, Kwesi A. Cobbina, and Zhicheng Liu.* **Evaluating the Semantic Profiling Abilities of LLMs for Natural Language Utterances in Data Visualization** <img src='https://img.shields.io/badge/VIS_Short_Paper-2024-yellow'> <a href='https://arxiv.org/pdf/2407.06129'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://github.com/hdi-umd/Semantic_Profiling_LLM_Evaluation'><img src='https://img.shields.io/badge/Code-orange'></a>

- *Huang, Kung-Hsiang, Mingyang Zhou, Hou Pong Chan, Yi R. Fung, Zhenhailong Wang, Lingyu Zhang, Shih-Fu Chang, and Heng Ji.* **Do LVLMs Understand Charts? Analyzing and Correcting Factual Errors in Chart Captioning** <img src='https://img.shields.io/badge/ACL_Findings-2024-yellow'> <a href='[Do LVLMs Understand Charts? Analyzing and Correcting Factual Errors in Chart Captioning](https://aclanthology.org/2024.findings-acl.41.pdf)'><img src='https://img.shields.io/badge/Paper-purple'></a> <a href='https://huggingface.co/datasets/khhuang/CHOCOLATE'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Wu, Yifan, Lutao Yan, Yuyu Luo, Yunhai Wang, and Nan Tang.* **Evaluating Task-based Effectiveness of MLLMs on Charts** <img src='https://img.shields.io/badge/Arxiv-2024-yellow'> <a href='https://arxiv.org/abs/2405.07001'><img src='https://img.shields.io/badge/Paper-purple'></a>  <a href='https://anonymous.4open.science/r/ChartInsights-D43E'><img src='https://img.shields.io/badge/Dataset-red'></a>

- *Islam, Mohammed Saidul, Raian Rahman, Ahmed Masry, Md Tahmid Rahman Laskar, Mir Tafseer Nayeem, and Enamul Hoque.* **Are Large Vision Language Models up to the Challenge of Chart Comprehension and Reasoning?** <img src='https://img.shields.io/badge/EMNLP-2024-yellow'> <a href='https://aclanthology.org/2024.findings-emnlp.191.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>

- *Mukhopadhyay, Srija, Adnan Qidwai, Aparna Garimella, Pritika Ramu, Vivek Gupta, and Dan Roth.* **Unraveling the Truth: Do VLMs really Understand Charts? A Deep Dive into Consistency and Robustness** <img src='https://img.shields.io/badge/EMNLP-2024-yellow'> <a href='https://aclanthology.org/2024.findings-emnlp.973.pdf'><img src='https://img.shields.io/badge/Paper-purple'></a>

### Surveys

- *Huang, Kung-Hsiang, Hou Pong Chan, Yi R. Fung, Haoyi Qiu, Mingyang Zhou, Shafiq Joty, Shih-Fu Chang, and Heng Ji.* **From Pixels to Insights: A Survey on Automatic Chart Understanding in the Era of Large Foundation Models** <img src='https://img.shields.io/badge/TKDE-2024-yellow'> <a href='https://dl.acm.org/doi/10.1109/TKDE.2024.3513320'><img src='https://img.shields.io/badge/Paper-purple'></a>



## Contributing
👍 Contributions to this repository are welcome! 

If you have come across relevant resources, feel free to open an issue or submit a pull request.

📌 For example：

```
- *Author1, Author2, Author3, ...*  **Paper Title (bolded)** <img src='https://img.shields.io/badge/Conference_Journal_Name-Year-Color'><a href='PDF_Link'><img src='https://img.shields.io/badge/Paper-purple'></a><a href='Code_Link'><img src='https://img.shields.io/badge/Code-orange'></a><a href='Dataset_Link'><img src='https://img.shields.io/badge/Dataset-red'></a><img src='https://img.shields.io/badge/Benchmark-green'>

```

[#contributing]: #-contributing
[#benchmarks--surveys]: #-benchmarks--surveys
