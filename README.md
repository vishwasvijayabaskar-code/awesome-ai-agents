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
| [LangChain](https://github.com/langchain-ai/langchain) | 137k+ | Python/JS | Most popular LLM framework. Chains, agents, RAG, tools. | ✅ Active |
| [LangGraph](https://github.com/langchain-ai/langgraph) | 32k+ | Python/JS | Stateful, multi-actor agent graphs built on LangChain. | ✅ Active |
| [CrewAI](https://github.com/crewAIInc/crewAI) | 51k+ | Python | Role-based multi-agent orchestration. Define agents with roles/goals. | ✅ Active |
| [AutoGen](https://github.com/microsoft/autogen) | 58k+ | Python | Microsoft's multi-agent conversation framework. | ✅ Active |
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel) | 27k+ | C#/Python/Java | Microsoft's SDK for integrating LLMs into apps. | ✅ Active |
| [Haystack](https://github.com/deepset-ai/haystack) | 25k+ | Python | End-to-end NLP/LLM framework by deepset. Pipelines-first. | ✅ Active |
| [Agno](https://github.com/agno-agi/agno) | 40k+ | Python | Lightweight agent framework. Fast, multi-modal, multi-agent. | ✅ Active |
| [Swarm](https://github.com/openai/swarm) | 21k+ | Python | OpenAI's lightweight multi-agent orchestration. Educational. | ✅ Active |
| [Atomic Agents](https://github.com/BrainBlend-AI/atomic-agents) | 5k+ | Python | Modular, composable agents with schema-driven I/O. | ✅ Active |
| [Pydantic AI](https://github.com/pydantic/pydantic-ai) | 17k+ | Python | Type-safe agent framework by Pydantic team. | ✅ Active |

## Agent Orchestration

*Tools for coordinating multiple agents working together.*

| Project | Stars | Language | Description | Maintained |
|---------|-------|----------|-------------|------------|
| [MetaGPT](https://github.com/geekan/MetaGPT) | 68k+ | Python | Multi-agent framework that assigns roles (PM, Architect, Engineer). | ✅ Active |
| [ChatDev](https://github.com/OpenBMB/ChatDev) | 33k+ | Python | Simulates a software company with AI agent employees. | ✅ Active |
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | 184k+ | Python | Autonomous GPT-4 experiment. Pioneer of agent space. | ⚠️ Pivoting |
| [BabyAGI](https://github.com/yoheinakajima/babyagi) | 22k+ | Python | Task-driven autonomous agent. Simple but influential. | ⚠️ Archived |
| [Camel](https://github.com/camel-ai/camel) | 17k+ | Python | Communicative agents for multi-agent cooperation. | ✅ Active |
| [Agency Swarm](https://github.com/VRSEN/agency-swarm) | 4k+ | Python | Agent communication framework using OpenAI Assistants API. | ✅ Active |

## Coding Agents

*AI agents that write, review, and debug code.*

| Project | Stars | Language | Description | Maintained |
|---------|-------|----------|-------------|------------|
| [Aider](https://github.com/Aider-AI/aider) | 45k+ | Python | AI pair programming in your terminal. Git-native. | ✅ Active |
| [Codex CLI](https://github.com/openai/codex) | 84k+ | Rust | OpenAI's terminal coding agent. | ✅ Active |
| [Gemini CLI](https://github.com/google-gemini/gemini-cli) | 104k+ | TypeScript | Google's terminal AI agent. | ✅ Active |
| [Cline](https://github.com/cline/cline) | 62k+ | TypeScript | Autonomous coding agent for VS Code. | ✅ Active |
| [Continue](https://github.com/continuedev/continue) | 33k+ | TypeScript | Open-source AI code assistant for VS Code / JetBrains. | ✅ Active |
| [Goose](https://github.com/block/goose) | 45k+ | Rust | Block's autonomous coding agent. MCP-native. | ✅ Active |
| [SWE-agent](https://github.com/princeton-nlp/SWE-agent) | 19k+ | Python | Princeton's agent that resolves GitHub issues autonomously. | ✅ Active |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | 74k+ | Python | AI agents for software development (formerly OpenDevin). | ✅ Active |

## Research Agents

*Agents that search, synthesize, and analyze information.*

| Project | Stars | Language | Description | Maintained |
|---------|-------|----------|-------------|------------|
| [GPT Researcher](https://github.com/assafelovic/gpt-researcher) | 27k+ | Python | Autonomous research agent. Multi-source, generates reports. | ✅ Active |
| [STORM](https://github.com/stanford-oval/storm) | 28k+ | Python | Stanford's research agent. Writes Wikipedia-style articles. | ✅ Active |
| [Khoj](https://github.com/khoj-ai/khoj) | 34k+ | Python | Personal AI for search and research across your data. | ✅ Active |
| [Perplexica](https://github.com/ItzCrazyKns/Perplexica) | 34k+ | TypeScript | Open-source Perplexity alternative. AI search engine. | ✅ Active |

## Browser Agents

*AI agents that navigate and interact with web browsers.*

| Project | Stars | Language | Description | Maintained |
|---------|-------|----------|-------------|------------|
| [Browser Use](https://github.com/browser-use/browser-use) | 95k+ | Python | Make AI agents interact with any website. | ✅ Active |
| [Playwright MCP](https://github.com/microsoft/playwright-mcp) | 32k+ | TypeScript | Browser automation via Model Context Protocol. | ✅ Active |
| [Stagehand](https://github.com/browserbase/stagehand) | 22k+ | TypeScript | AI web browsing framework by Browserbase. | ✅ Active |
| [Skyvern](https://github.com/Skyvern-AI/skyvern) | 21k+ | Python | Browser automation using LLMs and computer vision. | ✅ Active |
| [LaVague](https://github.com/lavague-ai/LaVague) | 6k+ | Python | Large action model for browser automation. | ✅ Active |

## Voice & Multimodal Agents

*Agents that process voice, images, and multiple modalities.*

| Project | Stars | Language | Description | Maintained |
|---------|-------|----------|-------------|------------|
| [LiveKit Agents](https://github.com/livekit/agents) | 10k+ | Python | Build real-time voice AI agents. | ✅ Active |
| [Pipecat](https://github.com/pipecat-ai/pipecat) | 12k+ | Python | Framework for voice and multimodal conversational AI. | ✅ Active |
| [Vocode](https://github.com/vocodedev/vocode-core) | 3k+ | Python | Open-source library for building voice agents. | ⚠️ Slowing |
| [OpenVoice](https://github.com/myshell-ai/OpenVoice) | 36k+ | Python | Instant voice cloning by MIT and MyShell. | ✅ Active |

## Memory & State

*Give agents persistent memory and context management.*

| Project | Stars | Language | Description | Maintained |
|---------|-------|----------|-------------|------------|
| [Mem0](https://github.com/mem0ai/mem0) | 56k+ | Python | Memory layer for AI agents. Persistent, contextual. | ✅ Active |
| [Letta](https://github.com/letta-ai/letta) | 22k+ | Python | Stateful LLM agents with long-term memory (formerly MemGPT). | ✅ Active |
| [Zep](https://github.com/getzep/zep) | 4k+ | Go | Long-term memory for AI assistants and agents. | ✅ Active |
| [Chroma](https://github.com/chroma-core/chroma) | 28k+ | Python | AI-native embedding database. Most popular for RAG. | ✅ Active |
| [Qdrant](https://github.com/qdrant/qdrant) | 31k+ | Rust | High-performance vector database for AI. | ✅ Active |

## Evaluation & Testing

*Test, evaluate, and monitor AI agents.*

| Project | Stars | Language | Description | Maintained |
|---------|-------|----------|-------------|------------|
| [Promptfoo](https://github.com/promptfoo/promptfoo) | 21k+ | TypeScript | Test prompts, agents, RAGs. CI/CD integration. Used by OpenAI. | ✅ Active |
| [Langfuse](https://github.com/langfuse/langfuse) | 27k+ | TypeScript | LLM observability — tracing, evals, prompt management. | ✅ Active |
| [Arize Phoenix](https://github.com/Arize-ai/phoenix) | 9k+ | Python | ML/LLM observability and evaluation. | ✅ Active |
| [Ragas](https://github.com/explodinggradients/ragas) | 14k+ | Python | RAG evaluation framework. | ✅ Active |
| [DeepEval](https://github.com/confident-ai/deepeval) | 15k+ | Python | Unit testing for LLMs. Pytest-like interface. | ✅ Active |

## Deployment & Infrastructure

*Run, deploy, and scale AI agents in production.*

| Project | Stars | Language | Description | Maintained |
|---------|-------|----------|-------------|------------|
| [LiteLLM](https://github.com/BerriAI/litellm) | 47k+ | Python | Unified API for 100+ LLM providers. Cost tracking. | ✅ Active |
| [Ollama](https://github.com/ollama/ollama) | 171k+ | Go | Run LLMs locally. Dead-simple CLI. | ✅ Active |
| [vLLM](https://github.com/vllm-project/vllm) | 80k+ | Python | High-throughput LLM serving engine. | ✅ Active |
| [LocalAI](https://github.com/mudler/LocalAI) | 46k+ | Go | Self-hosted OpenAI-compatible API. | ✅ Active |
| [Dify](https://github.com/langgenius/dify) | 142k+ | Python/TS | LLM app development platform. Visual workflow builder. | ✅ Active |
| [n8n](https://github.com/n8n-io/n8n) | 189k+ | TypeScript | Workflow automation with 400+ integrations. | ✅ Active |

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
