# PID工程调试指南

西门子 PID 工程调试指南（应用示例）的在线文档，面向自动化工程师，涵盖 PID 控制系统调试的全流程：前期准备、基础理论、工程调试、虚拟仿真、常见问题与附件工具。

## 主要内容

- **PID 控制系统调试前期准备** — 工艺了解、对象特性分析与调试规划
- **PID 基础理论** — 理想型 PID 公式、增量式 PID 离散算法、参数含义（Kp/Ti/Td）
- **PID 工程调试** — 等幅振荡法、1/4 衰减法、参数手动整定步骤
- **虚拟 PID 工程仿真** — 参数调整与响应特性仿真工具使用
- **常见问题 / 附件工具 / 参考资料 / 更新日志**

## 部署技术

- 静态站点：[MkDocs](https://www.mkdocs.org/) + [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) 主题
- 公式渲染：`pymdownx.arithmatex` + [MathJax 3](https://www.mathjax.org/)（支持文档内 LaTeX 公式）
- 托管：GitHub Pages，从 `gh-pages` 分支部署
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
