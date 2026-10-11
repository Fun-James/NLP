# HW1：NYT 新闻文本分类

- **作业要求**：在 NYT 数据集上比较词袋、100 维词向量和 BERT 文本分类方法，统一按 80% / 10% / 10% 划分训练、验证和测试集，以 Accuracy 和 Macro-F1 评价。详细要求见 [作业一要求.docx](作业一要求.docx)。
- **完成内容**：实现 Binary BoW、Word Frequency、GloVe、AG News Word2Vec、NYT Word2Vec 和 BERT 六组实验；前五组使用 Logistic Regression，BERT 设置最大长度 64、训练 3 轮，并汇总结果、绘制对比图和混淆矩阵。
- **代码运行**：在本文件夹下，用 Jupyter Notebook 或 VS Code 打开 [HW1_NYT_Text_Classification.ipynb](HW1_NYT_Text_Classification.ipynb)，选择 Python 3.10+ 环境并按顺序运行单元格。依赖安装命令见 Notebook 开头；数据为 `nyt.csv` 和 `ag.csv`，资源位于 `assets/`，首次运行需联网下载缺失资源，结果和模型参数保存至 `artifacts/`。
- **实验报告**：[2313447_HW1.pdf](2313447_HW1.pdf)。
