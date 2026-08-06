# PID工程调试指南

西门子 PID 工程调试指南（应用示例），使用 [MkDocs](https://www.mkdocs.org/) + [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) 构建，通过 gh-pages 分支部署到 GitHub Pages。

- 在线地址：<http://blowmoldingshare.cn/pid-debug-guide/>
- 源码仓库：<https://github.com/lybhb8/pid-debug-guide>

## 本地预览

```bash
pip install mkdocs-material
mkdocs serve
```

## 更新与部署

修改 `docs/` 下的内容后，重新构建并推送到 gh-pages 分支：

```bash
mkdocs gh-deploy --force
```

部署源已配置为 `gh-pages` 分支（`/` 根目录），推送后 GitHub Pages 会自动更新。
