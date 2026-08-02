# Awesome AI Story & Learning Video Skills

A bilingual, security-aware collection for turning ideas, fiction, and teaching material into motion comics or explainer videos. The list separates agent Skills, libraries, and full applications so a GitHub repository is never presented as a plug-and-play Skill when it is not one.

> Metadata snapshot: 2026-08-02. Stars are popularity signals, not security guarantees.

## Selection policy

- Default popularity gate: at least 1,000 GitHub stars.
- A recognizable open-source license is required for recommendations.
- Sponsorship, paid API promotion, and commercial restrictions must be disclosed. Integrations must remain provider-neutral.
- Review install hooks, process execution, network access, default credentials, service bindings, secret storage, model deserialization, and auto-update paths.
- Pin an exact commit or package version and keep provenance for generated assets.
- A lower-star exception must be explicitly approved and labeled.

## Core stack

| Project | Kind | Stars | License | Why it belongs |
|---|---|---:|---|---|
| [Jellyfish](https://github.com/Forget-C/Jellyfish) | Project/asset workflow app | 5,818 | Apache-2.0 | Story, character, scene, shot, asset, and generation-task tracking. Do not confuse project progress with native video completion. |
| [HyperFrames](https://github.com/heygen-com/hyperframes) | Video framework + Skills | 39,120 | Apache-2.0 | Deterministic HTML animation, preview, strict checks, and rendering. |
| [Anime.js](https://github.com/juliangarnier/anime) | Animation library | 71,689 | MIT | Timeline-friendly DOM, SVG, and JavaScript animation. |
| [Three.js](https://github.com/mrdoob/three.js) | 3D library | 114,170 | MIT | Procedural scenes, diagrams, props, cameras, and real-time 3D. |
| [img2threejs](https://github.com/img2threejs/img2threejs) | Agent Skill | 9,006 | Apache-2.0 | Quality-gated reference-image to procedural Three.js reconstruction. |
| [InkOS](https://github.com/Narcooo/inkos) | Bilingual fiction app + Skill | 8,613 | AGPL-3.0-only | Mature Chinese/English long-form workflow. Its README contains a Kimi sponsorship banner; keep integrations provider-neutral and never reproduce sponsor copy automatically. |
| [boring-video-studio](https://github.com/sugarforever/boring-video-studio) | Video production Skill | 58 | MIT | **User-approved star exception.** Useful HyperFrames production patterns; creator-specific branding and promotion blocks must remain opt-in. |

## Full applications, not agent Skills

| Project | Stars | License | Review note |
|---|---:|---|---|
| [MuMuAINovel](https://github.com/xiamuceer-j/MuMuAINovel) | 2,806 | GPL-3.0 | Strong Chinese novel app. Upstream Compose exposes ports broadly and ships weak fallback passwords; use a loopback-only, required-secret override before startup. |
| [AI Novel Writing Assistant](https://github.com/ExplosiveCoderflome/AI-Novel-Writing-Assistant) | 2,211 | AGPL-3.0-only plus commercial-authorization notice | Broad novel/comic workspace. Treat the extra service-use notice as a licensing review item before commercial hosting. |

## Audited but not selected

- [AI-Writer](https://github.com/BlinkDL/AI-Writer) — 3,824★, Apache-2.0. The repository calls its own workflow and models obsolete, and loads user-downloaded `.pth` checkpoints with `torch.load`; do not execute untrusted checkpoints.
- [chinese-novelist-skill](https://github.com/PenglongHuang/chinese-novelist-skill) — 2,541★. No detected repository license and explicit paid API credit promotion; not installed.
- [story-skills](https://github.com/danjdewhurst/story-skills) — 132★, MIT. Thoughtful English story skills, but below the requested 1,000★ gate.
- [creative-writing-skills](https://github.com/haowjy/creative-writing-skills) — 374★, Apache-2.0. Promising, but below the gate.
- [novel-creator-skill](https://github.com/leenbj/novel-creator-skill) — 561★ with no detected license; below the gate and not redistributable as a recommendation.

## Recommended pipeline

```text
idea / lesson / manuscript
        ↓
InkOS or provider-neutral bilingual writing contract
        ↓
story bible → script → storyboard → asset manifest
        ↓
img2threejs + Three.js + Anime.js
        ↓
Jellyfish project / shot / asset registration
        ↓
HyperFrames strict check → human preview approval → render
        ↓
ffprobe + full decode + digest + Jellyfish readback
```

Use the local `story-to-learning-video` Skill for an operational version of this pipeline. It forbids automatic sponsor/affiliate copy, keeps services on loopback, and distinguishes external HyperFrames completion from Jellyfish-native generation.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Security claims need evidence; “many stars” or “tests pass” is not enough.

## License

MIT. Upstream projects retain their own licenses and trademarks.
