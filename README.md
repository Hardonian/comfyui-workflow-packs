# ComfyUI Workflow Packs

Production-ready ComfyUI workflow packs for SDXL image generation. Drag-and-drop ready — no prompt engineering skills required.

**[Buy on Gumroad →](https://scottrmhardie.gumroad.com)**

## Packs

### [SDXL Workflow Pack — $19](https://scottrmhardie.gumroad.com/l/vkdjdd)

5 complete workflows for any subject:

| Workflow | Use Case |
|----------|----------|
| General Purpose | Versatile, any subject |
| Portrait | People, fashion, headshots |
| Product Photo | E-commerce, white background |
| Landscape | Nature, cityscapes, golden hour |
| Abstract Art | Creative, geometric, modern art |

**Includes:** 5 workflow JSONs + 5 prompt presets + 5 sample images

📂 [`sdxl-workflow-pack/`](./sdxl-workflow-pack/)

---

### [Product Photo Kit — $29](https://scottrmhardie.gumroad.com/l/wkhie)

5 category-specific workflows for e-commerce:

| Category | Best For |
|----------|----------|
| Electronics | Headphones, phones, gadgets |
| Food & Beverage | Dishes, drinks, restaurants |
| Fashion | Clothing, shoes, bags |
| Cosmetics | Perfume, skincare, makeup |
| Jewelry | Rings, necklaces, watches |

**Includes:** 5 workflow JSONs + 5 prompt presets + 5 sample images

📂 [`product-photo-kit/`](./product-photo-kit/)

---

## Requirements

- **ComfyUI** installed and running
- **SDXL checkpoint** (sd_xl_base_1.0.safetensors or compatible)
- **GPU with ≥8 GB VRAM** (12 GB+ recommended)
- Works on NVIDIA, AMD (ROCm), Apple Silicon

## Quick Start

1. Download a pack from [Gumroad](https://scottrmhardie.gumroad.com)
2. Open ComfyUI
3. Drag any `.json` workflow file into the canvas
4. Edit the prompt (node "6") to describe your subject
5. Click **Queue Prompt** → get a professional image in seconds

## Customization

- **Change subject:** Edit the positive prompt in node "6"
- **Adjust quality:** Modify `steps` (15-40) and `cfg` (5-10) in node "3"
- **Change resolution:** Edit `width`/`height` in node "5"
- **Use different checkpoint:** Change `ckpt_name` in node "4"

## ComfyUI API

These workflows are in ComfyUI API format. For programmatic execution, see [`Hardonian/comfyui-api`](https://github.com/Hardonian/comfyui-api).

## License

Personal and commercial use. Modify, redistribute, and use outputs commercially. No attribution required.

---

**[Buy on Gumroad →](https://scottrmhardie.gumroad.com)** · **[ComfyUI API →](https://github.com/Hardonian/comfyui-api)** · **[AI Automated Systems →](https://aiautomatedsystems.ca)**