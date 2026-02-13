# PGDPL
The official pytorch implemention of the paper ”Prototype-Guided Distillation and Personalized Learning: A Dual-Network Framework for Label-Noisy Endoscopic Images”
# Introduction
we propose a dual-network framework that incorporates a prototype-guided sample selection strategy and personalized learning to leverage noisy samples to enhance model robustness and thereby improve the performance of endoscopic image analysis under noisy-label scenarios.
# Dependencies
• python 3.6.13

• numpy 1.19.5

• pytorch 1.7.1

• torchvision 0.8.2

# Training
1. Download KVASIR or LIMUC datasets into ./data/.
2. python main.py  --dataset KVASIR --seed 101 --batch-size=128 --arch resnet32 --method ours
# Dataset
Our endoscopic lesion segmentation dataset WCH consisting of 6,420 images of atrophic gastritis and 3,728 images of intestinal metaplasia. The complete dataset can be obtained from the corresponding author upon reasonable request (email: juanliao@scu.edu.cn).
The following presents a subset of the data from WCH.
# GA
![GA](./GA.png)
# IM
![IM](./IM.png)
