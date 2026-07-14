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

*   **`prosodia-core` (Rust)**: The core orchestration crate managing document parsing (EPUB/TXT), page layouts, chapter segmentation, and cross-platform desktop/mobile runtime states.
*   **`prosodia-director` (Rust)**: The lookahead pacing director. Analyzes narrative context, maps text layouts, and translates emotional coordinates into dynamic acoustic style vectors.
*   **`prosodia-actor` (Rust)**: The speech synthesis engine. Performs on-device execution of StyleTTS2 models using our custom native synthesis engine, generating highly expressive audio waveforms dynamically.
*   **`AnimaReader` (App)**: A delightful cross-platform eBook reader application (built in Rust, Swift, and Kotlin) that wraps the pipeline into an immersive, offline reading and audiobook experience.

---

## 🤝 Getting Involved

Whether you are a developer, a linguist, an AI researcher, or just someone who loves a good book—we would love to have you in the community!

- **Refining Style Models**: Help us build and train our custom variant of StyleTTS2 to replace generic models.
- **Performance Tuning**: Submit PRs to optimize custom synthesis execution paths and CPU/GPU memory overhead across desktop and mobile platforms.
- **eReader Design**: Join us in designing and testing the user experience for the AnimaReader application.

---

## 🍿 Fun Facts

1. **Vocal Inflection**: Our Valence-Arousal-Tension model maps emotion coordinates. We are currently trying to figure out the coordinate for *"the exact moment the hero makes a tragic sacrifice"* to see if we can get the Actor's voice to crack slightly.
2. **Offline-First**: Every single line of code in our Prosodia engine compiles and runs entirely offline. If you ever find yourself stranded on a mountaintop with a laptop, you'll still have a perfect, expressive narrator reading to you.

Thanks for stopping by, and happy coding! 👤✨
