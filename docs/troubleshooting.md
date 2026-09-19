# Troubleshooting — ComfyUI Workflow Packs

## Common Issues

### "CUDA out of memory" Error

**Cause:** Your GPU doesn't have enough VRAM for the current settings.

**Fix:**
- Reduce image resolution (e.g., 1024×1024 → 768×768)
- Close other GPU-intensive applications
- Use `--lowvram` flag when launching ComfyUI
- Try a smaller checkpoint (fp16 instead of fp32)

### Workflow Loads But Nothing Happens

**Cause:** Missing checkpoint or custom nodes.

**Fix:**
1. Ensure your SDXL checkpoint is in `ComfyUI/models/checkpoints/`
2. Check the ComfyUI console for error messages
3. Some workflows require ControlNet models — see the pack's README

### Images Look Distorted or Artistic When They Shouldn't Be

**Cause:** Wrong checkpoint or modified quality settings.

**Fix:**
- Use an SDXL 1.0 checkpoint (not SD 1.5)
- Reset sampler to `dpmpp_2m_sde` and scheduler to `karras`
- Keep the provided negative prompt intact

### Prompt Text Not Affecting Output

**Cause:** You may be editing the wrong text node.

**Fix:**
- Look for the node labeled with the prompt text
- In most workflows, it's node "6" or the main CLIP text encoder
- Make sure you're connected to the positive prompt, not negative

### ControlNet Not Working

**Cause:** Missing ControlNet model or preprocessor.

**Fix:**
1. Download the required ControlNet model (check pack README)
2. Place it in `ComfyUI/models/controlnet/`
3. Install the ControlNet custom node if not already present

### Slow Generation Speed

**Possible causes:**
- Using CPU instead of GPU — check `nvidia-smi` during generation
- High step count — reduce from 35 to 20 for faster drafts
- Large resolution — start with 768×768 for testing
- Background processes consuming GPU — close other apps

## Still Stuck?

- Check the [FAQ](faq.md)
- Open a [GitHub Issue](https://github.com/Hardonian/comfyui-workflow-packs/issues)
- Visit [aiautomatedsystems.ca](https://aiautomatedsystems.ca) for support
