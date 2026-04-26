# AI Trust & Safety Digest

A curated current snapshot of AI trust, safety, and governance, including as many materially important fresh items as the day warrants.

Today's signal is concentrated in practical safeguards and evaluation gaps: OpenAI published a new system card, launched a bio-focused bug bounty, and released a privacy redaction model, while fresh research highlights a multi-turn jailbreak technique that can bypass stateless moderation. The common thread is that trust and safety work is shifting from single-prompt controls toward more realistic testing of deployment-time behavior, privacy protection, and domain-specific misuse risk.

## Worth Opening

- [Transient Turn Injection exposes stateless multi-turn safety failures in LLMs](https://arxiv.org/abs/2604.21860v1) - It identifies a realistic jailbreak pattern that single-turn moderation pipelines may systematically miss. Source: arXiv. Published: 2026-04-26T11:30:17Z.
- [GPT-5.5 Bio Bug Bounty opens red-teaming for bio-related jailbreaks](https://openai.com/index/gpt-5-5-bio-bug-bounty) - It expands external testing for high-consequence misuse pathways rather than relying only on internal evaluations. Source: OpenAI News. Published: 2026-04-23T00:00:00Z.
- [GPT-5.5 System Card](https://openai.com/index/gpt-5-5-system-card) - System cards are primary evidence for how a frontier model was evaluated, constrained, and judged deployable. Source: OpenAI News. Published: 2026-04-23T11:00:00Z.
- [OpenAI introduces Privacy Filter for PII detection and redaction](https://openai.com/index/introducing-openai-privacy-filter) - It targets a core deployment risk: preventing sensitive personal data from leaking through model pipelines. Source: OpenAI News. Published: 2026-04-22T00:00:00Z.
- [CrossCommitVuln-Bench targets vulnerabilities invisible to per-commit static analysis](https://arxiv.org/abs/2604.21917v1) - It offers a benchmark for evaluating whether AI security tools can catch multi-step software vulnerabilities. Source: arXiv. Published: 2026-04-26T11:30:17Z.
- [Revisiting non-verbatim memorization in LLMs through entity surface forms](https://arxiv.org/abs/2604.21882v1) - It suggests memorization and privacy evaluations may undercount recall by testing only canonical entity names. Source: arXiv. Published: 2026-04-26T11:30:17Z.

Selected from recent trust-and-safety relevant posts and papers by labs, evaluators, standards bodies, policy organizations, and arXiv, then summarized with GPT-5.4. Includes as many materially important fresh items as the day warrants.

Generated at: 2026-04-26T11:30:26Z
