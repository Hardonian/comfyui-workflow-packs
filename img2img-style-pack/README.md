# ComfyUI Img2Img Style Pack

**5 img2img workflows for style transfer, background replacement, enhancement, and artistic transformation.**

Drop in any photo, get a transformed result. Works with any SDXL checkpoint.

## Workflows

| Workflow | Denoise | Best For |
|----------|---------|----------|
| **Style Transfer** | 0.65 | Transform photos into oil painting, watercolor, etc. |
| **Background Replace** | 0.55 | Swap backgrounds (white studio, outdoor, etc.) |
| **Enhance** | 0.35 | Subtle quality improvement (sharpen, color, lighting) |
| **Season Change** | 0.50 | Transform seasons (summer→autumn, day→night) |
| **Artistic Style** | 0.60 | Apply artistic aesthetics (cyberpunk, vintage, etc.) |

## How It Works

These are img2img workflows — they take your input photo and transform it based on the prompt and denoise strength:

- **Low denoise (0.30-0.40):** Subtle changes, keeps original composition
- **Medium denoise (0.45-0.55):** Moderate transformation, keeps structure
- **High denoise (0.60-0.70):** Strong style change, may alter details

## Quick Start

1. Download and extract
2. Open ComfyUI → drag any `.json` workflow into canvas
3. Click the "Load Image" node → upload your photo
4. Edit the prompt (node "6") to describe desired output
5. Adjust denoise in KSampler (node "3") — lower = more subtle
6. Click Queue Prompt

## Tips

- Start with denoise 0.50 and adjust up/down based on results
- For background replacement: describe the NEW background in the prompt
- For style transfer: describe the TARGET style, not the input
- For enhancement: keep denoise low (0.30-0.40) and use enhancement-focused prompts
- Seed 0 = random. Set a specific seed to reproduce results.

## Requirements

- ComfyUI + any SDXL checkpoint + GPU with ≥8GB VRAM
- An input image (your photo)

## License

Personal and commercial use. No attribution required.
