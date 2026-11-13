# Deep Mix-Match: Hard Thinking on Lost Tech Revival

## Judging Reality Check (20% each)
- **Potential Impact**: Must solve a real problem for a real audience (not just cool demo).
- **Tech Implementation**: Deep, varied Kiro usage (specs, steering, hooks, MCP, Crew, property tests).
- **Design**: Complete product experience, polished, intentional.
- **Innovation**: Novel combination of unusual tech / public resources.
- **Presentation**: Clear end-to-end video + memorable pitch.

## Highest-Leverage Ideas (basic yet smart)

### 1. Sloot Reborn — Generative Extreme Compression (Resurrection)
**Core insight**: Modern diffusion/VAE research already achieves extreme ratios (0.02 bpp, 35× compression) by encoding only keyframes/semantics and generating the rest. This is the *spirit* of Sloot (tiny key → full reconstruction) made real and legal.

**Build**:
- Upload short clip or image sequence.
- Encode only 1-3 keyframes + semantic caption/seed (tiny payload).
- Decoder uses a lightweight generative model (or even a simple frame interpolator + VAE) to reconstruct.
- Side-by-side original vs reconstructed + real ratio + LPIPS/perceptual note.
- Historical Sloot card + citation to recent papers.

**Why it wins**: Clear historical hook, visual wow, measurable extreme ratio, real research backing. Easy to demo in video.

### 2. Lamarr Link — Adaptive Frequency-Hopping Agent Mesh (Frankenstein)
**Core insight**: Frequency hopping is foundational (Wi-Fi/Bluetooth) but was "too early." Pair it with modern multi-agent systems that need secure, anti-jamming coordination.

**Build**:
- Visual canvas of nodes hopping across frequency bands (deterministic seed).
- Agents can only exchange messages when on the same frequency.
- Toggleable jammer that forces adaptive hop sequence changes.
- Optional: simple task (e.g., collaborative puzzle or consensus) that only succeeds if hops stay synchronized.
- Patent reference + brief history.

**Why it wins**: Beautiful visualization, clear "stitching" of 1942 patent + 2026 agents, interactive, educational.

### 3. Quibi Ghost — Short-Form Generative Video from Tiny Seeds (Frankenstein or Resurrection)
**Mix**: Quibi's failed short vertical video bet + Sloot-style generative compression.
- Users generate or upload 10-15 second vertical clips.
- System produces a tiny seed; reconstructs a perceptually good version.
- Feels like "reviving" the short-form premium idea with AI that actually makes extreme compression useful.

### 4. NecroTemplate (Skeleton Crew)
Shared packages:
- `agent-core`: hop scheduler + message passing.
- `ui`: side-by-side viewer, seed display, hop canvas.
- Two apps:
  1. Compression playground (Sloot/Quibi style).
  2. Hop visualizer (Lamarr style).
Proves the skeleton is reusable.

### 5. Haunted Terminal (Costume Contest)
Skin any of the above with CRT/spectral aesthetics that *improve* readability (high contrast green/amber on black, scanlines that don't hurt, reduced-motion support). The theme enhances the "ancient tech revived" feeling.

## Recommended Priority
1. Finish Sloot Reborn demo with real (even tiny) generative step.
2. Build Lamarr visualizer (pure TS, high visual impact).
3. Package both under NecroTemplate for Skeleton Crew.
4. Apply haunted skin to the strongest one for Costume Contest.

## Kiro Strategy for High Scores
- Heavy use of `.kiro/steering/` (product, tech, structure).
- Specs in EARS style for key features.
- Hooks that run tests or lint on save.
- Document every Kiro feature used in the submission write-up.
- Record a clean end-to-end demo video early.
