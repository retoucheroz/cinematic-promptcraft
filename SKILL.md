---
name: cinematic-promptcraft
description: "Expert AI image generation prompt engineer specializing in cinematic and editorial photography aesthetics. Use this skill when generating prompts for fal.ai Nano Banana Pro or similar AI image generators that need to replicate specific camera bodies, cinema lenses, photo lenses, vintage lenses, focal lengths, apertures, and film stock simulations. Covers ARRI, RED, Sony, Panavision, Leica, Hasselblad, Fujifilm, Canon, Nikon camera systems; Cooke, Zeiss, Panavision, ARRI Signature, Leica, Canon K35, Helios vintage lenses; and film simulations for Kodak (Portra, Ektar, Vision3, Tri-X), Fujifilm (Eterna, Pro 400H, Superia, Provia, Velvia, Acros), Cinestill (800T, 50D), Ilford, Agfa, and Lomography film stocks. Triggers: any mention of 'cinematic prompt', 'camera look', 'film simulation', 'lens character', 'bokeh style', 'editorial photography prompt', 'fashion photography AI', or requests to generate images with specific optical/camera aesthetics."
---

# Cinematic PromptCraft — AI Image Generation Prompt Engineering Skill

## Overview

This skill transforms camera/lens/film stock specifications into optimized AI image generation prompts. It encodes deep knowledge of how real-world optical systems produce images — their color science, bokeh character, halation, bloom, grain structure, chromatic aberration, vignette, depth of field, and tonal response — and translates these characteristics into natural language prompts that AI image generators can interpret.

**Primary Target**: fal.ai Nano Banana Pro (and compatible Flux-based models)
**Domain**: Fashion e-commerce, editorial photography, cinematic stills, fine art

---

## Prompt Architecture

Every cinematic prompt should follow this layered structure:

```
[SUBJECT & SCENE] + [CAMERA BODY] + [LENS + FOCAL LENGTH + APERTURE] + [OPTICAL EFFECTS] + [FILM STOCK / COLOR GRADE] + [LIGHTING] + [MOOD/ATMOSPHERE]
```

### Prompt Construction Rules

1. **Be specific about optical physics** — Don't just say "bokeh". Say "large creamy circular bokeh orbs with soft edges" or "oval anamorphic bokeh with blue streak flares"
2. **Name the camera and lens explicitly** — AI models respond well to "shot on ARRI ALEXA 35 with Cooke S7/i 50mm T2.0"
3. **Describe the film stock effect, not just the name** — Instead of just "Kodak Portra 400", add "warm skin tones, pastel color palette, fine grain, soft highlight rolloff"
4. **Layer the atmosphere** — Combine optical effects with environmental mood: "golden hour halation bleeding through backlit hair"
5. **Use photography-native language** — "shallow depth of field", "rack focus", "motivated lighting", "practical lights", "fill bounce"

### Prompt Template

```
[Subject description], shot on [Camera Body] with [Lens] [Focal Length] at [Aperture], 
[Film Stock/Color Grade] aesthetic, [specific optical effects from lens character], 
[lighting description], [mood/atmosphere], [additional technical details]
```

---

## SECTION 1: CINEMA CAMERAS — Body Characteristics

### ARRI ALEXA 35
- **Sensor**: Super 35 (ALEV 4) — 4.6K
- **Dynamic Range**: 17+ stops
- **Color Science**: REVEAL Color Science, LogC4, ARRI Look File 2 (ALF2)
- **Prompt Keywords**: `shot on ARRI ALEXA 35, ARRI color science, organic film-like color separation, natural warm skin tones, smooth highlight rolloff reminiscent of film negative, clean organic grain structure at high ISO, LogC4 wide color gamut, cinematic tonal richness`
- **Character**: Industry gold standard. Unmatched organic color separation, especially in skin tones. Highlights roll off like film — never clip harshly. Even at high ISO, noise has a pleasing, film-like grain structure rather than digital noise pattern. Shadows are clean and detailed.
- **Best For**: High-end cinema, drama, commercial, fashion film
- **Prompt Example**: `fashion editorial, model in flowing silk dress, shot on ARRI ALEXA 35, rich organic color separation, warm natural skin tones with golden undertones, film-like highlight rolloff, subtle film grain texture, deep shadow detail`

### ARRI ALEXA Mini LF
- **Sensor**: Large Format 36.70×25.54mm — 4.5K
- **Dynamic Range**: 14+ stops
- **Color Science**: ARRI color science (same as ALEXA 35 but on LF sensor)
- **Prompt Keywords**: `shot on ARRI ALEXA Mini LF, large format shallow depth of field, cinematic 3D pop on faces, ARRI organic color science on full frame, beautiful subject isolation, large format bokeh, film-like natural skin rendering`
- **Character**: Full-frame sized sensor with ARRI's legendary color. Shallower depth of field creates more pronounced subject separation and 3D "pop" effect on faces. The larger sensor gives a more immersive, dimensional look compared to Super 35.
- **Best For**: High-end drama, fashion films, beauty commercials, anamorphic work
- **Prompt Example**: `close-up beauty portrait, shot on ARRI ALEXA Mini LF, extreme shallow depth of field, face has cinematic 3D dimensionality, creamy large format background blur, ARRI warm skin tone rendering, subtle halation around highlights`

### RED V-RAPTOR XL [X]
- **Sensor**: VistaVision 40.96×21.60mm — 8K
- **Dynamic Range**: 17+ stops, Global Shutter
- **Color Science**: IPP2, REDWideGamutRGB
- **Prompt Keywords**: `shot on RED V-RAPTOR 8K, ultra sharp hyper-detailed, RED color science, clinical precision with cinematic depth, 8K resolution micro-detail, global shutter frozen motion, razor sharp`
- **Character**: Sharper, more clinical than ARRI. Extreme resolution captures micro-details. Global shutter eliminates rolling shutter artifacts. Color science is more neutral — great canvas for heavy grading. The "digital cinema" look vs ARRI's "film-like" look.
- **Best For**: VFX-heavy work, high-res reframe needs, action, commercial
- **Prompt Example**: `product shot, luxury watch on wrist, shot on RED V-RAPTOR 8K, hyper-detailed macro-level sharpness, every texture visible, clinical precision, neutral color palette ready for grade, ultra-high resolution`

### Sony VENICE 2
- **Sensor**: Full Frame 36×24mm — 8.6K
- **Dynamic Range**: 16+ stops
- **Color Science**: S-Gamut3/S-Log3, Dual Base ISO 800/3200
- **Prompt Keywords**: `shot on Sony VENICE 2, dual base ISO low light mastery, S-Gamut3 wide color, neutral starting point for grading, soft highlight transitions, clean shadow detail even in darkness, natural skin rendering`
- **Character**: Low-light champion with Dual Base ISO. More neutral starting point than ARRI — extremely flexible for grading. Skin tones are natural and clean. Highlight transitions are soft. Built-in 8-segment ND filter system.
- **Best For**: Low-light scenes, night exteriors, documentary-style cinema, versatile production
- **Prompt Example**: `night street scene, neon-lit Tokyo alley, shot on Sony VENICE 2 at ISO 3200, pristine low-light clarity, neon colors rendered with full saturation, deep blacks with visible shadow detail, cinematic night atmosphere`

### Blackmagic URSA Cine 17K 65
- **Sensor**: 65mm Format — 17K
- **Dynamic Range**: 16+ stops
- **Color Science**: Blackmagic Gen 5 Color Science
- **Prompt Keywords**: `shot on 65mm format, Blackmagic URSA Cine, ultra shallow depth of field from massive sensor, 65mm format dimensionality, film-like tonal response, extreme subject isolation, IMAX-like immersive perspective`
- **Character**: Massive 65mm sensor creates ultra-shallow DOF and immersive perspective similar to IMAX. Even when cropped, resolution remains stunning. The 65mm look has a unique dimensionality that smaller formats cannot replicate.
- **Best For**: Epic landscapes, immersive close-ups, IMAX-style content
- **Prompt Example**: `epic landscape with lone figure, shot on 65mm format, Blackmagic URSA Cine, ultra shallow depth of field isolating subject against vast background, IMAX-like immersive dimensionality, rich film-like tones`

### Panavision Millennium DXL2
- **Sensor**: Large Format RED 8K Monstro
- **Dynamic Range**: 16+ stops
- **Color Science**: Panavision Light Iron Color 2
- **Prompt Keywords**: `shot on Panavision DXL2, Panavision Light Iron color, blue-silver highlight character, warm mid-tones with cool highlights, Hollywood A-list production look, nostalgic warmth with modern clarity, Panavision organic rendering`
- **Character**: The Hollywood machine. Panavision's proprietary color science creates a signature blue-silver highlight tone with warm mid-tones. When paired with Panavision glass (Primo 70, Ultra Vista), produces an organic, unmistakably "Hollywood" look. Nostalgic warmth combined with modern resolution.
- **Best For**: Hollywood features, prestige TV, A-list productions
- **Prompt Example**: `dramatic portrait, actor in period costume, shot on Panavision DXL2, Panavision blue-silver highlight tone, warm nostalgic mid-tones, Hollywood production aesthetic, organic and dimensional`

