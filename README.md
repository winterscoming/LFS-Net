# LFS-Net: Levels Feature Shared Network for Small Object Detection

# Abstract
Currently, small objects pose a challenge in object detection due to their limited feature information. Since small objects exhibit different feature representations at different network levels, processing their features remains difficult. Although (Feature Pyramid Network) FPN can integrate features, its indiscriminate fusion approach may introduce redundant deep-layer features, negatively impacting the feature representation of small objects. Moreover, conventional FPNs primarily focus on features at the current level, overlooking cross-level multi-scale and fine-grained features, which limits their ability to effectively represent small objects. To address this limitation, this study proposes the Levels Feature Shared Network (LFS-Net) for small object detection. Specifically, this study proposes the Levels Feature Shared (LFS) mechanism to facilitate feature sharing across different levels, thereby enhancing the representation capability of each level for small object features. Additionally, the Shared Feature Attention (SFA) is proposed to complement LFS, leveraging self-attention to focus on critical features and capture long-range dependencies. This mitigates the feature dilution effect that arises from shared feature fusion. Experimental results demonstrate that LFS-Net outperforms existing approaches on multiple datasets and achieves state-of-the-art performance on the AI-TOD dataset.

# Experiment
    Experiment environment:
    python: 3.8
    torch: 1.12.1
    torchvision: 0.13.1
    numpy: 1.23.5
    pandas: 2.0.1
    matplotlib: 3.5.1

# Method
![image](.png)

# Result
