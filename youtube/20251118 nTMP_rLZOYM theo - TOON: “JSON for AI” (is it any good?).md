TLDR

- JSON Prompting Inefficiency: Directly using JSON for LLM prompts is token-expensive, often doubling or tripling token counts compared to plain text, despite perceived conciseness. This increases cost and can reduce model effectiveness.

- Introducing TOON (Token-Oriented Object Notation): TOON is proposed as a lossless, drop-in replacement for JSON specifically designed to optimize LLM inputs.

- Key Benefits of TOON:
    - Token Reduction: Achieves 40-60% fewer tokens than JSON.
    - Improved Accuracy: Benchmarks suggest a ~4% increase in retrieval accuracy.
    - Ideal Use Case: Excels with flat, array-like structures (CSV-like compactness with explicit structure), making it suitable for passing large datasets (e.g., hundreds of rows of data) to LLMs.

- TOON's Limitations: Less effective with deeply nested or non-uniform data structures.

- Recommended Workflow: Use JSON programmatically for data handling, then convert to TOON format before sending to an LLM to optimize token cost and accuracy.

- JSON Prompting Effectiveness (Mixed Views): Opinions are divided on JSON prompting's overall utility; some studies show high failure rates, while others claim it improves outputs. The consensus suggests it's often not beneficial and can be counterproductive due to token costs.

- High-Performing LLMs for Data Retrieval/Large Contexts: Gemini 2.5 Flash and GPT-5 Nano demonstrate superior performance in data retrieval and handling large contexts compared to other models (e.g., Claude, Grok 5 Fast).

- Practical Action: For tasks involving passing large arrays of structured data to LLMs, consider using a JSON-to-TOON converter to save tokens and potentially enhance model performance. Lookup "toon-format" /toon, and /toon-python for more.