### Canon EOS C500 Mark II
- **Sensor**: Full Frame 38.1×20.1mm — 5.9K
- **Dynamic Range**: 15+ stops
- **Color Science**: Canon Cinema Gamut, Canon Log3
- **Prompt Keywords**: `shot on Canon C500 Mark II, Canon cinema color science, warm inviting skin tones, Canon signature warmth, pleasing color reproduction, Dual Pixel AF precision focus`
- **Character**: Canon's warm color science makes skin tones especially pleasing. The "Canon look" has a signature warmth that many DPs love for beauty and portrait work. Wide lens ecosystem with EF and PL mount support.
- **Best For**: Beauty, fashion, interview/documentary, broadcast
- **Prompt Example**: `beauty close-up, model with dewy skin, shot on Canon C500 Mark II, Canon warm color science, luminous healthy skin tones, soft inviting warmth, gentle highlight glow`

---

## SECTION 2: EDITORIAL & PHOTOGRAPHY CAMERAS

### Leica M11 / M11-P
- **Sensor**: Full Frame BSI CMOS — 60MP
- **Color Science**: Leica color science — unmatched color fidelity and pastel tonal separation
- **Prompt Keywords**: `shot on Leica M11, Leica color science, unparalleled color fidelity, pastel tonal separations, rangefinder perspective, editorial street photography, minimalist purity, Leica micro-contrast and 3D rendering`
- **Character**: The Leica look is iconic — exceptional color fidelity with pastel-like tonal separations. Micro-contrast gives images a three-dimensional quality. Rangefinder body encourages intimate, street-level perspectives. Triple Resolution (60/36/18MP).
- **Prompt Example**: `street photography, figure walking through rain-soaked alley, shot on Leica M11, Leica color science with pastel tonal separation, micro-contrast 3D pop, editorial documentary atmosphere, rangefinder intimacy`

### Hasselblad X2D 100C
- **Sensor**: Medium Format 43.8×32.9mm — 100MP
- **Color Science**: HNCS (Hasselblad Natural Colour Solution)
- **Prompt Keywords**: `shot on Hasselblad X2D 100C, medium format, 100 megapixel extreme detail, HNCS natural colour solution, 16-bit color depth tonal transitions, medium format shallow depth of field, skin tones beyond natural beauty, Hasselblad rendering`
- **Character**: The king of medium format. 16-bit color depth creates tonal transitions that full-frame cannot match. HNCS renders skin tones with a beauty that transcends reality — luminous, porcelain-like yet natural. 100MP resolves micro-texture. The medium format "look" has a unique dimensionality.
- **Prompt Example**: `high-end fashion editorial, model in haute couture, shot on Hasselblad X2D 100C medium format, 100MP extreme detail in fabric texture, HNCS luminous skin rendering, 16-bit tonal transitions, medium format dimensionality and depth`

### Fujifilm GFX 100 II
- **Sensor**: Medium Format 43.8×32.9mm — 102MP
- **Color Science**: Fujifilm color science with Film Simulations
- **Prompt Keywords**: `shot on Fujifilm GFX 100 II medium format, 102MP, Fujifilm color science, film simulation aesthetic, medium format shallow depth of field, velvety tonal transitions, Fujifilm skin tone rendering`
- **Character**: 102MP medium format with Fujifilm's legendary film simulation heritage. Delivers gorgeous in-camera looks. The combination of large format sensor + Fuji color science + film simulations creates a unique "digital but filmic" character. Velvety tonal transitions and excellent skin rendering.
- **Best For**: Fashion editorial, travel, fine art, medium format with film character
- **Prompt Example**: `travel editorial, figure at ancient temple, shot on Fujifilm GFX 100 II, Nostalgic Neg film simulation, medium format depth and dimensionality, 102MP detail, warm nostalgic color palette with desaturated highlights`

### Sony A1 / A9 III
- **Sensor**: Full Frame (A1: 50.1MP / A9 III: 24.6MP Global Shutter)
- **Color Science**: S-Cinetone, Creative Looks
- **Prompt Keywords**: `shot on Sony A1, 50 megapixel detail, S-Cinetone color profile, cinematic warmth, Sony advanced autofocus precision, hybrid photo-cinema aesthetic`
- **Character**: Hybrid monsters. A1 combines 50MP stills with 30fps and 8K video. A9 III has world's first global shutter full-frame. S-Cinetone profile gives warmer, more cinematic tones than Sony's historically clinical rendering.
- **Prompt Example**: `action sports editorial, athlete mid-leap, shot on Sony A1, frozen motion with 50MP detail, S-Cinetone warm cinematic tones, precise autofocus on eyes, dynamic angle`

### Nikon Z8 / Z9
- **Sensor**: Full Frame 45.7MP BSI Stacked
- **Color Science**: Nikon warm natural rendering, Expeed 7
- **Prompt Keywords**: `shot on Nikon Z8, Nikon warm natural color rendering, rich earth tones, deep shadow detail, photojournalistic authority, Nikon Z-mount optical precision`
- **Character**: Nikon's warm, natural color rendering with rich earth tones. Excellent for photojournalism and sports — images have an authoritative, trustworthy quality. Z-mount lenses are optically excellent.
- **Prompt Example**: `photojournalistic portrait, weathered farmer in golden light, shot on Nikon Z8, Nikon warm natural color rendering, rich earth tones in skin, deep shadow detail, authentic documentary quality`

### Canon EOS R5 Mark II
- **Sensor**: Full Frame 45MP BSI Stacked
- **Color Science**: Canon warm color science, Digic Accelerator
- **Prompt Keywords**: `shot on Canon EOS R5 Mark II, Canon warm color science, luminous skin tones, porcelain skin rendering, AI autofocus eye detection, Canon signature warmth`
- **Character**: Canon's warm color science continues to set the standard for skin tones. The "Canon look" makes people look their best — luminous, warm, with porcelain-like skin rendering that's extremely flattering.
- **Prompt Example**: `wedding portrait, bride in soft window light, shot on Canon EOS R5 Mark II, Canon warm color science, luminous porcelain skin tones, flattering soft warmth, delicate highlight glow`

### Leica Q3
- **Sensor**: Full Frame 60MP
- **Lens**: Fixed Summilux 28mm f/1.7
- **Prompt Keywords**: `shot on Leica Q3 with Summilux 28mm f/1.7, Leica color science, wide-angle street intimacy, 28mm environmental perspective, Leica micro-contrast, compact precision, editorial reportage`
- **Character**: Fixed 28mm f/1.7 Summilux lens. Leica color science with wide-angle environmental storytelling perspective. Crop modes simulate 35mm, 50mm, 75mm fields of view. The 28mm perspective places the viewer inside the scene.
- **Prompt Example**: `street editorial, crowded market scene, shot on Leica Q3 Summilux 28mm f/1.7, Leica color science, 28mm wide environmental perspective, micro-contrast pop, documentary intimacy`

### Fujifilm X-T5 / X100VI
- **Sensor**: APS-C 40MP X-Trans 5 HR
- **Color Science**: Fujifilm Film Simulations (Nostalgic Neg, Classic Chrome, Acros, Eterna, Provia, Velvia)
- **Prompt Keywords**: `shot on Fujifilm X100VI with 23mm f/2, Fujifilm film simulation aesthetic, retro design classic look, 40MP X-Trans sensor, street editorial character, film-like straight from camera`
- **Character**: Iconic retro design with legendary film simulations. X100VI has a fixed 23mm f/2 lens (35mm equiv.) — the ultimate street/editorial camera. Film simulations provide stunning in-camera looks that emulate classic film stocks.
- **Prompt Example**: `café scene, couple in conversation, shot on Fujifilm X100VI, Classic Chrome film simulation, muted warm tones with gentle fade, retro editorial atmosphere, 35mm equivalent perspective`

---

## SECTION 3: CINEMA LENS COMBINATIONS & OPTICAL CHARACTER

### Cooke S7/i Full Frame Primes
- **Focal Range**: 18, 25, 32, 40, 50, 65, 75, 100, 135mm
- **Aperture**: T2.0
- **Best Camera Pairing**: ARRI ALEXA 35 / ALEXA Mini LF
- **The "Cooke Look"**:
  - Legendary warm color tone — skin tones feel "touched by gold"
  - Creamy, round bokeh (never harsh or oval)
  - Soft, gentle highlight rolloff
  - Minimal chromatic aberration
  - Light vignette at wide apertures
  - Shallow cinematic DOF at T2.0
- **Prompt Keywords**: `Cooke S7/i [focal]mm T2.0, the Cooke Look, golden warm skin tones, creamy round bokeh orbs, gentle highlight rolloff, cinematic shallow depth of field, warm organic rendering, soft vignette at edges`
- **Prompt Example**: `cinematic portrait, actor in warm practicals, shot on ARRI ALEXA 35 with Cooke S7/i 50mm T2.0, the Cooke Look golden warm skin rendering, creamy round bokeh orbs in background, gentle highlight rolloff, soft natural vignette, shallow depth of field`

### ARRI Signature Primes
- **Focal Range**: 12–280mm (16 lenses)
- **Aperture**: T1.8
- **Best Camera Pairing**: ARRI ALEXA Mini LF / ALEXA 35
- **Character**:
  - Modern cinematic perfection — clean but never sterile
  - Ultra-shallow DOF at T1.8 with visible large bokeh
  - Minimal distortion, clean optics
  - Highlights fall off softly and naturally
  - Very little vignette
  - Nearly zero chromatic aberration
  - LPL mount covers full large format sensors
