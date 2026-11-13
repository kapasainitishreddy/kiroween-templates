# Tech Farming Strategy for Kiroween 2026

## What is Tech Farming?
Systematically harvesting abandoned patents, failed startups, and forgotten technologies, then reviving their core insight with modern AI. Not copying, but extracting the *spirit* and making it real, legal, and useful.

## Core Farm Plot 1: Sloot → Generative Extreme Compression
**Original**: Claimed 8KB movie key (mythical, never verified).
**Modern realization**: Diffusion / VAE models that encode only keyframes or semantic cues, then generate the rest.
- Research shows 0.02 bpp and 35× compression with high perceptual quality.
- Demo: Upload → tiny seed → side-by-side reconstruction + real ratio.
- Category: Resurrection (or Frankenstein with Quibi short-form).

## Core Farm Plot 2: Lamarr Frequency Hopping → Agent Mesh
**Original**: 1942 patent (US 2,292,387) for jam-resistant torpedo guidance using player-piano synchronized hopping. Navy ignored it. Later foundational to Bluetooth adaptive frequency hopping and spread-spectrum techniques.
**Modern realization**: Visual multi-agent system where agents only communicate when on the same frequency. Adaptive hopping under jamming.
- Pure TypeScript visualizer already scaffolded.
- Category: Frankenstein.

## Additional Farm Plots (mix-and-match)

### Quibi Ghost
Failed short-form premium video ($1.75B) + generative compression. Vertical clips from tiny seeds.

### Humane AI Pin Soft Simulation
Wearable AI that got bricked when servers died. Software mesh of agents that hop frequencies to stay alive without a central server.

### Skeleton Crew NecroTemplate
Shared packages (`agent-core`, `ui`, `compression`) demonstrated with:
1. Compression playground
2. Hop visualizer

### Costume Contest Skin
Haunted CRT / spectral terminal that improves readability of the ancient-tech-revived demos.

## Farming Process (how to harvest more)
1. Identify core insight of the dead tech (not the implementation).
2. Find the modern analog that actually works (diffusion, adaptive hopping, on-device agents).
3. Build the smallest demo that shows the insight + side-by-side or visual proof.
4. Document historical connection clearly in the UI.
5. Use Kiro heavily: steering, specs (EARS), hooks, MCP.

## Diffusion Reconstruction (how it works simply)
1. Encode only a few keyframes or a semantic description (tiny payload).
2. At the decoder, a conditional diffusion or VAE model "hallucinates" the missing frames using the keyframes as guidance.
3. When quality drops, encode another keyframe and continue.
4. Result: extreme ratio with perceptual quality that traditional codecs can't match at the same bitrate.

## Wi-Fi / Bluetooth History Notes
- Lamarr + Antheil 1942 patent used mechanical player-piano rolls for 88 frequencies.
- Navy rejected it as impractical.
- Electronic versions appeared in the 1950s–60s (Cuban Missile Crisis).
- Bluetooth uses adaptive frequency hopping (up to 1600 hops/sec) in the 2.4 GHz band.
- Wi-Fi early versions used frequency hopping; later moved to OFDM for higher bandwidth, but the spread-spectrum idea remains foundational.

## Priority Order
1. Polish Sloot Reborn demo (real ratio + reconstruction visualization).
2. Polish Lamarr Link (message passing only on matching frequency).
3. Package both under NecroTemplate for Skeleton Crew.
4. Apply haunted skin for Costume Contest if time remains.

## Kiro Farming Tactics
- Keep `.kiro/steering/` always included.
- Write failure cases into specs first.
- Use hooks for lint/tests on save.
- Record end-to-end demo video early.
