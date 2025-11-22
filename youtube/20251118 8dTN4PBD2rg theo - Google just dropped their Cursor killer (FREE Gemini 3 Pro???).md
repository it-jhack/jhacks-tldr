TLDR

- Anti-gravity (Google's New AI IDE): A VS Code fork by Google, currently free to use in preview.

- Core AI Integration: Built around Gemini 3 and other upcoming models, leveraging Google's AI capabilities.

- Key Features:
    - Agent Manager Workflow: A separate window that manages tasks, projects, and commands the editor, promoting a "managing an inbox" mindset.
    - Browser Control Mode: Allows the IDE to control the browser, capture screenshots, and record gameplay reels for verification.
    - Asset Generation: Capable of generating assets (e.g., images) as part of its reasoning flow.
    - One-Shot Task Performance: Demonstrated impressive ability to create functional applications (e.g., 3JS and Phaser games) from initial prompts.

- Strengths:
    - Free access to Gemini 3 (with generous limits during preview).
    - Innovative agent manager UX that could improve workflow for multi-tasking.
    - Strong performance for rapid prototyping and one-shot code generation.

- Weaknesses/Current Issues (Beta State):
    - Numerous bugs and "catches" typical of a new editor.
    - Lacks Git worktree support.
    - Experiences agent errors, thread failures, and recovery issues.
    - Inconsistent extension compatibility (e.g., Svelte extension bug).
    - UI/UX issues reported (e.g., missing syntax highlighting, arrow key navigation problems).
    - Initial authentication limitations (personal Gmail only).
    - Doesn't always explicitly show web browsing activity for context.
    - Can exhibit text entry lag and high battery consumption.
    - Doesn't default to `bun` even if specified in the project.