- **Prompt Keywords**: `ARRI Signature Prime [focal]mm T1.8, modern cinematic perfection, ultra shallow depth of field, large clean bokeh, minimal distortion, soft natural highlight falloff, pristine large format optics`
- **Prompt Example**: `luxury fashion film still, model walking through gallery, shot on ARRI ALEXA Mini LF with ARRI Signature Prime 47mm T1.8, ultra shallow depth of field, large soft bokeh, modern cinematic perfection, pristine optical clarity`

### Panavision Primo 70 Primes
- **Focal Range**: 27, 35, 40, 50, 65, 80, 100, 125, 150, 200mm
- **Aperture**: T2.2
- **Best Camera Pairing**: Panavision DXL2
- **Character**:
  - Signature "blue-silver" highlight characteristic
  - Warm mid-tones, cool highlights
  - Film-like tonal separation
  - Large, soft bokeh
  - Minimal chromatic aberration
  - Oscar-winning film favorite
  - Only available for rental from Panavision
- **Prompt Keywords**: `Panavision Primo 70 [focal]mm T2.2, Panavision blue-silver highlights, warm mid-tones with cool highlight transition, Hollywood film tonal separation, large soft bokeh, Oscar-winning cinematography aesthetic`
- **Prompt Example**: `period drama close-up, shot on Panavision DXL2 with Primo 70 65mm T2.2, Panavision blue-silver highlight tone, warm golden mid-tones transitioning to cool silver highlights, Hollywood prestige film aesthetic, large dimensional bokeh`

### Zeiss Supreme Primes
- **Focal Range**: 15–200mm (14 lenses)
- **Aperture**: T1.5
- **Best Camera Pairing**: Sony VENICE 2 / RED V-RAPTOR
- **Character**:
  - Balance of Zeiss sharpness with cinematic softness
  - Incredible bokeh and ultra-shallow DOF at T1.5
  - Clean, neutral color rendering
  - Minimal flare
  - Very low chromatic aberration
  - Slightly warm tone
  - PL mount
- **Prompt Keywords**: `Zeiss Supreme Prime [focal]mm T1.5, Zeiss sharpness with cinematic softness, ultra shallow depth of field at T1.5, beautiful large bokeh, neutral clean color rendering, slightly warm tone, minimal flare`
- **Prompt Example**: `night scene, actor under streetlight, shot on Sony VENICE 2 with Zeiss Supreme Prime 85mm T1.5, ultra shallow depth of field, beautiful large bokeh from streetlights, Zeiss precision sharpness on face, slightly warm neutral rendering`

### Cooke Anamorphic/i SF (Special Flare)
- **Focal Range**: 25, 32, 40, 50, 65, 75, 100, 135, 180mm
- **Aperture**: T2.3
- **Best Camera Pairing**: ARRI ALEXA Mini LF / ALEXA 35
- **Character**:
  - 2x anamorphic squeeze — widescreen cinematic format
  - Oval/elliptical bokeh (signature anamorphic look)
  - Horizontal blue/amber streak flares
  - Controlled flare and halation (SF version)
  - Cooke warmth + anamorphic character
  - Edge softness and field curvature add cinematic depth
  - Barrel/mustache distortion
- **Prompt Keywords**: `Cooke Anamorphic/i SF [focal]mm T2.3, 2x anamorphic, oval elliptical bokeh, horizontal blue amber lens flare streaks, anamorphic widescreen format, Cooke warm anamorphic character, controlled halation and flare, edge softness with field curvature, cinematic widescreen aspect ratio`
- **Prompt Example**: `sci-fi corridor scene, figure walking toward camera, shot on ARRI ALEXA 35 with Cooke Anamorphic/i SF 40mm T2.3, 2.39:1 widescreen anamorphic, oval bokeh from corridor lights, horizontal blue lens flare streaks, warm anamorphic halation, edge softness adding depth`

### Atlas Mercury 1.5x Anamorphic
- **Focal Range**: 36, 42, 54, 65, 80, 100, 138mm
- **Aperture**: T2.0
- **Best Camera Pairing**: RED V-RAPTOR / ARRI ALEXA 35
- **Character**:
  - 1.5x anamorphic — "vintage modern"
  - Pronounced blue/amber anamorphic streak flares
  - Oval bokeh
  - Controlled edge softness and light leaks
  - Modern sharpness + vintage character balance
- **Prompt Keywords**: `Atlas Mercury [focal]mm T2.0, 1.5x anamorphic, vintage modern character, blue amber anamorphic streak flares, oval bokeh, controlled edge softness, modern sharpness with vintage soul, indie cinema anamorphic`
- **Prompt Example**: `music video still, singer in moody blue light, shot with Atlas Mercury 54mm T2.0, 1.5x anamorphic, blue amber horizontal flare streaks, oval bokeh in background, vintage modern character, indie cinema feel`

### Canon K35 Primes (Vintage 1970s)
- **Focal Range**: 18, 24, 35, 55, 85mm
- **Aperture**: T1.3 – T1.5
- **Best Camera Pairing**: ARRI ALEXA 35 / ALEXA Mini LF
- **Character**:
  - 1970s legendary cinema lenses
  - Pronounced halation and bloom, especially wide open
  - Warm, golden color tone
  - Visible chromatic aberration at edges
  - Soft out-of-focus areas with organic transition
  - Film-like rendering on modern sensors
  - Barry Lyndon / Stanley Kubrick aesthetic
- **Prompt Keywords**: `Canon K35 [focal]mm T1.3, 1970s vintage cinema lens, pronounced halation and bloom around highlights, warm golden color cast, visible chromatic aberration at edges, dreamy soft out-of-focus areas, film-era organic rendering, nostalgic vintage cinema look`
- **Prompt Example**: `candlelit dinner scene, shot on ARRI ALEXA 35 with vintage Canon K35 55mm T1.3, 1970s cinema lens character, pronounced warm halation around candle flames, golden color cast on skin, dreamy bloom, visible chromatic fringing, Barry Lyndon nostalgic aesthetic`

### Leitz/Leica Summicron-C Cinema Primes
- **Focal Range**: 15, 18, 21, 25, 29, 35, 40, 50, 75, 100, 135mm
- **Aperture**: T2.0
- **Best Camera Pairing**: ARRI ALEXA 35 / Sony VENICE 2
- **Character**:
  - Leica optical DNA in cinema format
  - Clean, high-contrast but still cinematic
  - Leica's famous "glow" on skin tones
  - Minimal distortion
  - Subtle vintage character
  - Soft, orderly bokeh
  - Very low chromatic aberration
- **Prompt Keywords**: `Leitz Summicron-C [focal]mm T2.0, Leica optical DNA cinema format, clean high contrast cinematic, Leica glow on skin tones, subtle vintage character, orderly soft bokeh, editorial cinema aesthetic`
- **Prompt Example**: `editorial fashion film, model in minimal set, shot on ARRI ALEXA 35 with Leitz Summicron-C 75mm T2.0, Leica glow on luminous skin, high contrast cinematic clarity, subtle vintage character, clean orderly bokeh, editorial precision`

### Tribe7 Blackwing7 Primes
- **Focal Range**: 27, 37, 47, 57, 77, 107, 137mm
- **Aperture**: T1.9
- **Best Camera Pairing**: ARRI ALEXA 35 / RED V-RAPTOR
- **Character**:
  - Adjustable "tuning" mechanism — customizable character
  - Can dial from sharp → soft, clean → flamboyant
  - Controlled halation
  - Variable flare and bokeh characteristics
  - Each lens configurable differently
  - Ultimate creative cinematographer tool
- **Prompt Keywords**: `Tribe7 Blackwing7 [focal]mm T1.9, tunable lens character, [sharp/soft] rendering, controlled halation, customizable flare character, creative cinematography`

### Angénieux Optimo Primes & Zoom
- **Focal Range**: Primes: 21–135mm / Zoom: 24-290mm
- **Aperture**: T1.8 (primes) / T2.8 (zoom)
- **Best Camera Pairing**: ARRI ALEXA Mini LF / Panavision DXL2
- **Character**:
  - French optical perfection
  - Warm European tone
  - Soft, elegant bokeh
  - Subtle vintage character
  - Even zooms maintain cinematic quality
  - Minimal breathing
  - Golden glow in highlights
- **Prompt Keywords**: `Angénieux Optimo [focal]mm T1.8, French optical elegance, warm European tone, soft elegant bokeh, golden highlight glow, minimal breathing, cinematic zoom quality, Wes Anderson aesthetic warmth`
- **Prompt Example**: `symmetrical composition, pastel-colored room, shot with Angénieux Optimo 40mm T1.8, French optical warmth, golden highlight glow, soft elegant bokeh, warm European tonal palette, Wes Anderson inspired aesthetic`

---

## SECTION 4: PHOTOGRAPHY LENS COMBINATIONS & OPTICAL CHARACTER

