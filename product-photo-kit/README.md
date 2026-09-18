# ComfyUI Product Photo Kit

**5 specialized product photography workflows for e-commerce — drag, load, generate professional product shots.**

Battle-tested on real GPU hardware (RTX 3060, SDXL). No subscriptions, no cloud dependency.

## What's Included

### 5 Category-Specific Workflows

| Category | File | Best For |
|----------|------|----------|
| **Electronics** | `product-electronics.json` | Headphones, phones, gadgets, tech accessories |
| **Food & Beverage** | `product-food.json` | Dishes, drinks, packaged food, restaurants |
| **Fashion** | `product-fashion.json` | Clothing, shoes, bags, accessories |
| **Cosmetics & Beauty** | `product-cosmetics.json` | Perfume, skincare, makeup, beauty tools |
| **Jewelry & Luxury** | `product-jewelry.json` | Rings, necklaces, watches, luxury items |

### 5 Curated Prompt Presets

Each preset is tuned for its category — optimized positive/negative prompts, resolution, and sampling settings. Works with any SDXL checkpoint.

### 5 Sample Output Images

Generated on real hardware so you can see exactly what to expect before buying.

## Why This Kit?

- **Save hours of prompt tuning** — each preset is tested across multiple seeds for consistent quality
- **White background ready** — optimized for clean e-commerce listings
- **Category-specific negatives** — trained to avoid common artifacts per product type
- **1024×1024 output** — ready for Amazon, Shopify, Etsy, eBay listings
- **No AI skills needed** — drag, load, change the subject, generate

## System Requirements

- **ComfyUI** installed and running
- **SDXL checkpoint** (sd_xl_base_1.0.safetensors or compatible)
- **GPU with ≥8 GB VRAM**
- Works on NVIDIA, AMD (ROCm), Apple Silicon

## Quick Start

1. Download and extract this kit
2. Open ComfyUI → drag any `.json` workflow into the canvas
3. Edit the positive prompt (node "6") to describe your product
4. Click Queue Prompt → get a professional product photo

## Customization Tips

- **Change product**: Edit the positive prompt in node "6" — keep the style keywords, swap the product description
- **Adjust lighting**: Add "dramatic side lighting" or "bright flat lighting" to the prompt
- **Change background**: Replace "white background" with "gradient background", "lifestyle setting", etc.
- **Batch generate**: Use seed -1 for random variations, or set a fixed seed for consistent results
- **Upscale for print**: Run the output through an ESRGAN upscaler for 4× resolution

## File Structure

```
comfyui-product-photo-kit/
├── workflows/
│   ├── product-electronics.json
│   ├── product-food.json
│   ├── product-fashion.json
│   ├── product-cosmetics.json
│   └── product-jewelry.json
├── presets/
│   ├── electronics.json
│   ├── food.json
│   ├── fashion.json
│   ├── cosmetics.json
│   └── jewelry.json
├── previews/
│   ├── product_electronics.png
│   ├── product_food.png
│   ├── product_fashion.png
│   ├── product_cosmetics.png
│   └── product_jewelry.png
├── docs/
│   └── SUPPORT.md
└── README.md
```

## License

Personal and commercial use. Modify, redistribute, and use outputs commercially. No attribution required.
