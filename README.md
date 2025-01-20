# Implementation of a Multi-Image Fusion and Stitching Algorithm Based on Lightweight Deep Learning Method and Xfeat Feature Matching (HITSZ: Computer Vision, Fall 2024)

本项目基于哈尔滨工业大学（深圳）计算机视觉研究生课程（2024 Fall）大作业，完成了如下目标：

1. 图像增强和锐化实现
2. 基于Xfeat进行深度学习特征匹配，同时设计算法实现对图像的快速仿射变换拼接
3. 图像多频段融合实现

## 项目概述


项目的关键模块包括：
- **特征匹配**：基于Xfeat进行图像特征提取与匹配。
- **图像对齐**：估算图像间的转换关系，确保准确对齐。
- **图像融合与拼接**：将对齐后的图像无缝合成一张全景图。
- **轻量深度学习**：通过轻量化的深度学习架构优化特征匹配过程，提高处理速度，适用于实时应用。
有关详细技术实现、算法设计和实验结果，请参阅《计算机视觉》课程设计报告：[报告](./基于Xfeat特征匹配的多图像融合拼接算法实现.pdf)
## 特性

- **基于Xfeat的特征匹配**：利用Xfeat方法进行高质量、轻量化的特征提取与匹配。
- **高效的图像对齐**：能够处理图像间的不同尺度、旋转和转换，确保精确对齐。
- **无缝图像拼接**：将多张图像合成一张无缝的全景图像，最小化拼接痕迹。
- **轻量快速**：优化算法性能，适合实时应用场景。


## 环境配置

- **Python**: 3.8  
- **PyTorch**: 1.10.1  
- **NumPy**: 1.24.4  
- **OpenCV**: 4.10  
- **Matplotlib**: 3.7.5  

**实验运行环境**:  
- 系统：Ubuntu 20.04  
- 处理器：Intel Core i9  
- 显卡：NVIDIA Geforce RTX 4060 (8G)
- 
## 示例结果

**特征匹配(部分)：**
![匹配1](Code/results/match_result_6_with_11.jpg)
![匹配2](Code/results/match_result_1_with_0.jpg)
![匹配3](Code/results/match_result_2_with_1.jpg)
![匹配4](Code/results/match_result_6_with_5.jpg)
![匹配5](Code/results/match_result_11_with_10.jpg)


**拼接结果：**
![拼接后](Code/results/final_image_compensation2lenel..jpg)