### Leica Noctilux-M 50mm f/0.95 ASPH
- **Camera**: Leica M11
- **Character**:
  - Razor-thin DOF at f/0.95 — paper-thin focus plane
  - Magnificent large round bokeh orbs
  - Pronounced glow and halation wide open
  - Warm golden highlight transitions
  - Swirl bokeh character
  - Rich, saturated colors
  - Heavy cinematic vignette
- **Prompt Keywords**: `Leica Noctilux 50mm f/0.95, razor thin depth of field, magnificent large round bokeh orbs, pronounced warm glow and halation, golden highlight transitions, swirl bokeh character, rich saturated Leica colors, heavy cinematic vignette, f/0.95 ultra shallow focus`
- **Prompt Example**: `night portrait, face illuminated by warm practicals, shot on Leica M11 with Noctilux 50mm f/0.95, razor thin focus plane on eyes, magnificent large round bokeh orbs from city lights, warm golden halation glow, heavy vignette framing, swirl bokeh character`

### Leica Summilux-M 35mm f/1.4 ASPH FLE II
- **Camera**: Leica M11 / M11-P
- **Character**:
  - Iconic editorial/street lens
  - Soft bokeh with sharp focus at f/1.4
  - Leica color fidelity and micro-contrast
  - Light vignette at wide apertures
  - Very low chromatic aberration
  - Neutral to slightly warm tone
  - Perfect 35mm perspective
- **Prompt Keywords**: `Leica Summilux 35mm f/1.4, iconic editorial street lens, Leica micro-contrast 3D rendering, sharp focus with soft bokeh, Leica color fidelity, light vignette, 35mm perspective`

### Hasselblad XCD 80mm f/1.9
- **Camera**: Hasselblad X2D 100C
- **Character**:
  - Medium format f/1.9 = full frame f/1.5 DOF equivalent
  - 100MP detail + creamy medium format bokeh
  - HNCS 16-bit skin tone transitions — beyond natural beauty
  - Micro-detail in eyes and skin texture
  - Soft highlight rolloff
  - Minimal chromatic aberration
- **Prompt Keywords**: `Hasselblad XCD 80mm f/1.9, medium format shallow depth of field, 100MP extreme detail, HNCS luminous skin rendering, 16-bit tonal transitions, creamy medium format bokeh, Hasselblad beauty rendering`
- **Prompt Example**: `beauty editorial close-up, model with flawless skin, shot on Hasselblad X2D with XCD 80mm f/1.9, medium format shallow DOF, 100MP micro-detail in iris and skin texture, HNCS luminous porcelain skin rendering, creamy medium format bokeh, 16-bit tonal perfection`

### Fujifilm GF 110mm f/2 R LM WR
- **Camera**: Fujifilm GFX 100 II
- **Character**:
  - Medium format portrait lens
  - Gorgeous bokeh at f/2
  - Film simulations = direct cinematic output
  - 102MP + large format = extraordinary detail
  - Velvety tonal transitions
  - Slightly warm tone
  - Excellent skin micro-contrast
- **Prompt Keywords**: `Fujifilm GF 110mm f/2, medium format portrait, gorgeous bokeh, Fujifilm film simulation aesthetic, 102MP extraordinary detail, velvety tonal transitions, warm Fujifilm skin rendering`

### Sony FE 35mm f/1.4 GM
- **Camera**: Sony A1 / A9 III
- **Character**:
  - Ultra sharp + beautiful bokeh balance
  - 11-blade diaphragm = round bokeh orbs
  - XA element with slight aberration character
  - S-Cinetone cinematic tones
  - Impressive background separation at close focus
  - Minimal distortion
- **Prompt Keywords**: `Sony FE 35mm f/1.4 GM, ultra sharp with beautiful round bokeh, 11-blade circular bokeh orbs, S-Cinetone cinematic tones, Sony precision optics, impressive background separation`

### Nikon NIKKOR Z 50mm f/1.2 S
- **Camera**: Nikon Z8 / Z9
- **Character**:
  - Enchanting bokeh at f/1.2
  - Nikon's sharpest 50mm ever
  - Paper-thin DOF
  - No "onion ring" effect in bokeh
  - Natural warm color rendering
  - Beautiful skin tone beauty
- **Prompt Keywords**: `Nikon Z 50mm f/1.2, enchanting smooth bokeh, paper thin depth of field at f/1.2, Nikon warm natural rendering, no onion ring bokeh artifacts, beautiful skin tone rendering, Nikon's sharpest 50mm`

### Canon RF 85mm f/1.2L USM DS
- **Camera**: Canon EOS R5 Mark II
- **Character**:
  - DS (Defocus Smoothing) = smoothest bokeh on the market
  - Dream-like background dissolution at f/1.2
  - No cat's eye bokeh even at edges
  - Canon warm color science
  - "Porcelain" skin effect
  - Gentle glow wide open
  - Holy grail portrait lens
- **Prompt Keywords**: `Canon RF 85mm f/1.2 DS, Defocus Smoothing ultra smooth bokeh, dream-like background dissolution, no cat's eye effect, Canon warm porcelain skin rendering, gentle halation glow wide open, holy grail portrait lens`
- **Prompt Example**: `beauty portrait, soft studio light, shot on Canon R5 II with RF 85mm f/1.2 DS, Defocus Smoothing ultra creamy bokeh, dream-like background, Canon warm porcelain skin effect, gentle glow on highlights, f/1.2 razor shallow focus on eyes`

### Voigtländer Nokton 50mm f/1.0 Aspherical
- **Camera**: Leica M11 / Sony (with adapter)
- **Character**:
  - f/1.0 extreme shallow DOF
  - "Dreamy" glow wide open
  - Swirl bokeh character
  - Visible chromatic aberration and halation = vintage cinematic look
  - Center sharp, edges soft
  - Heavy vignette
  - Ethereal dreamlike atmosphere
- **Prompt Keywords**: `Voigtländer Nokton 50mm f/1.0, extreme shallow depth of field, dreamy soft glow wide open, swirl bokeh character, visible chromatic aberration vintage look, heavy vignette, ethereal atmosphere`

### Sigma 35mm f/1.4 DG DN Art
- **Camera**: Sony A1 / Leica SL2-S
- **Character**:
  - Price/performance king
  - Very sharp at f/1.4 with soft bokeh
  - Minimal chromatic aberration
  - Light vignette
  - Neutral-warm color rendering
  - 11-blade diaphragm = clean sun stars
  - Versatile for all editorial work
- **Prompt Keywords**: `Sigma 35mm f/1.4 Art, sharp with soft bokeh, neutral warm rendering, clean sun stars at small apertures, versatile editorial optics`

### Zeiss Otus 55mm f/1.4
- **Camera**: Nikon Z8 (FTZ adapter)
- **Character**:
  - Manual focus reference lens
  - Market's sharpest 55mm
  - Zero chromatic aberration
  - Zero distortion
  - Incredible 3D pop and dimensionality
  - "Structured" bokeh that adds depth
  - Absolute color fidelity
- **Prompt Keywords**: `Zeiss Otus 55mm f/1.4, reference-grade sharpness, zero chromatic aberration, incredible 3D pop and dimensionality, structured bokeh with depth, absolute color fidelity, fine art editorial precision`

---

## SECTION 5: VINTAGE & SPECIAL CHARACTER LENSES

### Helios 44-2 58mm f/2
- **Mount**: M42 (adapter to any system)
- **Character**:
  - Legendary "swirl bokeh" — background rotates in circular pattern like a windy painting
  - Warm, slightly yellow color cast
  - Pronounced halation and bloom in highlights
  - Visible chromatic aberration and coma at edges
  - Heavy vignette
  - Soviet-era Biotar copy
  - Ultra-low cost, incredible character
- **Prompt Keywords**: `Helios 44-2 58mm f/2, swirl bokeh rotating background, warm yellow color cast, pronounced halation bloom in highlights, visible chromatic aberration at edges, heavy vignette, Soviet vintage character, dreamy organic rendering`
- **Prompt Example**: `portrait in golden hour field, shot with Helios 44-2 58mm f/2, dramatic swirl bokeh with rotating background, warm golden halation around backlit hair, heavy vignette, vintage Soviet lens character, dreamy organic atmosphere`

### Meyer-Optik Görlitz Trioplan 100mm f/2.8
- **Mount**: Adapter to any system
- **Character**:
  - "Soap bubble bokeh" — bokeh orbs have distinct outlined edges like soap bubbles
  - Unique and instantly recognizable style
  - Center sharpness good, edges naturally soft
  - Warm vintage tone
  - Pronounced vignette
  - Cult status in botanical and portrait photography
- **Prompt Keywords**: `Trioplan 100mm f/2.8, soap bubble bokeh with outlined bubble edges, unique recognizable style, center sharp edges soft, warm vintage tone, pronounced vignette, botanical portrait aesthetic`
- **Prompt Example**: `botanical close-up, flower with dew drops, shot with Trioplan 100mm f/2.8, soap bubble bokeh with distinct outlined orbs in background, warm vintage tone, center sharp with soft edges, pronounced vignette`

### Petzval 85mm f/2.2 (Lomography)
- **Mount**: Canon/Nikon native
- **Character**:
  - 1840s Petzval design — modern reinterpretation
  - Intense swirl bokeh
  - Center sharp, edges dramatically rotating
  - Heavy field curvature
  - Brass body with Waterhouse aperture plates
  - Adjustable Bokeh Control Ring
