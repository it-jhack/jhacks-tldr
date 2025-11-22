TLDR

05:31 Inherent Inefficiency of Direct MCP Tool Calls: The original MCP design, relying on direct tool calls and passing all tool definitions/intermediate results through the model's context, leads to massive token waste (up to 99% reduction possible), increased costs, slower performance, and makes models less effective.

10:57 Code Execution as the Primary Solution: Anthropic, MCP's creator, now advocates for AI agents to write code to interact with tools. This approach allows on-demand tool loading, pre-processing of data, and execution of complex logic outside the model's context, fundamentally addressing the inefficiencies.

14:41 Enhanced Security and State Management: Code execution keeps sensitive data (like PII) within the execution environment, preventing it from ever entering the model's context, and enables explicit state persistence, providing critical security and reliability advantages over stateless LLM interactions.