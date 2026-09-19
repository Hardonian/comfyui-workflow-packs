# ComfyUI Inpainting & Outpainting Pack

**5 inpainting + outpainting workflows for AI image editing — object remove, object replace, background swap, skin retouch, canvas extend.**

Paint a mask on any image. SDXL fills in what belongs there. No Photoshop skills needed.

## Workflows

| Workflow | Method | Best For |
|----------|--------|----------|
| **Object Remove** | Inpaint | Remove unwanted objects, clean backgrounds |
| **Object Replace** | Inpaint | Replace objects with AI-generated alternatives |
| **Background Swap** | Inpaint | Change product backgrounds, studio scenes |
| **Skin Retouch** | Inpaint | Natural beauty retouching, blemish removal |
| **Canvas Extend** | Outpaint | Extend image borders, create panoramas |

## How It Works

1. **Load your image** — the photo you want to edit
2. **Load a mask** — white = area to regenerate, black = keep unchanged
3. **Write a prompt** describing what should appear in the masked area
4. **SDXL generates** — fills the masked area while keeping the rest intact

## Quick Start

1. Download and extract
2. Open ComfyUI → drag any `.json` workflow into canvas
3. Click "Load Input" → upload your photo
4. Click "Load Mask" → upload a black/white mask image
5. Edit the prompt to describe what should fill the masked area
6. Click Queue Prompt

## Creating Masks

Use any image editor:
- **GIMP**: Paint white on black layer, export as PNG
- **Photoshop**: Select area, fill white on black layer
- **Online**: photpea.com, lunapic.com
- **ComfyUI**: Use built-in mask painting nodes

## Tips

- Grow mask by 6px (default) for seamless blending
- Use denoise 0.85 for inpainting (preserves context)
- For outpainting, use denoise 1.0 (full generation)
- Match your prompt to the surrounding image style

## Requirements

- ComfyUI + SDXL checkpoint + GPU ≥8GB VRAM
- An input image + black/white mask

## License

Personal and commercial use. No attribution required.
