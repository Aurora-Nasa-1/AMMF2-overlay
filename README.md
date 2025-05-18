# AMMF2-overlay

[English](./README_EN.md)

## 简介

AMMF2-overlay 是一个为 AMMF2 框架制作的快速模块开发工具。它提供了一个简单的框架，让开发者能够快速创建和维护基于 AMMF2 的 Magisk 模块。

## 快速开始

1. 克隆仓库
```bash
git clone https://github.com/your-username/AMMF2-overlay.git
cd AMMF2-overlay
```

2. 修改配置
```bash
# 编辑 module_settings/build_config.sh
action_id="your_module_id"
action_name="Your Module Name"
```

3. 创建仓库推送代码并创建标签
```bash
git tag v1.0.0
git push --tags
```

## 文档

- [模块开发指南](./docs/module_development.md)
- [Module Development Guide](./docs/module_development_en.md)

## 许可证

本项目采用 MIT 许可证。

## 贡献

欢迎提交 Issue 和 Pull Request！

## 致谢

- [AMMF2](https://github.com/Aurora-Nasa-1/AMMF2)
- [Magisk](https://github.com/topjohnwu/Magisk)