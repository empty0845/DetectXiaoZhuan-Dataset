# DetectXiaoZhuan-Dataset

[English README available here](README.md)

**DetectXiaoZhuan-Dataset** 旨在通过 **YOLOv5** 目标检测框架训练和评估 **detect_xiaozhuan** 模型。该数据集模拟了识别**石碑拓片**上的**小篆**的任务。图像均由黑色背景、白色篆字组成，以模拟**拓片**的效果。
此数据集包含**30个篆字**，适用于小篆的文本识别和分类任务。

## 数据集概览

- **训练集**：351张图像
- **测试集**：75张图像
- **验证集**：75张图像
- **类别总数**：30个类别

## 数据集结构

数据集文件结构：

- `images/train/` — 包含训练用的图像。
- `images/test/` — 包含测试用的图像。
- `images/val/` — 包含验证用的图像。
- `labels/train/` — 包含训练用的注释。
- `labels/test/` — 包含测试用的注释。
- `labels/val/` — 包含验证用的注释。

每个图像都有一个对应的 YOLO 格式的注释文件（每个图像一个 `.txt` 文件）。

## 数据集生成与标注

- **使用字体**：数据集使用了*全字庫說文解字.ttf*字体。
- **生成方法**：数据集中图像使用 Python 的 `wordcloud` 包和 *全字庫說文解字.ttf* 字体生成，以模拟石碑拓片效果。
- **标注工具**：注释使用 *labelImg* 工具手动创建，*labelImg* 是一个用于目标检测的图形图像注释工具。

## YOLOv5 使用说明

此数据集可直接用于 YOLOv5 的训练、验证和测试。请确保在数据集配置文件中指定正确的图像和注释路径。

## 许可证

本数据集遵循知识共享署名 4.0 国际许可协议 (CC BY 4.0)。您可以：

- 共享 — 以任何媒介或形式复制、再发布本数据集
- 修改 — 改编、转换并基于此数据集创作衍生作品，包括商业用途

条件是您必须给予适当的署名，注明是否对数据集进行修改，并附上许可证链接。

完整许可协议： [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/)

## 贡献者

此数据集由以下成员贡献：

- [empty0845](https://github.com/empty0845)
- [SparseMatric-1](https://github.com/SparseMatric-1)
- [Xi2aoyu24](https://github.com/Xi2aoyu24)
- [Eloisseee](https://github.com/Eloisseee)
