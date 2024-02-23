# VGG-Kface : An Optimization Study on Korean Face Recognition Using VGG-Face
This is a PyTorch implementation of the paper "VGG-Kface : An Optimization Study on Korean Face Recognition Using VGG-Face"
---
As the face recognition model is tailored to Western faces, it is necessary to improve the recognition performance of Korean faces. Born 
In this paper, we add a Korean face dataset provided by AIHub to the face recognition model and compare Westerners
Facial recognition was conducted by adding the characteristics of Koreans. of the image pair of continuous learning 
We propose a VGG-Kface that improves Korean recognition performance by hierarchically conducting appropriate ratio evaluation.

http://kips.or.kr/bbs/confn/article/3347
# Dataset
Our LSVH dataset is available for download at AIhub's Korean facial recognition dataset. Please understand that examples cannot be referenced as a research dataset. I will refer to the link instead.
https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=&topMenu=&aihubDataSe=data&dataSetSn=83

# Requirements
The main model for image learning was the VGG-Face model and continuous learning to improve performance. Therefore, it is implemented using V100 GPU or A100 GPU in the Google Colab environment.
This is because smaller models cannot be implemented due to the capacity problem of VRAM.
# 
