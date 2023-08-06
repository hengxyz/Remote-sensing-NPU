# Deep Hierarchical Vision Transformer for Hyperspectral and LiDAR Data Classification
## info
``` ad-info
# 用于高光谱和 LiDAR 数据分类的深度分层视觉转换器
title: Metadata
- **CiteKey**: {{citekey}}
- **Type**: Journal Article
- **Author**: Xue, Zhixiang; Tan, Xiong; Yu, Xuchu; Liu, Bing; Yu, Anzhu; Zhang, Pengqiang
- **Editor**: {{editor}}
- **Translator**: {{translator}}
- **Publisher**: {{publisher}}
- **Location**: {{place}}
- **Series**: {{series}}
- **Series Number**: {{seriesNumber}}
- **Journal**: IEEE Transactions on Image Processing
- **Volume**: 31
- **Issue**: {{issue}}
- **Pages**: 3095-3110
- **Year**: 2022
- **DOI**: 10.1109/TIP.2022.3162964
- **ISSN**: 1057-7149, 1941-0042
- **ISBN**: {{ISBN}}
```

```
```ad-quote
title: Abstract
In this study, we develop a novel deep hierarchical vision transformer (DHViT) architecture for hyperspectral and light detection and ranging (LiDAR) data joint classiﬁcation. Current classiﬁcation methods have limitations in heterogeneous feature representation and information fusion of multi-modality remote sensing data (e.g., hyperspectral and LiDAR data), these shortcomings restrict the collaborative classiﬁcation accuracy of remote sensing data. The proposed deep hierarchical vision transformer architecture utilizes both the powerful modeling capability of long-range dependencies and strong generalization ability across different domains of the transformer network, which is based exclusively on the self-attention mechanism. Speciﬁcally, the spectral sequence transformer is exploited to handle the long-range dependencies along the spectral dimension from hyperspectral images, because all diagnostic spectral bands contribute to the land cover classiﬁcation. Thereafter, we utilize the spatial hierarchical transformer structure to extract hierarchical spatial features from hyperspectral and LiDAR data, which are also crucial for classiﬁcation. Furthermore, the cross attention (CA) feature fusion pattern could adaptively and dynamically fuse heterogeneous features from multi-modality data, and this contextual aware fusion mode further improves the collaborative classiﬁcation performance. Comparative experiments and ablation studies are conducted on three benchmark hyperspectral and LiDAR datasets, and the DHViT model could yield an average overall classiﬁcation accuracy of 99.58%, 99.55%, and 96.40% on three datasets, respectively, which sufﬁciently certify the effectiveness and superior performance of the proposed method.

