# OpenClaw NovelAI Opus Free

An Opus-focused OpenClaw Skill for NovelAI workflows that must stay within **zero NovelAI Image Anlas** while allowing tested-free image editing operations.

This variant keeps story writing, prompt planning, account queries, cost estimation, tag suggestions, and local records. It allows single text-to-image, img2img, inpainting, pre-encoded Vibe generation, annotation, and selected Director tools only when the active Opus account and current gates allow them.

It blocks Vibe encoding, background removal, Precise Reference, Enhance, dedicated upscaling, batches, high-resolution generation, more than 28 Steps, and any paid fallback.

## Important distinction

Zero Anlas is not zero usage:

- Opus V5 free images consume the separate V5 Usage Limit;
- A zero-Anlas result is account- and parameter-sensitive, not a permanent provider guarantee;
- text generation through a third-party OpenClaw provider may have its own price;
- network, hosting, or other model costs are outside this Skill.

## Files

- `SKILL.md` — the enforceable orchestration policy;
- `README.zh-CN.md` — Chinese overview;
- `docs/COSTS-AND-QUOTAS.md` — English cost boundary;
- `docs/费用与额度说明.md` — Chinese cost boundary;
- `LICENSE` — license for standalone distribution.

The strict `openclaw-novelai-free` variant remains available for users who want only the narrowest zero-estimate image path. The advanced Skill remains in the parent project. These variants should not replace each other silently.
