# AI FOMO

> A curated collection of trending open-source AI projects, tools, skills, agents, and experiments — updated for builders who don't want to miss what's next.
>
> Last reviewed: March 27, 2026

AI moves fast. Agent tooling moves faster.

This repo is not a generic "awesome list". It is a focused watchlist for builders who want a tighter filter on what is actually worth tracking.

Projects make this list when they are not just interesting, but operationally relevant for real agent systems.

This repo favors projects that:
- matter for real agent systems, not just demos
- have strong attention or momentum
- solve durable problems likely to matter for the next 6 to 18 months
- remain genuinely useful even after the hype cycle cools down

## How to use this repo

Use this repo in three ways:
- as a high-signal watchlist if you only want to track a small number of projects
- as a market map if you are deciding which layer of the agent stack to build on
- as a curation lens if you want to separate durable infrastructure from short-lived hype

If you are new to the space, start with `If you only track 10`.
If you already build agents, jump to `Build by use case`.
If you care about where the ecosystem is heading next, read the `Skills and Protocols` section too.

> **Note:** To maintain the highest signal-to-noise ratio, each category in this README is strictly limited to 6-8 projects. For a broader look at other trending and honorable mentions, see the [EXTENDED_WATCHLIST.md](./EXTENDED_WATCHLIST.md).

## Scope

This repo is biased toward:
- browser and computer-use agents
- coding agents
- CLI and terminal-native agents
- agent runtimes and orchestration
- memory and state
- skills and reusable capability packs
- model gateways and routing
- standard communication protocols (MCP, A2A)
- serving, local runtime, and deployment layers

This repo generally skips:
- closed-source wrappers
- prompt-only collections
- model-only launches with little builder surface area
- projects with license restrictions that make them a gray area for an OSS-only list

## How this list is curated

This list does not use GitHub stars alone.

Projects are selected using a mix of:
- official repos and docs
- release cadence and changelog velocity
- developer-community discussion across Hacker News and broader web chatter
- whether the project improves a real part of the agent stack
- whether the project still looks useful after removing the hype narrative

## Selection rubric

Projects are more likely to make the list when they score well on at least three of these:
- clear leverage for builders, not just a flashy demo
- fast enough release cadence to show active product learning
- credible docs, examples, or developer onboarding
- clean enough licensing for an OSS-focused reader
- strong user pull across GitHub, docs, social chatter, or community discussion
- a durable place in the stack instead of a short-lived wrapper layer

## Status guide

- `Breakout`: attention is accelerating and the category signal looks real
- `Durable`: already meaningful and likely to remain part of the stack
- `Emerging`: early, uneven, or still forming, but worth active tracking

## Current thesis

The open-source agent stack is consolidating around eight layers:
1. Browser and computer use
2. Software engineering and CLI agents
3. Stateful runtimes and orchestration
4. Memory and context layers
5. Gateway, model routing, and tool integration
6. Serving and local runtime
7. Standard communication protocols (e.g., MCP, A2A)
8. Skills and reusable capability packs

## If you only track 10

1. Browser Use
2. OpenClaw
3. OpenHands
4. LangGraph
5. n8n
6. Mem0
7. LiteLLM
8. vLLM
9. Ollama
10. Composio

## Curated watchlist

*(Note: Each category is strictly curated to 6-8 high-conviction items.)*

### 1) Breakout attention

