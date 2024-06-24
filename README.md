# 图像分类系统项目

## 项目简介
本项目是一个基于Python的图像分类系统，利用SIFT特征提取、KMeans聚类、词袋模型和支持向量机(SVM)对图像进行分类。系统适用于`scene_categories`数据集，该数据集包含15个类别的图像，适用于计算机视觉任务的研究和评估。

## 主要功能
- **SIFT特征提取**：自动提取图像的关键点和特征描述符。
- **KMeans聚类**：对特征描述符进行聚类，生成视觉词汇。
- **词袋模型**：将图像表示为视觉词汇的直方图。
- **SVM分类器**：使用词袋特征训练和预测图像分类。
- **性能评估**：计算分类准确率和混淆矩阵。

## 技术栈
- Python 3.9
- OpenCV
- scikit-learn
- NumPy
- joblib
- Matplotlib (用于绘图)
- Seaborn (用于混淆矩阵的可视化)

## 安装指南
1. 确保Python环境已安装。
2. 使用pip安装所需库：
   ```bash
   pip install numpy opencv-python scikit-learn joblib matplotlib seaborn
   ```
3. 下载[scene_categories数据集](https://figshare.com/articles/dataset/15Scene_Image_Dataset/7007177)。

## 文件说明
- `图像分类.ipynb`：包含图像分类系统的主要逻辑，包括数据准备、特征提取、特征聚类、分类器训练和评估。
- `加载权重_混淆矩阵.ipynb`：用于加载训练好的模型权重，评估分类器，并绘制混淆矩阵。
- `实验报告：图像分类实验.pdf`：包含实验的详细描述、结果和分析。

## 实验报告摘要
实验报告详细介绍了图像分类的方法、实验流程、结果和分析。报告中探讨了不同参数对分类性能的影响，并提出了改进方向。
