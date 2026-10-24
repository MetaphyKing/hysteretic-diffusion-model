# Hysteretic Diffusion Model

**DEAR & Hysteretic Diffusion 3D Emotional Topography & Intervention Lab**

Interactive WebGL visualization and quantitative simulation environment for mapping, analyzing, and intervening on affective manifolds. Projects 40-dimensional EmotionalTextureAnalyzer (ETA) vectors onto a golden-ratio (φ) dodecahedral manifold with score vector fields, hysteretic remanence dynamics, and topological bridging protocols.

## Overview

Within the [DEAR (Dynamic Emotional Adjustments and Responses)](https://drive.google.com/drive/folders/1EBlfz0LxYtnPH6dZg7gwc0-v3HGVBgGR) and [Hysteretic Diffusion](https://notebook.google.com/notebook/dfb62cad-ab0a-4dc3-855b-7e19ed945d3b) architecture, emotional states are represented as 40D vectors fused with physiological telemetry and projected onto a 3D golden-ratio dodecahedron (12 parent archetype faces, 144 child micro-facets).

**Coordinate System:**
- **X**: Emotional Valence (−1.0 hostile/cold → +1.0 warm/constructive)
- **Y**: Arousal / Excitation Intensity (0.0 dormant → 10.0 peak)
- **Z**: Longitudinal Remanence / Baseline Stability (0.0 → 6.0)

### Stock Profiles
1. **Emotionally Healthy Individual** — Score-smoothed safe basin at (+0.35, 3.80, Z=3.85) with organic upward excitation and gentle de-escalation loops.
2. **Polymath / Creative Genius** — Sustained figure-eight Eureka vortex across the upper-right inspiration band (Y=6.20–9.20, Z=5.10–5.80) with maximized tangential score smoothing.
3. **Sociopathic Serial Killer (Predatory Anomaly)** — Characterized by three pathological barriers: Empathy Repulsion Wall (X=−0.15), unsmoothed memorization cliffs (λ_wd=0.10), and zero affective remanence.

## Intervention Protocols

Six conceived methods (M1–M6) were simulated over 500 longitudinal steps to elevate the sociopathic manifold to healthy or genius levels:

| Protocol | Outcome | Steady-State (X, Y, Z) | +Valence Residency | Relapses |
|----------|---------|------------------------|--------------------|----------|
| **M1** Direct Affective Empathy Push | Fails (repelled) | (−0.19, 1.77, 0.99) | 0.0% | 0 |
| **M2** Monotonic −1 Hard Containment | Stagnant | (−0.21, 2.05, 1.60) | 0.0% | 0 |
| **M3** Raw Dopaminergic Novelty Hijack | Backfires | (−0.89, 5.99, 1.07) | 0.0% | 152 |
| **M4** Synthetic Score-Cliff Annealing | Partial bridge | (+0.14, 3.64, 2.51) | 39.6% | 0 |
| **M5** Orthogonal F06 Game-Theoretic Bridge | **Sustained Healthy (91%)** | (+0.48, 7.21, 4.50) | 78.0% | 0 |
| **M6** Tri-Phasic Hysteretic Bridge | **Sustained Genius (97%)** | (+0.70, 8.19, 5.48) | 79.2% | 0 |

**Winning approach (M5/M6):** Orthogonal routing through intact high-certainty clusters (D21–D25 = 92%) and Dodecahedral Face F06 (Technical & Strategic Focus), combined with score-cliff annealing (λ_wd → 0.92) and ego-syntonic mastery remanence.

## Features of the Interactive Lab

- Real-time 3D WebGL visualization of the φ-dodecahedral manifold and score vector field ∇_x log p(c | x_t)
- Interactive stock profile selector and 6-mode longitudinal swing generator (Organic, Creative Surge, Acute Stress, Burnout & Recovery, Rapid Oscillation, Resonance Pulse)
- Sociopathic Bridging Lab with live protocol switching (M1–M6)
- 2D CIELAB radar projection and longitudinal B-H remanence curve
- Live 40D ETA cluster telemetry and convergence metrics
- Layer toggles for score vectors, dodecahedral mesh, and flow particles

## Deployment

This repository is configured for instant Vercel deployment as a static site.

```bash
# Clone and deploy
git clone https://github.com/MetaphyKing/hysteretic-diffusion-model.git
cd hysteretic-diffusion-model
npx vercel deploy --prod
```

**Live Demo:** Deployed via Vercel (see project settings).

## Technical References

- Scarvelis et al. (2025). *Demystifying Diffusion Creativity: Score Smoothing and the Interpolation Zone*. [arXiv:2310.12395](https://arxiv.org/pdf/2310.12395)
- Loshchilov & Hutter (2017). *Decoupled Weight Decay Regularization*. [arXiv:1711.05101](https://arxiv.org/abs/1711.05101)
- DEAR Architecture Drive Repository
- Hysteretic Diffusion Gemini Notebook

## License

Research and educational use. All rights reserved by Metaphy LLC.

---

*Developed as part of the Metaphy LLC research initiative into topological models of affective dynamics and ethical AI intervention frameworks.*