在这项研究中，我们开发了一种新颖的深度分层视觉变换器（DHViT）架构，用于高光谱和光检测与测距（LiDAR）数据联合分类。
目前的分类方法在多模态遥感数据（如高光谱和激光雷达数据）的异构特征表示和信息融合方面存在局限性，这些缺点限制了遥感数据的协同分类精度。
所提出的深度分层视觉变压器架构利用了变压器网络强大的远程依赖建模能力和跨不同领域的强大泛化能力，这是完全基于自注意力机制的。
具体来说，利用光谱序列变换器来处理高光谱图像沿光谱维度的远程依赖性，因为所有诊断光谱带都有助于土地覆盖分类。
此后，我们利用空间分层变换器结构从高光谱和激光雷达数据中提取分层空间特征，这对于分类也至关重要。
此外，交叉注意（CA）特征融合模式可以自适应地、动态地融合来自多模态数据的异构特征，并且这种上下文感知融合模式进一步提高了协作分类性能。
在三个基准高光谱和激光雷达数据集上进行了比较实验和消融研究，DHViT 模型在三个数据集上的平均整体分类精度分别为 99. 58%、99. 55% 和 96. 40%，这足以满足
证明所提出方法的有效性和优越性能。
```

```ad-abstract
title: Files and Links
- **Url**: https://ieeexplore.ieee.org/document/9755059/
- **Uri**: http://zotero.org/users/9643615/items/VXFB963R
- **Eprint**: {{eprint}}
- **File**: [Xue 等 - 2022 - Deep Hierarchical Vision Transformer for Hyperspectral and LiDAR Data Classification.pdf](file:///D:%5CAASoftware%5CZotero%5CData%5Cstorage%5CWMQY6DYV%5CXue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf)
- **Local Library**: [Zotero](zotero://select/library/items/VXFB963R)
```
```ad-note
title: Tags and Collections
- **Keywords**: RS; classification 分类; multimodal
- **Collections**: {{collectionsParent}}
```

## Contributions
1. [spectral sequence transformer](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=b71d9d76-c3a3-c952-1714-23ea5f59f3e8&page=2&rect=114.573,685.608,237.324,696.726) 捕获光谱长期依赖性 could handle long-range dependen-cies along the spectral dimension of HSI, and these global spectral relationships have strong representation ability for hyperspectral data.
2. [spatial hierarchical transformer](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=9e3ac143-3e0d-e095-888a-2887a2a36573&page=2&rect=124.598,625.728,251.770,636.846) utilizes the desirable scale and distortion invariance properties of convolutional neural networks while maintaining the bet-ter generalization merit of transformers to extract hier-archical spatial features from hyperspectral and LiDAR data under the multi-stage hierarchy structure. 利用卷积神经网络的尺度不变性和失真不变性，同时保持变换器较好的泛化能力，在多级层次结构下从高光谱和LiDAR数据中提取层次空间特征。
3. 利用交叉注意力机制自适应融合多模态数据
4. Fourth, sufﬁcient comparative experiments and ablation studies carried out on three hyperspectral and LiDAR datasets demonstrate the effectiveness and superior per-formance of the proposed model.

## RELATED WORK
[Handcrafted Feature Stacking Fusion](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=fae51472-9c9f-7a08-b624-4a202f1bbba5&page=2&rect=61.094,333.277,214.151,344.137) 人工制作的功能堆叠融合
[Subspace-Based Feature Fusion](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=02c88be8-1066-789a-affa-b18332659a38&page=2&rect=324.132,723.873,454.632,734.733) 多分支深度学习结构
[Multi-Branch Deep Learning Structure](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=e4128ad2-b38b-36ec-f0e0-f1c13763890e&page=2&rect=324.758,474.752,483.442,485.612)
[Content-Aware Feature Fusion](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=49f43475-6010-7bd1-771d-44d2926f351f&page=2&rect=325.199,177.870,450.450,188.729) 内容感知特征融合

## METHODOLOGY
![[Pasted image 20230805144750.png]]
[The schematic architecture of deep hierarchical vision transformer](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=8b0c3f0c-bf76-a24a-185b-93e37b9c0738&page=3&rect=78.645,352.203,296.122,361.097)

### [Spectral Sequence Transformer](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=913ef22f-b48a-cde4-3851-3302ddcdd9bb&page=4&rect=61.084,491.173,188.757,502.056)
从光谱维度划分patch，捕获光谱序列长距离依赖关系

![[Pasted image 20230805152743.png]]



### [Spatial Hierarchical Transformer](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=bac313d1-3f55-3f0b-c7bb-027ab4245ee8&page=4&rect=324.135,260.653,460.087,271.536)
空间层次 Transformer
首先利用PCA将光谱维度降低到3 ：输入数据格式：M * N * 3
[Convolutional Token Embedding:](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=ec115114-3c5c-e259-5604-9d50cc5cd450&page=4&rect=333.839,102.046,473.248,113.163)
[Convolutional Projection for Attention](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=10dd02d3-a773-7679-bcbb-b11e4ed2425b&page=5&rect=333.834,247.607,491.858,258.725)
![[Pasted image 20230805153632.png]]

### [Cross Attention Feature Fusion](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=5ea06709-011a-0150-3edc-57dd43830e98&page=6&rect=48.960,355.693,189.660,366.576)
交叉注意力进行特征融合

![[Pasted image 20230805154025.png]]

[Network Architecture of DHViT](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=ccf3ca13-97bc-8eb9-f2ed-51d775628a2a&page=6&rect=325.190,475.934,455.002,486.817)

The input for the spectral branch is hyperspectral data patches, and the size of the image patch is 16 × 16 × B,in which B is the number of spectral bands.
For the spatial branch, the principal component analysis (PCA) operation is ﬁrst applied to the HSI patches,and ﬁrst three principal components are selected as the input for following convolutional embedding, and the size of the spa-tial patch is 32×32×3.

![[Pasted image 20230805154000.png]]

## [EXPERIMENTS](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=b86e8068-888d-fb45-2f01-48f8791542e7&page=7&rect=153.001,413.088,214.075,424.206)
### Datasets
Trento, Houston 2013, Houston 2018
### Comparison to State-of-the-Arts
[Quantitative Evaluation:](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=2b5fb93d-9356-8eda-5ffe-d14a242af5e9&page=9&rect=70.800,86.085,173.373,97.203)
[Classiﬁcation Maps:](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=05c155e0-f35b-0c42-9750-e673f5a83220&page=11&rect=70.795,267.409,154.043,278.527)
### [Ablation Studies of the Proposed Model](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=379c8f52-4d89-3269-b727-0a44fdfadef3&page=11&rect=325.199,233.171,489.002,244.054)
Different Modal Features:
![[Pasted image 20230805154644.png]]
[Feature Fusion Mode](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=c8faecb5-92ac-c39e-b9b4-d360c040c992&page=12&rect=333.835,154.847,421.277,165.964)
![[Pasted image 20230805154757.png]]
[Parameter Sensitivity Analysis](obsidian://booknote?type=annotation&book=WMQY6DYV/Xue%20%E7%AD%89%20-%202022%20-%20Deep%20Hierarchical%20Vision%20Transformer%20for%20Hyperspectral%20and%20LiDAR%20Data%20Classification.pdf&id=c635f0ab-39c4-9afc-7261-4741180d6a88&page=13&rect=61.050,215.414,184.612,226.297)
## CONCLUSION
In this study, we investigate a novel deep hierarchical vision transformer network for hyperspectral and LiDAR data collaborative classiﬁcation, which have two main advantages.
In the RS data land cover classiﬁcation, different data have different modal features, for instance, the spectral feature is one-dimensional while the spatial feature is two-dimensional.
Based on this fact, we exploit a novel transformer architecture to model RS data, namely spectral sequence transformer to handle the long-range dependencies along spectral dimension and spatial hierarchical transformer to extract hierarchical spatial features. Thereafter, using the powerful generalization ability of the transformer, we further propose a novel decision-level feature fusion pattern based on the cross attention mechanism to adaptively fuse heterogeneous features for collaborative classiﬁcation. Therefore, the deep hierarchical vision transformer model can extract more discriminative characteristics and effectively fuse heterogeneous features for land cover classiﬁcation. We perform three groups of HSI and LiDAR data collaborative classiﬁcation to verify the performance of DHViT, and comparative experiments as well as ablation studies certify the effectiveness and superior performance of the proposed model.
## 结论
在本研究中，我们研究了一种用于高光谱和激光雷达数据协作分类的新型深度分层视觉变换器网络，它具有两个主要优点。

在遥感数据土地覆盖分类中，不同的数据具有不同的模态特征，例如光谱特征是一维的，而空间特征是二维的。

基于这一事实，我们利用一种新颖的变压器架构来对遥感数据进行建模，即频谱序列变压器来处理沿频谱维度的远程依赖性，以及空间分层变压器来提取分层空间特征。
此后，利用变压器强大的泛化能力，我们进一步提出了一种基于交叉注意机制的新型决策级特征融合模式，以自适应地融合异构特征以进行协作分类。
因此，深层分层视觉变换器模型可以提取更具辨别力的特征，并有效融合异质特征以进行土地覆盖分类。
我们进行了三组 HSI 和 LiDAR 数据协同分类来验证 DHViT 的性能，并且对比实验和消融研究证明了所提出模型的有效性和优越性能。