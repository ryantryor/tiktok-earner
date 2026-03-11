<div align="center">
  <h1>TikEarner</h1>
  <p>An intelligent TikTok carousel generator powered by AI. Transform text into engaging visual stories.</p>
  <p>一款由 AI 驱动的智能 TikTok / 抖音 图文生成器。将简单的文本转化为引人入胜的视觉故事。</p>
  
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
</div>

---

## 📖 English / 英文版

**TikEarner** is a powerful application designed to streamline the creation of carousel posts for platforms like TikTok and Instagram. It leverages Large Language Models (LLMs) to automatically generate outlines and image generation APIs to produce the corresponding visuals.

### 🌟 Features
*   **AI-Powered Outline Generation:** Intelligently splits topics into logical pages (Cover, Content, Summary).
*   **Automated Image Creation:** Seamlessly integrates with various image generation APIs (Google GenAI, OpenAI compatible) to produce high-quality images.
*   **Bilingual Interface:** Fully translated English user interface with dark mode support.
*   **Visual Storyboarding:** An intuitive drag-and-drop outline editor to refine the narrative structure.
*   **History Management:** A comprehensive gallery to view, edit, and manage all your past creations.
*   **Parallel Generation:** High concurrency mode to speed up the image creation process.

### 🚀 Getting Started

#### Prerequisites
*   Node.js (v18+)
*   pnpm (v8+)
*   Python (v3.10+)
*   uv (Python package installer)

#### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/ryantryor/tiktok-earner.git
    cd tiktok-earner
    ```

2.  **Frontend Setup:**
    ```bash
    cd frontend
    pnpm install
    pnpm dev
    ```

3.  **Backend Setup:**
    ```bash
    # (In another terminal, from the project root)
    uv sync
    python -m backend.app
    ```

4.  **Configuration:**
    *   Open `http://localhost:5173` in your browser.
    *   Navigate to **Settings** to configure your API providers and keys for Text Generation (e.g., Google Gemini) and Image Generation.

### 🛠️ Tech Stack
*   **Frontend:** Vue 3, TypeScript, Vite
*   **Backend:** Python, Flask
*   **AI Integrations:** Google GenAI, OpenAI API compatible services

---

## 📖 Chinese / 中文版

**TikEarner** 是一款强大的应用程序，旨在简化 TikTok、抖音和 Instagram 等平台的图文轮播帖子的创建过程。它利用大语言模型 (LLMs) 自动生成大纲，并结合图片生成 API 来制作相应的视觉内容。

### 🌟 核心功能
*   **AI 智能大纲生成:** 智能地将主题拆分为逻辑页面（封面、内容、总结）。
*   **自动化图片创作:** 无缝集成各种图片生成 API (Google GenAI，OpenAI 兼容接口) 以生成高质量图片。
*   **全英文界面:** 提供完全翻译的英文用户界面，并支持深色模式。
*   **可视化分镜编辑:** 直观的拖拽式大纲编辑器，用于完善叙事结构。
*   **历史记录管理:** 综合画廊，用于查看、编辑和管理您所有过去的作品。
*   **并发生成:** 支持高并发模式，加快图片创建过程。

### 🚀 快速开始

#### 环境要求
*   Node.js (v18+)
*   pnpm (v8+)
*   Python (v3.10+)
*   uv (Python 包管理器)

#### 安装步骤

1.  **克隆仓库:**
    ```bash
    git clone https://github.com/ryantryor/tiktok-earner.git
    cd tiktok-earner
    ```

2.  **前端设置:**
    ```bash
    cd frontend
    pnpm install
    pnpm dev
    ```

3.  **后端设置:**
    ```bash
    # (在另一个终端中，从项目根目录运行)
    uv sync
    python -m backend.app
    ```

4.  **配置 API:**
    *   在浏览器中打开 `http://localhost:5173`。
    *   导航至 **Settings（设置）** 页面，配置用于文本生成和图片生成的 API 服务商及密钥。

### 🛠️ 技术栈
*   **前端:** Vue 3, TypeScript, Vite
*   **后端:** Python, Flask
*   **AI 接口集成:** Google GenAI, OpenAI 兼容服务

---

<div align="center">
  <p>Made with ❤️ by Ryan</p>
</div>
