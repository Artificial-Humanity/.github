# Artificial Humanity 👤✨

Welcome to **Artificial Humanity**! We are a research and engineering studio dedicated to building AI projects that touch upon the space between machine intelligence and human emotion.

Our core philosophy is simple: **we believe artificial intelligence should run locally, respect privacy, and engage with human feeling.** No remote cloud APIs, no data locks, and no delay. Just native, high-performance engines that feel alive.

---

## 🎙️ Introducing Project Prosodia

Our flagship initiative is **[Project Prosodia](https://github.com/Artificial-Humanity/Prosodia)**—an open-source framework for expressive, continuous, emotion-driven speech synthesis. It splits speech generation into a protocol-based pipeline, separating semantic interpretation (the **Director**) from vocal performance (the **Actor**, powered by our own **Sonora** model), so digital books are read with dynamic pacing, dramatic pauses, and real-time voice blending—no robotic conveyor-belt narration here.

**Fun facts:** we're hunting for the exact Valence-Arousal-Tension coordinate for *"the hero's tragic sacrifice,"* to get the Actor's voice to crack slightly. And since the engine compiles and runs entirely offline, you'd still have a perfect narrator even stranded on a mountaintop with a laptop.

---

## 🎭 Introducing Sonora

The voice inside Prosodia is its own project: **[Sonora](https://github.com/Artificial-Humanity/Sonora)**—a directable, castable, mobile-friendly TTS actor we train from scratch on license-clean data. It is built on the **Matcha-TTS** architecture (a conditional flow-matching mel decoder solved with a few-step ODE), augmented with emotion conditioning and continuous voice casting, so valence, energy and tension arrive as things you *tell* the model rather than hope for. Small enough to run on a phone, and Apache-2.0 like everything else here.

---

## 🧑‍⚖️ Introducing Council of Experts

Another studio initiative is **[Council of Experts](https://github.com/Artificial-Humanity/Council-of-Experts)**—a native macOS orchestration platform that runs a configurable council of LLM experts (Claude, Gemini, GPT, Grok, and local models) in parallel, has them critique and revise each other's drafts, and synthesizes their consensus through a Chairman model. It's built on the same philosophy as Prosodia: a Rust core with a native Swift/SwiftUI FFI layer, supporting live streaming, workspace file context, and multi-turn session persistence.

---

## 🎨 Introducing Lucida

**[Lucida](https://github.com/Artificial-Humanity/Lucida)** is the studio's own image and video generation tool, and a single Rust binary either way. It reaches Google Gemini and Veo, Runway, Kling, hosted FLUX, Stability AI, OpenAI, or a ComfyUI running on your own hardware. It works as a command-line tool and as an **MCP server**, so the coding agents working on these projects can make their own artwork instead of waiting for someone to hand it over.

---

## 🔄 Incubating: FerroLoop

Currently in the architecture phase, **[FerroLoop](https://github.com/Artificial-Humanity/FerroLoop)** is our cross-vendor agent orchestration and coordination platform for solo developers and small teams. It enables heterogeneous coding agents across different vendors (Claude Code, Antigravity CLI, Codex, Gemini, local models) to communicate, hand off tasks, enforce role-gated review loops, and track telemetry safely without vendor lock-in.

True to our studio philosophy: an open-source (Apache-2.0), self-hosted, single static Rust binary with an embedded database engine—coordinating external agent CLIs via standard protocols (ACP, MCP) with hard budget and token ceilings, all without cloud accounts or per-seat licensing.

---

Thanks for stopping by, and happy coding! 👤✨
