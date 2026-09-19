# Getting Started with ComfyUI Workflow Packs

## Prerequisites

1. **Install ComfyUI** — [github.com/comfyanonymous/ComfyUI](https://github.com/comfyanonymous/ComfyUI)
2. **Download an SDXL checkpoint** — We recommend Juggernaut XL, RealVisXL, or DreamShaper XL
3. **GPU with ≥8 GB VRAM** — NVIDIA (CUDA), AMD (ROCm), or Apple Silicon (MPS)

## Installation

### Step 1: Download Your Workflow Pack

Purchase and download from [Gumroad](https://scottrmhardie.gumroad.com). You'll receive a `.zip` file containing workflow JSON files and preset configurations.

### Step 2: Extract the Files

```bash
unzip comfyui-workflow-pack.zip -d ~/ComfyUI/user/workflows/
```

Or extract to any convenient location — ComfyUI can load JSON files from anywhere.

### Step 3: Load a Workflow

1. Open ComfyUI in your browser (default: `http://127.0.0.1:8188`)
2. Drag and drop a `.json` workflow file onto the canvas
3. The workflow graph will appear with all nodes connected

### Step 4: Configure

1. **Load your checkpoint** — Click the checkpoint loader node and select your SDXL model
2. **Edit the prompt** — Find the text node (usually node "6") and enter your prompt
3. **Adjust settings** — The default settings are optimized, but you can tweak steps, CFG, and sampler

### Step 5: Generate

Click **"Queue Prompt"** to start generation. First run may take longer as models load into VRAM.

## Tips for Best Results

- **Use the negative prompts** — Each workflow includes carefully crafted negative prompts. Don't remove them.
- **Keep quality settings** — The sampler, scheduler, and step counts are tuned per workflow type.
- **Start with defaults** — Get familiar with the workflow before customizing advanced settings.
- **Check VRAM usage** — If you get OOM errors, try reducing resolution or batch size.

## Next Steps

- Read the [Troubleshooting Guide](troubleshooting.md) if you run into issues
- Check the [FAQ](faq.md) for common questions
- Visit [Gumroad](https://scottrmhardie.gumroad.com) for more workflow packs
