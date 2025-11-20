## Part A — Research Questions

1. **What new improvements were introduced in Gemini 3.0?**

   * Gemini 3 (Pro) delivers *much stronger reasoning* capabilities, outperforming earlier models on several AI benchmarks. ([blog.google][1])
   * It supports a **1 million–token context window**, which enables it to handle very long inputs. ([Google AI for Developers][2])
   * It introduces new *safety improvements*: lower risk of prompt injections, improved resistance to misuse. ([blog.google][3])
   * There is more control for developers via new API parameters (e.g., `thinking_level`) to manage latency, cost, and reasoning depth. ([Google AI for Developers][2])
   * Multimodal fidelity is more granular, meaning developers can choose visual processing quality to balance cost/latency. ([Google AI for Developers][2])

2. **How does Gemini 3.0 improve coding & automation workflows?**

   * It supports *agentic coding*: through the Gemini API, it can propose shell commands, perform tool use (like terminal operations), and automate system-level tasks. ([blog.google][1])
   * Google introduced **Antigravity**, an “agent-first” development platform, where AI agents powered by Gemini 3 can operate in the editor, terminal, and browser to run tasks autonomously. ([blog.google][1])
   * There is “vibe coding”: you can give high-level natural language prompts (no need for low-level syntax), and Gemini 3 can generate interactive apps, web UIs, or full code bases. ([blog.google][1])
   * Gemini 3 is integrated in **Android Studio**, so developers can get AI assistance (in Agent Mode) for boilerplate, bug fixing, etc. ([Android Developers Blog][4])

3. **How does Gemini 3.0 improve multimodal understanding?**

   * It brings *better visual reasoning*: not just simple OCR, but deeper document understanding, reasoning about layout, structure, and content. ([blog.google][1])
   * Spatial reasoning is stronger: Gemini 3 can understand screen states (mouse movement, annotations), and reason about trajectories or task progression. ([blog.google][1])
   * Video reasoning is enhanced: the model can process high-frame-rate video, recall long-context information, and reason across hours of continuous footage. ([blog.google][1])
   * With the large context window (1 M tokens), Gemini 3 can combine multimodal inputs (like images + text) in long-form tasks. ([Google AI for Developers][2])

4. **Name any two developer tools introduced with Gemini 3.0.**

   * **Google Antigravity**: a new agent-first IDE/development platform for orchestrating multiple AI agents. ([blog.google][1])
   * **Gemini CLI / Gemini API**: The API has been enhanced to support tool use (e.g., shell commands), structured outputs, and more granular control (`thinking_level` etc.). ([Google AI for Developers][2])
   * (Bonus) **Android Studio integration**: Gemini 3 Pro is now usable in Android Studio Otter for AI-assisted development. ([Android Developers Blog][4])
