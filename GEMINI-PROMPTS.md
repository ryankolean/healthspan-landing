# Healthspan Landing Page — Gemini Image Prompts

Paste each prompt into gemini.google.com. Optionally attach reference photos of the current landing page for style consistency.

---

## 1. Hero Background — Abstract Health Data Visualization

```
Create a wide-format (1920x1080) abstract digital artwork for a dark-themed health technology website hero section. The composition should evoke the feeling of health data flowing and connecting — think abstract representations of heartbeat waveforms, DNA helixes, and neural pathways rendered as elegant golden-amber light traces on a very dark forest green/black background (#0C0F0A). The aesthetic is premium, editorial, scientific — NOT generic health app imagery. No people, no stock photo feel. The golden traces should feel like bioluminescent data streams. Subtle green (#4ADE80) accent glows scattered throughout. The overall feel should be like looking at a beautiful data visualization of a living system. Leave the left 40% relatively clear/dark for text overlay. High contrast, cinematic lighting, ultra-detailed. 16:9 aspect ratio.
```

## 2. Dashboard Section — Lifestyle Context Shot

```
Create a moody, atmospheric photograph-style image of a modern home office desk at dawn. On the desk: an open laptop showing a dark-themed health dashboard with green and amber data visualizations (blurred/abstract, not readable), an Oura Ring sitting on the desk surface catching morning light, and a cup of espresso. The scene is lit by soft warm window light from the left. Background is softly out of focus. The color palette emphasizes deep shadows, warm amber tones, and touches of green from the laptop screen. No people visible. The mood should convey: someone who takes their health data seriously as part of their morning routine. Shot from slightly above at an angle, like an editorial lifestyle photograph. Ultra-realistic, shallow depth of field.
```

## 3. Open Source Section — Community/Code Aesthetic

```
Create a wide-format (1600x900) abstract digital artwork representing open-source collaboration on a health platform. Visualize it as interconnected nodes forming a network structure — some nodes glow amber/gold (#C8A84E), others glow green (#4ADE80) — on a very dark background (#0C0F0A). The nodes should subtly suggest health-related shapes: a heart rhythm line connecting some nodes, circular rings (like an Oura Ring) around others, small DNA-like spirals in the connections. The overall feeling should be: a living ecosystem of contributors building something together. No text, no people, no literal code. Premium, editorial quality. The composition should be horizontally balanced for use as a section background.
```

## 4. Problem Section — Fragmentation Visual

```
Create a conceptual illustration showing medical data fragmentation. Visualize it as a grid of glass-like translucent cards/panels floating in dark space, each containing abstract representations of different health data types — a heartbeat line on one, a bar chart on another, a circular gauge on a third, lab values on a fourth. The panels are disconnected, scattered at different angles and depths, with visible gaps between them. Some panels have a subtle red tint suggesting inaccessibility. The overall color palette is dark (#0C0F0A background) with the panels having subtle borders and glowing edges. One panel in the center glows amber/gold, suggesting the solution of unification. No text should be readable. Ultra-clean, minimal, editorial style. Wide format 1600x600.
```

---

## Usage Notes

- Save images to `healthspan-landing/images/` directory
- Reference in HTML via `<img src="images/hero-bg.webp" />` or as CSS `background-image`
- Convert to WebP for optimal file size before committing
- Hero image works best as a `position: absolute` background with `opacity: 0.15-0.25` behind the hero text
- Dashboard lifestyle shot works as a standalone image next to or above the dashboard mockup
- Open source and problem section images work as subtle section backgrounds at low opacity
