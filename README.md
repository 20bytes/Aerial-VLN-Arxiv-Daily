<p align="center">
  <h1 align="center">🚁 Awesome-Aerial-VLN-Arxiv-Daily</h1>
  <p align="center">
    <img src="https://img.shields.io/badge/Navigation-Aerial_VLN-blue?style=for-the-badge&logo=dji" alt="Aerial VLN">
    <img src="https://img.shields.io/badge/3DGS-Simulation-green?style=for-the-badge&logo=unity" alt="3DGS">
    <img src="https://img.shields.io/badge/Embodied-AI-orange?style=for-the-badge&logo=robotframework" alt="Embodied AI">
  </p>
  <p align="center">
    <img src="https://img.shields.io/github/stars/20bytes/Awesome-Aerial-VLN-Arxiv-Daily?style=for-the-badge" alt="Stars">
    <img src="https://img.shields.io/github/forks/20bytes/Awesome-Aerial-VLN-Arxiv-Daily?style=for-the-badge" alt="Forks">
    <img src="https://img.shields.io/github/issues/20bytes/Awesome-Aerial-VLN-Arxiv-Daily?style=for-the-badge" alt="Issues">
  </p>
</p>

> 🚀 每日自动追踪 **无人机视觉语言导航 (Aerial-VLN)**、**3DGS场景重建与仿真** 和 **具身智能基础模型** 的最新 Arxiv 论文。

---

## 📌 研究方向 (Research Directions)

| 方向 | 核心关键词 |
|------|-----------|
| 🚁 **无人机视觉语言导航** | Aerial VLN, UAV Navigation, CityNav, AerialVLN, Drone Navigation |
| 🌐 **3DGS场景重建与仿真** | 3D Gaussian Splatting, Aerial 3D Reconstruction, Real-to-Sim, UAV SLAM |
| 🤖 **具身智能基础模型与数据** | VLA Model, Embodied AI, World Model, Sim-to-Real, Navigation Benchmark |

---

## 📖 使用方法 (Usage)

### 1. 配置环境

```bash
pip install -r requirements.txt
```

### 2. 配置参数

编辑 `config.yaml`，修改以下字段：

```yaml
user_name: "your_github_username"
repo_name: "Awesome-Aerial-VLN-Arxiv-Daily"
```

如需论文自动翻译（中文），设置 DeepSeek API Key：

```bash
export DEEPSEEK_API_KEY="your_api_key_here"
```

### 3. 手动运行

```bash
python daily_arxiv.py
```

### 4. 自动运行（GitHub Actions）

Fork 本仓库后，在 GitHub 仓库设置中：

- **Settings → Actions → Workflow permissions** → 选择 `Read and write permissions`
- **Actions** → 启用 `Run Arxiv Papers Daily` workflow → 点击 `Run workflow`

---

## ⚙️ 配置说明 (Configuration)

| 配置项 | 说明 |
|--------|------|
| `max_results` | 每次每个方向抓取的最大论文数量 |
| `translate_title` | 是否开启 DeepSeek 标题中文翻译 |
| `translate_abstract` | 是否开启摘要中文翻译 |
| `publish_gitpage` | 是否生成 GitHub Pages 网页版 |

---

## 📄 许可证 (License)

本项目基于 [MIT License](LICENSE)。

---

[contributors-shield]: https://img.shields.io/github/contributors/20bytes/Awesome-Aerial-VLN-Arxiv-Daily.svg?style=for-the-badge
[contributors-url]: https://github.com/20bytes/Awesome-Aerial-VLN-Arxiv-Daily/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/20bytes/Awesome-Aerial-VLN-Arxiv-Daily.svg?style=for-the-badge
[forks-url]: https://github.com/20bytes/Awesome-Aerial-VLN-Arxiv-Daily/network/members
[stars-shield]: https://img.shields.io/github/stars/20bytes/Awesome-Aerial-VLN-Arxiv-Daily.svg?style=for-the-badge
[stars-url]: https://github.com/20bytes/Awesome-Aerial-VLN-Arxiv-Daily/stargazers
[issues-shield]: https://img.shields.io/github/issues/20bytes/Awesome-Aerial-VLN-Arxiv-Daily.svg?style=for-the-badge
[issues-url]: https://github.com/20bytes/Awesome-Aerial-VLN-Arxiv-Daily/issues