- **Prompt Keywords**: `Petzval 85mm f/2.2, intense swirl bokeh dramatically rotating edges, sharp center with curved field, 1840s optical design character, vintage portrait aesthetic, heavy field curvature`

### Canon FD 50mm f/1.2 L (Vintage 1980s)
- **Mount**: Canon FD (adapter to Sony/Fuji)
- **Character**:
  - 1980s legend
  - Pronounced glow and halation at f/1.2
  - Dreamlike soft focus transition
  - Warm amber color rendering
  - Visible "beautiful" chromatic aberration
  - Cat's eye bokeh at edges
  - Brings film photography aesthetic to digital
- **Prompt Keywords**: `Canon FD 50mm f/1.2L vintage, 1980s lens character, pronounced glow and halation, dreamlike soft focus, warm amber color rendering, visible chromatic fringing, cat's eye bokeh at edges, film-era aesthetic on digital`

### Lensbaby Velvet 56mm f/1.6
- **Mount**: Multi-mount (all systems)
- **Character**:
  - Controlled "velvet glow" at f/1.6
  - Unique soft focus character
  - Sharp at f/4 and beyond
  - Warm, dreamy atmosphere
  - 1:2 macro magnification
- **Prompt Keywords**: `Lensbaby Velvet 56mm f/1.6, velvet glow soft focus effect, dreamy warm atmosphere, controlled softness at wide apertures, sharp when stopped down, portrait botanical dreamscape`

### Dallmeyer Super-Six 2" f/1.9 (Antique 1920s)
- **Mount**: Custom adapter
- **Character**:
  - 1920s cinema projection lens
  - Extreme swirl bokeh
  - Heavy halation and bloom
  - Center sharp, edges completely dissolve
  - Chromatic aberration looks like stained glass
  - Ultimate character lens for art photography
- **Prompt Keywords**: `Dallmeyer Super-Six f/1.9, 1920s antique projection lens, extreme swirl bokeh, heavy halation and bloom, center sharp edges dissolving, stained glass chromatic aberration, ultimate art photography character`

---

## SECTION 6: KODAK FILM STOCK SIMULATIONS

### Kodak Portra 160
- **Type**: Color Negative — Low Speed Fine Grain
- **ISO**: 160
- **Character**: Ultra fine grain. Pastel, muted color palette. Exceptional skin tone rendering — rosy, healthy, natural. Low contrast with long tonal range. Soft, delicate highlight rolloff. Gentle desaturated shadows. Slight warm bias. Studio and controlled light portrait film.
- **Prompt Keywords**: `Kodak Portra 160 film aesthetic, ultra fine grain, pastel muted color palette, rosy natural skin tones, low contrast long tonal range, soft delicate highlights, gentle desaturated shadows, slight warm bias, studio portrait film look`
- **Prompt Application**: Add to any portrait/fashion prompt: `...Kodak Portra 160 color palette, pastel muted tones, ultra fine grain, rosy healthy skin rendering, soft highlight rolloff, low contrast with gentle shadow fade...`

### Kodak Portra 400
- **Type**: Color Negative — Medium Speed
- **ISO**: 400
- **Character**: THE portrait film. Warm, slightly desaturated color palette. Beautiful skin tones with golden warmth. Visible but pleasant fine grain. Soft, forgiving highlight rolloff — never blows out harshly. Muted greens and blues. Lifted blacks/shadows. Versatile latitude.
- **Prompt Keywords**: `Kodak Portra 400 film aesthetic, warm slightly desaturated colors, golden warm skin tones, visible pleasant fine grain, soft forgiving highlight rolloff, muted greens and blues, lifted shadow tones, versatile portrait film character`
- **Prompt Application**: `...Kodak Portra 400 film look, warm desaturated palette, golden skin tones, pleasant film grain texture, soft highlight rolloff, muted greens, lifted shadow blacks...`

### Kodak Portra 800
- **Type**: Color Negative — High Speed
- **ISO**: 800
- **Character**: Heavier visible grain adding texture and mood. Warm color cast, more saturated than Portra 400. Pushed color saturation in warm tones. Visible grain structure adds analog character. Good shadow detail. More contrast than lower Portras. Evening and indoor film.
- **Prompt Keywords**: `Kodak Portra 800 film aesthetic, visible warm grain texture, heavier film grain structure, saturated warm color cast, analog textured character, good shadow detail, higher contrast than Portra 400, evening indoor film mood`

### Kodak Ektar 100
- **Type**: Color Negative — Fine Grain High Saturation
- **ISO**: 100
- **Character**: World's finest grain color negative. Hyper-saturated vivid colors — punchy reds, deep blues, rich greens. High contrast. Ultra fine grain, almost grainless. Vibrant, bold, punchy. Not traditionally flattering for skin (too saturated) — better for landscape, product, and fashion color.
- **Prompt Keywords**: `Kodak Ektar 100 film aesthetic, hyper saturated vivid colors, ultra fine grain nearly grainless, punchy reds deep blues rich greens, high contrast bold vibrant, world's finest grain color negative, vivid landscape fashion colors`
- **Prompt Application**: `...Kodak Ektar 100 vivid color saturation, ultra fine grain, punchy bold reds and deep blues, high contrast vibrant tones, rich saturated greens...`

### Kodak Gold 200
- **Type**: Color Negative — Consumer Classic
- **ISO**: 200
- **Character**: THE nostalgic consumer film. Warm golden color cast — everything bathed in golden warmth. Visible grain. Slightly lower contrast. Reds and yellows emphasized. Greens shift warm. Blue skies become warm teal. Casual, nostalgic, summer memories feel.
- **Prompt Keywords**: `Kodak Gold 200 film aesthetic, warm golden color cast, everything bathed in golden warmth, visible nostalgic grain, reds and yellows emphasized, warm green shift, casual summer nostalgia, consumer film character, golden hour look`

### Kodak ColorPlus 200
- **Type**: Color Negative — Budget Classic
- **ISO**: 200
- **Character**: Similar to Gold but slightly cooler and less saturated. Moderate grain. More neutral than Gold. Budget film with honest, unpretentious character. Muted colors with a slight cool-warm split. Blues retain more accuracy. Great for everyday editorial with authentic amateur film feel.
- **Prompt Keywords**: `Kodak ColorPlus 200 film aesthetic, moderate grain, slightly cool-warm split, muted honest colors, unpretentious authentic film character, everyday editorial look`

### Kodak Vision3 50D (5203)
- **Type**: Motion Picture Negative — Daylight
- **ISO**: 50
- **Character**: Cinema film stock for daylight. Extremely fine grain, almost imperceptible. Rich, saturated colors with excellent separation. Very high resolution feel. Accurate, punchy skin tones. Clean shadows. The "modern blockbuster" film look. Christopher Nolan's film of choice.
- **Prompt Keywords**: `Kodak Vision3 50D cinema film aesthetic, extremely fine grain imperceptible, rich saturated colors with excellent separation, punchy accurate skin tones, clean shadow detail, modern blockbuster film look, daylight cinema negative character`

### Kodak Vision3 200T (5213)
- **Type**: Motion Picture Negative — Tungsten
- **ISO**: 200
- **Character**: Tungsten-balanced cinema film. Cool blue cast under daylight (uncorrected), warm and accurate under tungsten. Fine grain. Rich mid-tone saturation. Beautiful under mixed lighting. Slightly more contrast than 50D. Versatile cinema workhorse.
- **Prompt Keywords**: `Kodak Vision3 200T cinema film aesthetic, tungsten balanced, cool blue cast under daylight, warm accurate under tungsten light, fine grain, rich mid-tone saturation, beautiful mixed lighting rendering, cinema workhorse`

### Kodak Vision3 500T (5219)
- **Type**: Motion Picture Negative — Tungsten High Speed
- **ISO**: 500
- **Character**: High-speed cinema film. Visible organic grain structure. Tungsten balanced with blue daylight cast. Excellent shadow detail and latitude. Grain adds gritty, textured character. Deep blacks with detail. Night scene and low-light cinema favorite. The "indie film" grain.
- **Prompt Keywords**: `Kodak Vision3 500T cinema film aesthetic, visible organic film grain, tungsten blue daylight cast, excellent shadow latitude, gritty textured grain character, deep detailed blacks, night scene low-light cinema, indie film grain texture`
- **Prompt Application**: `...Kodak Vision3 500T gritty film grain, blue-shifted tungsten balanced tones, organic grain texture, deep blacks with shadow detail, low-light cinema character...`

### Kodak Tri-X 400
- **Type**: Black & White Negative
- **ISO**: 400
- **Character**: THE iconic black and white film. Rich, deep blacks. Pronounced visible grain with beautiful structure. Wide tonal range from deep shadow to bright highlight. High contrast but with detail throughout. Gritty, photojournalistic character. Push-processable to 1600/3200 for even grainier, moodier look.
- **Prompt Keywords**: `Kodak Tri-X 400 black and white film aesthetic, rich deep blacks, pronounced beautiful grain structure, wide tonal range, high contrast photojournalistic character, gritty textured monochrome, iconic black and white film look`
- **Prompt Application**: `...black and white, Kodak Tri-X 400 film grain, rich deep blacks, pronounced grain texture, high contrast, photojournalistic gritty character...`

