
# 视觉Transformer鲁棒性
## Robustifying Token Attention for Vision Transformers, ICCV2023

[paper link](https://arxiv.org/abs/2303.11126)； 

视觉Transformer在面对图像扰动时，性能会显著下降。原因在于ViT的关键部分———自注意力机制中存在“token overfocusing”的问题，即注意力机制过度依赖于少数重要的token，但这些token对图像扰动极为敏感。

为此提出：Token-aware Average Pooling(TAP)和Attention Diversification Loss(ADL)，所提出的方法可应用于大多数ViT架构，在不增加训练开销情况下提升分类精度和鲁棒性，此外，这种改进也可以很好推广到其他下游任务，比如语义分割。

该文为提升ViT的鲁棒性提供了有效途径。


