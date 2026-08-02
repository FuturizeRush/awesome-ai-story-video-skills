# Awesome AI Story & Learning Video Skills

A bilingual, security-aware collection for turning ideas, fiction, and teaching material into motion comics or explainer videos. The list separates agent Skills, libraries, and full applications so a GitHub repository is never presented as a plug-and-play Skill when it is not one.

> Metadata snapshot: 2026-08-02. Stars are popularity signals, not security guarantees.

## Selection policy

- Default popularity gate: at least 1,000 GitHub stars.
- A recognizable open-source license is required for recommendations.
- Sponsorship, paid API promotion, and commercial restrictions must be disclosed. Integrations must remain provider-neutral.
- Review install hooks, process execution, network access, default credentials, service bindings, secret storage, model deserialization, and auto-update paths.
- Pin an exact commit or package version and keep provenance for generated assets.
- Installation requests and audit candidates are not automatically awesome-list recommendations.

## Core stack

| Project | Kind | Stars | License | Why it belongs |
|---|---|---:|---|---|
| [Jellyfish](https://github.com/Forget-C/Jellyfish) | Project/asset workflow app | 5,818 | Apache-2.0 | Story, character, scene, shot, asset, and generation-task tracking. Do not confuse project progress with native video completion. |
| [HyperFrames](https://github.com/heygen-com/hyperframes) | Video framework + Skills | 39,120 | Apache-2.0 | Deterministic HTML animation, preview, strict checks, and rendering. |
| [Anime.js](https://github.com/juliangarnier/anime) | Animation library | 71,689 | MIT | Timeline-friendly DOM, SVG, and JavaScript animation. |
| [Three.js](https://github.com/mrdoob/three.js) | 3D library | 114,170 | MIT | Procedural scenes, diagrams, props, cameras, and real-time 3D. |
| [img2threejs](https://github.com/img2threejs/img2threejs) | Agent Skill | 9,006 | Apache-2.0 | Quality-gated reference-image to procedural Three.js reconstruction. |

## Recommended pipeline

```text
idea / lesson / manuscript
        ↓
provider-neutral bilingual writing contract
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

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Security claims need evidence; “many stars” or “tests pass” is not enough.

## License

MIT. Upstream projects retain their own licenses and trademarks.
