# ComfyUI ControlNet Essentials Pack

**5 ControlNet workflows for guided SDXL generation — canny edge, depth map, pose, lineart, scribble.**

ControlNet lets you control composition with a reference image. Drop in a sketch, edge map, or pose guide — SDXL generates a polished result that follows your structure.

## Workflows

| Workflow | Control Method | Best For |
|----------|---------------|----------|
| **Canny Edge** | Edge detection map | Product photos from sketches, architecture |
| **Depth Map** | Depth information | Interior design, 3D-aware generation |
| **Pose Guide** | Human pose skeleton | Fashion, character poses, action shots |
| **Lineart** | Clean line drawing | Illustration colorization, concept art |
| **Scribble** | Rough sketch | Quick concept exploration, creative iteration |

## How It Works

1. **Load your control image** — sketch, photo, or pose reference
2. **Write a prompt** describing the desired output
3. **ControlNet guides generation** — SDXL follows your structure while adding detail

## Quick Start

1. Download and extract
2. Download ControlNet models for SDXL to ComfyUI/models/controlnet/
3. Open ComfyUI → drag any `.json` workflow into canvas
4. Click "Load Control Image" node → upload your reference
5. Edit the prompt to describe desired output
6. Click Queue Prompt

## Recommended ControlNet Models

- controlnet-canny-sdxl.safetensors
- controlnet-depth-sdxl.safetensors
- controlnet-openpose-sdxl.safetensors
- controlnet-lineart-sdxl.safetensors
- controlnet-scribble-sdxl.safetensors

Download from: https://huggingface.co/comfyanonymous/ControlNet-v1-1_fp16_safetensors

## Requirements

- ComfyUI + SDXL checkpoint + ControlNet models + GPU ≥8GB VRAM

## License

Personal and commercial use. No attribution required.