### Kodak T-Max 400
- **Type**: Black & White Negative — T-Grain Technology
- **ISO**: 400
- **Character**: Finer, more controlled grain than Tri-X. Modern T-grain technology. Smoother tonal gradations. More "refined" black and white look. Less gritty, more elegant. Excellent detail resolution. Great for portraits and fine art where smoothness is desired over grit.
- **Prompt Keywords**: `Kodak T-Max 400 black and white film, finer controlled grain than Tri-X, smooth elegant tonal gradations, refined monochrome character, modern grain structure, excellent detail, fine art portrait black and white`

### Kodak Ektachrome E100
- **Type**: Color Reversal (Slide) Film
- **ISO**: 100
- **Character**: Slide film transparency. Very fine grain. Punchy, vivid colors with high saturation. Higher contrast than negative film. Cooler color temperature than Kodak negatives. Blues are vivid and deep. Shadows fall to pure black quickly. Less latitude than negative — requires precise exposure. The "chrome" look.
- **Prompt Keywords**: `Kodak Ektachrome E100 slide film aesthetic, very fine grain, punchy vivid high saturation, higher contrast than negative, cooler color temperature, vivid deep blues, quick shadow falloff to black, slide film transparency look`

---

## SECTION 7: FUJIFILM FILM STOCK SIMULATIONS

### Fujifilm Pro 400H (Discontinued — Legendary)
- **Type**: Color Negative — Professional
- **ISO**: 400
- **Character**: Cool-toned complement to Portra 400. Pastel, airy color palette. Blues and greens beautifully rendered. Skin tones slightly cooler, porcelain-like. Fine grain. Soft, ethereal highlight handling. Muted, desaturated shadows. The "fashion editorial" film. Greatly missed since discontinuation.
- **Prompt Keywords**: `Fujifilm Pro 400H film aesthetic, cool pastel airy color palette, beautiful blues and greens, porcelain cool skin tones, fine grain, ethereal soft highlights, muted desaturated shadows, fashion editorial film character, dreamy ethereal atmosphere`
- **Prompt Application**: `...Fujifilm Pro 400H film look, cool pastel color palette, airy ethereal atmosphere, porcelain skin tones, beautiful cool blues and greens, soft muted highlights, fashion editorial dreamy quality...`

### Fujifilm Superia 400
- **Type**: Color Negative — Consumer
- **ISO**: 400
- **Character**: Cool-toned consumer classic. Green/teal shift in shadows. More saturated than Pro 400H but with similar cool bias. Visible grain. Punchy colors. Distinctive teal shadow tones. 90s/00s nostalgia aesthetic. Casual, spontaneous feel.
- **Prompt Keywords**: `Fujifilm Superia 400 film aesthetic, cool toned with teal green shadow shift, visible grain, punchy saturated colors, distinctive teal shadows, 90s 2000s nostalgia, casual spontaneous film character`

### Fujifilm Superia X-TRA 400
- **Type**: Color Negative — Consumer Plus
- **ISO**: 400
- **Character**: Slightly more saturated than regular Superia. Warmer greens. More pronounced teal in shadows. Higher contrast. Good all-around consumer film with distinctive Fuji color signature. Reds are vivid. Blues tend toward cyan.
- **Prompt Keywords**: `Fujifilm Superia X-TRA 400 film, saturated Fuji colors, warm greens, teal shadows, higher contrast, vivid reds, cyan-shifted blues, consumer film character`

### Fujifilm C200 (Fujicolor 200)
- **Type**: Color Negative — Budget
- **ISO**: 200
- **Character**: Budget film with surprising charm. Slightly cool, green-shifted tones. Moderate grain. Lower saturation than Superia. Muted, quiet color palette. Great for casual street photography with an understated, honest look.
- **Prompt Keywords**: `Fujifilm C200 film aesthetic, cool green-shifted tones, moderate grain, muted quiet colors, understated honest character, casual street film look`

### Fujifilm Eterna 250 / 500
- **Type**: Motion Picture Negative
- **ISO**: 250 / 500
- **Character**: Fujifilm's cinema film stock. Very desaturated, muted color palette. Low contrast with flat, wide tonal range. Skin tones neutral and natural. Blues tend toward teal. Reds are muted, not punchy. Grain varies by speed (250 finer, 500 more visible). "Quiet" cinematic look. Great base for grading. The anti-Ektar — subtlety over punch.
- **Prompt Keywords**: `Fujifilm Eterna cinema film aesthetic, very desaturated muted colors, low contrast flat tonal range, neutral natural skin tones, teal-shifted blues, muted restrained reds, quiet cinematic character, subtle understated film look, great grading base`
- **Prompt Application**: `...Fujifilm Eterna desaturated muted palette, low contrast wide tonal range, neutral skin tones, teal blues, quiet understated cinematic atmosphere, film grain texture...`

### Fujifilm Eterna Vivid 500
- **Type**: Motion Picture Negative
- **ISO**: 500
- **Character**: More saturated version of Eterna. Still cinema-oriented but with more color punch. Better color separation than standard Eterna. Retains the quiet, controlled character but with more vibrancy. Good for scenes needing more color presence while maintaining cinema feel.
- **Prompt Keywords**: `Fujifilm Eterna Vivid 500 cinema film, more saturated cinema palette, better color separation, controlled vibrancy, quiet cinematic character with color punch`

### Fujifilm Provia 100F
- **Type**: Color Reversal (Slide) Film
- **ISO**: 100
- **Character**: Reference slide film for accurate color reproduction. Fine grain. Neutral color balance — neither warm nor cool. High saturation but controlled. Excellent color accuracy. High contrast. Clean, precise rendering. The "documentary accuracy" slide film.
- **Prompt Keywords**: `Fujifilm Provia 100F slide film aesthetic, accurate neutral color reproduction, fine grain, high controlled saturation, high contrast, clean precise rendering, reference color accuracy, documentary precision`

### Fujifilm Velvia 50 / 100
- **Type**: Color Reversal (Slide) Film
- **ISO**: 50 / 100
- **Character**: EXTREME color saturation. The most vivid film ever made. Ultra fine grain. Very high contrast. Reds blaze, greens glow, blues intensify. Shadows crush to black. Not for skin (way too saturated). THE landscape film. Sunrise/sunset film. Bold, punchy, hyper-real color.
- **Prompt Keywords**: `Fujifilm Velvia 50 slide film aesthetic, extreme hyper saturation, blazing vivid reds, glowing intense greens, deep vivid blues, ultra fine grain, very high contrast, crushed deep blacks, hyper-real bold landscape colors, most vivid film ever`
- **Prompt Application**: `...Fujifilm Velvia 50 extreme saturation, blazing vivid colors, ultra fine grain, high contrast, glowing greens and intense blues, hyper-real bold color rendering...`

### Fujifilm Acros 100 / Acros II
- **Type**: Black & White Negative
- **ISO**: 100
- **Character**: Ultra fine grain black and white — finest grain B&W film available. Smooth, creamy tonal transitions. Elegant, refined monochrome. Excellent detail. Less gritty than Tri-X — more "gallery quality." Rich mid-tones. Clean highlights. Beautiful long exposure capability.
- **Prompt Keywords**: `Fujifilm Acros 100 black and white film aesthetic, ultra fine grain, smooth creamy tonal transitions, elegant refined monochrome, excellent detail, gallery quality black and white, rich mid-tones, clean highlights`

### Fujifilm Neopan 1600 (Discontinued)
- **Type**: Black & White Negative — High Speed
- **ISO**: 1600
- **Character**: Heavy, dramatic grain structure. Very contrasty B&W. Deep rich blacks. Gritty, moody atmosphere. Concert and night photography classic. Grain adds energy and rawness. Push to 3200 for even more drama.
- **Prompt Keywords**: `Fujifilm Neopan 1600 black and white, heavy dramatic grain, very high contrast, deep rich blacks, gritty moody atmosphere, concert night photography character, raw energetic grain`

---

## SECTION 8: FUJIFILM DIGITAL FILM SIMULATIONS

These are Fujifilm's digital camera film simulation modes — designed to replicate film aesthetics in-camera.

### Classic Chrome
- **Character**: Desaturated, muted tones with increased contrast. Inspired by vintage documentary/reportage photography. Warm mid-tones, cool shadows. Reds are muted and shifted toward orange. Greens are olive-toned. Blues are slightly desaturated. "Magazine editorial" look.
- **Prompt Keywords**: `Fujifilm Classic Chrome film simulation, desaturated muted editorial tones, increased contrast, warm mid-tones with cool shadows, muted orange-shifted reds, olive greens, magazine editorial look, vintage documentary character`

### Classic Negative
- **Type**: Digital Film Simulation
- **Character**: High contrast with distinctive color shifts. Highlights warm, shadows cool (split-toning). Desaturated but punchy. Reds shift to orange/amber. Blues deepen. Skin tones get a unique warm-cool character. Street photography and casual editorial favorite.
- **Prompt Keywords**: `Fujifilm Classic Negative film simulation, high contrast split-tone, warm highlights cool shadows, desaturated punchy colors, amber-shifted reds, deepened blues, street photography editorial character`

