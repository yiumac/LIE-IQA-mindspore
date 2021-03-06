# LIE-IQA

The [MindSpore](https://www.mindspore.cn/) implementation of LIE-IQA is released [HERE](https://gitee.com/yiumac/contrib/tree/master/papers/LIE-IQA) and is merged with **[MindSpore/contrib](https://gitee.com/mindspore/contrib/tree/master/papers/LIE-IQA)** on Gitee. 

You can get the [Pytorch](https://pytorch.org/) implementation here [LIE-IQA-pytorch](https://github.com/yiumac/LIE-IQA-pytorch). It is worth noting that the MindSpore implementation of Image Intrinsic Decomposition (IID) Module is different from the Pytorch implementation , but there is not much difference in performance. Please refer to the specific code for details.

The code on Pytorchwill be released soon.

### Requirements

+ Python 3.7.5
+ MindSpore 1.2.1
+ CUDA 10.1

### Quality Assessment for Enhanced Low-light Image

+ LIE-IQA Framework

  <img src="fig/LIE-IQA-Framework.png" width="100%" />

+ Performance on LIE-IQA Dataset

  <img src="fig/performance-LIE-IQA-Dataset.png" width="80%"/>

+ Performance on General Scene IQA Dataset
  + LIVE, MDID, CSIQ
  
  <img src="fig/performance-IQA-Dataset.png" width="100%" />

### Quality Optimization for Low-light Image Enhancement

+ Optimization framework

  <img src="fig/optimization-framework.png" width="80%" />

