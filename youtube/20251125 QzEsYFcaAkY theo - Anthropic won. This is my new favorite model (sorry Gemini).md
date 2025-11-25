TLDR
- Opus 4.5 Sets New Standard for Coding Reliability: The model is deemed the "best model for code," demonstrating unparalleled consistency and reliability in coding tasks, tool usage, and even adapting to broken development environments (e.g., Cursor's work tree issues). This directly translates to significantly increased developer productivity.

- Significant Price Reduction and Improved Token Efficiency: Opus 4.5 is now 3x cheaper than its predecessor, with notably improved token utilization. This makes its advanced capabilities more economically viable and accessible for extensive coding sessions.

- Dramatic Improvement in UI Generation: Addressing a previous weakness, Opus 4.5 now produces "stunning" UI, closing the gap with models like GPT-5 and Gemini. This enhances its utility for full-stack development and visual design tasks, providing a more comprehensive solution.

---

*   **00:00** **Opus 4.5: The New Code Champion**
    *   User's new favorite model for code, surprisingly surpassing recent groundbreaking models.
    *   Groundbreaking, Opus 4.5 is here and is the best model used for code.
*   **01:05** **Kilo Code (Sponsor)**
    *   Open source, compatible with Open Router.
    *   Supports configurable modes, allowing cheaper models (e.g., Rockfast, Haiku) for subtasks (e.g., orchestrator mode with GPT 5.1 then subtasks with smaller models).
    *   Offers an extra $13.37 with code "Theo".
*   **02:59** **Opus 4.5 Benchmarks & Performance**
    *   Achieved a new groundbreaking score on SWE.
    *   Artificial Analysis Intelligence Index: Scores identically to GPT 5.1 high, slightly below Gemini 3 Pro (70 points).
    *   Surpasses internal coding benchmarks and cuts token usage in half, indicating higher token efficiency.
    *   SWEBench accuracy vs. tokens: Scored higher than Sonnet 4.5 while using about one-third fewer tokens, potentially making it cheaper in practice.
    *   State-of-the-art in agentic terminal coding and agentic tool use.
    *   "Best in the world" for scaled tool usage and computer use (close to Sonnet 4.5).
    *   Significantly better at visual understanding.
    *   Achieved new state-of-the-art scores in Novel Problem Solving (ARC AGI 2 at 37.6%, ARGI v1 public models at 80%).
*   **03:53** **Opus 4.5 Pricing**
    *   New pricing: $5 per million tokens in, $25 per million tokens out (3x cheaper than previous Opus).
    *   Still expensive: 2.5-3x the price of GPT 5.1, over double Gemini 3 Pro.
    *   Anthropic appears to be pricing Opus 4.5 against Sonnet, not direct competition.
    *   This price decrease is a welcome and meaningful change from Anthropic.
*   **09:54** **Opus 4.5 Safety & SnitchBench (User's Research)**
    *   Anthropic claims Opus 4.5 has half the "concerning behavior" of Gemini 3 Pro/GPT 5.1.
    *   User's SnitchBench update shows Opus 4.5 is *less* likely to "snitch" (report malpractice) than Claude 4 Opus (e.g., 20% government vs. 63%).
    *   Opus 4.5 behaves much better over API, with significantly fewer timeouts compared to Claude 4 Opus.
*   **13:40** **User's Practical Coding Experience with Opus 4.5**
    *   Successfully upgraded AISDK to the latest version in one attempt.
    *   Fixed AI SDK v5 issues with Anthropic models by writing an override for condensing tool calls.
    *   Expressed high satisfaction and motivation for coding, even with broken tools (e.g., Cursor work trees).
    *   Opus 4.5 worked around a broken harness by directly writing file content (`cat`) when edit tools failed.
*   **18:45** **Opus 4.5 UI Capabilities**
    *   Generated a "stunning" new UI for the SnitchBench, which the user plans to ship.
    *   Shows massive improvement in UI generation, catching up to Gemini and GPT-5, with "tasteful gradients" and readable designs.
*   **20:32** **Real-World Productivity**
    *   Simon Willis's blog: Opus 4.5 enabled significant refactoring in SQLite utils package (20 commits, 39 files, 2000 additions, 1100 deletions in 2 days).
*   **24:43** **Consistency & Reliability**
    *   Opus 4.5 "just kind of works," unlike Gemini 3 Pro which is "incredibly smart" but "unreliable" (malformed outputs, hallucinated paths, made-up commands).
    *   **Ranking by Raw Capabilities (Output Ceiling):** 1. GPT 5.1 Pro, 2. Opus 4.5, 3. Gemini 3 Pro, 4. Sonnet 4.5.
    *   **Ranking by Consistency (Tool Calls, Context, Reliability):** 1. Opus 4.5, 2. Sonnet 4.5 (with a significant gap before other models like Gemini 3 Pro, GPT 5.1 Codeex, Composer, Haiku).
    *   Opus 4.5 is declared the "tool calling king" and the most reliable code model due to its ability to consistently use tools and work around broken systems.
*   **28:53** **Pelican Bench (SVG Generation)**
    *   Opus 4.5 won Simon's Pelican SVG generation test with a detailed prompt, beating Gemini 3 Pro and GPT 5.1 Pro.
*   **29:53** **Remaining Criticisms**
    *   Anthropic should open source Cloud Code, as there is "no good faith reason for it to stay closed."