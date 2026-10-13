# Miles Johnson

AI engineer. I build LLM systems end to end: agents with tool calling, retrieval pipelines, and LLM-scored evaluation that sends uncertain cases to a human.

From 2024 to 2026 I was the sole AI developer at Chemwatch, a chemical-safety data company. That code is private. In brief:

- **Agents:** an AWS Bedrock agent platform, with a Node.js tool-calling framework and a React chat interface.
- **Evaluation and triage:** LLM scoring of scientific literature against a weighted rubric. High scores are included automatically and mid scores go to human review. A 4-hour manual review cycle now takes minutes.
- **Retrieval-augmented extraction:** web search plus GPT-4o enrichment, with a validation layer that scores source recency and reliability. 97.5% field completion.

## Public projects

| Project | What it shows |
| --- | --- |
| [vs-wiki-rag](https://github.com/miles-h-johnson/vs-wiki-rag) | Local RAG over a game-modding wiki (nomic embeddings, ChromaDB), served to coding agents as an MCP tool. A 40-question retrieval eval finds the answering page in the top 3 for 90% of questions, with an ablation of what helped and what didn't |
| [qr-lab](https://github.com/miles-h-johnson/qr-lab) | Evaluation harness for AI-generated QR artwork: ComfyUI batch runs scored by a two-decoder, multi-resolution scan gate plus an art-distance metric, which caught a prompt template that scanned perfectly only because the model was copying its input |
| [qr-code-styler](https://github.com/miles-h-johnson/qr-code-styler) | Next.js app that generates scannable QR-code artwork through Replicate, with Google sign-in, Stripe subscription tiers and a Postgres-backed gallery |
| [merchant-ledger](https://github.com/miles-h-johnson/merchant-ledger) | Flask and PostgreSQL pricing service: reconciles a price list with game recipe data, then prices orders by recursive recipe decomposition |

## Stack

Python · TypeScript · C# · SQL — AWS Bedrock, Lambda, Lex, Cognito — OpenAI, Anthropic, local models (llama.cpp, GGUF) — ChromaDB, PostgreSQL — React, Next.js, Node.js, Flask

mhaakonj@gmail.com
