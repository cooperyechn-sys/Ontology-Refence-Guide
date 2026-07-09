# Ontology References 导读

> 从哲学根基到智能体应用 · 一份面向计算机/AI背景读者的本体论文文献地图

收录 **3 篇核心论文**，配合 7 个阶段的逻辑脉络，展示"本体"（Ontology）从哲学概念到 LLM 时代技术落地的完整知识链。

## 三篇核心论文

| 阶段 | 论文 | 核心问题 |
|------|------|----------|
| 概念反思 | Neuhaus 2018 · What is an Ontology? | 本体的定义到底应该是什么？ |
| LLM 时代 | Giglou 2023 · LLMs4OL | LLM 如何自动构建本体？ |
| LLM 时代 | Sharma 2024 · OG-RAG | 本体如何让 RAG 更可靠？ |

## 阅读顺序

Neuhaus 2018 → Giglou 2023 → Sharma 2024

先厘清本体到底是什么，再看 LLM 如何自动构建本体，最后看本体如何让 LLM 更可靠。

## 上传 PDF

将你修改过的三篇 PDF 放入 `papers/` 目录，文件名对应：

- `Neuhaus-2018-What-is-an-Ontology.pdf`
- `Giglou-2023-LLMs4OL.pdf`
- `Sharma-2024-OG-RAG.pdf`

页面中的"本仓库 PDF（修改版）"链接会自动生效。

## 部署为 GitHub Pages

```bash
# 1. 在 GitHub 上创建新仓库（如 ontology-references）
# 2. 初始化并推送
git init
git add .
git commit -m "Ontology references reading guide: 3 core papers across 7 stages"
git branch -M main
git remote add origin https://github.com/<your-username>/ontology-references.git
git push -u origin main
# 3. 仓库 Settings → Pages → Source 选 main 分支 → Save
# 几分钟后访问 https://<your-username>.github.io/ontology-references/
```

## 技术说明

- 纯 HTML/CSS/JS，零外部依赖
- 响应式设计，支持移动端
- Sticky 导航栏
- 浅色主题，适合长时间阅读
