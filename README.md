# HTML-anime: Specialized Web & 2D Anime AI Architecture Registry

Welcome to the **HTML-anime** open-source AI registry.

> [!IMPORTANT]
> **Zero Local Storage Footprint Guarantee**: This repository contains **specifications, model cards, architectural parameters, Hugging Face endpoints, and deployment configs only**.
> **No heavy binary model weights (.safetensors, .bin, .gguf) are stored locally or committed to GitHub.**

---

## 📂 Categories & Parameter Tiers

| Category | Primary Focus | Key Models |
|---|---|---|
| [**01-HTML-And-Web-Generation**](./01-HTML-And-Web-Generation/README.md) | Wireframe-to-HTML, UI screenshot-to-code, Tailwind CSS, DOM parsers | Design2Code, LayoutLMv3, Qwen2.5-Coder, DeepSeek-Coder-V2 |
| [**02-Anime-And-Manga-AI**](./02-Anime-And-Manga-AI/README.md) | 2D Anime art, Manga OCR, Danbooru tagging, character consistency | Animagine XL 3.1, Pony Diffusion V6 XL, MangaOCR, WD14 Tagger |
| [**03-Video-And-Anime-Motion**](./03-Video-And-Anime-Motion/README.md) | 2D Anime motion, animated GIFs, LivePortrait character puppetry | AnimateDiff, LivePortrait, CogVideoX, HunyuanVideo |

---

## 📈 Parameter Tiers
- `1_Sub-1B`: Under 1B (MangaOCR, WD14 tagger, LayoutLMv3)
- `2_1B-7B`: 1B - 7B (Animagine XL 3.1, Pony V6 XL, Design2Code, Qwen-Coder-7B, AnimateDiff)
- `3_7B-30B`: 7B - 30B (Qwen2.5-Coder-32B, Illustrious-XL, HunyuanVideo)
- `4_MoE-Trillion+`: DeepSeek-Coder-V2 (236B MoE)
