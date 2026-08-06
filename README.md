# PID工程调试指南

西门子 PID 工程调试指南（应用示例），使用 [MkDocs](https://www.mkdocs.org/) + [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) 构建，通过 GitHub Actions 自动部署到 GitHub Pages。

- 在线地址：<http://blowmoldingshare.cn/pid-debug-guide/>
- 源码仓库：<https://github.com/lybhb8/pid-debug-guide>

## 本地预览

```bash
pip install mkdocs-material
mkdocs serve
```

## 更新流程

修改 `docs/` 下的内容后推送到 `main` 分支，GitHub Actions 会自动构建并部署。
