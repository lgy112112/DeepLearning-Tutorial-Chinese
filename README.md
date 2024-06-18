# 🚀 DeepLearning-Tutorial-Chinese 🎉

欢迎来到 **DeepLearning-Tutorial-Chinese** 仓库！这里有一系列精彩的深度学习教程和示例代码，旨在帮助大家更好地理解和应用深度学习技术。无论你是初学者还是进阶者，都能在这里找到有用的资源。 🌟

## 📈 2024/06/18 本次更新：蒸汽量回归预测 📊

我非常兴奋地向大家介绍本次仓库的最新更新：**蒸汽量回归预测**。在这个更新中，我通过构建和训练一个简单而强大的神经网络模型，来预测蒸汽的输出量。这些代码涵盖了数据预处理、模型构建、训练、评估等多个环节，帮助你全面掌握回归任务的实现过程。🤖

### 更新内容 🌟

1. **数据预处理** 🧹
   - 使用 `pandas` 进行数据加载和清洗。
   - 对数据进行标准化处理，确保特征在同一尺度下进行训练。
   - 详见 [steam_preprocess.ipynb](https://github.com/lgy112112/DeepLearning-Tutorial-Chinese/blob/main/steam_preprocess.ipynb)。

2. **模型构建** 🏗️
   - 定义了一个简单的深度神经网络模型，包括多个残差块和输出层。
   - 使用 `PyTorch` 构建模型，并实现了前向传播和损失计算。

3. **训练流程** 🚀
   - 使用批量梯度下降法进行模型训练。
   - 在训练过程中实时监测和绘制损失、MAE、MSE 和 R² 分数。
   - 每100个epoch保存一次模型，确保可以回溯到最佳模型状态。
   - 详见 [steam_train.ipynb](https://github.com/lgy112112/DeepLearning-Tutorial-Chinese/blob/main/steam_train.ipynb)。

4. **评估指标** 📊
   - 实现了多种评估指标，包括 MAE、MSE 和 R² 分数，全面评估模型性能。
   - 在训练和验证集上计算和对比评估指标，确保模型的泛化能力。

5. **可视化** 📈
   - 实时绘制训练和验证集的损失、MAE、MSE 和 R² 分数，帮助直观了解模型性能变化。

### 代码结构 📂

```plaintext
.
├── README.md                 # 仓库说明文件
├── steam_preprocess.ipynb    # 数据预处理代码
├── steam_test.txt            # 测试集数据
├── steam_train.ipynb         # 模型训练代码
├── steam_train.txt           # 训练集数据
```

### 快速开始 🚀

1. 克隆仓库：
   ```bash
   git clone https://github.com/lgy112112/DeepLearning-Tutorial-Chinese.git
   cd DeepLearning-Tutorial-Chinese
   ```
   
### 结语 🌟

希望大家能从本次更新中学到更多深度学习的知识，并将其应用到自己的项目中。如果你有任何问题或建议，欢迎提交issue或pull request。让我一起在深度学习的世界里探索更多可能性！🚀

感谢大家的支持！🎉

---
**保持学习，保持热情！** 💪

🎉 **DeepLearning-Tutorial-Chinese 团队** 🎉

[![GitHub stars](https://img.shields.io/github/stars/lgy112112/DeepLearning-Tutorial-Chinese?style=social)](https://github.com/lgy112112/DeepLearning-Tutorial-Chinese)
[![GitHub forks](https://img.shields.io/github/forks/lgy112112/DeepLearning-Tutorial-Chinese?style=social)](https://github.com/lgy112112/DeepLearning-Tutorial-Chinese)
