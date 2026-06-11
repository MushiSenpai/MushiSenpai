# Hi, I'm Mushi 👋

🌐 **[theinvalid.me](https://theinvalid.me)** — portfolio, resume, and the failure log (new post weekly).

**AI infrastructure engineer — I spec, direct LLMs, and verify.** I build and operate sovereign, self-hosted AI systems: the planning, architecture, debugging direction, and operations are mine; the code is written by LLMs under my direction. B.E. in Computer Science. **Open to freelance and full-time work.**

## What I've built (and operate daily)

One RTX 5090 workstation running three integrated stacks — every design decision, failure, and fix documented publicly:

### 🧠 [mushishi-sovereign-ai-stack](https://github.com/MushiSenpai/mushishi-sovereign-ai-stack)
Multimodal LLM serving (vLLM + Nemotron NVFP4, 275 tok/s, 180K context on 32GB) with **routing-enforced privacy tiers** — three fallback chains where "this data never touches a cloud API" is guaranteed by architecture, not policy. Includes the full Decision Log: why TensorRT-LLM lost six hours and vLLM won.

### 🎬 [mushishi-creative-stack](https://github.com/MushiSenpai/mushishi-creative-stack)
Local video production: FLUX.2 / Wan 2.2 / HunyuanVideo generation, VOID object removal (takes the object *and its reflection*), SAM3+VACE masked editing, RIFE 60fps + SeedVR2 4K finishing. Driven by a forensic-analysis bridge so diffusion models obey specifications instead of hallucinating.

### 🎙️ [mushishi-audio-stack](https://github.com/MushiSenpai/mushishi-audio-stack)
Fully local voice cloning, TTS, lip-sync avatars (3 quality tiers), music generation, and auto-dubbing — job-queue architecture, all MIT/Apache-2.0 models, 25+ documented install lessons.

## What the infrastructure produces

### 📖 [comic-manga-narrator](https://github.com/MushiSenpai/comic-manga-narrator)
A comic page goes in; a dramatized video comes out — panel detection, cloned character voices acting the dialogue, narrator on captions, Ken Burns + 2.5D parallax camera. Built entirely on the three stacks above: the proof the infrastructure ships products.

### 🍃 [komorebi](https://github.com/MushiSenpai/komorebi)
A Studio Ghibli-inspired productivity suite in Flutter — tasks, kanban, calendar, notes, pomodoro, and a physics tower-stacking break game with online leaderboards. Local-first SQLite; spec-driven with a documented upgrade path per feature.

## How I work

```
discuss (multi-LLM) → consolidate → spec → execute (LLM-directed) → verify (gates) → operate
```

- **Spec-driven:** every phase has a written spec and a verification gate; snapshots before changes
- **Honest by default:** benchmark tables ship with empty cells and fill in public, weekly; failures are documented next to successes
- **Sovereignty-first:** local-first routing, Tailscale-only exposure, default-deny firewall, monitored backups

## Currently

- 📊 Publishing weekly benchmarks across all three stacks
- ✍️ Writing up the build: the TRT-LLM→vLLM pivot, the SAM3 video-mode fix, the audio stack's 25 lessons
- 🌐 Portfolio site + case studies — coming soon

📫 Reach me: GitHub issues on any repo, or the contact on my profile.
