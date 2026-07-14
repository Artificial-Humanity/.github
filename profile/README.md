# Artificial Humanity 👤✨

Welcome to **Artificial Humanity**! We are a research and engineering studio dedicated to building AI projects that touch upon the space between machine intelligence and human emotion.

Our core philosophy is simple: **we believe artificial intelligence should run locally, respect privacy, and engage with human feeling.** No remote cloud APIs, no data locks, and no delay. Just native, high-performance engines that feel alive.

---

## 🎙️ Introducing Project Prosodia

Our flagship initiative is **[Project Prosodia](https://github.com/Artificial-Humanity/Prosodia)**—an open-source framework for expressive, continuous, emotion-driven speech synthesis. It splits speech generation into a protocol-based pipeline, separating semantic interpretation (the **Director**) from vocal performance (the **Actor**, powered by **StyleTTS2**), so digital books are read with dynamic pacing, dramatic pauses, and real-time voice blending—no robotic conveyor-belt narration here.

**Fun facts:** we're hunting for the exact Valence-Arousal-Tension coordinate for *"the hero's tragic sacrifice,"* to get the Actor's voice to crack slightly. And since the engine compiles and runs entirely offline, you'd still have a perfect narrator even stranded on a mountaintop with a laptop.

---

## 🧭 The Prosodia Workspace

We maintain all of our code, crates, and client packages in a single unified workspace at **[Artificial-Humanity/Prosodia](https://github.com/Artificial-Humanity/Prosodia)**:

*   **`core` (Rust)**: The vocabulary index, BPE tokenizer, and shared traits underpinning the rest of the workspace.
*   **`folioparser` (Rust)**: Parses EPUB XML structures and extracts plain text for narration.
*   **`director` (Rust)**: The lookahead pacing director. Driven by Gemma (LiteRT-LM), it reads book passages and translates emotional context into Valence-Arousal-Tension coordinates and casting assignments.
*   **`actor` (Rust)**: The speech synthesis engine. Performs on-device execution of StyleTTS2 models via our custom native synthesis engine, generating expressive audio waveforms dynamically.
*   **`stage` (Rust)**: The Stage Manager. Coordinates the Director and the Actor and keeps playback gapless.
*   Platform bridges for **Apple, Android, Linux, and Windows**, plus downstream apps: the **AppleReader** and **Android Reader** eBook readers, and the **Tuner** rehearsal workbench (desktop app + Chrome extension) for auditioning VAD sliders and casting profiles.

---

## 🧑‍⚖️ Introducing Council of Experts

Our second studio initiative is **[Council of Experts](https://github.com/Artificial-Humanity/Council-of-Experts)**—a native macOS orchestration platform that runs a configurable council of LLM experts (Claude, Gemini, GPT, Grok, and local models) in parallel, has them critique and revise each other's drafts, and synthesizes their consensus through a Chairman model. It's built on the same philosophy as Prosodia: a Rust core with a native Swift/SwiftUI FFI layer, supporting live streaming, workspace file context, and multi-turn session persistence.

---

Thanks for stopping by, and happy coding! 👤✨
