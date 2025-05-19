<p align=center><img src="figs/logo.png" width="200px"> </p>

# <p align=center> `MultiCOS` </p> 

<b><p align=center> <a href='https://arxiv.org/abs/2502.14471'><img src='https://img.shields.io/badge/ArXiv-2502.14471-red'></a></p></b>

This is the official PyTorch codes for the paper. 
>**Integrating Extra Modality Helps Segmentor Find Camouflaged Objects Well** <br> [Chengyu Fang](https://cnyvfang.github.io/), [Chunming He](https://chunminghe.github.io/), Longxiang Tang, Yuelin Zhang, Chenyang Zhu, Yuqi Shen, Chubin Chen, Guoxia Xu, Xiu Li, arXiv 2025<br>

**Abstract:** Camouflaged Object Segmentation (COS) remains challenging because camouflaged objects exhibit only subtle visual differences from their backgrounds and single-modality RGB methods provide limited cues, leading researchers to explore multimodal data to improve segmentation accuracy. In this work, we presenet MultiCOS, a novel framework that effectively leverages diverse data modalities to improve segmentation performance. MultiCOS comprises two modules: Bi-space Fusion Segmentor (BFSer), which employs a state space and a latent space fusion mechanism to integrate cross-modal features within a shared representation and employs a fusion‐feedback mechanism to refine context‐specific features, and Cross-modal Knowledge Learner (CKLer), which leverages external multimodal datasets to generate pseudo‐modal inputs and establish cross‐modal semantic associations, transferring knowledge to COS models when real multimodal pairs are missing. When real multimodal COS data are unavailable, CKLer yields additional segmentation gains using only non‐COS multimodal sources. Experiments on standard COS benchmarks show that BFSer outperforms existing multimodal baselines with both real and pseudo‐modal data.


<details>
<summary>🏃 The architecture of the proposed UniCOS</summary>
<center> 
    <img 
    src="figs/framework.png">
</center>
</details>


## 🔥 News
- **2025-02-21:** We release a part of results, bibtex, and the preprint of full paper.
- **2025-02-10:** We release this repository, the preprint of full paper will be release soon.


## 🔧 Todo

- [ ] Complete this repository



## 🔗 Contents

- [ ] Datasets
- [ ] Training
- [ ] Testing
- [x] Results
- [x] Citation

## 🔍 Results

We achieved state-of-the-art performance on _COD10K_, _CAMO_, _NC4K_, _CHAMELEON_, and _PCOD1200_. More results can be found in the paper. We will release all results from different datasets when the paper is accepted.

<details open> 
<summary>Visual Comparison (click to expand)</summary>

- Visual results on UniLearner
  <p align="center">
  <img width="400" src="figs/fig-1.png">
  </p>
- Visual comparison on RGB and RGB-I
  <p align="center">
  <img width="900" src="figs/fig-2.png">
  </p>
- Visual comparison on RGB-P and RGB-D
  <p align="center">
  <img width="900" src="figs/fig-3.png">
  </p>
  
  </details>


## 📎 Citation

If you find the code helpful in your research or work, please cite the following paper(s).

```
@misc{fang2025multicos,
      title={Integrating Extra Modality Helps Segmentor Find Camouflaged Objects Well}, 
      author={Chengyu Fang and Chunming He and Longxiang Tang and Yuelin Zhang and Chenyang Zhu and Yuqi Shen and Chubin Chen and Guoxia Xu and Xiu Li},
      year={2025},
      eprint={2502.14471},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2502.14471}, 
}
```

