<div align="center">
  <p>
    <a href="https://platform.ultralytics.com/?utm_source=github&utm_medium=referral&utm_campaign=platform_launch&utm_content=banner&utm_term=yolo26_github" target="_blank">
      <img width="100%" src="https://raw.githubusercontent.com/ultralytics/assets/main/yolov8/banner-yolov8.png" alt="Ultralytics YOLO banner"></a>
  </p>

[中文](README.zh-CN.md) | [한국어](https://docs.ultralytics.com/ko) | [日本語](https://docs.ultralytics.com/ja) | [Русский](https://docs.ultralytics.com/ru) | [Deutsch](https://docs.ultralytics.com/de) | [Français](https://docs.ultralytics.com/fr) | [Español](https://docs.ultralytics.com/es) | [Português](https://docs.ultralytics.com/pt) | [Türkçe](https://docs.ultralytics.com/tr) | [Tiếng Việt](https://docs.ultralytics.com/vi) | [العربية](https://docs.ultralytics.com/ar) <br>

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

[Ultralytics](https://www.ultralytics.com/) [YOLO26](https://docs.ultralytics.com/models/yolo26) is available
through the official [Ultralytics YOLO](https://github.com/ultralytics/ultralytics) package. It supports object
detection, instance segmentation, semantic segmentation, image classification, pose estimation, oriented object
detection, and tracking in a fast, accurate, and easy to use Python and CLI workflow.

This repository is a lightweight discovery page for YOLO26. The canonical implementation, package releases, model
downloads, issues, and pull requests are maintained in [ultralytics/ultralytics](https://github.com/ultralytics/ultralytics).

<a href="https://platform.ultralytics.com/ultralytics/yolo26" target="_blank">
  <img width="100%" src="https://raw.githubusercontent.com/ultralytics/assets/refs/heads/main/yolo/performance-comparison.png" alt="YOLO26 performance plots">
</a>

<div align="center">
  <a href="https://github.com/ultralytics"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-github.png" width="2%" alt="Ultralytics GitHub"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="2%" alt="space">
  <a href="https://www.linkedin.com/company/ultralytics/"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-linkedin.png" width="2%" alt="Ultralytics LinkedIn"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="2%" alt="space">
  <a href="https://twitter.com/ultralytics"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-twitter.png" width="2%" alt="Ultralytics Twitter"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="2%" alt="space">
  <a href="https://www.youtube.com/ultralytics?sub_confirmation=1"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-youtube.png" width="2%" alt="Ultralytics YouTube"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="2%" alt="space">
  <a href="https://www.tiktok.com/@ultralytics"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-tiktok.png" width="2%" alt="Ultralytics TikTok"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="2%" alt="space">
  <a href="https://ultralytics.com/bilibili"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-bilibili.png" width="2%" alt="Ultralytics BiliBili"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="2%" alt="space">
  <a href="https://discord.com/invite/ultralytics"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-discord.png" width="2%" alt="Ultralytics Discord"></a>
</div>

## 📄 Documentation

See below for quickstart installation and YOLO26 usage examples. For comprehensive guidance on training, validation,
prediction, and deployment, refer to the full [Ultralytics Docs](https://docs.ultralytics.com).

<details open>
<summary>Install</summary>

Install the `ultralytics` package in a [Python>=3.8](https://www.python.org/) environment with
[PyTorch](https://pytorch.org/get-started/locally/).

[![PyPI - Version](https://img.shields.io/pypi/v/ultralytics?logo=pypi&logoColor=white)](https://pypi.org/project/ultralytics/)
[![Ultralytics Downloads](https://static.pepy.tech/badge/ultralytics)](https://clickpy.clickhouse.com/dashboard/ultralytics)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/ultralytics?logo=python&logoColor=gold)](https://pypi.org/project/ultralytics/)

```bash
pip install ultralytics
```

</details>

<details open>
<summary>Usage</summary>

### CLI

```bash
yolo predict model=yolo26n.pt source="https://ultralytics.com/images/bus.jpg"
```

### Python

```python
from ultralytics import YOLO

# Load a pretrained YOLO26n model
model = YOLO("yolo26n.pt")

# Run inference on the sample image
results = model("https://ultralytics.com/images/bus.jpg")

# Display the annotated results
results[0].show()
```

</details>

## ✨ Models

YOLO26 models are available for detection, instance segmentation, semantic segmentation, classification, pose estimation,
and oriented object detection. All model weights download automatically from the latest Ultralytics assets release on
first use.

<a href="https://docs.ultralytics.com/tasks" target="_blank">
    <img width="100%" src="https://raw.githubusercontent.com/ultralytics/assets/main/docs/ultralytics-yolov8-tasks-banner.avif" alt="Ultralytics YOLO supported tasks">
</a>

| Model Family                                                       | Example Weights                                                                           | Task                                                                 | Train | Val | Predict | Export |
| ------------------------------------------------------------------ | ----------------------------------------------------------------------------------------- | -------------------------------------------------------------------- | ----- | --- | ------- | ------ |
| [YOLO26](https://platform.ultralytics.com/ultralytics/yolo26)      | `yolo26n.pt` `yolo26s.pt` `yolo26m.pt` `yolo26l.pt` `yolo26x.pt`                          | [Detection](https://docs.ultralytics.com/tasks/detect)               | ✅    | ✅  | ✅      | ✅     |
| [YOLO26-seg](https://platform.ultralytics.com/ultralytics/yolo26)  | `yolo26n-seg.pt` `yolo26s-seg.pt` `yolo26m-seg.pt` `yolo26l-seg.pt` `yolo26x-seg.pt`      | [Instance Segmentation](https://docs.ultralytics.com/tasks/segment)  | ✅    | ✅  | ✅      | ✅     |
| [YOLO26-sem](https://platform.ultralytics.com/ultralytics/yolo26)  | `yolo26n-sem.pt` `yolo26s-sem.pt` `yolo26m-sem.pt` `yolo26l-sem.pt` `yolo26x-sem.pt`      | [Semantic Segmentation](https://docs.ultralytics.com/tasks/semantic) | ✅    | ✅  | ✅      | ✅     |
| [YOLO26-cls](https://platform.ultralytics.com/ultralytics/yolo26)  | `yolo26n-cls.pt` `yolo26s-cls.pt` `yolo26m-cls.pt` `yolo26l-cls.pt` `yolo26x-cls.pt`      | [Classification](https://docs.ultralytics.com/tasks/classify)        | ✅    | ✅  | ✅      | ✅     |
| [YOLO26-pose](https://platform.ultralytics.com/ultralytics/yolo26) | `yolo26n-pose.pt` `yolo26s-pose.pt` `yolo26m-pose.pt` `yolo26l-pose.pt` `yolo26x-pose.pt` | [Pose Estimation](https://docs.ultralytics.com/tasks/pose)           | ✅    | ✅  | ✅      | ✅     |
| [YOLO26-obb](https://platform.ultralytics.com/ultralytics/yolo26)  | `yolo26n-obb.pt` `yolo26s-obb.pt` `yolo26m-obb.pt` `yolo26l-obb.pt` `yolo26x-obb.pt`      | [Oriented Detection](https://docs.ultralytics.com/tasks/obb)         | ✅    | ✅  | ✅      | ✅     |

## 🧩 Integrations

Ultralytics integrations extend dataset labeling, training, visualization, deployment, and model management workflows.
Explore [Ultralytics Platform](https://platform.ultralytics.com) and the
[Ultralytics Integrations docs](https://docs.ultralytics.com/integrations) to connect YOLO26 with your AI stack,
including popular export formats like [TensorRT](https://docs.ultralytics.com/integrations/tensorrt),
[ONNX](https://docs.ultralytics.com/integrations/onnx),
[CoreML](https://docs.ultralytics.com/integrations/coreml), and
[TFLite](https://docs.ultralytics.com/integrations/tflite).

<a href="https://platform.ultralytics.com" target="_blank">
    <img width="100%" src="https://github.com/ultralytics/assets/raw/main/yolov8/banner-integrations.png" alt="Ultralytics active learning integrations">
</a>

## 🤝 Contribute

We thrive on community collaboration! Ultralytics YOLO would not be the SOTA framework it is without contributions from
developers like you. Please see our [Contributing Guide](https://docs.ultralytics.com/help/contributing) to get started.
For source changes, documentation improvements, bug reports, and feature requests, use the canonical
[ultralytics/ultralytics](https://github.com/ultralytics/ultralytics) repository.

[![Ultralytics open-source contributors](https://raw.githubusercontent.com/ultralytics/assets/main/im/image-contributors.png)](https://github.com/ultralytics/ultralytics/graphs/contributors)

## 📜 License

Ultralytics offers two licensing options to suit different needs:

- **AGPL-3.0 License**: This [OSI-approved](https://opensource.org/license/agpl-3.0) open-source license is perfect for students, researchers, and enthusiasts. It encourages open collaboration and knowledge sharing. See the [LICENSE](LICENSE) file for full details.
- **Ultralytics Enterprise License**: For development and production use, this license enables seamless integration of Ultralytics software and AI models into business products and services, including internal tools, automated workflows, and production deployments, bypassing the open-source requirements of AGPL-3.0. To get started, please contact us via [Ultralytics Licensing](https://www.ultralytics.com/license).

## 📞 Contact

For YOLO26 usage guidance, start with the [YOLO26 documentation](https://docs.ultralytics.com/models/yolo26). Install
or upgrade the [Ultralytics Python package](https://pypi.org/project/ultralytics/) with `pip`, and review the
[canonical source code](https://github.com/ultralytics/ultralytics) for implementation details.

> [!IMPORTANT]
> Please submit bug reports and feature requests in the
> [ultralytics/ultralytics issue tracker](https://github.com/ultralytics/ultralytics/issues/new/choose), where
> maintainers triage them alongside the source code.

For questions, discussions, and community support, join our active communities on
[Discord](https://discord.com/invite/ultralytics), [Reddit](https://www.reddit.com/r/ultralytics/), and the
[Ultralytics Community Forums](https://community.ultralytics.com/).

<br>
<div align="center">
  <a href="https://github.com/ultralytics"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-github.png" width="3%" alt="Ultralytics GitHub"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://www.linkedin.com/company/ultralytics/"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-linkedin.png" width="3%" alt="Ultralytics LinkedIn"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://twitter.com/ultralytics"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-twitter.png" width="3%" alt="Ultralytics Twitter"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://www.youtube.com/ultralytics?sub_confirmation=1"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-youtube.png" width="3%" alt="Ultralytics YouTube"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://www.tiktok.com/@ultralytics"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-tiktok.png" width="3%" alt="Ultralytics TikTok"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://ultralytics.com/bilibili"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-bilibili.png" width="3%" alt="Ultralytics BiliBili"></a>
  <img src="https://github.com/ultralytics/assets/raw/main/social/logo-transparent.png" width="3%" alt="space">
  <a href="https://discord.com/invite/ultralytics"><img src="https://github.com/ultralytics/assets/raw/main/social/logo-social-discord.png" width="3%" alt="Ultralytics Discord"></a>
</div>
