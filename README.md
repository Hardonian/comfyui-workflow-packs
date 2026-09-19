# ComfyUI Workflow Packs

Production-ready ComfyUI workflow packs for SDXL image generation. Drag-and-drop ready — no prompt engineering skills required.

**[Buy on Gumroad →](https://scottrmhardie.gumroad.com)**

## Packs

### [SDXL Workflow Pack — $19](https://scottrmhardie.gumroad.com/l/ggtuzd)
5 complete workflows: general, portrait, product photo, landscape, abstract art.

### [Product Photo Kit — $29](https://scottrmhardie.gumroad.com/l/wkhie)
5 category workflows: electronics, food, fashion, cosmetics, jewelry.

### [Portrait Studio — $29](https://scottrmhardie.gumroad.com/l/xttsl)
5 portrait workflows: headshot, fashion, lifestyle, artistic, beauty.

### [Thumbnail Creator Kit — $29](https://scottrmhardie.gumroad.com/l/hkpdn)
5 platform workflows: YouTube (1280×720), podcast (1024²), social (1080²), blog (1200×630), e-commerce (1200×628).

## Requirements
- ComfyUI + any SDXL checkpoint + GPU with ≥8GB VRAM
- Works on NVIDIA, AMD (ROCm), Apple Silicon

## Quick Start
1. Download from [Gumroad](https://scottrmhardie.gumroad.com)
2. Open ComfyUI → drag `.json` into canvas
3. Edit prompt (node "6") → Queue Prompt

## Quality Settings
All workflows use production-grade settings:
- Sampler: `dpmpp_2m_sde` (best quality/speed balance)
- Scheduler: `karras` (smoother noise schedule)
- Steps: 28-35 (quality-optimized per workflow type)
- Comprehensive negative prompts (handles common artifacts)

## Related
- [ComfyUI API](https://github.com/Hardonian/comfyui-api) — programmatic workflow execution
- [AI Automated Systems](https://aiautomatedsystems.ca) — storefront

## License
Personal and commercial use. No attribution required.
