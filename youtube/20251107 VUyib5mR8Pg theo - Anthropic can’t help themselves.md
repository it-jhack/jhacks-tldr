TLDR

Anthropic is aggressively restricting access to its Claude models to prevent competitors (like TikTok's Trey and Windsurf) from using its AI outputs to train their own models, leading to criticism over its closed-source nature and anti-competitive practices.

- Anthropic's Restrictions: Anthropic has cut off access to its Claude AI models for several entities, including:
    - Trey: A TikTok/ByteDance AI IDE, due to concerns over Chinese ownership, national security risks, and the potential for "distillation" (training competing models on Claude's output). Trey's "Seed Coder" model scored 78% on SWEBench.
    - Windsurf: An AI IDE previously cut off, with its `sw.5` model exhibiting "Claude brain," suggesting training on Claude-generated data.
    - OpenAI: Access was revoked, with Anthropic citing data usage for training while OpenAI claimed it was for benchmarking.

- Expansion of Restrictions: Anthropic enforces these access prohibitions beyond direct API usage, extending to its models offered through cloud platforms like Google Cloud and AWS Bedrock via terms of service.

- Concerns over "Distillation": A primary motivation for Anthropic's actions is the fear that other companies are using Claude's outputs to train their own, potentially cheaper and faster, competing models. Evidence for this is observed in the behavior ("Claude brain") of models developed by entities like Windsurf.

- Anthropic's Unique Stance: Anthropic is highlighted as the only major AI lab that:
    - Offers zero open-weight models.
    - Provides a CLI with a popular GitHub repo that lacks actual source code.
    - Actively publishes research and benchmarks without releasing the majority of said benchmarks.

- Perceived Hypocrisy/Strategy: The speaker criticizes Anthropic for:
    - Positioning itself as safety-focused while engaging in perceived unethical business practices.
    - Strategically timing cutoffs to maximize harm to competitors (e.g., during major product releases) while minimizing impact on its own public image.
    - Being uniquely sensitive to competition, particularly from well-funded entities like ByteDance's Trey.

- Developer Impact: The cutoffs cause significant frustration among developers who rely on Claude models for their workflows and subscriptions.

- Cursor's Status: Cursor, another AI IDE, has not yet been cut off, but the speaker suggests it could be next.