| Project | Layer | Why it matters for agents | Status |
|---|---|---|---|
| [Browser Use](https://github.com/browser-use/browser-use) | Browser agents | Turns websites into agent surfaces. Spanning past 78,000 stars, it's the clearest signal that browser-native agents are a real product category. | Breakout |
| [OpenClaw](https://github.com/openclaw/openclaw) | Personal agent platform | An astonishing 210,000+ stars by early 2026. Acquired by OpenAI, it blends a serious CLI, system skills, and local workflow automation. | Breakout |
| [OpenHands](https://github.com/OpenHands/OpenHands) | Coding agents | The strongest open-source bet for software engineering agents and autonomous coding workflows, now powered by the highly optimized `software-agent-sdk`. | Breakout |
| [n8n](https://github.com/n8n-io/n8n) | Workflow automation | Fair-code UI for building logic-heavy AI workflows. With 180,000+ stars, it merges AI with powerful API integration capabilities natively. | Breakout |
| [Composio](https://github.com/ComposioHQ/composio) | Tool integration | An emerging critical "action layer" platform offering 500+ secure, pre-built LLM-optimized toolkits (GitHub, etc.) to give agent "brains" a "body." | Breakout |
| [Crawl4AI](https://github.com/unclecode/crawl4ai) | Web data for agents | Gives agents cleaner web extraction than ad-hoc scraping. The v0.8.0 release brings crash recovery, stealth capabilities, and self-hosting. | Breakout |
| [Langflow](https://github.com/langflow-ai/langflow) | Visual agent builder | A high-adoption visual layer (140,000+ stars) for building and shipping agent workflows without losing deployment flexibility. | Breakout |
| [RAGFlow](https://github.com/infiniflow/ragflow) | Document & Context engine | Combines deep document understanding with agent capabilities. Rapidly scaling past 74,000 stars as the default structured RAG engine in production. | Breakout |

### 2) High-conviction, durable bets

| Project | Layer | Why it matters for agents | Status |
|---|---|---|---|
| [LangGraph](https://github.com/langchain-ai/langgraph) | Stateful runtime | The standard for complex workflows requiring loops, branching, and state. v1.1 brings a highly predictable Functional API and deep Pydantic validation. | Durable |
| [CrewAI](https://github.com/crewAIInc/crewAI) | Multi-agent orchestration | Massive enterprise adoption. Highly visible role-based multi-agent orchestration, expanding significantly with their Agent Operations Platform (AOP). | Durable |
| [Mem0](https://github.com/mem0ai/mem0) | Memory layer | Adopted by AWS as a core memory provider and boasting 41,000+ stars, offering a multi-store layer (vector, graph, key-value) for long-term agent context. | Durable |
| [LlamaIndex](https://github.com/run-llama/llama_index) | Data & Agent framework | Shifting heavily into agentic capabilities with event-driven workflows, Agent Client Protocol (ACP) integration, and advanced document processing. | Durable |
| [LiteLLM](https://github.com/BerriAI/litellm) | Gateway and routing | The proxy standard. Heavily updated in early 2026 with Agent-to-Agent (A2A) invocation, MCP Global Mode, and deep organizational cost controls. | Durable |
| [Ollama](https://github.com/ollama/ollama) | Local runtime | The default for local LLM deployment. Recent updates bring native Windows ARM64 support, OpenClaw integration, and headless automation. | Durable |
| [vLLM](https://github.com/vllm-project/vllm) | Serving engine | The high-throughput workhorse. Expanding heavily in 2026 with FP8 inference, FlashAttention 4, and disaggregated multimodal serving (vLLM-Omni). | Durable |
| [SGLang](https://github.com/sgl-project/sglang) | Serving engine | Highly performant for extreme throughput. Optimized for next-generation hardware (GB300, Blackwell), offering general FP8 quantization. | Durable |

### 3) Early, but likely to matter

| Project | Layer | Why it matters for agents | Status |
|---|---|---|---|
| [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) | Multi-agent framework | The production-ready evolution of OpenAI's experimental "Swarm", offering dynamic handoffs, modular standard architectures, and strict guardrails. | Emerging |
| [SWE-agent](https://github.com/princeton-nlp/SWE-agent) | Autonomous software engineer | Princeton/Stanford's research-backed agent. Specifically tailored with a custom Agent-Computer Interface (ACI) to resolve GitHub issues automatically. | Emerging |
| [Mastra](https://github.com/mastra-ai/mastra) | TypeScript agent framework | Passed v1.0 with robust supervisor patterns for multi-agent coordination, persistent filesystems, and native TypeScript type-safe inference capabilities. | Emerging |
| [Devika](https://github.com/stitionai/devika) | Autonomous software engineer | An active open-source alternative to Devin, combining planning algorithms and web browsing to push autonomous feature development forward. | Emerging |
| [PydanticAI](https://github.com/pydantic/pydantic-ai) | Python agent framework | Nearing 16,000 stars. Uses standard Python typing and Pydantic validation to offer a highly credible, production-minded approach to agent I/O. | Emerging |
| [SmolAgents](https://github.com/huggingface/smolagents) | Python agent framework | Hugging Face's lightweight framework emphasizing a "CodeAgent" philosophy—agents generate Python code to execute actions instead of JSON tool calls. | Emerging |
| [Stagehand](https://github.com/browserbase/stagehand) | Browser automation | A structured path from natural language to repeatable browser actions for workflows that need rigid verification and state awareness. | Emerging |

### 4) High-value CLI and terminal-native tools

| Project | Layer | Why it matters for agents | Status |
|---|---|---|---|
| [Aider](https://github.com/Aider-AI/aider) | Terminal coding workflow | Still the most battle-tested CLI pair programmer for developers who want strict git discipline and human-in-the-loop granular code editing. | Durable |
| [Gemini CLI](https://github.com/google/gemini-cli) | Terminal reasoning agent | Google's open-source ReAct loop terminal agent for complex debugging, featuring built-in tools and direct workspace integration. | Breakout |
| [Cline](https://github.com/cline/cline) | CLI & IDE coding agent | Brings Plan/Act modes and native MCP integration to developers. Deeply extensible into CI pipelines and cron jobs for hands-off automation. | Breakout |
| [OpenCode](https://github.com/anomalyco/opencode) | Terminal-native coding agent | A highly visible TUI-first coding agent built for ecosystem scale, supporting provider-agnostic planners and workflows. | Breakout |
| [Crush](https://github.com/charmbracelet/crush) | Terminal-native coding agent | From the Charm tooling team: a highly polished terminal agent blending built-in skill workflows, deep aesthetics, and local MCP tool awareness. | Breakout |
| [Plandex](https://github.com/plandex-ai/plandex) | Large-task CLI agent | A strong choice for spanning multi-step implementation work across extremely large codebases where standard context windows start to fragment. | Durable |
| [Qwen Code](https://github.com/QwenLM/qwen-code) | Optimized terminal agent | Specifically fine-tuned for Qwen3-Coder models, offering multi-protocol support and excellent large codebase navigation directly in the terminal. | Emerging |

### 5) Agent Skills, Standards, and Workflows

Skills and interoperable protocols are becoming a foundational layer of the agent stack, moving far beyond prompt tricks.

| Project | Layer | Why it matters | Status |
|---|---|---|---|
| [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) | Context & communication standard | Now under the Linux Foundation (AAIF) as of March 2026. With 6,400+ servers, its newest roadmap elevates Agent-to-Agent (A2A) to a first-class concept. | Breakout |
| [A2A Protocol](https://github.com/a2a-protocol/a2a) | Agent communication standard | Donated to the Linux Foundation by Google. Provides a standardized HTTP/JSON-RPC pipeline for diverse AI agents to seamlessly negotiate and collaborate. | Emerging |
| [Superpowers](https://github.com/obra/superpowers) | Workflow system | The strongest open-source bet on skills as a full development methodology: design, planning, TDD, review, delegation, and verification. | Breakout |
| [gstack](https://github.com/garrytan/gstack) | Workflow system | A highly opinionated "software factory" built from slash-command specialists and skill files. High signal for structured review gates. | Breakout |
| [BETTER-SKILLS](https://better-skills.dev/) | Discovery & management | Pushes skills beyond loose files toward synced, versioned, graph-shaped agent context. | Emerging |
| [Skillport](https://github.com/gotalab/skillport) | Discovery & management | A pragmatic bridge that helps teams manage skill libraries across CLI agents and MCP-compatible tools. | Emerging |
| [Agent Skills](https://agentskills.io/home) | Standard & runtime | A portable open format for packaging instructions and resources into strict, loadable skill templates. | Emerging |
| [Open Agent Skills](https://openagentskills.dev/) | Discovery hub | Shows that search, sharing, and curation for reusable agent skills is rapidly becoming its own product surface. | Emerging |

## Build by use case

### If you care about browser and computer-use agents

Start with:
- Browser Use
- Stagehand
- Crawl4AI

### If you care about coding agents

Start with:
- OpenHands
- LangGraph
- PydanticAI
- LlamaIndex
- OpenAI Agents SDK / SWE-agent

### If you care about shipping agent products and pipelines

Start with:
- n8n
- Langflow
- CrewAI
- Composio
- RAGFlow
- Mem0

### If you care about self-hosted or local agent stacks

Start with:
- Ollama
- LiteLLM
- vLLM
- SGLang

### If you care about CLI and terminal-native agents

Start with:
- OpenClaw
- OpenCode
- Crush
- Aider
- Gemini CLI
- Plandex
- Cline

### If you care about deep integration protocols

Start with:
- Model Context Protocol (MCP)
- A2A Protocol

## Projects intentionally left out of the core OSS list

These projects may still be important in practice, but they are not treated here as clean open-source defaults for an OSS-only list:

- Dify
  - Important product with over 120,000+ stars, but the licensing model should be reviewed carefully.
  
- Open WebUI
  - Very widely used in self-hosted setups, but newer versions add branding protection clauses, pushing it into a gray area.

## What would make a project enter this list

A project is more likely to get added if it has at least two of these:
- clear fit for real agent systems
- strong community attention
- fast release cadence
- evidence of production-minded features
- strong developer love
- durable leverage beyond the current hype cycle

## Contributing

PRs are welcome. Please ensure the project aligns with the criteria and does not push a category over the 8-item limit (older projects may need to be moved to the EXTENDED_WATCHLIST).

## License

- Code in this repository: MIT
- Curated content in this repository: CC BY 4.0
