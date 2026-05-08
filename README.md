# 计算机视觉快速入门讲义

这个项目主要是作者的学习笔记，是面向初学者的计算机视觉快速入门讲义。

写作目标不是罗列概念，也不是做论文式摘要，而是**像优秀老师讲课一样，把初学者真正带懂**。

目前项目的重点放在两条主线：

1. 从注意力机制到Transformer
2. 从Transformer到Vision Transformer（ViT）

后续计划补齐CNN、目标检测、语义分割、多模态视觉等内容，使整套讲义更完整地覆盖计算机视觉入门所需的核心主线。

## 适合读者

- 想快速建立计算机视觉整体框架的初学者
- 已经接触过一些深度学习，但对Transformer、ViT理解还不系统的读者
- 希望用讲义而不是论文摘要方式来学习相关内容的读者

## 当前已完成内容

### Transformer基础

- [Transformer-1-注意力机制.ipynb](./Transformer-1-注意力机制.ipynb)
- [Transformer-2-Embedding与位置编码.ipynb](./Transformer-2-Embedding与位置编码.ipynb)
- [Transformer-3-Encoder结构解析.ipynb](./Transformer-3-Encoder结构解析.ipynb)
- [Transformer-4-Decoder结构解析.ipynb](./Transformer-4-Decoder结构解析.ipynb)

### Vision Transformer

- [ViT-1-核心思想与整体结构.ipynb](./ViT-1-核心思想与整体结构.ipynb)
- [ViT-2-模型的输入.ipynb](./ViT-2-模型的输入.ipynb)
- [ViT-3-CLSToken与分类输出.ipynb](./ViT-3-CLSToken与分类输出.ipynb)
- [ViT-4-ViT中的位置编码.ipynb](./ViT-4-ViT中的位置编码.ipynb)
- [ViT-5-Transformer Encoder主干.ipynb](./ViT-5-Transformer%20Encoder主干.ipynb)
- [ViT-6-训练、特点与局限.ipynb](./ViT-6-训练、特点与局限.ipynb)

## 计划中的整体目录

下面是这套“计算机视觉快速入门讲义”建议采用的整体主线。

### 第一部分：图像与视觉基础

1. 图像的基本表示
2. 图像张量、通道、分辨率
3. 常见视觉任务概览

### 第二部分：CNN基础

1. 为什么卷积适合图像
2. 卷积层、步幅、填充
3. 池化、通道与特征图
4. 感受野与层级特征
5. 经典CNN到ResNet

### 第三部分：Transformer基础（已完成）

1. 注意力机制
2. Embedding与位置编码
3. Encoder结构解析
4. Decoder结构解析

### 第四部分：Vision Transformer（已完成）

1. ViT核心思想与整体结构
2. ViT模型的输入
3. CLS Token与分类输出
4. ViT中的位置编码
5. Transformer Encoder主干
6. 训练、特点与局限

### 第五部分：计算机视觉中的更广泛任务

1. 目标检测基础
2. 语义分割基础
3. 实例分割与全景分割概览

### 第六部分：进阶方向

1. 自监督学习与视觉预训练
2. 多模态视觉与CLIP
3. 生成式视觉模型与扩散模型
4. 视觉大模型基础

## 项目文件说明

- [讲义写作规范.md](./讲义写作规范.md)：后续讲义统一遵循的写作规范
- `test.md`：过程性文件，不属于正式讲义主线

## 写作特点

- 强调问题驱动，而不是上来直接堆公式
- 强调直觉、例子、结构和公式之间的过渡
- 主动补充初学者最容易卡住的隐含前提
- 需要图示的地方会提供单独的绘图提示词

## 说明

这套讲义目前仍在持续补写中。现阶段最完整的部分是Transformer与ViT主线，后续会继续补齐CNN和更完整的计算机视觉任务体系。


