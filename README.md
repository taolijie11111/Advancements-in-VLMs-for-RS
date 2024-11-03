# 📒Awesome VLMs in RS

<div align='center'>
  <img src="images\Awesome VLMs in RS.png">  
</div>

This is the repository of **Advancements in Visual Language Models for Remote Sensing: Datasets, Capabilities, and Enhancement Techniques**, a systematic survey of recent VLM studies in Remote Sensing including Datasets, Capabilities, and Enhancement Techniques. For details, please refer to:

**Advancements in Visual Language Models for Remote Sensing: Datasets, Capabilities, and Enhancement Techniques**
[[paper]](https://arxiv.org/pdf/2410.17283)
<div align='center'>
<img src=https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg >
<img src=https://img.shields.io/badge/Release-v1.0-brightgreen.svg >
<img src=https://img.shields.io/badge/License-GPLv3.0-turquoise.svg >
<img src=https://img.shields.io/badge/arxiv-2410.17283-ccf.svg >
</div>

# ©️Abstract
Recently, the remarkable success of ChatGPT has sparked a renewed wave of interest in artificial intelligence (AI), and the advancements in visual language models (VLMs) have pushed this enthusiasm to new heights. Differring from previous AI approaches that generally formulated different tasks as discriminative models, VLMs frame tasks as generative models and align language with visual information, enabling the handling of more challenging problems. The remote sensing (RS) field, a highly practical domain, has also embraced this new trend and introduced several VLM-based RS methods that have demonstrated promising performance and enormous potential. In this paper, we first review the fundamental theories related to VLM, then summarize the datasets constructed for VLMs in remote sensing and the various tasks they addressed. Finally, we categorize the improvement methods into three main parts according to the core components of VLMs and provide a detailed introduction and comparison of these methods.

# ©️Citation
If you find our work useful in your research, please consider citing:
```BibTeX
@misc{tao2024advancementsvisuallanguagemodels,
      title={Advancements in Visual Language Models for Remote Sensing: Datasets, Capabilities, and Enhancement Techniques}, 
      author={Lijie Tao and Haokui Zhang and Haizhao Jing and Yu Liu and Kelu Yao and Chao Li and Xizhe Xue},
      year={2024},
      eprint={2410.17283},
      archivePrefix={arXiv},
      primaryClass={cs.AI},
      url={https://arxiv.org/abs/2410.17283}, 
}
```

# 📖Contents 
* 📖[Recent VLMs for RS](#Recent-Advances-in-Visual-Language-Models-for-Remote-Sensing)
  * 📖[Contrastive Methods](#Contrastive-Methods)
  * 📖[Conversational Methods](#Conversational-Methods)🔥 
  * 📖[Other Methods](#Other-Methods)
* 📖[Datasets in VLMs for RS](#Datasets)
  * 📖[Manual Datasets](#Manual)
  * 📖[Combining Datasets](#Combining-with-Existing-Dataset)
  * 📖[Automatically Annoteted Datasets](#Automatically-Annoteted-Datasets)🔥
* 📖[Capabilities in VLMs for RS](#Capabilities)

## 📖Recent in VLMs for RS ([©️back👆🏻](#paperlist))  
<div id="Recent-Advances-in-Visual-Language-Models-for-Remote-Sensing"></div> 

### 📖Contrastive Methods ([©️back👆🏻](#paperlist))  
<div id="Contrastive-Methods"></div> 

|Published in|Title|Paper|Code/Project|
|:---:|:---:|:---:|:---:| 
|TGRS 2024|[**RemoteCLIP**] Remoteclip: A vision language foundation model for remote sensing|[link](https://ieeexplore.ieee.org/document/10504785)|[RemoteCLIP](https://github.com/ChenDelong1999/RemoteCLIP)![](https://img.shields.io/github/stars/ChenDelong1999/RemoteCLIP.svg?style=social)|
|RS 2024|[**CRSR**] Cross-modal retrieval and semantic refinement for remote sensing image captioning|[link](https://www.mdpi.com/2072-4292/16/1/196)|![](https://img.shields.io/badge/!-ToDo-white)|
|arXiv 2024|[**ProGEO**] Progeo: Generating prompts through image-text contrastive learning for visual geo-localization|[pdf](https://arxiv.org/pdf/2406.01906)|[ProGEO](https://github.com/Chain-Mao/ProGEO)![](https://img.shields.io/github/stars/Chain-Mao/ProGEO.svg?style=social)|
|ICLR 2024|[**GRAFT**] Remote sensing vision-language foundation models without annotations via ground remote alignment|[pdf](https://arxiv.org/pdf/2312.06960)|![](https://img.shields.io/badge/!-ToDo-white)|
|TGRS 2024|[**GeoRSCLIP**] Rs5m and georsclip: A large scale vision-language dataset and a large vision-language model for remote sensing|[pdf](https://arxiv.org/pdf/2306.11300)|[GeoRSCLIP](https://github.com/om-ai-lab/RS5M)![](https://img.shields.io/github/stars/om-ai-lab/RS5M.svg?style=social)|
|ISPRS 2024|[**ChangeCLIP**] Changeclip: Remote sensing change detection with multimodal vision-language representation learning|[link](https://www.sciencedirect.com/science/article/abs/pii/S0924271624000042)|[ChangeCLIP](https://github.com/dyzy41/ChangeCLIP)![](https://img.shields.io/github/stars/dyzy41/ChangeCLIP.svg?style=social)|
|CVPR 2023|[**APPLeNet**]Applenet: Visual attention parameterized prompt learning for few-shot remote sensing image generalization using clip|[pdf](https://arxiv.org/pdf/2304.05995)|[APPLeNet](https://github.com/mainaksingha01/AppleNet)![](https://img.shields.io/github/stars/mainaksingha01/AppleNet.svg?style=social)|
|TGRS 2023|[**MGVLF**] Rsvg: Exploring data and models for visual grounding on remote sensing data|[pdf](https://arxiv.org/pdf/2210.12634)|[MGVLF](https://github.com/ZhanYang-nwpu/RSVG-pytorch)![](https://img.shields.io/github/stars/ZhanYang-nwpu/RSVG-pytorch.svg?style=social)|


### 📖Conversational Methods ([©️back👆🏻](#paperlist))  
<div id="Conversational-Methods"></div>

|Published in|Title|Paper|Code/Project|
|:---:|:---:|:---:|:---:| 
|RS 2024|[**RS-LLaVA**] Rs-llava: A large vision-language model for joint captioning and question answering in remote sensing imagery|[link](https://www.mdpi.com/2072-4292/16/9/1477)|[RS-LLaVA](https://github.com/BigData-KSU/RS-LLaVA)![](https://img.shields.io/github/stars/BigData-KSU/RS-LLaVA.svg?style=social)|
|arXiv 2023|[**H2RSVLM**] H2rsvlm: Towards helpful and honest remote sensing large vision language model|[pdf](https://arxiv.org/pdf/2403.20213)|[H2RSVLM](https://github.com/opendatalab/H2RSVLM)![](https://img.shields.io/github/stars/opendatalab/H2RSVLM.svg?style=social)| 
|arXiv 2024|[**SkySenseGPT**] Skysensegpt: A fine-grained instruction tuning dataset and model for remote sensing vision-language understanding|[pdf](https://arxiv.org/pdf/2406.10100)|[SkySenseGPT](https://github.com/Luo-Z13/SkySenseGPT)![](https://img.shields.io/github/stars/Luo-Z13/SkySenseGPT.svg?style=social)|
|CVPR 2024|[**GeoChat**] Geochat: Grounded large vision-language model for remote sensing|[pdf](https://arxiv.org/pdf/2311.15826)|[GeoChat](https://github.com/mbzuai-oryx/geochat)![](https://img.shields.io/github/stars/mbzuai-oryx/geochat.svg?style=social)|
|arXiv 2023|[**RSGPT**] RSGPT: A Remote Sensing Vision Language Model and Benchmark|[pdf](https://arxiv.org/pdf/2307.15266)|[RSGPT](https://github.com/Lavender105/RSGPT)![](https://img.shields.io/github/stars/Lavender105/RSGPT.svg?style=social)|
|arXiv 2024|[**Skyeyegpt**] Skyeyegpt: Unifying remote sensing vision-language tasks via instruction tuning with large language model|[pdf](https://arxiv.org/pdf/2401.09712)|[Skyeyegpt](https://github.com/ZhanYang-nwpu/SkyEyeGPT)![](https://img.shields.io/github/stars/ZhanYang-nwpu/SkyEyeGPT.svg?style=social)|
|arXiv 2024|[**RS-CapRet**] Large language models for captioning and retrieving remote sensing images|[pdf](https://arxiv.org/pdf/2402.06475)|![](https://img.shields.io/badge/!-ToDo-white)|
|arXiv 2024|[**LHRS-Bot**] Lhrs-bot: Empowering remote sensing with vgi-enhanced large multimodal language model|[pdf](https://arxiv.org/pdf/2402.02544)|[LHRS-Bot](https://github.com/NJU-LHRS/LHRS-Bot)![](https://img.shields.io/github/stars/NJU-LHRS/LHRS-Bot.svg?style=social)|
|TGRS 2024|[**EarthGPT**] Earthgpt: A universal multi-modal large language model for multi-sensor image comprehension in remote sensing domain|[pdf](https://arxiv.org/pdf/2401.16822)|[EarthGPT](https://github.com/wivizhang/EarthGPT)![](https://img.shields.io/github/stars/wivizhang/EarthGPT.svg?style=social)|
|TGRS 2023|A decoupling paradigm with prompt learning for remote sensing image change captioning|[link](https://ieeexplore.ieee.org/document/10271701)|[code](https://github.com/Chen-Yang-Liu/PromptCC)![](https://img.shields.io/github/stars/Chen-Yang-Liu/PromptCC.svg?style=social)|

### 📖Other Methods ([©️back👆🏻](#paperlist))  
<div id="Other-Methods"></div>

|Published in|Title|Paper|Code/Project|
|:---:|:---:|:---:|:---:| 
|TIP 2023|[**Txt2Img**] Txt2img-mhn: Remote sensing image generation from text using modern hopfield networks|[pdf](https://arxiv.org/pdf/2208.04441)|[Txt2Img](https://github.com/YonghaoXu/Txt2Img-MHN)![](https://img.shields.io/github/stars/YonghaoXu/Txt2Img-MHN.svg?style=social)|
|WACV 2024|[**CPSeg**] Cpseg: Finer-grained image semantic segmentation via chain-of-thought language prompting|[pdf](https://arxiv.org/pdf/2310.16069)|![](https://img.shields.io/badge/!-ToDo-white)|
|TGRS 2023|[**SHRNet**] A spatial hierarchical reasoning network for remote sensing visual question answering|[link](https://ieeexplore.ieee.org/document/10018408)|![](https://img.shields.io/badge/!-ToDo-white)|
|SIGIR 2023|[**MGeo**] Mgeo: Multi-modal geographic language model pre-training|[pdf](https://arxiv.org/pdf/2301.04283)|[Mgeo](https://github.com/PhantomGrapes/MGeo)![](https://img.shields.io/github/stars/PhantomGrapes/MGeo.svg?style=social)|
|NeurIPS 2023|[**GeoCLIP**] Geoclip: Clip-inspired alignment between locations and images for effective worldwide geo-localization|[pdf](https://arxiv.org/pdf/2309.16020)|[GeoCLIP](https://vicentevivan.github.io/GeoCLIP)![](https://img.shields.io/badge/Web-white?logo=github&logoColor=black)|
|TPAMI 2024|[**SpectralGPT**] Spectralgpt: Spectral remote sensing foundation model|[pdf](https://arxiv.org/pdf/2311.07113v3)|[SpectralGPT](https://github.com/danfenghong/IEEE_TPAMI_SpectralGPT/)![](https://img.shields.io/github/stars/danfenghong/IEEE_TPAMI_SpectralGPT.svg?style=social)|
|TGRS 2023|[**TEMO**] Few-shot object detection in aerial imagery guided by text-modal knowledge|[link](https://ieeexplore.ieee.org/document/10056362/citations#citations)|![](https://img.shields.io/badge/!-ToDo-white)|

## 📖Datasets in VLMs for RS ([©️back👆🏻](#paperlist))  
<div id="Datasets"></div>  

### 📖Manual Datasets ([©️back👆🏻](#paperlist))  
<div id="Manual-Datasets"></div>  

|Published in|Title|Image|Paper|Code/Project|
|:---:|:---:|:---:|:---:|:---:|   
|CVPR 2024|[**Hallusionbench**] HallusionBench: An Advanced Diagnostic Suite for Entangled Language Hallucination and Visual Illusion in Large Vision-Language Models |346|[pdf](https://arxiv.org/pdf/2310.14566) |[Hallusionbench](https://github.com/tianyi-lab/HallusionBench)![](https://img.shields.io/github/stars/tianyi-lab/HallusionBench.svg?style=social)|
|arXiv 2023|[**RSICap**] RSGPT: A Remote Sensing Vision Language Model and Benchmark|2585|[pdf](https://arxiv.org/pdf/2307.15266)|[RSICap](https://github.com/Lavender105/RSGPT)![](https://img.shields.io/github/stars/Lavender105/RSGPT.svg?style=social)|
|TGRS 2023|[**CRSVQA**] Multistep Question-Driven Visual Question Answering for Remote Sensing|4639|[pdf](https://ieeexplore.ieee.org/document/10242124)|[CRSVQA](https://github.com/MeimeiZhang-data/MQVQA)![](https://img.shields.io/github/stars/MeimeiZhang-data/MQVQA.svg?style=social)|
### 📖Combining Datasets ([©️back👆🏻](#paperlist))  
<div id="Combining-Datasets"></div>  

|Published in|Title|Image|Paper|Code/Project|
|:---:|:---:|:---:|:---:|:---:|  
|ICCV 2023|[**SATIN**] Satin: A multi-task metadataset for classifying satellite imagery using vision-language models | ≈775K | [pdf](https://arxiv.org/pdf/2304.11619)|[SATIN](https://satinbenchmark.github.io/)![](https://img.shields.io/badge/Web-white?logo=github&logoColor=black)|
|ICCV 2023|[**GeoPile**] Towards geospatial foundation models via continual pretraining|600K|[pdf](https://arxiv.org/pdf/2302.04476)|[GeoPile](https://github.com/mmendiet/GFM)![](https://img.shields.io/github/stars/mmendiet/GFM.svg?style=social)| 
|ICCV 2023|[**SatlasPretrain**] Satlaspretrain: A large-scale dataset for remote sensing image understanding|856K| [pdf](https://arxiv.org/abs/2211.15660)|[SatlasPretrain](https://satlas-pretrain.allen.ai/)![](https://img.shields.io/badge/Web-white?logo=github&logoColor=black)|
|TGRS 2023|[**RSVGD**] Rsvg: Exploring data and models for visual grounding on remote sensing data|17402|[pdf](https://arxiv.org/pdf/2210.12634)|[RSVGD](https://github.com/ZhanYang-nwpu/RSVG-pytorch)![](https://img.shields.io/github/stars/ZhanYang-nwpu/RSVG-pytorch.svg?style=social)|
|TGRS 2024|[**RefsegRS**] Rrsis: Referring remote sensing image segmentation|4420|[pdf](https://arxiv.org/pdf/2306.08625)|[RefsegRS](https://gitlab.lrz.de/ai4eo/reasoning/rrsis)![](https://img.shields.io/badge/Web-white?logo=github&logoColor=black)|
|arXiv 2024|[**SkyEye-968K**] Skyeyegpt: Unifying remote sensing vision-language tasks via instruction tuning with large language model|968K|[pdf](https://arxiv.org/pdf/2401.09712)|[SkyEye-968K](https://github.com/ZhanYang-nwpu/SkyEyeGPT)![](https://img.shields.io/github/stars/ZhanYang-nwpu/SkyEyeGPT.svg?style=social)|
|TGRS 2024|[**MMRS-1M**] Earthgpt: A universal multi-modal large language model for multi-sensor image comprehension in remote sensing domain|1M|[pdf](https://arxiv.org/pdf/2401.16822)|[MMRS-1M](https://github.com/wivizhang/EarthGPT)![](https://img.shields.io/github/stars/wivizhang/EarthGPT.svg?style=social)|
|arXiv 2023|[**RSSA**] H2rsvlm: Towards helpful and honest remote sensing large vision language model|44K|[pdf](https://arxiv.org/pdf/2403.20213)|[RSSA](https://github.com/opendatalab/H2RSVLM)![](https://img.shields.io/github/stars/opendatalab/H2RSVLM.svg?style=social)| 
|TGRS 2024|[**FineGrip**] Panoptic perception: A novel task and fine-grained dataset for universal remote sensing image interpretation|2649|[pdf](https://arxiv.org/pdf/2404.04608)|![](https://img.shields.io/badge/!-ToDo-white)|
|CVPR 2024|[**RRSIS-D**] Rotated multiscale interaction network for referring remote sensing image segmentation|17402|[pdf](https://arxiv.org/pdf/2312.12470)|[RRSIS-D](https://github.com/Lsan2401/RMSIN)![](https://img.shields.io/github/stars/Lsan2401/RMSIN.svg?style=social)|
|TGRS 2022|[**RingMo**] Ringmo: A remote sensing foundation model with masked image modeling| 2096640|[link](https://ieeexplore.ieee.org/abstract/document/9844015)|![](https://img.shields.io/badge/!-ToDo-white)|
|arXiv 2023|[**GRAFT**] Remote sensing vision-language foundation models without annotations via ground remote alignment|-|[pdf](https://arxiv.org/pdf/2312.06960)|![](https://img.shields.io/badge/!-ToDo-white)|
|CVPR 2024|[**SkySense**] Skysense: A multi-modal remote sensing foundation model towards universal interpretation for earth observation imagery| 21.5M|[pdf](https://arxiv.org/abs/2312.10115v1)|![](https://img.shields.io/badge/!-ToDo-white)|
|AAAI 2024|[**EarthVQA**] Earthvqa: Towards queryable earth via relational reasoning-based remote sensing visual question answering| 6000|[pdf](https://arxiv.org/pdf/2312.12222)|[EarthVQA](https://junjuewang.top/EarthVQA)![](https://img.shields.io/badge/Web-white?logo=github&logoColor=black)|
|TGRS 2024|[**GeoSense**] Generative convnet foundation model with sparse modeling and low-frequency reconstruction for remote sensing image interpretation| ≈9M|[link](https://ieeexplore.ieee.org/abstract/document/10378718)|[GeoSense](https://github.com/HIT-SIRS/SMLFR)![](https://img.shields.io/github/stars/HIT-SIRS/SMLFR.svg?style=social)|

### 📖Automatically Annoteted Datasets ([©️back👆🏻](#paperlist))  
<div id="Automatically-Annoteted-Datasets"></div>  

|Published in|Title|Image|Paper|Code/Project|
|:---:|:---:|:---:|:---:|:---:| 
|TGRS 2024|[**RS5M**] Rs5m and georsclip: A large scale vision-language dataset and a large vision-language model for remote sensing|5M|[pdf](https://arxiv.org/pdf/2306.11300)|[RS5M](https://github.com/om-ai-lab/RS5M)![](https://img.shields.io/github/stars/om-ai-lab/RS5M.svg?style=social)|
|AAAI 2024|[**SkyScript**] Skyscript: A large and semantically diverse vision-language dataset for remote sensing|2.6M|[pdf](https://arxiv.org/pdf/2312.12856)|![](https://img.shields.io/badge/!-ToDo-white)|
|arXiv 2024|[**LHRS-Align**] Lhrs-bot: Empowering remote sensing with vgi-enhanced large multimodal language model|1.15M|[pdf](https://arxiv.org/pdf/2402.02544)|[LHRS-Align](https://github.com/NJU-LHRS/LHRS-Bot)![](https://img.shields.io/github/stars/NJU-LHRS/LHRS-Bot.svg?style=social)|
|CVPR 2024|[**GeoChat**] Geochat: Grounded large vision-language model for remote sensing|318K|[pdf](https://arxiv.org/pdf/2311.15826)|[GeoChat](https://github.com/mbzuai-oryx/geochat)![](https://img.shields.io/github/stars/mbzuai-oryx/geochat.svg?style=social)|
|ICML 2024|[**GeoReasoner**] Georeasoner: Geo-localization with reasoning in street views using a large vision-language model|70K+|[pdf](https://arxiv.org/pdf/2406.18572)|[GeoReasoner](https://github.com/lingli1996/GeoReasoner)![](https://img.shields.io/github/stars/lingli1996/GeoReasoner?style=social)|
|arXiv 2023|[**HqDC-1.4M**] H2rsvlm: Towards helpful and honest remote sensing large vision language model|≈1.4M|[pdf](https://arxiv.org/pdf/2403.20213)|[HqDC-1.4M](https://github.com/opendatalab/H2RSVLM)![](https://img.shields.io/github/stars/opendatalab/H2RSVLM.svg?style=social)|
|CVPR 2024|[**ChatEarthNet**] ChatEarthNet: A Global-Scale Image-Text Dataset Empowering Vision-Language Geo-Foundation Models|163488|[pdf](https://arxiv.org/pdf/2402.11325)|[ChatEarthNet](https://github.com/zhu-xlab/ChatEarthNet)![](https://img.shields.io/github/stars/zhu-xlab/ChatEarthNet.svg?style=social)|
|arXiv 2024|[**VRSBench**] Vrsbench: A versatile vision-language benchmark dataset for remote sensing image understanding|29614|[pdf](https://arxiv.org/pdf/2406.12384)|[VRSBench](https://github.com/lx709/VRSBench)![](https://img.shields.io/github/stars/lx709/VRSBench.svg?style=social)|
|arXiv 2024|[**FIT-RS**] Skysensegpt: A fine-grained instruction tuning dataset and model for remote sensing vision-language understanding|1800.8K|[pdf](https://arxiv.org/pdf/2406.10100)|[FIT-RS](https://github.com/Luo-Z13/SkySenseGPT)![](https://img.shields.io/github/stars/Luo-Z13/SkySenseGPT.svg?style=social)|


## 📖Capabilities in VLMs for RS ([©️back👆🏻](#paperlist))
<div id="Capabilities"></div> 

<div align='center'>
  <img src="images\capabilities.png">  
</div>


## ©️License  

GNU General Public License v3.0  

## 🎉Contribute  

Welcome to star & submit a PR to this repo! 