### Nostalgic Negative (Nostalgic Neg.)
- **Type**: Digital Film Simulation
- **Character**: Amber/golden warm color cast. High contrast. Desaturated cyans. Warm highlights, muted shadows. Skin tones with golden amber warmth. Vintage 1970s/1980s photography feel. Film-like tonal response. Very popular for editorial and lifestyle.
- **Prompt Keywords**: `Fujifilm Nostalgic Neg film simulation, amber golden warm color cast, high contrast, desaturated cyans, warm vintage 1970s 1980s feel, golden amber skin warmth, muted shadows, nostalgic editorial lifestyle character`
- **Prompt Application**: `...Fujifilm Nostalgic Neg aesthetic, amber golden warmth throughout, vintage 1970s color cast, high contrast, desaturated cyans, warm glowing skin tones, nostalgic editorial atmosphere...`

### Eterna (Digital)
- **Type**: Digital Film Simulation
- **Character**: Cinema-inspired flat profile. Very low contrast, wide tonal range. Desaturated, muted colors. Neutral skin tones. Great base for color grading. "Cinematic raw" look. Blues tend teal. Overall quiet, understated aesthetic.
- **Prompt Keywords**: `Fujifilm Eterna digital simulation, cinema flat profile, very low contrast, desaturated muted colors, neutral skin tones, wide tonal range, cinematic raw base, teal blues, quiet understated`

### Eterna Bleach Bypass
- **Type**: Digital Film Simulation
- **Character**: Simulates the lab process of skipping bleach in film development. Very high contrast. Severely desaturated — almost monochromatic with color hints. Metallic, gritty look. Harsh shadows. Silver-toned highlights. War film, dystopian, edgy editorial. Saving Private Ryan, 300 aesthetic.
- **Prompt Keywords**: `Fujifilm Eterna Bleach Bypass simulation, extremely desaturated near monochrome with color hints, very high contrast, metallic gritty look, harsh shadows, silver-toned highlights, war film dystopian aesthetic, Saving Private Ryan look`

### ACROS (Digital)
- **Type**: Digital Film Simulation — Black & White
- **Character**: Emulates Fujifilm Acros film. Ultra smooth tonal gradations. Fine grain simulation. Rich blacks without crushing. Elegant, refined B&W. Available with Yellow, Red, and Green filter variants for different contrast and tonal responses.
- **Prompt Keywords**: `Fujifilm ACROS digital simulation, ultra smooth black and white tonal gradations, fine grain, rich blacks, elegant refined monochrome, film-like B&W rendering`

### PRO Neg. Hi / PRO Neg. Std
- **Type**: Digital Film Simulation
- **Character**: Hi: Higher contrast, suitable for portraits with strong studio light. Std: Lower contrast, softer transitions. Both have muted, professional color palette. Skin tones well-controlled. Studio portrait oriented.
- **Prompt Keywords**: `Fujifilm PRO Neg portrait simulation, professional controlled color palette, [Hi: higher contrast studio / Std: soft transitions], well-controlled skin tones`

---

## SECTION 9: CINESTILL FILM SIMULATIONS

### CineStill 800T
- **Type**: Color Negative — Tungsten (repurposed cinema film)
- **ISO**: 800
- **Character**: THE modern cult film. Based on Kodak Vision3 500T cinema stock with remjet removed. Signature RED HALATION around bright light sources — the most distinctive characteristic. Tungsten balanced = blue cast under daylight. Warm, golden under tungsten/practical lights. Visible grain. Deep, moody blacks. Neon and night photography icon. Urban cinematic.
- **Prompt Keywords**: `CineStill 800T film aesthetic, signature red halation around light sources, red glow bleeding from highlights, tungsten blue cast under daylight, warm golden under tungsten practicals, visible organic grain, deep moody blacks, neon night urban cinematic character, modern cult film look`
- **Prompt Application**: `...CineStill 800T film look, distinctive red halation halos around lights, tungsten blue-shifted tones, warm golden practicals, visible grain, deep moody blacks, night urban cinematic atmosphere, neon glow with red halation bleeding...`
- **Critical Note**: The RED HALATION is the defining feature. Always mention it prominently for CineStill 800T looks.

### CineStill 50D
- **Type**: Color Negative — Daylight (repurposed cinema film)
- **ISO**: 50
- **Character**: Based on Kodak Vision3 50D cinema stock with remjet removed. Ultra fine grain. Rich, saturated daylight colors. Less halation than 800T (lower ISO = less light overflow). High resolution feel. Accurate, punchy color rendering. Clean cinema look for daylight shooting.
- **Prompt Keywords**: `CineStill 50D film aesthetic, ultra fine grain, rich saturated daylight colors, minimal halation, high resolution cinema feel, punchy accurate color rendering, clean daylight cinema look`

---

## SECTION 10: ILFORD BLACK & WHITE FILM SIMULATIONS

### Ilford HP5 Plus 400
- **Type**: Black & White Negative
- **ISO**: 400
- **Character**: Classic B&W workhorse. Medium grain with pleasing structure. Good contrast range. Rich tonal scale. Less contrasty than Tri-X — more forgiving. Versatile pushability (800, 1600, 3200). Documentary, street, photojournalism standard. Slightly softer character than Tri-X.
- **Prompt Keywords**: `Ilford HP5 Plus 400 black and white film, medium pleasing grain, good contrast range, rich tonal scale, documentary street photography character, versatile classic B&W, slightly softer than Tri-X`

### Ilford Delta 3200
- **Type**: Black & White Negative — Ultra High Speed
- **ISO**: 3200
- **Character**: Extreme high ISO B&W. Very heavy, pronounced grain — grain IS the aesthetic. Very high contrast. Deep blacks. Night and low-light specialist. Dramatic, gritty, raw. Concert, night street, atmospheric B&W. Grain adds visceral energy.
- **Prompt Keywords**: `Ilford Delta 3200 black and white, extreme heavy grain texture, very high contrast, deep dramatic blacks, night low-light specialist, gritty raw atmospheric, visceral grain energy, concert night street character`

### Ilford FP4 Plus 125
- **Type**: Black & White Negative — Fine Grain
- **ISO**: 125
- **Character**: Fine grain B&W. Long tonal range with smooth transitions. Detailed, resolved highlights. Clean, precise rendering. Lower contrast than HP5. Landscape, architecture, fine art B&W. The "careful, contemplative" B&W film.
- **Prompt Keywords**: `Ilford FP4 Plus 125 black and white, fine grain, long smooth tonal range, detailed resolved highlights, clean precise rendering, landscape architecture fine art B&W, contemplative character`

### Ilford Pan F Plus 50
- **Type**: Black & White Negative — Ultra Fine Grain
- **ISO**: 50
- **Character**: Finest grain B&W available. Extreme resolution and detail. Smooth, creamy tones. Low ISO requires good light. The most "pristine" B&W film. Fine art, studio, macro, landscape in good light.
- **Prompt Keywords**: `Ilford Pan F Plus 50 black and white, finest grain available, extreme resolution detail, smooth creamy pristine tones, fine art studio quality B&W`

---

## SECTION 11: SPECIAL & EXPERIMENTAL FILM SIMULATIONS

### Lomography Color Negative 400 / 800
- **Type**: Color Negative — Lomography
- **Character**: Oversaturated, punchy colors. Heavy grain. Strong vignette. Unpredictable color shifts — part of the charm. Cross-processing compatible for even wilder looks. Fun, experimental, lo-fi aesthetic. Toy camera feel with real film soul.
- **Prompt Keywords**: `Lomography film aesthetic, oversaturated punchy colors, heavy visible grain, strong vignette, unpredictable color shifts, lo-fi experimental character, toy camera analog soul`

### Lomography Redscale XR
- **Type**: Color Negative — Reversed Exposure
- **ISO**: 50-200
- **Character**: Film exposed from the wrong side, creating dominant red/orange/amber tones. Everything bathed in warm red-orange. Surreal, experimental look. Heavy grain. Unique color palette impossible to replicate any other way.
- **Prompt Keywords**: `Lomography Redscale film aesthetic, dominant red orange amber tones, warm red-shifted surreal palette, heavy grain, experimental lo-fi character, unique warm color impossible to replicate`

### Lomography Purple / LomoChrome Purple
- **Type**: Color Negative — Color Shifting
- **Character**: Greens shift to purple/magenta. Blues remain. Reds shift orange. Surreal, psychedelic color palette. Infrared film-like effect without actual IR. Landscapes become alien. Unique and instantly recognizable.
- **Prompt Keywords**: `LomoChrome Purple film aesthetic, greens shifted to purple magenta, surreal psychedelic color palette, infrared-like effect, alien landscape colors, unique recognizable color shifts`

### Agfa Vista 200 / 400 (Discontinued)
- **Type**: Color Negative
- **Character**: Warm, slightly retro color palette. Moderate grain. Reds and oranges emphasized. Greens slightly muted. Nostalgic warm character. European film look. Casual everyday photography with vintage warmth.
- **Prompt Keywords**: `Agfa Vista film aesthetic, warm retro color palette, moderate grain, emphasized reds and oranges, slightly muted greens, nostalgic European vintage warmth, casual everyday character`

