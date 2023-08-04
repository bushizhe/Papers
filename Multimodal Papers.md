## Vision-Language Transformer
### UPop: Unified and Progressive Pruning for Compressing Vision-Language Transformers, **ICML2023**
[paper link](https://proceedings.mlr.press/v202/shi23e/shi23e.pdf) ; [code link](https://github.com/sdc17/UPop)

UPop是首个用于Vision-Transformer模型的结构化剪枝框架，能够对各种多模态和单模态任务、数据集和模型结构（BLIP、CLIP、DeiT和Segmenter)进行有效的结构化剪枝。
UPop所解决的问题：
- 不同于以往使用网格搜索进行重复实验，UPop使用`Unified Search`高效地为不同模态和结构搜索给定总压缩率下各自的最优压缩率；
- UPop使用的`Progressive Pruning`消除了以往的剪枝方法中存在的搜索后的模型与待重新训练的自网络之间的参数权重gap，从而获得更好的收敛性和高压缩率下更好表现
