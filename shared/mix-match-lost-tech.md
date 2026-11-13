# Mix-Match Ideas: Lost Patents + Failed Startups + Forgotten Tech

## Core Combos (basic yet smart)

### 1. Sloot + Quibi (Resurrection / Frankenstein)
- **Lost**: Sloot's mythical 8KB movie compression (never verified).
- **Failed**: Quibi ($1.75B short-form mobile video, dead in 2020).
- **Revival**: Neural generative compression that produces tiny seeds for short vertical clips. Reconstruct on-device or via generative decoder. Side-by-side original vs AI reconstruction. Perfect for demo.

### 2. Lamarr Frequency Hopping + Humane AI Pin (Frankenstein)
- **Lost/Too early**: 1942 frequency-hopping patent (now Wi-Fi/Bluetooth foundation).
- **Failed**: Humane AI Pin (wearable AI, servers shut down, devices bricked).
- **Revival**: Software simulation of an "AI Pin" mesh where agents hop frequencies to communicate securely. Visualizer shows hop pattern + message only when synced. Adaptive jamming recovery. No hardware needed.

### 3. Neural Compression + Dead Media Libraries
- Use generative models to "reconstruct" low-quality or partial media from tiny seeds (spirit of Sloot).
- Showcase with public domain or synthetic clips.

### 4. Skeleton Crew Template
- Shared agent runner + UI primitives.
- App 1: Compression playground (Sloot).
- App 2: Hop visualizer (Lamarr).
- Proves the skeleton works for both.

### 5. Costume Contest Skin
- Wrap any of the above in a haunted terminal / CRT / spectral aesthetic.
- Functional: the spooky UI makes the compression seed or hop visualization more memorable and readable.

## Recommended Build Order (basic yet smart)
1. Next.js + Tailwind demo with fake extreme ratio + side-by-side placeholder.
2. Replace fake seed with a tiny real autoencoder or Hugging Face VAE.
3. Add hop protocol simulator in pure TS.
4. Polish UI and document Kiro usage in `.kiro/`.
5. Deploy to Vercel.

## Tech Stack (shared)
- Next.js 15 App Router + TypeScript + Tailwind
- Optional Python/FastAPI backend for real ML
- Canvas or SVG for hop visualizer
- Framer Motion for costume animations
