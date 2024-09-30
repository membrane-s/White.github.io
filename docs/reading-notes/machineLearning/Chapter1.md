<!-- 记录机器学习的笔记 -->

```mermaid
graph LR
    A[数据/经验] --> B[学习算法]
    B --> C[模型]
    C --> D[预测/决策]
    
    subgraph 数据相关
    E[示例/样本]
    F[特征/属性]
    G[标记/标签]
    end
    
    subgraph 模型相关
    H[假设空间]
    I[假设]
    J[学习器]
    end
    
    subgraph 评估
    K[训练集]
    L[测试集]
    M[泛化能力]
    end
```mermaid