# GNN应用
## GNN + Knowledge Graph
### Cross-lingual Knowledge Graph Alignment via Graph Convolutional Networks（实体对齐），ACL2018
[paper link](https://aclanthology.org/D18-1032/)；[code link](https://github.com/1049451037/GCN-Align)

文中提出，通过图卷积网络（GCN）完成跨语言知识图谱对齐。给定一组预先对齐的实体，GCn-Align训练GCN将每种语言的实体嵌入到一个统一的向量空间中，然后基于嵌入空间中实体之间的距离进行实体对齐。该嵌入可以从实体的结构和属性信息中学习，结合结构嵌入和属性嵌入的结构得到准确的对齐结果。在真实的多语言知识图谱对齐实验中，与其他基于嵌入的知识图谱对齐方法相比，GCN-Align取得了SOTA。

**GCN-Align是第一个将GCNs应用到知识图谱实体对齐领域的工作。**