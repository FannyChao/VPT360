# Transformer-based Long-Term Viewport Prediction in 360° Video: Scanpath is All You Need
- This repo contains the codes that used in paper [*Transformer-based Long-Term Viewport Prediction in 360° Video: Scanpath is All You Need (MMSP2021)*](https://www.researchgate.net/publication/353821903_Transformer-based_Long-Term_Viewport_Prediction_in_360_Video_Scanpath_is_All_You_Need) by Fang-Yi Chao, Cagri Ozcinar, Aljosa Smolic.

## Abstract
Virtual Reality (VR) multimedia technology has dramatically advanced in recent years. Its immersive and interactive natures enable users to view any direction in 360° content freely. Users do not see the entire 360° content at a glance, but only a portion in the viewport. Viewport-based adaptive streaming, which streams only the user’s viewport of interest with high quality, has emerged as the primary technique to save bandwidth over the best-effort Internet. Thus, users’ viewport prediction in the forthcoming seconds becomes an essential task for informing the streaming decisions in the VR system. Various viewport prediction methods based on deep neural networks have been proposed. However, typically they are composed of complex Convolutional Neural Networks (CNN) and Recurrent Neural Networks (RNN) that require heavy computation. To achieve high prediction accuracy in limited computation time in a streaming system, we propose a new transformer-based architecture, named 360° Viewport Prediction Transformer (VPT360), that only leverages the past viewport scanpath to predict a user’s future viewport scanpath. We evaluate VPT360 over three widely-used datasets and compare the computation complexity with the state-of-the-art methods. The experiments show that our VPT360 provides the highest accuracy for short-term and long-term prediction and achieves the lowest computation complexity. The code is publicly available at https://github.com/FannyChao/VPT360 to further contribute to the community.

## Architecture
![diagram]()

## To Be Continued...


## Citing
```
@INPROCEEDINGS{9301766,
  author={F. -Y. {Chao} and C. {Ozcinar} and A. {Smolic}},
  booktitle={IEEE 23nd International Workshop on Multimedia Signal Processing (MMSP)}, 
  title={Transformer-based Long-Term Viewport Prediction in 360° Video: Scanpath is All You Need}, 
  year={2021},
  volume={},
  number={},
  pages={},
  doi={}}
```
