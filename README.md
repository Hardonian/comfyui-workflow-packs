# ComfyUI Workflow Packs — Production-Ready SDXL Workflows for Product Photography, Portraits & More

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![ComfyUI](https://img.shields.io/badge/ComfyUI-Compatible-orange.svg)](https://github.com/comfyanonymous/ComfyUI)
[![SDXL](https://img.shields.io/badge/SDXL-1.0-blue.svg)](https://stability.ai/stable-diffusion)
[![Gumroad](https://img.shields.io/badge/Buy-Gumroad-pink.svg)](https://scottrmhardie.gumroad.com)
[![GitHub Stars](https://img.shields.io/github/stars/Hardonian/comfyui-workflow-packs?style=social)](https://github.com/Hardonian/comfyui-workflow-packs)

> **Drag-and-drop ComfyUI workflows for SDXL image generation.** Product photography, portraits, thumbnails, fashion lookbooks, and more — production-tested with optimized quality settings. No prompt engineering skills required.

**[Buy on Gumroad →](https://scottrmhardie.gumroad.com)** · **[AI Automated Systems](https://aiautomatedsystems.ca)**

---

## 🎯 What You Get

Professional ComfyUI workflow JSON files for **Stable Diffusion SDXL** — optimized for:

- **E-commerce product photography** — clean backgrounds, consistent lighting, multiple angles
- **Portrait photography** — headshots, fashion, lifestyle, beauty retouching
- **YouTube & social media thumbnails** — platform-specific dimensions baked in
- **Fashion lookbooks** — editorial-quality AI-generated fashion imagery
- **Landscape & abstract art** — creative generation with style control
- **Upscaling & enhancement** — 4x upscale pipelines with artifact removal

---

## 📦 Workflow Packs

### [SDXL Workflow Pack — $19](https://scottrmhardie.gumroad.com/l/ggtuzd)
5 complete workflows: general, portrait, product photo, landscape, abstract art.

### [Product Photo Kit — $29](https://scottrmhardie.gumroad.com/l/wkhie)
5 category workflows: electronics, food, fashion, cosmetics, jewelry. **Perfect for e-commerce stores.**

### [Portrait Studio — $29](https://scottrmhardie.gumroad.com/l/xttsl)
5 portrait workflows: headshot, fashion, lifestyle, artistic, beauty.

### [Thumbnail Creator Kit — $29](https://scottrmhardie.gumroad.com/l/hkpdn)
5 platform workflows: YouTube (1280×720), podcast (1024²), social (1080²), blog (1200×630), e-commerce (1200×628).

### Controlnet Essentials Pack
Advanced controlnet workflows for precise image composition and style transfer.

### Fashion Lookbook Pack
Editorial-style fashion AI workflows for lookbooks and catalog generation.

### Inpainting Pack
Professional inpainting and outpainting workflows for image editing.

### Img2Img Style Transfer Pack
Style transfer and img2img workflows for creative image transformation.

### Upscale & Enhance Pack
4x upscaling with artifact removal and detail enhancement pipelines.

---

## 🚀 Quick Start

1. **[Download from Gumroad](https://scottrmhardie.gumroad.com)**
2. Open ComfyUI → drag `.json` into canvas
3. Edit prompt (node "6") → Queue Prompt

**[→ Full Getting Started Guide](docs/getting-started.md)**

---

## 📸 Screenshots

<!-- Add workflow preview images here -->
| Product Photography | Portrait Studio | Thumbnails |
|---|---|---|
| ![Product](product-photo-kit/previews/) | ![Portrait](portrait-studio/previews/) | ![Thumbnails](thumbnail-kit/previews/) |

---

## ⚙️ Requirements

- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) (latest version)
- Any **SDXL checkpoint** (Stable Diffusion XL 1.0)
- GPU with **≥8 GB VRAM** (NVIDIA recommended)
- Works on **NVIDIA**, **AMD (ROCm)**, and **Apple Silicon**

---

## 🎛️ Quality Settings

All workflows use production-grade defaults:

| Setting | Value | Why |
|---------|-------|-----|
| Sampler | `dpmpp_2m_sde` | Best quality/speed balance |
| Scheduler | `karras` | Smoother noise schedule |
| Steps | 28–35 | Optimized per workflow type |
| Negative prompts | Comprehensive | Handles common artifacts |

---

## ❓ FAQ

**Q: Do I need prompt engineering skills?**
A: No. Each workflow has a pre-configured prompt node — just edit the text and queue.

**Q: Can I use these for commercial projects?**
A: Yes. Personal and commercial use allowed. No attribution required.

**Q: What SDXL checkpoints work best?**
A: Any SDXL 1.0 checkpoint. We recommend Juggernaut XL, RealVisXL, or DreamShaper XL for photography.

**Q: Do I need ControlNet models?**
A: Only for the Controlnet Essentials Pack. Other packs work with just a base SDXL checkpoint.

**Q: Can I modify the workflows?**
A: Absolutely. The JSON files are fully editable in ComfyUI's visual editor.

**[→ Full FAQ](docs/faq.md)**

---

## 🛠️ Troubleshooting

Having issues? Check our **[Troubleshooting Guide](docs/troubleshooting.md)** for solutions to common problems.

---

## 🔗 Related Projects

- [AI Ops Toolkit](https://github.com/Hardonian/ai-ops-toolkit) — CLI tools for GPU monitoring, Ollama management, service health
- [AI Prompt Templates](https://github.com/Hardonian/ai-prompt-templates) — 200+ tested prompt templates for ChatGPT, Claude, Gemini
- [AI Automated Systems](https://aiautomatedsystems.ca) — Full product catalog

---

## 💬 Support

- **Documentation:** [docs/](docs/)
- **Issues:** [GitHub Issues](https://github.com/Hardonian/comfyui-workflow-packs/issues)
- **Products:** [Gumroad Store](https://scottrmhardie.gumroad.com)
- **Website:** [aiautomatedsystems.ca](https://aiautomatedsystems.ca)

---

## 📚 Guides & Tutorials

Learn how to get the most from these workflows:

- [ControlNet for Beginners](https://aiautomatedsystems.ca/blog/controlnet-tutorial-beginners-guide)
- [5 ComfyUI Workflows Every E-Commerce Seller Needs](https://aiautomatedsystems.ca/blog/2026-09-20-5-comfyui-workflows-every-ecommerce-seller-needs)
- [ComfyUI Batch Processing Automation](https://aiautomatedsystems.ca/blog/comfyui-batch-processing-automation-guide)
- [SDXL LoRA Training Guide](https://aiautomatedsystems.ca/blog/comfyui-lora-training-guide-sdxl)
- [Amazon Product Photography AI Workflow](https://aiautomatedsystems.ca/blog/amazon-product-photography-ai-workflow)

More guides at [aiautomatedsystems.ca/blog](https://aiautomatedsystems.ca)

## ❓ FAQ

**Q: Do I need a GPU?**
A: Yes. ComfyUI requires a GPU with at least 8GB VRAM (12GB+ recommended). Works with NVIDIA RTX 3060, 4060, or better.

**Q: Is this better than Midjourney for product photography?**
A: For e-commerce, yes. ComfyUI gives you full control over composition, lighting, and batch processing. Midjourney is better for creative/artistic work. See our [comparison guide](https://aiautomatedsystems.ca/blog/comfyui-vs-midjourney-product-photography-2026).

**Q: How do I batch-process 100+ product images?**
A: Each workflow includes a batch processing node. See our [batch automation guide](https://aiautomatedsystems.ca/blog/comfyui-batch-processing-automation-guide).

**Q: Can I train on my own products?**
A: Yes. LoRA training workflows let you fine-tune on your actual product photos. See the [LoRA training guide](https://aiautomatedsystems.ca/blog/comfyui-lora-training-guide-sdxl).

**Q: What SDXL checkpoints work best?**
A: We recommend Juggernaut XL for products and RealVisXL for portraits. Full list in our [best checkpoints guide](https://aiautomatedsystems.ca/blog/best-sdxl-checkpoints-product-photography-2026).

## 🏷️ Keywords

ComfyUI workflows, SDXL workflow pack, product photography AI, stable diffusion product photos, e-commerce image generation, AI portrait studio, SDXL thumbnails, ComfyUI drag and drop, AI image generation workflows, product photo AI tool, stable diffusion XL workflows, ComfyUI presets, AI fashion lookbook, SDXL ControlNet

---

## License

MIT — Personal and commercial use. No attribution required.
