## Hi, I'm Josh👋

I am a AI/ML PhD researcher and engineer specialising in deep learning for biomedical image analysis. 

## 🛠️ Technical Skills

**Machine Learning & Computer Vision**
Deep Learning · Computer Vision · Self-Supervised Learning · Domain Adaptation · Foundation Models · CNNs · Transformers · Biomedical Image Segmentation

**Programming & ML Frameworks**
Python · PyTorch · PyTorch Lightning · scikit-learn · NumPy · pandas · SciPy · SQL

**ML Engineering & HPC**
Distributed Training & Inference · SLURM · HPC · Weights & Biases · Linux · Bash · Git

**Software Engineering**
Version Control · Reproducible Research · Experiment Configuration & Tracking · Testing · Documentation

**Biomedical Imaging**
Electron Microscopy · Cryo-ET · Light Microscopy · CBCT · Medical & Microscopy Image Analysis

## Selected Projects

### [Consistency based Model Ranking -- CMR](https://github.com/kreshuklab/model_ranking)

**Python · PyTorch · Deep Learning · HPC/SLURM · Biomedical Image Segmentation**

Developed a novel source-free, unsupervised metric for ranking the transferability of pre-trained biomedical segmentation models without access to target-domain labels. CMR enables systematic model selection under distribution shift and supports the wider reuse of pre-trained models from model zoos. Accepted at [ECCV 2026](https://eccv.ecva.net/virtual/2026/poster/4464) [ArXiV](https://arxiv.org/abs/2503.00450).

---

## Current Research Projects

Some of my research software is maintained in private institutional repositories because it supports ongoing or unpublished research. Code is not yet publicly available, but development activity may be visible through my GitHub contribution history.

### Self Supervised Foundation Model for Cryo-Electron Tomography**

**Python · Pytorch Lightning · HPC**

Lead model developer of a self-supervised foundation model for cryo-electron tomography (cryo-ET), exploring learning useful self-supervised representations that can transfer to downstream tasks including denoising, subcellular segmentation, and macromolecular detection and identification.

This is an ongoing research and development project, with current work focused on developing and selecting suitable model architectures, self-supervised learning strategies, data requirements for foundation models trained on large-scale cryo-ET data.

**My contributions**

* Developing a modular Python/PyTorch Lightning training framework for iterative experimentation with self-supervised foundation models on large-scale cryo-ET data.
* Building distributed multi-GPU training workflows for HPC environments, including scalable data loading, checkpointing, experiment tracking, and reproducible configuration of training runs.
* Exploring model architectures, self-supervised objectives, and training strategies for learning representations that generalise across heterogeneous cryo-ET datasets and downstream biological tasks.
* Designing data pipelines for training on cryo-ET collections spanning hundreds of terabytes, with an emphasis on scalable I/O, sampling, preprocessing, and efficient utilisation of HPC resources.
* Working closely with domain scientists to translate biological requirements and data-quality considerations into training-data selection, preprocessing, and model-evaluation strategies.


## 📚 Research & Publications:

Talks, J., Marchesini, K., Lumetti, L., Bolelli, F., Kreshuk, A. (2026). Unsupervised Source-Free Ranking of Biomedical Segmentation Models Under Distribution Shift. In: Favaro, P., Kukelova, Z., Maki, A., Rohrbach, A., Schindler, K., Tombari, F. (eds) Computer Vision – ECCV 2026. ECCV 2026. Lecture Notes in Computer Science, vol 17010. Springer, Cham. https://doi.org/10.1007/978-3-032-36839-3_23

