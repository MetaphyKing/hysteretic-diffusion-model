# Hysteretic Diffusion Model

**DEAR & Hysteretic Diffusion 3D Emotional Topography & Intervention Lab**

Interactive WebGL visualization of affective manifolds projected from 40-dimensional EmotionalTextureAnalyzer (ETA) vectors onto a golden-ratio (φ) dodecahedral manifold (12 parent faces → 144 child micro-facets).

This repository hosts the production 3D lab for exploring score vector fields ∇ₓ log p(c | xₜ), ternary control modes (-1 / 0 / +1), longitudinal remanence (Z-axis), and topological rehabilitation protocols for pathological affective states.

## Live Demo

[Deployed on Vercel](https://hysteretic-diffusion-model.vercel.app) *(link will update after deployment)*

## Architecture Overview

- **Input**: 40D ETA vectors fused with physiological facial telemetry.
- **Projection**: 3D manifold — X (Valence: -1.0 cold/hostile → +1.0 warm/constructive), Y (Arousal/Intensity: 0–10), Z (Longitudinal Remanence / Baseline Stability: 0–6).
- **Manifold**: Golden-ratio dodecahedron with 144 localized facets.
- **Control**: Ternary hysteretic router (DEAR) with guided score ε̃θ(xₜ, t) = εθ + s · ∇ₓₜ log p(c | xₜ).
- **Score Smoothing**: Weight-decay regularization λ_wd (Loshchilov & Hutter 2017; Scarvelis et al. 2025) to create interpolation zones vs. razor cliffs.

### Stock Profiles

1. **Emotionally Healthy Individual** — Score-smoothed safe basin (+0.35, 3.80, Z≈3.85), organic +1→0 remanence lift, soft -1 S-curve recovery.
2. **Polymath / Creative Genius** — High tangential smoothing (λ_wd≈0.90), lowered inspiration threshold (Y=6.2), sustained figure-eight Eureka vortex (6.2–9.2, Z=5.1–5.8).
3. **Sociopathic Serial Killer (Predatory Anomaly)** — Empathy Repulsion Barrier at X=-0.15, unsmoothed cliffs (λ_wd=0.10), Cold Reptilian Void and Predatory Fixation Spike, zero affective remanence.

## Sociopathic Rehabilitation Protocols (M1–M6)

500-step longitudinal simulations of six conceived interventions:

| Protocol | Mechanism | Outcome |
|----------|-----------|---------|
| M1 Direct Affective Empathy | Raw +X warm gradients | **Fails** — repelled by X=-0.15 barrier |
| M2 Hard -1 Containment | Continuous damping | Stagnant hypo-arousal |
| M3 Raw Dopaminergic Novelty | +1 excitation, no smoothing | **Backfires** — predatory spikes |
| M4 Score-Cliff Annealing | λ_wd 0.10→0.85 + Langevin noise | Partial bridge |
| **M5 Orthogonal F06 Bridge** | Routes via D21 Certainty (92%) & Face F06 (Technical) | **Sustained Healthy (91% fit)** |
| **M6 Tri-Phasic Hysteretic Bridge** | Annealing + F06 + Ego-Syntonic Mastery | **Sustained Genius Flow (97% fit)** |

Winning path: Phase I cliff annealing → Phase II orthogonal Z-axis bridge through F06 (game-theoretic mastery, not affective guilt) → Phase III ego-syntonic remanence lock into Genius vortex.

## Features of the 3D Lab

- Real-time WebGL (Three.js) 3D viewport with 144-facet φ-mesh, score vectors, flow particles.
- Interactive 2D CIELAB radar + longitudinal B-H remanence curve.
- Six longitudinal swing generators (Organic, Creative Surge, Acute Stress, Burnout & Recovery, Rapid Oscillation, Resonance Pulse) across all profiles.
- Ternary control modes and intervention protocol selector (M0–M6).
- Live telemetry HUD (X/Y/Z, target fit %, parent face / child facet).

## Deployment

This is a static site. `vercel.json` enables clean URLs.

```bash
# Local preview
npx serve .

# Or deploy directly
npx vercel --prod
```

Repository is linked to Vercel for automatic production deploys on push to `main`.

## Sources & Grounding

- [Hysteretic Diffusion Gemini Notebook](https://notebook.google.com/notebook/dfb62cad-ab0a-4dc3-855b-7e19ed945d3b)
- [DEAR Architecture Drive Repository](https://drive.google.com/drive/folders/1EBlfz0LxYtnPH6dZg7gwc0-v3HGVBgGR)
- Scarvelis et al. (2025). *Demystifying Diffusion Creativity: Score Smoothing and the Interpolation Zone*. arXiv:2310.12395
- Loshchilov & Hutter (2017). *Decoupled Weight Decay Regularization*. arXiv:1711.05101

## License

MIT — Research & demonstration artifact for the DEAR / Hysteretic Diffusion framework.

---

*Built as part of the Metaphy LLC / HMSS research program. One family, one love.*