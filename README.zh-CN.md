<div align="center">
  <p>
    <a href="https://platform.ultralytics.com/?utm_source=github&utm_medium=referral&utm_campaign=platform_launch&utm_content=banner&utm_term=yolo26_github" target="_blank">
      <img width="100%" src="https://raw.githubusercontent.com/ultralytics/assets/main/yolov8/banner-yolov8.png" alt="Ultralytics YOLO banner"></a>
  </p>

[中文](https://docs.ultralytics.com/zh) | [한국어](https://docs.ultralytics.com/ko) | [日本語](https://docs.ultralytics.com/ja) | [Русский](https://docs.ultralytics.com/ru) | [Deutsch](https://docs.ultralytics.com/de) | [Français](https://docs.ultralytics.com/fr) | [Español](https://docs.ultralytics.com/es) | [Português](https://docs.ultralytics.com/pt) | [Türkçe](https://docs.ultralytics.com/tr) | [Tiếng Việt](https://docs.ultralytics.com/vi) | [العربية](https://docs.ultralytics.com/ar) <br>

<div>
    <a href="https://github.com/ultralytics/ultralytics/actions/workflows/ci.yml"><img src="https://github.com/ultralytics/ultralytics/actions/workflows/ci.yml/badge.svg" alt="Ultralytics CI"></a>
    <a href="https://clickpy.clickhouse.com/dashboard/ultralytics"><img src="https://static.pepy.tech/badge/ultralytics" alt="Ultralytics Downloads"></a>
    <a href="https://discord.com/invite/ultralytics"><img alt="Ultralytics Discord" src="https://img.shields.io/discord/1089800235347353640?logo=discord&logoColor=white&label=Discord&color=blue"></a>
    <a href="https://community.ultralytics.com/"><img alt="Ultralytics Forums" src="https://img.shields.io/discourse/users?server=https%3A%2F%2Fcommunity.ultralytics.com&logo=discourse&label=Forums&color=blue"></a>
    <a href="https://www.reddit.com/r/ultralytics/"><img alt="Ultralytics Reddit" src="https://img.shields.io/reddit/subreddit-subscribers/ultralytics?style=flat&logo=reddit&logoColor=white&label=Reddit&color=blue"></a>
    <br>
    <a href="https://console.paperspace.com/github/ultralytics/ultralytics"><img src="https://assets.paperspace.io/img/gradient-badge.svg" alt="Run Ultralytics on Gradient"></a>
    <a href="https://colab.research.google.com/github/ultralytics/ultralytics/blob/main/examples/tutorial.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open Ultralytics In Colab"></a>
    <a href="https://www.kaggle.com/models/ultralytics/yolo26"><img src="https://kaggle.com/static/images/open-in-kaggle.svg" alt="Open Ultralytics In Kaggle"></a>
    <a href="https://mybinder.org/v2/gh/ultralytics/ultralytics/HEAD?labpath=examples%2Ftutorial.ipynb"><img src="https://mybinder.org/badge_logo.svg" alt="Open Ultralytics In Binder"></a>
</div>
</div>
<br>

[Ultralytics](https://www.ultralytics.com/) [YOLO26](https://docs.ultralytics.com/zh/models/yolo26) 可通过官方
[Ultralytics YOLO](https://github.com/ultralytics/ultralytics) 包使用，支持目标检测、实例分割、语义分割、图像分类、姿态估计、旋转目标检测和跟踪，并提供快速、准确、易用的 Python 与 CLI 工作流。

本仓库是 YOLO26 的轻量级发现入口。官方实现、软件包发布、模型下载、Issues 和 Pull Requests 均在
[ultralytics/ultralytics](https://github.com/ultralytics/ultralytics) 仓库维护。

<a href="https://platform.ultralytics.com/ultralytics/yolo26" target="_blank">
  <img width="100%" src="https://raw.githubusercontent.com/ultralytics/assets/refs/heads/main/yolo/performance-comparison.png" alt="YOLO26 performance plots">
</a>

## 📄 文档

请参阅下文了解快速安装和 YOLO26 使用示例。有关训练、验证、预测和部署的完整指南，请参阅
[Ultralytics 文档](https://docs.ultralytics.com/zh)。

<details open>
<summary>安装</summary>

在 [Python>=3.8](https://www.python.org/) 环境中安装 `ultralytics` 包，并使用
[PyTorch](https://pytorch.org/get-started/locally/)。

[![PyPI - Version](https://img.shields.io/pypi/v/ultralytics?logo=pypi&logoColor=white)](https://pypi.org/project/ultralytics/)
[![Ultralytics Downloads](https://static.pepy.tech/badge/ultralytics)](https://clickpy.clickhouse.com/dashboard/ultralytics)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/ultralytics?logo=python&logoColor=gold)](https://pypi.org/project/ultralytics/)

```bash
pip install ultralytics
```

</details>

<details open>
<summary>使用方法</summary>

### CLI

```bash
yolo predict model=yolo26n.pt source="https://ultralytics.com/images/bus.jpg"
```

### Python

```python
from ultralytics import YOLO

# 加载预训练的 YOLO26n 模型
model = YOLO("yolo26n.pt")

# 对示例图像运行推理
results = model("https://ultralytics.com/images/bus.jpg")

# 显示带标注的结果
results[0].show()
```

</details>

## ✨ 模型

YOLO26 模型支持检测、实例分割、语义分割、分类、姿态估计和旋转目标检测。所有模型权重都会在首次使用时从最新的 Ultralytics assets 发布版本自动下载。

<a href="https://docs.ultralytics.com/zh/tasks" target="_blank">
    <img width="100%" src="https://raw.githubusercontent.com/ultralytics/assets/main/docs/ultralytics-yolov8-tasks-banner.avif" alt="Ultralytics YOLO supported tasks">
</a>

| 模型系列                                                           | 示例权重                                                                                  | 任务                                                       | Train | Val | Predict | Export |
| ------------------------------------------------------------------ | ----------------------------------------------------------------------------------------- | ---------------------------------------------------------- | ----- | --- | ------- | ------ |
| [YOLO26](https://platform.ultralytics.com/ultralytics/yolo26)      | `yolo26n.pt` `yolo26s.pt` `yolo26m.pt` `yolo26l.pt` `yolo26x.pt`                          | [检测](https://docs.ultralytics.com/zh/tasks/detect)       | ✅    | ✅  | ✅      | ✅     |
| [YOLO26-seg](https://platform.ultralytics.com/ultralytics/yolo26)  | `yolo26n-seg.pt` `yolo26s-seg.pt` `yolo26m-seg.pt` `yolo26l-seg.pt` `yolo26x-seg.pt`      | [实例分割](https://docs.ultralytics.com/zh/tasks/segment)  | ✅    | ✅  | ✅      | ✅     |
| [YOLO26-sem](https://platform.ultralytics.com/ultralytics/yolo26)  | `yolo26n-sem.pt` `yolo26s-sem.pt` `yolo26m-sem.pt` `yolo26l-sem.pt` `yolo26x-sem.pt`      | [语义分割](https://docs.ultralytics.com/zh/tasks/semantic) | ✅    | ✅  | ✅      | ✅     |
| [YOLO26-cls](https://platform.ultralytics.com/ultralytics/yolo26)  | `yolo26n-cls.pt` `yolo26s-cls.pt` `yolo26m-cls.pt` `yolo26l-cls.pt` `yolo26x-cls.pt`      | [分类](https://docs.ultralytics.com/zh/tasks/classify)     | ✅    | ✅  | ✅      | ✅     |
| [YOLO26-pose](https://platform.ultralytics.com/ultralytics/yolo26) | `yolo26n-pose.pt` `yolo26s-pose.pt` `yolo26m-pose.pt` `yolo26l-pose.pt` `yolo26x-pose.pt` | [姿态估计](https://docs.ultralytics.com/zh/tasks/pose)     | ✅    | ✅  | ✅      | ✅     |
| [YOLO26-obb](https://platform.ultralytics.com/ultralytics/yolo26)  | `yolo26n-obb.pt` `yolo26s-obb.pt` `yolo26m-obb.pt` `yolo26l-obb.pt` `yolo26x-obb.pt`      | [旋转目标检测](https://docs.ultralytics.com/zh/tasks/obb)  | ✅    | ✅  | ✅      | ✅     |

## 🧩 集成

Ultralytics 集成扩展了数据集标注、训练、可视化、部署和模型管理工作流。了解
[Ultralytics Platform](https://platform.ultralytics.com) 和
[Ultralytics 集成文档](https://docs.ultralytics.com/integrations)，将 YOLO26 连接到您的 AI 工作流，包括常用导出格式
[TensorRT](https://docs.ultralytics.com/integrations/tensorrt)、[ONNX](https://docs.ultralytics.com/integrations/onnx)、
[CoreML](https://docs.ultralytics.com/integrations/coreml) 和
[TFLite](https://docs.ultralytics.com/integrations/tflite)。

<a href="https://platform.ultralytics.com" target="_blank">
    <img width="100%" src="https://github.com/ultralytics/assets/raw/main/yolov8/banner-integrations.png" alt="Ultralytics active learning integrations">
</a>

## 🤝 贡献

请参阅[贡献指南](https://docs.ultralytics.com/help/contributing)开始贡献。源码更改、文档改进、错误报告和功能请求请提交到官方
[ultralytics/ultralytics](https://github.com/ultralytics/ultralytics) 仓库。

[![Ultralytics open-source contributors](https://raw.githubusercontent.com/ultralytics/assets/main/im/image-contributors.png)](https://github.com/ultralytics/ultralytics/graphs/contributors)

## 📜 许可证

- **AGPL-3.0 许可证**：有关完整详细信息，请参阅 [LICENSE](LICENSE) 文件。
- **Ultralytics 企业许可证**：如需商业用途，请通过 [Ultralytics 授权许可](https://www.ultralytics.com/license)与我们联系。

## 📞 联系方式

YOLO26 使用指南请先查看 [YOLO26 文档](https://docs.ultralytics.com/zh/models/yolo26)。可通过 `pip` 安装或升级
[Ultralytics Python 包](https://pypi.org/project/ultralytics/)，并在
[官方源代码](https://github.com/ultralytics/ultralytics)中查看实现细节。

> [!IMPORTANT]
> 请在 [ultralytics/ultralytics issue tracker](https://github.com/ultralytics/ultralytics/issues/new/choose)
> 提交错误报告和功能请求，方便维护者结合源代码统一分类处理。

如有疑问、讨论和社区支持，请加入 [Discord](https://discord.com/invite/ultralytics)、[Reddit](https://www.reddit.com/r/ultralytics/)
和 [Ultralytics 社区论坛](https://community.ultralytics.com/)。
