# ComfyUI SDXL Workflow Pack

**10 ready-to-load ComfyUI workflows + curated prompt presets, battle-tested on real GPU hardware.**

Drag into ComfyUI, load, generate. Works with any SDXL checkpoint. No API keys, no subscriptions, no cloud dependency.

## What's Included

### 5 Complete Workflow JSONs (API Format)

| Workflow | File | Best For |
|----------|------|----------|
| **General Purpose** | `sdxl-general.json` | Versatile, any subject |
| **Portrait** | `sdxl-portrait.json` | People, fashion, headshots |
| **Product Photo** | `sdxl-product.json` | E-commerce, catalog, white background |
| **Landscape** | `sdxl-landscape.json` | Nature, cityscapes, golden hour |
| **Abstract Art** | `sdxl-abstract.json` | Creative, geometric, modern art |

### 5 Prompt Presets (JSON)

Each preset contains optimized positive/negative prompts, resolution, steps, and CFG values. Load them into any workflow for instant quality.

### 5 Sample Output Images

Generated on real hardware (RTX 3060, SDXL Base 1.0) so you can see exactly what to expect.

## System Requirements

- **ComfyUI** installed and running (any version)
- **SDXL checkpoint** — `sd_xl_base_1.0.safetensors` or any compatible SDXL model
- **GPU with ≥8 GB VRAM** (12 GB+ recommended)
- Works on NVIDIA, AMD (ROCm), and Apple Silicon

## Quick Start (3 Steps)

1. **Download** this pack and extract it
2. **Open ComfyUI** → drag any `.json` file into the canvas
3. **Click Queue Prompt** — generates a 1024×1024 image

## Customization

- **Change the subject**: Edit the positive prompt in node "6" (Positive Prompt)
- **Adjust quality**: Modify `steps` (15-40) and `cfg` (5-10) in node "3" (KSampler)
- **Change resolution**: Edit `width`/`height` in node "5" (Empty Latent)
- **Use a different checkpoint**: Change `ckpt_name` in node "4" (Load Checkpoint)

## Tips

- **Seed -1** = random seed every run. Set a specific number to reproduce results.
- **Steps 20-30** is the sweet spot for SDXL quality/speed balance.
- **CFG 7-8** gives the best prompt adherence without artifacts.
- **Portrait workflow** works great with LoRA models for specific faces/styles.
- **Product workflow** is optimized for clean white backgrounds — perfect for e-commerce.

## File Structure

```
comfyui-sdxl-workflow-pack/
├── workflows/
│   ├── sdxl-general.json
│   ├── sdxl-portrait.json
│   ├── sdxl-product.json
│   ├── sdxl-landscape.json
│   └── sdxl-abstract.json
├── presets/
│   ├── general.json
│   ├── portrait.json
│   ├── product.json
│   ├── landscape.json
│   └── abstract.json
├── previews/
│   ├── sdxl_general.png
│   ├── sdxl_portrait.png
│   ├── sdxl_product.png
│   ├── sdxl_landscape.png
│   └── sdxl_abstract.png
├── docs/
│   └── SUPPORT.md
└── README.md
```

## License

These workflows are provided as-is for personal and commercial use. You may modify, redistribute, and use outputs commercially. No attribution required.

---

**Questions?** See `docs/SUPPORT.md` for troubleshooting.
