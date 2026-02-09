# 🎬 Cinematic PromptCraft

### AI Image Generation Prompt Engineering Skill for Cinematic & Editorial Photography

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-Any%20LLM-blue.svg)](#-platform-integration-guide)
[![Cameras](https://img.shields.io/badge/Cameras-16-green.svg)](#cameras-16)
[![Lenses](https://img.shields.io/badge/Lenses-25%2B-green.svg)](#lenses-25)
[![Film Stocks](https://img.shields.io/badge/Film%20Stocks-35%2B-green.svg)](#film-stocks-35)

> Transform real-world camera, lens, and film stock specifications into optimized AI image generation prompts — with deep knowledge of bokeh, halation, bloom, grain, chromatic aberration, vignette, depth of field, color science, and tonal response.

---

## ✨ What Is This?

**Cinematic PromptCraft** is a comprehensive knowledge base / system prompt / AI skill that turns any LLM into an expert **cinematic photography prompt engineer**.

Instead of generic prompts like *"beautiful portrait with blurry background"*, it generates:

```
fashion editorial, model in flowing silk dress, shot on ARRI ALEXA 35 with 
Cooke S7/i 50mm T2.0, Cooke Look golden warm skin rendering, creamy round 
bokeh orbs in background, Kodak Portra 400 warm desaturated palette with 
fine grain, soft filmic highlight rolloff, natural optical vignette, 
golden hour backlight with halation bleeding through hair
```

This level of specificity produces dramatically better results in AI image generators like **Flux, Midjourney, DALL-E, Stable Diffusion, fal.ai Nano Banana Pro**, and others.

---

## 🎯 What's Covered

### Cameras (16)

| Category | Models |
|----------|--------|
| **Cinema** | ARRI ALEXA 35, ALEXA Mini LF, RED V-RAPTOR XL, Sony VENICE 2, Blackmagic URSA Cine 17K 65, Panavision DXL2, Canon C500 II |
| **Photo** | Leica M11, Hasselblad X2D 100C, Fujifilm GFX 100 II, Sony A1/A9 III, Nikon Z8/Z9, Canon R5 II, Leica Q3, Fujifilm X100VI |

### Lenses (25+)

| Category | Models |
|----------|--------|
| **Cinema** | Cooke S7/i, ARRI Signature, Panavision Primo 70, Zeiss Supreme, Cooke Anamorphic SF, Atlas Mercury, Canon K35 (1970s), Leitz Summicron-C, Tribe7 Blackwing7, Angénieux Optimo |
| **Photo** | Leica Noctilux f/0.95, Summilux 35mm, Hasselblad XCD 80mm, Canon RF 85mm DS, Nikon Z 50mm f/1.2, Sony 35mm GM, Voigtländer Nokton f/1.0, Zeiss Otus, Sigma Art |
| **Vintage** | Helios 44-2, Trioplan 100mm, Petzval 85mm, Canon FD 50mm f/1.2L, Lensbaby Velvet, Dallmeyer Super-Six (1920s) |

### Film Stocks (35+)

| Brand | Stocks |
|-------|--------|
| **Kodak** | Portra 160/400/800, Ektar 100, Gold 200, ColorPlus 200, Vision3 50D/200T/500T, Tri-X 400, T-Max 400, Ektachrome E100 |
| **Fujifilm** | Pro 400H, Superia 400, C200, Eterna 250/500, Eterna Vivid, Provia 100F, Velvia 50/100, Acros 100, Neopan 1600 |
| **Fuji Digital** | Classic Chrome, Classic Negative, Nostalgic Neg, Eterna, Eterna Bleach Bypass, ACROS, PRO Neg |
| **CineStill** | 800T *(signature red halation!)*, 50D |
| **Ilford** | HP5 400, Delta 3200, FP4 125, Pan F 50 |
| **Special** | Lomography, LomoChrome Purple, Redscale, Agfa Vista, Polaroid/Instax |

### For Every Entry You Get
- ✅ Technical specs (sensor, resolution, dynamic range, ISO)
- ✅ Color science and tonal character description
- ✅ Optical effects (bokeh type, halation, bloom, CA, vignette, grain)
- ✅ Ready-to-use **Prompt Keywords** (copy-paste directly)
- ✅ Complete **Prompt Examples**
- ✅ Best camera-lens pairing recommendations
- ✅ 6 **Prompt Engineering Patterns** for different scenarios
- ✅ **Quick Reference Combos** for common use cases

---

## 📦 Files

```
cinematic-promptcraft/
├── SKILL.md                              # Full skill (70KB) — Claude/Antigravity native
├── cinematic-promptcraft-universal.md    # Universal system prompt (28KB) — Any LLM
├── cinematic-promptcraft-compact.md      # Compact version (7KB) — Token-limited platforms
├── README.md                             # This file
├── LICENSE                               # MIT License
└── evals/
    └── evals.json                        # 6 test scenarios with expectations
```

### Which File Should I Use?

| Your Platform | Use This File |
|--------------|---------------|
| Claude Projects, Gemini Gems, n8n, Dify, API calls | `cinematic-promptcraft-universal.md` |
| Claude Skills / Antigravity | `SKILL.md` |
| ChatGPT Custom GPT, Ollama, small context models | `cinematic-promptcraft-compact.md` |
| RAG / Knowledge Base systems | `cinematic-promptcraft-universal.md` |

---

## 🚀 Quick Start (2 Minutes)

1. Copy the contents of **`cinematic-promptcraft-universal.md`**
2. Paste it as a **System Prompt** in your favorite AI platform
3. Ask: *"Create a fashion editorial prompt with Hasselblad X2D, XCD 80mm f/1.9, and Kodak Portra 400 look"*
4. Use the generated prompt in your AI image generator

That's it!

---

## 🔌 Platform Integration Guide

<details>
<summary><b>☁️ Claude.ai — Projects</b></summary>

1. Go to [claude.ai](https://claude.ai) → **Projects** → **Create Project**
2. Name it "Cinematic PromptCraft"
3. Click **"Set custom instructions"**
4. Paste contents of `cinematic-promptcraft-universal.md`
5. Save → Start chatting

</details>

<details>
<summary><b>🤖 ChatGPT — Custom GPT</b></summary>

1. Go to [ChatGPT](https://chat.openai.com) → **Explore GPTs** → **Create**
2. **Name**: Cinematic PromptCraft
3. **Instructions**: Paste `cinematic-promptcraft-compact.md`
4. **Conversation starters**: "Fashion editorial with Leica M11 and Portra 400", "Cinematic anamorphic sci-fi scene", "Night street with CineStill 800T red halation"
5. Publish

</details>

<details>
<summary><b>💎 Google Gemini — Gems</b></summary>

1. Go to [gemini.google.com](https://gemini.google.com) → **Gems** → **New Gem**
2. Paste `cinematic-promptcraft-universal.md` into Instructions
3. Save

</details>

<details>
<summary><b>⚡ n8n — AI Agent Workflow</b></summary>

1. Add **AI Agent** node → System Message → paste `universal.md`
2. Connect to fal.ai / Midjourney / DALL-E tool node
3. Agent writes prompt → passes to image generator

</details>

<details>
<summary><b>🐍 Python / LangChain / API</b></summary>

```python
with open("cinematic-promptcraft-universal.md") as f:
    system_prompt = f.read()

# Works with any LLM library
messages = [
    {"role": "system", "content": system_prompt},
    {"role": "user", "content": "Night portrait, Noctilux f/0.95, CineStill 800T"}
]
```

</details>

<details>
<summary><b>🦙 Ollama / Local Models</b></summary>

```bash
echo 'FROM llama3.1:70b' > Modelfile
echo 'SYSTEM """' >> Modelfile
cat cinematic-promptcraft-compact.md >> Modelfile
echo '"""' >> Modelfile
ollama create cinematic-promptcraft -f Modelfile
ollama run cinematic-promptcraft
```

</details>

<details>
<summary><b>🔧 Cursor / Windsurf</b></summary>

```bash
cp cinematic-promptcraft-compact.md .cursorrules    # Cursor
cp cinematic-promptcraft-compact.md .windsurfrules  # Windsurf
```

</details>

<details>
<summary><b>🧩 Dify / FlowiseAI / Voiceflow / Botpress</b></summary>

Upload `universal.md` as Knowledge Base document or paste into System Prompt.

</details>

---

## 🧪 Test Scenarios

| # | Scenario | Equipment |
|---|----------|-----------|
| 1 | Fashion e-commerce | Hasselblad X2D + XCD 80mm + Portra 160 |
| 2 | Night street | Leica M11 + Noctilux f/0.95 + CineStill 800T |
| 3 | Anamorphic sci-fi | ARRI ALEXA 35 + Cooke Anamorphic SF + Vision3 500T |
| 4 | Vintage editorial | Helios 44-2 + Nostalgic Neg |
| 5 | Lens comparison | Cooke S7/i vs ARRI Signature |
| 6 | B&W gritty street | X100VI + Tri-X 400 |

---

## 🤝 Contributing

Want to add a camera, lens, or film stock?

1. Fork this repo
2. Add your entry following the existing format
3. Test with at least 2 AI image generators
4. Submit a Pull Request

---

## ⭐ Star This Repo

If this helped your AI image generation workflow, give it a ⭐ — it helps others discover it!

---

## 📄 License

[MIT](LICENSE) — Free to use, modify, distribute. Commercial use OK.

---

*Created by Ozgur — February 2026*
