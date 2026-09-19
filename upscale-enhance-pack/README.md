# ComfyUI Upscale & Enhance Pack

**5 upscale + refine workflows — photo enhance, product sharpen, portrait retouch, landscape HDR, old photo restore.**

Uses RealESRGAN 4× upscaler + SDXL refinement pass for professional-quality enhancement.

## Workflows

| Workflow | Best For |
|----------|----------|
| **Photo Enhance** | General photography — details, colors, lighting |
| **Product Sharpen** | E-commerce product photos — sharp edges, texture |
| **Portrait Retouch** | Beauty portraits — natural skin, enhanced eyes |
| **Landscape HDR** | Nature/city photos — HDR detail, vibrant colors |
| **Old Photo Restore** | Damaged/faded photos — clarity, color, repair |

## How It Works

Each workflow runs a 2-stage pipeline:
1. **Upscale** — RealESRGAN 4× resolution increase
2. **Refine** — SDXL low-denoise pass (0.25) to add natural detail

This produces better results than upscaling alone — the refinement pass adds realistic detail that pure upscaling misses.

## Quick Start

1. Download and extract
2. Install RealESRGAN upscaler: download `RealESRGAN_x4plus.pth` to ComfyUI models/upscale_models/
3. Open ComfyUI → drag any `.json` workflow into canvas
4. Click "Load Image" node → upload your photo
5. Edit the prompt (node "6") to describe desired enhancement
6. Click Queue Prompt

## Requirements

- ComfyUI + any SDXL checkpoint + GPU with ≥8GB VRAM
- RealESRGAN_x4plus.pth upscaler model
- An input image

## License

Personal and commercial use. No attribution required.
