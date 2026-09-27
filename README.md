# Gemma in Ollama (Colab)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/158h5wXQtqDvW9yDCyTZ9uVdWXjJIt-A1?usp=sharing)

[🇺🇸 **Switch to English**](#english)

---

<a id="chinese"></a>
### 🇨🇳 项目简介
本项目提供在 Google Colab 中一键部署 **Gemma 4 (12B)** 模型的完整指南。通过 Ollama 框架，您可以轻松体验流畅的文本对话与多模态图像理解，并利用 Gradio 构建美观的交互式 WebUI。此外，项目预置了基于 LlamaIndex 和 ChromaDB 的 RAG（检索增强生成）环境，助您快速搭建本地 AI 知识库与文档问答应用。

---

<a id="english"></a>
### 🇺🇸 Introduction
[🇨🇳 **返回中文**](#chinese)

This project provides a complete guide to deploying the **Gemma 4 (12B)** model in Google Colab with one click. Powered by Ollama, you can easily experience fluent text chat and multimodal image understanding, and build a sleek interactive WebUI with Gradio. Additionally, it includes a ready-to-use RAG (Retrieval-Augmented Generation) setup using LlamaIndex and ChromaDB, helping you quickly build a localized AI knowledge base and document Q&A application.

---

###  核心特性 / Features
- ⚡ **一键部署**：自动化安装 Ollama 及所需系统依赖。
- 🧠 **Gemma 4 (12B)**：支持高性能本地大语言模型推理。
- 🖼️ **多模态支持**：支持图像输入与视觉内容描述。
- 💬 **Gradio WebUI**：提供带温度调节、历史记录导出 (TXT) 的友好聊天界面。
- 📚 **RAG 就绪**：内置 LlamaIndex + ChromaDB + `nomic-embed-text`，轻松实现本地文档检索增强生成。

###  使用方法 / Usage
1. 点击上方的 **"Open In Colab"** 徽章打开笔记本。
2. 在 Colab 环境中，按顺序从上到下执行各个代码单元格 (Cells)。
3. 等待运行完成，点击 Gradio 输出的公共 URL (Public URL) 即可开始与模型对话。
