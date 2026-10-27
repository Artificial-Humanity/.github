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

## 🎨 Introducing Lucida

**[Lucida](https://github.com/Artificial-Humanity/Lucida)** is the studio's own image and video generation tool, and a single Rust binary either way. It reaches Google Gemini and Veo, Runway, Kling, hosted FLUX, Stability AI, OpenAI, Lemonade for local NPU/GPU inference, or a ComfyUI running on your own hardware. It works as a command-line tool and as an **MCP server**, so the coding agents working on these projects can make their own artwork instead of waiting for someone to hand it over.

---

## 🔄 Introducing FerroLoop

**[FerroLoop](https://github.com/Artificial-Humanity/FerroLoop)** is our cross-vendor agent orchestration and coordination platform for solo developers and small teams, and it is shipping today as a Rust workspace: the `fl` CLI with `fl-store` on embedded `redb`, `FerroWire` agent-to-agent messaging, five vendor adapters (Claude Code, Antigravity, Codex, Muse, and Grok), role-gated GitHub pull-request review loops, and **FerroDeck**, its web command center. Heterogeneous coding agents communicate, hand off tasks, and track telemetry safely without vendor lock-in.

True to our studio philosophy: an open-source (Apache-2.0), self-hosted Rust binary with an embedded database engine—coordinating external agent CLIs over MCP with hard budget and token ceilings, all without cloud accounts or per-seat licensing.

---

Thanks for stopping by, and happy coding! 👤✨
