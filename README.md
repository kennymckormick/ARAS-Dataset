# Action with RAre Scene (ARAS)

Action with RAre Scene is a small scale dataset collected from Youtube. By definition, it includes video clips of human actions (those action categories fall into Kinetics-400 action classes) with rare scenes or backgrounds. To collect this dataset, we begin with action labels in Kinetics and consider some rare scenes. The combinations of actions and rare scenes are used as queries to obtain web videos from YouTube. We manually examine the web videos and obtain around ten videos for each class in 104 Kinetics classes, denoted as Action with RAre Scenes (ARAS). In our paper [Mitigating Representation Bias in Action Recognition: Algorithms and Benchmarks](https://arxiv.org/pdf/2209.09393.pdf), we use ARAS to simulate the out-of-distribution testing for scene-debiasing evaluation.

We have made the ARAS dataset publicly available now! You can download the [video clips](https://mycuhk-my.sharepoint.com/:u:/g/personal/1155136485_link_cuhk_edu_hk/Ec_sMtgujRFEpMsLJp1wYTUB_wZSQXTJVJTGl78svXu3ZA?e=ZDjLYo) and the [annotations files](https://mycuhk-my.sharepoint.com/:u:/g/personal/1155136485_link_cuhk_edu_hk/EX8brWB7u1ZHn0-nz6558vYBHDdW19v5bVRhYu9B3E6dmA?e=LtxJI3) with the provided links. Also, check [raw videos](https://mycuhk-my.sharepoint.com/:f:/g/personal/1155136485_link_cuhk_edu_hk/Ehvq1BzIWgVEqARTzJ279YoBR0SBpIE-zBdBvorOawqu3A?e=evVvPc) if you want to browse some raw videos. 

Please cite this work if you find ARAS useful to your research project:

```BibTex
@misc{https://doi.org/10.48550/arxiv.2209.09393,
  doi = {10.48550/ARXIV.2209.09393},
  url = {https://arxiv.org/abs/2209.09393},
  author = {Duan, Haodong and Zhao, Yue and Chen, Kai and Xiong, Yuanjun and Lin, Dahua},
  keywords = {Computer Vision and Pattern Recognition (cs.CV), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {Mitigating Representation Bias in Action Recognition: Algorithms and Benchmarks},
  publisher = {arXiv},
  year = {2022},
  copyright = {arXiv.org perpetual, non-exclusive license}
}
```