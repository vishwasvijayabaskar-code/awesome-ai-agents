# Awesome AI Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI agent frameworks, platforms, tools, and resources for building autonomous AI systems in 2026.

Unlike other lists, this one is **opinionated** — every entry is categorized by maturity, use case, and whether it's actually maintained. Dead projects are removed monthly.

## Contents

- [Agent Frameworks](#agent-frameworks)
- [Agent Orchestration](#agent-orchestration)
- [Coding Agents](#coding-agents)
- [Research Agents](#research-agents)
- [Browser Agents](#browser-agents)
- [Voice & Multimodal Agents](#voice--multimodal-agents)
- [Memory & State](#memory--state)
- [Evaluation & Testing](#evaluation--testing)
- [Deployment & Infrastructure](#deployment--infrastructure)
- [Learning Resources](#learning-resources)

---

## Agent Frameworks

*General-purpose frameworks for building AI agents.*

| Project | Stars | Language | Description | Maintained |
|---------|-------|----------|-------------|------------|
| [LangChain](https://github.com/langchain-ai/langchain) | 100k+ | Python/JS | Most popular LLM framework. Chains, agents, RAG, tools. | ✅ Active |
| [LangGraph](https://github.com/langchain-ai/langgraph) | 10k+ | Python/JS | Stateful, multi-actor agent graphs built on LangChain. | ✅ Active |
| [CrewAI](https://github.com/crewAIInc/crewAI) | 25k+ | Python | Role-based multi-agent orchestration. Define agents with roles/goals. | ✅ Active |
| [AutoGen](https://github.com/microsoft/autogen) | 40k+ | Python | Microsoft's multi-agent conversation framework. | ✅ Active |
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel) | 25k+ | C#/Python/Java | Microsoft's SDK for integrating LLMs into apps. | ✅ Active |
| [Haystack](https://github.com/deepset-ai/haystack) | 18k+ | Python | End-to-end NLP/LLM framework by deepset. Pipelines-first. | ✅ Active |
| [Phidata](https://github.com/phidatahq/phidata) | 15k+ | Python | Build AI assistants with memory, knowledge, and tools. | ✅ Active |
| [Agno](https://github.com/agno-agi/agno) | 20k+ | Python | Lightweight agent framework. Fast, multi-modal, multi-agent. | ✅ Active |
| [Atomic Agents](https://github.com/BrainBlend-AI/atomic-agents) | 5k+ | Python | Modular, composable agents with schema-driven I/O. | ✅ Active |
| [Pydantic AI](https://github.com/pydantic/pydantic-ai) | 10k+ | Python | Type-safe agent framework by Pydantic team. | ✅ Active |

## Agent Orchestration

*Tools for coordinating multiple agents working together.*

| Project | Stars | Language | Description | Maintained |
|---------|-------|----------|-------------|------------|
| [MetaGPT](https://github.com/geekan/MetaGPT) | 50k+ | Python | Multi-agent framework that assigns roles (PM, Architect, Engineer). | ✅ Active |
| [ChatDev](https://github.com/OpenBMB/ChatDev) | 30k+ | Python | Simulates a software company with AI agent employees. | ✅ Active |
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | 170k+ | Python | Autonomous GPT-4 experiment. Pioneer of agent space. | ⚠️ Pivoting |
| [BabyAGI](https://github.com/yoheinakajima/babyagi) | 20k+ | Python | Task-driven autonomous agent. Simple but influential. | ⚠️ Archived |
| [Camel](https://github.com/camel-ai/camel) | 10k+ | Python | Communicative agents for multi-agent cooperation. | ✅ Active |
| [Agency Swarm](https://github.com/VRSEN/agency-swarm) | 4k+ | Python | Agent communication framework using OpenAI Assistants API. | ✅ Active |

## Coding Agents

*AI agents that write, review, and debug code.*

| Project | Stars | Language | Description | Maintained |
|---------|-------|----------|-------------|------------|
| [Aider](https://github.com/Aider-AI/aider) | 39k+ | Python | AI pair programming in your terminal. Git-native. | ✅ Active |
| [OpenCode](https://github.com/nicepkg/OpenCode) | 70k+ | Go | Terminal-native coding agent. 75+ providers. Free. | ✅ Active |
| [Claw Code](https://github.com/claw-project/claw-code) | 190k+ | Python/Rust | Clean-room Claude Code rewrite. Open source. | ✅ Active |
| [Codex CLI](https://github.com/openai/codex) | 75k+ | Rust | OpenAI's terminal coding agent. | ✅ Active |
| [Gemini CLI](https://github.com/google/gemini-cli) | 96k+ | TypeScript | Google's terminal AI agent. | ✅ Active |
| [Continue](https://github.com/continuedev/continue) | 25k+ | TypeScript | Open-source AI code assistant for VS Code / JetBrains. | ✅ Active |
| [Goose](https://github.com/block/goose) | 15k+ | Rust | Block's autonomous coding agent. MCP-native. | ✅ Active |
| [SWE-agent](https://github.com/princeton-nlp/SWE-agent) | 15k+ | Python | Princeton's agent that resolves GitHub issues autonomously. | ✅ Active |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | 50k+ | Python | AI agents for software development (formerly OpenDevin). | ✅ Active |

## Research Agents

*Agents that search, synthesize, and analyze information.*

| Project | Stars | Language | Description | Maintained |
|---------|-------|----------|-------------|------------|
| [GPT Researcher](https://github.com/assafelovic/gpt-researcher) | 20k+ | Python | Autonomous research agent. Multi-source, generates reports. | ✅ Active |
| [STORM](https://github.com/stanford-oval/storm) | 18k+ | Python | Stanford's research agent. Writes Wikipedia-style articles. | ✅ Active |
| [Khoj](https://github.com/khoj-ai/khoj) | 20k+ | Python | Personal AI for search and research across your data. | ✅ Active |
| [Perplexica](https://github.com/ItzCrazyKns/Perplexica) | 20k+ | TypeScript | Open-source Perplexity alternative. AI search engine. | ✅ Active |

## Browser Agents

*AI agents that navigate and interact with web browsers.*

| Project | Stars | Language | Description | Maintained |
|---------|-------|----------|-------------|------------|
| [Browser Use](https://github.com/browser-use/browser-use) | 55k+ | Python | Make AI agents interact with any website. | ✅ Active |
| [Playwright MCP](https://github.com/anthropics/playwright-mcp) | 6k+ | TypeScript | Browser automation via Model Context Protocol. | ✅ Active |
| [Stagehand](https://github.com/browserbase/stagehand) | 10k+ | TypeScript | AI web browsing framework by Browserbase. | ✅ Active |
| [LaVague](https://github.com/lavague-ai/LaVague) | 6k+ | Python | Large action model for browser automation. | ✅ Active |
| [Skyvern](https://github.com/Skyvern-AI/skyvern) | 10k+ | Python | Browser automation using LLMs and computer vision. | ✅ Active |

## Voice & Multimodal Agents

*Agents that process voice, images, and multiple modalities.*

| Project | Stars | Language | Description | Maintained |
|---------|-------|----------|-------------|------------|
| [LiveKit Agents](https://github.com/livekit/agents) | 5k+ | Python | Build real-time voice AI agents. | ✅ Active |
| [Pipecat](https://github.com/pipecat-ai/pipecat) | 5k+ | Python | Framework for voice and multimodal conversational AI. | ✅ Active |
| [Vocode](https://github.com/vocodedev/vocode-core) | 3k+ | Python | Open-source library for building voice agents. | ⚠️ Slowing |
| [OpenVoice](https://github.com/myshell-ai/OpenVoice) | 30k+ | Python | Instant voice cloning by MIT and MyShell. | ✅ Active |

## Memory & State

*Give agents persistent memory and context management.*

| Project | Stars | Language | Description | Maintained |
|---------|-------|----------|-------------|------------|
| [Mem0](https://github.com/mem0ai/mem0) | 25k+ | Python | Memory layer for AI agents. Persistent, contextual. | ✅ Active |
| [Letta](https://github.com/letta-ai/letta) | 15k+ | Python | Stateful LLM agents with long-term memory (formerly MemGPT). | ✅ Active |
| [Zep](https://github.com/getzep/zep) | 3k+ | Go | Long-term memory for AI assistants and agents. | ✅ Active |
| [Chroma](https://github.com/chroma-core/chroma) | 18k+ | Python | AI-native embedding database. Most popular for RAG. | ✅ Active |
| [Qdrant](https://github.com/qdrant/qdrant) | 29k+ | Rust | High-performance vector database for AI. | ✅ Active |

## Evaluation & Testing

*Test, evaluate, and monitor AI agents.*

| Project | Stars | Language | Description | Maintained |
|---------|-------|----------|-------------|------------|
| [Promptfoo](https://github.com/promptfoo/promptfoo) | 5k+ | TypeScript | Test prompts, agents, RAGs. CI/CD integration. Used by OpenAI. | ✅ Active |
| [Langfuse](https://github.com/langfuse/langfuse) | 26k+ | TypeScript | LLM observability — tracing, evals, prompt management. | ✅ Active |
| [Arize Phoenix](https://github.com/Arize-ai/phoenix) | 8k+ | Python | ML/LLM observability and evaluation. | ✅ Active |
| [Ragas](https://github.com/explodinggradients/ragas) | 8k+ | Python | RAG evaluation framework. | ✅ Active |
| [DeepEval](https://github.com/confident-ai/deepeval) | 5k+ | Python | Unit testing for LLMs. Pytest-like interface. | ✅ Active |

## Deployment & Infrastructure

*Run, deploy, and scale AI agents in production.*

| Project | Stars | Language | Description | Maintained |
|---------|-------|----------|-------------|------------|
| [LiteLLM](https://github.com/BerriAI/litellm) | 42k+ | Python | Unified API for 100+ LLM providers. Cost tracking. | ✅ Active |
| [Ollama](https://github.com/ollama/ollama) | 162k+ | Go | Run LLMs locally. Dead-simple CLI. | ✅ Active |
| [vLLM](https://github.com/vllm-project/vllm) | 50k+ | Python | High-throughput LLM serving engine. | ✅ Active |
| [LocalAI](https://github.com/mudler/LocalAI) | 30k+ | Go | Self-hosted OpenAI-compatible API. | ✅ Active |
| [Dify](https://github.com/langgenius/dify) | 80k+ | Python/TS | LLM app development platform. Visual workflow builder. | ✅ Active |
| [n8n](https://github.com/n8n-io/n8n) | 150k+ | TypeScript | Workflow automation with 400+ integrations. | ✅ Active |

## Learning Resources

*Guides, courses, and tutorials for building AI agents.*

| Resource | Type | Description |
|----------|------|-------------|
| [LLM Engineer Handbook](https://github.com/SylphAI-Inc/LLM-engineer-handbook) | Guide | Curated resources for training, serving, fine-tuning LLMs. |
| [AI System Design Primer](https://github.com/vishwasvijayabaskar-code/ai-system-design-primer) | Guide | System design for AI systems — RAG, agents, vector DBs, evals. |
| [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) | Guide | Comprehensive prompt engineering techniques and papers. |
| [LangChain Cookbook](https://github.com/langchain-ai/langchain/tree/master/cookbook) | Tutorials | Official LangChain examples and recipes. |
| [Anthropic Courses](https://github.com/anthropics/courses) | Course | Official Anthropic prompt engineering and tool use courses. |

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

**Rules:**
- Only include actively maintained projects (commit in last 3 months)
- Include GitHub stars count (approximate is fine)
- One project per line, consistent format
- No paid-only tools without a free tier

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=vishwasvijayabaskar-code/awesome-ai-agents&type=Date)](https://star-history.com/#vishwasvijayabaskar-code/awesome-ai-agents&Date)

---

**Last updated:** May 2026 | **Maintained by:** [@vishwasvijayabaskar-code](https://github.com/vishwasvijayabaskar-code)