### Agfa APX 100 / 400
- **Type**: Black & White Negative
- **Character**: APX 100: Very fine grain, smooth tones, low contrast, classic European B&W. APX 400: Medium grain, higher contrast, more dramatic. Both have a distinctive "European" B&W quality — less gritty than Tri-X, more structured than T-Max.
- **Prompt Keywords**: `Agfa APX black and white film, [100: fine grain smooth / 400: medium grain dramatic], European B&W quality, structured tonal character, distinctive continental monochrome aesthetic`

### Polaroid / Instax
- **Type**: Instant Film
- **Character**: Slightly desaturated, dreamy colors. Soft, low contrast. Warm color cast. Unique Polaroid border frame. Slight color shifts and imperfections. Nostalgic, intimate, one-of-a-kind feel. Skin tones slightly warmed and softened.
- **Prompt Keywords**: `Polaroid instant film aesthetic, slightly desaturated dreamy colors, soft low contrast, warm color cast, nostalgic intimate character, soft imperfect color rendering, vintage instant film look`

---

## SECTION 12: PROMPT ENGINEERING PATTERNS

### Pattern 1: Camera + Lens + Film Stock Stack
Combine camera body, specific lens, and film stock for maximum specificity:

```
[Subject], shot on [Camera] with [Lens] [focal]mm at [aperture], 
[Film Stock] color palette and grain, [specific optical effects], 
[lighting], [mood]
```

**Example**:
```
fashion editorial, model in trench coat on rainy street, 
shot on ARRI ALEXA 35 with Cooke S7/i 50mm T2.0, 
Kodak Portra 400 warm desaturated palette with fine grain, 
Cooke Look golden skin tones, creamy round bokeh from streetlights, 
soft rain-diffused backlight, moody cinematic atmosphere
```

### Pattern 2: Vintage Lens + Film Stock Nostalgia
Stack vintage lens aberrations with classic film stocks:

```
[Subject], shot with vintage [Lens] at [aperture], 
[Film Stock] aesthetic, pronounced [halation/bloom/swirl bokeh], 
[chromatic aberration], heavy vignette, [lighting], [era-appropriate mood]
```

**Example**:
```
candlelit portrait, intimate close-up, 
shot with vintage Canon K35 55mm T1.3, 
CineStill 800T red halation halos around candle flames, 
warm golden halation bloom, visible chromatic fringing at edges, 
tungsten warm practical lighting, heavy vignette, 
moody intimate cinematic atmosphere
```

### Pattern 3: Medium Format + Fine Art
Leverage medium format dimensionality with fine grain film:

```
[Subject], shot on [Medium Format Camera] with [Lens] at [aperture], 
medium format shallow depth of field, [Film Stock] fine grain aesthetic, 
[16-bit tonal transitions / HNCS skin rendering], [lighting], 
fine art editorial quality
```

**Example**:
```
beauty close-up, model with minimal makeup, 
shot on Hasselblad X2D with XCD 80mm f/1.9, 
medium format shallow depth of field, 
Fujifilm Pro 400H cool pastel color palette, 
HNCS luminous porcelain skin rendering, 16-bit tonal perfection, 
soft diffused studio light, fine art beauty editorial
```

### Pattern 4: Anamorphic + Cinema Film
Full widescreen cinematic treatment:

```
[Subject in wide composition], shot on [Camera] with [Anamorphic Lens] at [aperture],
[anamorphic ratio] widescreen, oval bokeh, horizontal [color] lens flare streaks,
[Cinema Film Stock] aesthetic, [grain level], [anamorphic edge characteristics],
[cinematic lighting], epic atmospheric
```

**Example**:
```
figure walking down neon-lit corridor, wide cinematic composition,
shot on ARRI ALEXA 35 with Cooke Anamorphic/i SF 40mm T2.3,
2.39:1 widescreen anamorphic format, oval elliptical bokeh from neon signs,
horizontal blue amber lens flare streaks across frame,
Kodak Vision3 500T gritty film grain, blue-shifted tungsten tones,
anamorphic edge softness, volumetric haze, epic sci-fi atmosphere
```

### Pattern 5: B&W Film + High Contrast Editorial
Black and white with maximum drama:

```
[Subject], black and white, [B&W Film Stock] aesthetic, 
[grain level and character], [contrast level], 
rich deep blacks, [highlight handling], 
[lighting style], [mood]
```

**Example**:
```
street portrait, weathered face in harsh shadows,
black and white, Kodak Tri-X 400 film grain, 
pronounced beautiful grain structure, high contrast, 
rich deep blacks, bright specular highlights,
hard directional side light with deep shadows,
gritty photojournalistic documentary atmosphere
```

### Pattern 6: Bleach Bypass / Desaturated Cinematic
Desaturated, high-contrast cinematic treatment:

```
[Subject], [Bleach Bypass / Eterna Bleach Bypass] aesthetic,
extremely desaturated near monochrome with [color] hints remaining,
very high contrast, metallic gritty texture, harsh shadows,
silver-toned highlights, [Film grain], [lighting], [dark mood]
```

---

## SECTION 13: OPTICAL EFFECTS GLOSSARY FOR PROMPTS

Use these specific descriptions in prompts instead of just naming the effect:

| Effect | Prompt Description |
|--------|-------------------|
| **Bokeh (creamy)** | "creamy smooth circular bokeh orbs with soft feathered edges" |
| **Bokeh (oval/anamorphic)** | "oval elliptical anamorphic bokeh stretched horizontally" |
| **Bokeh (swirl)** | "swirl bokeh with background rotating in circular pattern" |
| **Bokeh (soap bubble)** | "soap bubble bokeh with distinct outlined orb edges" |
| **Bokeh (cat's eye)** | "cat's eye mechanical bokeh at frame edges" |
| **Halation** | "warm halation glow bleeding from bright highlights into surrounding areas" |
| **Red Halation** | "distinctive red halation halos around light sources" (CineStill) |
| **Bloom** | "soft bloom glow spreading from overexposed highlights" |
| **Chromatic Aberration** | "visible color fringing at high-contrast edges, purple/green separation" |
| **Vignette (optical)** | "natural optical vignette darkening at frame edges" |
| **Vignette (heavy)** | "heavy dark vignette dramatically framing the subject" |
| **Shallow DOF** | "extremely shallow depth of field, razor-thin focus plane" |
| **Lens Flare (anamorphic)** | "horizontal blue amber lens flare streaks across frame" |
| **Lens Flare (classic)** | "warm lens flare with geometric ghost elements" |
| **Film Grain (fine)** | "ultra fine imperceptible grain texture" |
| **Film Grain (visible)** | "visible pleasant organic film grain texture" |
| **Film Grain (heavy)** | "heavy pronounced grain structure adding raw texture" |
| **Highlight Rolloff** | "soft filmic highlight rolloff, never clipping harshly" |
| **3D Pop** | "three-dimensional subject separation with dimensional pop" |
| **Micro-contrast** | "high micro-contrast giving tactile three-dimensional quality" |

---

## SECTION 14: QUICK REFERENCE COMBINATIONS

### For Fashion E-commerce (Clean, Professional)
```
Camera: Hasselblad X2D / Canon R5 II / Sony A1
Lens: Hasselblad XCD 80mm f/1.9 / Canon RF 85mm f/1.2 DS / Sony 35mm f/1.4 GM
Film: Kodak Portra 160 / Fujifilm Pro 400H
Style: Clean, luminous skin, soft bokeh, fine grain, pastel tones
```

### For Editorial Fashion (Mood, Character)
```
Camera: Leica M11 / Fujifilm X100VI / ARRI ALEXA 35
Lens: Noctilux 50mm f/0.95 / Summilux 35mm f/1.4 / Cooke S7/i
Film: Kodak Portra 400 / CineStill 800T / Fuji Classic Chrome
Style: Moody, glow, halation, visible grain, character
```

### For Cinematic Stills (Film Look)
```
Camera: ARRI ALEXA 35 / Sony VENICE 2 / Panavision DXL2
Lens: Cooke S7/i / Canon K35 / ARRI Signature / Anamorphic
Film: Kodak Vision3 500T / CineStill 800T / Fuji Eterna
Style: Deep blacks, film grain, halation, cinematic color, atmosphere
```

### For Fine Art / Gallery
```
Camera: Hasselblad X2D / Leica M11 / Fujifilm GFX 100 II
Lens: Zeiss Otus 55mm / Leica Noctilux / Hasselblad XCD
Film: Fujifilm Acros / Ilford Pan F 50 / Kodak T-Max
Style: Precise, pristine, extreme detail, smooth tones, gallery quality
```

### For Gritty / Documentary
```
Camera: Leica M11 / Fujifilm X100VI / Nikon Z8
Lens: Summilux 35mm f/1.4 / Helios 44-2 / Sigma 35mm Art
Film: Kodak Tri-X 400 / Ilford HP5 / Kodak Gold 200
Style: Heavy grain, high contrast, raw, authentic, photojournalistic
```

### For Night / Neon / Urban
```
Camera: Sony VENICE 2 / ARRI ALEXA 35 / Sony A1
Lens: Zeiss Supreme T1.5 / Voigtländer Nokton f/1.0 / Atlas Mercury Anamorphic
Film: CineStill 800T / Kodak Vision3 500T / Fuji Superia 400
Style: Red halation, blue tungsten cast, neon glow, deep blacks, urban grit
```
