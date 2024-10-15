# Overcoming Domain Limitations in Open-vocabulary Segmentation

by [Dongjun Hwang](https://dongjunhwang.github.io/), [Seong Joon Oh](https://coallaoh.github.io/), [Junsuk Choe^](https://sites.google.com/site/junsukchoe/)

<sup> ^ corresponding author </sup> <br>

**News**

- **[2024.10.15]** We have released the preprint on arXiv.

<br>

<div align="center">
  <img width="600" alt="image" src="https://github.com/user-attachments/assets/72472a63-399f-40d2-8c73-b499caaa04aa">
</div>

<br>

> **Abstract**: Open-vocabulary segmentation (OVS) has gained attention for its ability to recognize a broader range of classes. However, OVS models show significant performance drops when applied to unseen domains beyond the previous training dataset. Fine-tuning these models on new datasets can improve performance, but often leads to the catastrophic forgetting of previously learned knowledge. To address this issue, we propose a method that allows OVS models to learn information from new domains while preserving prior knowledge. Our approach begins by evaluating the input sample's proximity to multiple domains, using precomputed multivariate normal distributions for each domain. Based on this prediction, we dynamically interpolate between the weights of the pre-trained decoder and the fine-tuned decoders. Extensive experiments demonstrate that this approach allows OVS models to adapt to new domains while maintaining performance on the previous training dataset.

## Getting Started with DWI (Decoder Weight Interpolation)
Code will be uploaded.
