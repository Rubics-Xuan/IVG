
# Beyond Literal Descriptions: Understanding and Locating Open-World Objects Aligned with Human Intentions
Wenxuan Wang, Yisi Zhang, Xingjian He, Yichen Yan, Zijia Zhao, Xinlong Wang, Jing Liu

<p align="center">
 <a href='https://jingw193.github.io/AdaptiveFSS/'><img src='https://img.shields.io/badge/Project_Page-Green' alt='Paper PDF'></a> <a href='https://arxiv.org/pdf/2312.15731.pdf'><img src='https://img.shields.io/badge/arXiv_Paper-red' alt='Project Page'></a> <a href=''><img src='https://badges.aleen42.com/src/youtube.svg'> </a>
</p>

## 🚩 **Updates**
Welcome to this repository for the latest updates.

✅ **[2024.2.17]** : Released our paper on arXiv.

 **[ ]** : Released our data and baselines.

## 🌕 Abstract
In this work, we take a step further to the intention-driven visual-language (V-L) understanding. To promote classic VG towards human intention interpretation, we propose a new intention-driven visual grounding (IVG) task and build a largest-scale IVG dataset named IntentionVG with free-form intention expressions. Considering that practical agents need to move and find specific targets among various scenarios to realize the grounding task, our IVG task and IntentionVG dataset have taken the crucial properties of both multi-scenario perception and egocentric view into consideration. Besides, various types of models are set up as the baselines to realize our IVG task. Extensive experiments on our IntentionVG dataset and baselines demonstrate the necessity and efficacy of our method for the V-L field. To foster future research in this direction, our newly built dataset and baselines will be publicly available.
<p align="center">
 <img src="Figures/intro.png" width="100%">
</p>

---
## 🌖 Intention-Driven Visual Grounding (IVG) Task
<p align="center">
 <img src="Figures/task_definition.png" width="80%">
</p>

## 🌗 Data Collection Engine & IntentionVG Dataset
<p align="center">
 <img src="Figures/data_collection_engine.png" width="75%">
</p>
<p align="center">
 <img src="Figures/samples.png" width="80%">
</p>
<p align="center">
 <img src="Figures/data_analysis1.png" width="60%">
</p>
<p align="center">
 <img src="Figures/data_analysis2.png" width="60%">
</p>
<p align="center">
 <img src="Figures/data_analysis3.png" width="85%">
</p>

## 🌘 Baseline Constructions
<p align="center">
 <img src="Figures/baseline.png" width="90%">
</p>

## 🌑 Results
<p align="center">
 <img src="Figures/IVG.png" width="80%">
</p>

## 🚀 Citation
If you use our data or model in your work or find it is helpful, please cite the corresponding paper:

```
@article{wang2023unveiling,
  title={Unveiling Parts Beyond Objects: Towards Finer-Granularity Referring Expression Segmentation},
  author={Wang, Wenxuan and Yue, Tongtian and Zhang, Yisi and Guo, Longteng and He, Xingjian and Wang, Xinlong and Liu, Jing},
  journal={arXiv preprint arXiv:2312.08007},
  year={2023}
}
```

## 🏭 Acknowledgement
This work is built on many excellent research works and open-source projects, thanks a lot to all the authors for sharing!

1.[EVA-CLIP](https://github.com/baaivision/EVA/tree/master/EVA-CLIP)

2.[Qwen-VL](https://github.com/QwenLM/Qwen-VL)

3.[MiniGPT-4](https://github.com/Vision-CAIR/MiniGPT-4)

