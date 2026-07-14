# Artificial Humanity 👤✨

Welcome to **Artificial Humanity**! We are a research and engineering studio dedicated to building AI projects that touch upon the space between machine intelligence and human emotion.

Our core philosophy is simple: **we believe artificial intelligence should run locally, respect privacy, and engage with human feeling.** No remote cloud APIs, no data locks, and no delay. Just native, high-performance engines that feel alive.

---

## 🎙️ Introducing Project Prosodia

Our flagship initiative is **[Project Prosodia](https://github.com/Artificial-Humanity/Prosodia)**—an open-source framework and suite of engines dedicated to expressive, continuous, emotion-driven speech synthesis. 

Existing speech engines treat reading like a dry, robotic conveyor belt. Project Prosodia treats it like **acting**. By splitting speech generation into a protocol-based pipeline—separating semantic interpretation (the **Director**) from vocal performance (the **Actor**) and executing it using **StyleTTS2**—we enable digital books to be read with dynamic pacing, dramatic pauses, and real-time voice blending.

Yes, our local models are taught to pause for a deep breath mid-sentence—even though they don't have lungs. It just sounds better that way.

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

## 🤝 Getting Involved

Whether you are a developer, a linguist, an AI researcher, or just someone who loves a good book—we would love to have you in the community!

- **Refining Style Models**: Help us build and train our custom variant of StyleTTS2 to replace generic models.
- **Performance Tuning**: Submit PRs to optimize custom synthesis execution paths and CPU/GPU memory overhead across desktop and mobile platforms.
- **eReader Design**: Join us in designing and testing the user experience for the AppleReader and Android Reader apps.
- **Multi-Agent Orchestration**: Help refine the critique/consensus loops and sandboxed agentic coding flow in Council of Experts.

---

## 🍿 Fun Facts

1. **Vocal Inflection**: Our Valence-Arousal-Tension model maps emotion coordinates. We are currently trying to figure out the coordinate for *"the exact moment the hero makes a tragic sacrifice"* to see if we can get the Actor's voice to crack slightly.
2. **Offline-First**: Every single line of code in our Prosodia engine compiles and runs entirely offline. If you ever find yourself stranded on a mountaintop with a laptop, you'll still have a perfect, expressive narrator reading to you.

Thanks for stopping by, and happy coding! 👤✨
