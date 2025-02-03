<p align=center><img src="figs/logo.png" width="200px"> </p>

# <p align=center> `UniCOS` </p> 

[//]: # (<b><p align=center> <a href='https://arxiv.org/pdf/2406.07966'><img src='https://img.shields.io/badge/ArXiv-2406.07966-red'></a></p></b>)

This is the official PyTorch codes for the paper. 
>**Integrating Extra Modality Helps Segmentor Find Camouflaged Objects Well** <br> [Chengyu Fang](https://cnyvfang.github.io/), [Chunming He](https://chunminghe.github.io/), Longxiang Tang, Yuelin Zhang, Chenyang Zhu, Yuqi Shen, Chubin Chen, Guoxia Xu, Xiu Li<br>
> arXiv 2025<br>

**Abstract:** Camouflaged Object Segmentation (COS) remains a challenging problem due to the subtle visual differences between camouflaged objects and backgrounds. Owing to the exceedingly limited visual cues available from visible spectrum, previous RGB single-modality approaches often struggle to achieve satisfactory results, prompting the exploration of multimodal data to enhance detection accuracy. In this work, we present UniCOS, a novel framework that effectively leverages diverse data modalities to improve segmentation performance. UniCOS comprises two key components: a multimodal segmentor, UniSEG, and a cross-modal knowledge learning module, UniLearner. UniSEG employs a state space fusion mechanism to integrate cross-modal features within a unified state space, enhancing contextual understanding and improving robustness to integration of heterogeneous data. Additionally, it includes a fusion-feedback mechanism that facilitate feature extraction. UniLearner exploits multimodal data unrelated to the COS task to improve the segmentation ability of the COS models by generating pseudo-modal content and cross-modal semantic associations. Extensive experiments demonstrate that UniSEG outperforms existing Multimodal COS (MCOS) segmentors, regardless of whether real or pseudo-multimodal COS data is available. Moreover, in scenarios where multimodal COS data is unavailable but multimodal non-COS data is accessible, UniLearner effectively exploits these data to enhance segmentation performance.   


<details open>
<summary>🏃 The architecture of the proposed UniCOS</summary>
<center> 
    <img 
    src="figs/framework.png">
</center>
</details>


## 🔥 News

- **2025-02-10:** We release this repository, the preprint of full paper will be release soon.


## 🔧 Todo

- [ ] Complete this repository



## 🔗 Contents

- [ ] Datasets
- [ ] Training
- [ ] Testing
- [ ] Results
- [ ] Citation
- [ ] Acknowledgements

