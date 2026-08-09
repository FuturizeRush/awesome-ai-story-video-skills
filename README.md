# Awesome AI Story, Learning Video & Creative Content Tools

A curated list of open-source tools and agent skills for storytelling, motion comics, learning videos, UGC, digital humans, and the visual or marketing work that supports them.

The groups describe each project's primary creative capability. Many entries are complete applications or skill collections that work independently; others specialize in a task such as avatar animation or lip sync. The list does not imply a built-in integration between projects.

## Story, Motion Comics & Narrative Production

- [AI Comic Builder](https://github.com/LingyiChen-AI/AIComicBuilder) — Turn scripts into character designs, storyboards, generated clips, subtitles, and assembled motion-comic videos. Requires configured image and video providers.
- [Jellyfish](https://github.com/Forget-C/Jellyfish) — Plan stories, characters, scenes, shots, and media assets in one production workspace.

## Agentic & End-to-End Video Production

- [ArcReel](https://github.com/ArcReel/ArcReel) — Run a self-hosted workspace for novels, scripts, product materials, reference assets, storyboards, generated clips, narration, final videos, and Jianying editing drafts. Media generation requires configured providers; modified user interfaces must preserve its AGPL Section 7 attribution notice.
- [MoneyPrinterTurbo](https://github.com/harry0703/MoneyPrinterTurbo) — Create AI-assisted faceless short videos from a topic or script, with narration, captions, music, and stock-media workflows.
- [OpenMontage](https://github.com/calesthio/OpenMontage) — Let a coding agent handle research, scripts, assets, narration, subtitles, approval gates, quality checks, and final rendering across complete production pipelines. Its core is AGPL-3.0; external providers and rendering dependencies retain their own terms.
- [OpenShorts](https://github.com/mutonby/openshorts) — Assemble AI-actor UGC videos from a product website, script, actor, voice, generated clips, B-roll, captions, and social-ready exports. The core app is MIT; its `cloud/` directory has a separate commercial license, and the workflow needs third-party APIs.
- [ViMax](https://github.com/HKUDS/ViMax) — Orchestrate an idea, screenplay, or novel into a multi-scene video with storyboards, continuity tracking, and reference-image cameos. Requires configured LLM, image, and video providers.

## Generative Media Orchestration

- [ComfyUI](https://github.com/Comfy-Org/ComfyUI) — Build reusable node-graph workflows for image, video, audio, 3D, and text generation with local models or optional API nodes. Model weights and API-node terms vary.
- [Generative Media Skills](https://github.com/SamurAIGPT/Generative-Media-Skills) — Agent-ready UGC and product-video workflow recipes. Runs through the external MuAPI CLI and its model providers, rather than as a local video model.

## Learning Videos & Programmatic Motion

- [html-video](https://github.com/nexu-io/html-video) — Turn a prompt, article, or GitHub repository into a storyboard and local MP4 with a coding agent and HyperFrames. Other rendering adapters remain on its roadmap.
- [HyperFrames](https://github.com/heygen-com/hyperframes) — Create and render videos with HTML, CSS, and JavaScript.
- [Manim Community](https://github.com/ManimCommunity/manim) — Program precise mathematical, scientific, and explanatory animations in Python.
- [Manim Skills](https://github.com/adithya-s-k/manim_skill) — Give coding agents tested patterns and examples for Manim Community and ManimGL. The corresponding Manim runtime is still required.
- [Motion Canvas](https://github.com/motion-canvas/motion-canvas) — Program informative vector animations in TypeScript with real-time preview and voice-over synchronization.
- [Slidev](https://github.com/slidevjs/slidev) — Create animated Markdown and Vue presentations with presenter mode, camera view, annotations, and browser recording.

## Editing, Repurposing & Localization

- [Cap](https://github.com/CapSoftware/Cap) — Record screen, camera, and microphone input, then edit, caption, export, share, or self-host the result. Most code is AGPL-3.0; selected capture crates are MIT.
- [FunClip](https://github.com/modelscope/FunClip) — Transcribe local videos, select text or speakers, create clips, and export subtitles through a local UI or CLI. LLM-based selection is optional, and downloaded model weights retain their own licenses.
- [KrillinAI](https://github.com/krillinai/KrillinAI) — Localize videos through download or local ingest, ASR, subtitle translation, TTS dubbing, cover generation, and horizontal or vertical rendering. Local and hosted providers are both supported.

## Digital Humans, Avatar Animation & Voice

- [CosyVoice](https://github.com/QwenAudio/CosyVoice) — Run multilingual TTS and cross-language zero-shot voice cloning through a Web UI, API, gRPC, or Docker deployment. Review the applicable model-card terms before using downloaded weights.
- [EchoMimicV2](https://github.com/antgroup/echomimic_v2) — Generate audio-driven semi-body human animation for an avatar shot within a larger UGC workflow.
- [LatentSync](https://github.com/bytedance/LatentSync) — Synchronize supplied speech audio with an existing face video as a finishing step.
- [LiveTalking](https://github.com/lipku/LiveTalking) — Self-host a digital-human workflow with custom avatars, TTS, lip sync, and APIs for batch-script video recording. Avatar backends and downloaded models retain their own licenses.
- [LongCat-Video](https://github.com/meituan-longcat/LongCat-Video) — Run text-to-video, image-to-video, video continuation, and audio-driven single- or multi-character avatar generation. The 13.6B models require substantial GPU resources.
- [OpenAvatarChat](https://github.com/HumanAIGC-Engineering/OpenAvatarChat) — Compose real-time digital humans with interchangeable ASR, LLM, TTS, and avatar backends. Provider, model-license, and GPU requirements vary by preset.
- [OpenTalking](https://github.com/datascale-ai/opentalking) — Compose interactive digital humans from local or remote avatar, speech, and LLM backends. Backend licenses and hardware requirements vary.

## Design & Marketing for Creative Production

- [Claude Skills](https://github.com/alirezarezvani/claude-skills) — Broad multi-agent skill library that includes marketing, content-production, research, and video-oriented workflows.
- [Marketing Skills](https://github.com/coreyhaines31/marketingskills) — Agent skills for product positioning, copy, image direction, video briefs, launch planning, and related marketing work.
- [Open Design](https://github.com/nexu-io/open-design) — Local-first agent design environment with product-image, presentation, and media workflows; its ecommerce workflow creates reference-faithful main, feature, and lifestyle image sets.

## Commerce-Adjacent Content Workflows

- [eCommerce Skills](https://github.com/nexscope-ai/eCommerce-Skills) — E-commerce planning skills including product content, marketplace listings, video marketing, and shoppable-video guidance. This entry is an explicit curator exception to the star guideline.

## Animation & 3D

- [Anime.js](https://github.com/juliangarnier/anime) — Animate JavaScript, CSS, SVG, and DOM properties.
- [img2threejs](https://github.com/img2threejs/img2threejs) — Rebuild reference images as procedural Three.js models with an agent-guided workflow.
- [Three.js](https://github.com/mrdoob/three.js) — Build and render interactive 3D graphics in the browser.

## Inclusion Criteria

- An open-source core license; material source-available components must be disclosed in the entry
- At least 1,000 GitHub stars at the time of inclusion; curator exceptions must be marked
- Meaningful maintenance or a stable, documented release with ongoing utility
- A runnable creative workflow or a clearly defined production task; model repositories must provide a practical creation path, not only a paper or benchmark
- Capability and license claims supported by the upstream README, documentation, or license files
- Direct repository links with no affiliate links or paid placement in this list

## Disclaimer

This repository is an informational index. Inclusion is not an endorsement, security assessment, or guarantee of quality, maintenance, compatibility, or fitness for a particular use. Many listed projects have not been installed, run, or independently reviewed for security by the maintainers of this list.

GitHub stars are a discovery signal, not evidence that a project is safe, correctly licensed, or suitable for production.

Before using a project, review its source code, license, dependencies, install scripts, network behavior, data handling, permissions, and release history. Pin versions and test in an isolated environment. You are responsible for evaluating and operating each tool safely.

"Open source" describes an entry's core repository license. It does not mean that model weights, hosted providers, API services, or separately licensed subdirectories share that license; affected entries identify those boundaries.

For a correction to a listing's source, license, ownership, or security status, read [SECURITY.md](SECURITY.md).

## Contributing

Contributions are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## License

[MIT](LICENSE). Each listed project retains its own license and trademarks.
