# The AI Agents Repository

<p align="center">
  <img src="assets/images/1.png" alt="Awesome AI Agents Banner" width="100%">
</p>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

Welcome to the definitive map for navigating the autonomous agent ecosystem in 2026. As artificial intelligence transitions from conversational patterns to structural autonomy, the necessity for robust, scalable, and secure agentic architectures has never been clearer. This index aggregates the most advanced frameworks, offensive security agents, OSINT digesters, and enterprise deployment tools currently defining the state of the art.

Whether you are building distributed systems with Directed Cyclic Graphs (DCGs), configuring container-isolated coding environments, or implementing tensor ablations for red-teaming tasks, this repository serves as a pragmatic, highly technical compass. We prioritize execution capability over hype, focusing strictly on tools that provide tangible operational parity with human counterparts in complex workflows.

---

## 📖 Glossary
To ensure clarity across all repository tables, we classify tools using the following parameters:
- **Engine Classification**:
  - **Local Inference**: Requires access to local hardware resources (GPUs/TPUs) or is optimized for edge/local deployment using quantized models.
  - **API-based**: Execution relies heavily or entirely on managed external endpoints (e.g., OpenAI, Anthropic, Gemini APIs).
  - **Hybrid**: Can operate utilizing both local system intelligence and fallback/routing to external provider APIs.
- **Deployment Mode**: The primary interface for utilizing the tool (e.g., *CLI*, *Web UI*, *Docker*, *Library* / *SDK*).

---

## 📑 Index
1. [AI Agent Frameworks](#1-ai-agent-frameworks)
2. [Programming and Coding Agents](#2-programming-and-coding-agents)
3. [Agentic Workflows and Automation](#3-agentic-workflows-and-automation)
4. [Ethical Hacking and Bug Hunting](#4-ethical-hacking-and-bug-hunting)
5. [OSINT (Open Source Intelligence)](#5-osint-open-source-intelligence)
6. [PC Control and Desktop Automation](#6-pc-control-and-desktop-automation)
7. [Uncensored Models and Jailbreak](#7-uncensored-models-and-jailbreak)
8. [Advanced Guides, Tips, and Prompts](#8-advanced-guides-tips-and-prompts)
9. [GitLab and Corporate Projects](#9-gitlab-and-corporate-projects)
10. [Agent Directories and Marketplaces](#10-agent-directories-and-marketplaces)
11. [Specialized Agents](#11-specialized-agents)
12. [Memory and Persistence for Agents](#12-memory-and-persistence-for-agents)
13. [Evaluation Benchmarks](#13-evaluation-benchmarks)
14. [Simulations of Societies and Virtual Worlds](#14-simulations-of-societies-and-virtual-worlds)
15. [Security, Guardrails, and Alignment](#15-security-guardrails-and-alignment)
16. [Edge and Local AI Agents (Mobile/IoT)](#16-edge-and-local-ai-agents-mobileiot)
17. [Web3 and Crypto Agents](#17-web3-and-crypto-agents)
18. [Voice and Real-Time Audio Agents](#18-voice-and-real-time-audio-agents)
19. [Data Engineering and Analytics Agents](#19-data-engineering-and-analytics-agents)

---

## 1. AI Agent Frameworks
Base infrastructure to build autonomous agents.

| Repository | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **LangChain** | Graph-based routing for NLP operations. Executes abstraction wrappers over proprietary REST APIs and local inferences. | Python/TS | Hybrid | Library | [Link](https://github.com/langchain-ai/langchain) |
| **LangGraph** | Stateful multi-actor orchestrator mapping iterative nodes via Directed Cyclic Graphs (DCGs) with check-pointing. | Python/TS | Hybrid | Library | [Link](https://github.com/langchain-ai/langgraph) |
| **CrewAI** | Role-delegated DAG executor orchestrating task arrays through inter-agent message passing and memory state sharing. | Python | Hybrid | Library | [Link](https://github.com/crewAIInc/crewAI) |
| **AutoGen** | Multi-agent converse framework utilizing socket-based RPC loops for distributed execution safely sandboxed in Docker. | Python | Hybrid | Web UI | [Link](https://github.com/microsoft/autogen) |
| **MetaGPT** | Waterfall SOP emulator mapping standard operational procedures to agent hierarchies for complex codebase iteration. | Python | Hybrid | CLI | [Link](https://github.com/geekan/MetaGPT) |
| **AutoGPT** | Recursive heuristic loop agent generating execution plans with local filesystem caching and vector embeddings. | Python/Docker | Hybrid | Web UI | [Link](https://github.com/Significant-Gravitas/AutoGPT) |
| **Dify** | Backend-as-a-Service architecture unifying API gateways for LLM requests with embedded vector DB routing. | Docker/Python | Hybrid | Web UI | [Link](https://github.com/langgenius/dify) |
| **Camel-AI** | Sociodynamic role-playing simulator executing prompt-based adversarial networks through isolated inference channels. | Python | Hybrid | Library | [Link](https://github.com/camel-ai/camel) |
| **SmolAgents** | Minimal dependency wrapper supporting local safetensors parsing and direct execution of inline python tools. | Python | Hybrid | Library | [Link](https://github.com/huggingface/smolagents) |
| **SuperAGI** | Dockerized scalable infrastructure supporting distributed concurrent agent workers and shared vector store backends. | Docker/Python | Hybrid | Web UI | [Link](https://github.com/TransformerOptimus/SuperAGI) |

---

## 2. Programming and Coding Agents
Development, review, and scaling of source code managed by AI.

| Repository | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Aider** | Command-line AST manipulator supporting real-time git-diff integration and context-aware repository embeddings. | Python | Hybrid | CLI | [Link](https://github.com/Aider-AI/aider) |
| **OpenHands** | Container-isolated execution environment with bidirectional headless browser manipulation and pseudo-TTY interfaces. | Docker/Python | Hybrid | Web UI | [Link](https://github.com/All-Hands-AI/OpenHands) |
| **Void** | Electron-based IDE fork with embedded inference routing, preventing telemetry leakage via local LLM socket binding. | TypeScript | Local Inference | IDE Extension | [Link](https://github.com/voideditor/void) |
| **Continue** | IDE proxy layer routing context payloads and FIM requests to strictly configured local/remote inference endpoints. | TypeScript | Hybrid | IDE Extension | [Link](https://github.com/continuedev/continue) |
| **SWE-agent** | Automated patching daemon mapping GitHub issues to local repository diffs utilizing isolated bash evaluation. | Python | Hybrid | CLI | [Link](https://github.com/princeton-nlp/SWE-agent) |
| **GPT-Engineer** | Scaffolding compiler converting high-level markdown specs to fully initialized workspaces via sequential AST generation. | Python | API-based | CLI | [Link](https://github.com/gpt-engineer-org/gpt-engineer) |
| **Cline** | IDE-embedded background worker interacting with the Language Server Protocol and filesystem watchdogs for code mutating. | TypeScript | Hybrid | IDE Extension | [Link](https://github.com/cline/cline) |
| **Mentat** | CLI abstraction operating over raw file streams and repository graphs for cross-file variable reference propagation. | Python | Hybrid | CLI | [Link](https://github.com/Mentat-AI/mentat) |
| **Plandex** | Go-based background orchestrator executing iterative refactoring tasks through detached daemon processes and git tracking. | Go | Hybrid | CLI | [Link](https://github.com/plandex-ai/plandex) |
| **Tabby** | Rust-optimized inference engine providing low-latency FIM (Fill-In-the-Middle) payload processing for code completion. | Rust/Docker | Local Inference | Docker | [Link](https://github.com/TabbyML/tabby) |

---

## 3. Agentic Workflows and Automation
Integration of agents with APIs, nodes, and conditional process flows.

| Repository | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **GitHub Agentic Workflows** | CI/CD pipeline wrapper converting natural language to GitHub Action YAML files triggering matrix runners. | YAML/TS | API-based | Docker | [Link](https://github.com/github/gh-aw) |
| **Composio** | Authentication middleware providing OAuth2 bridging and strictly-typed endpoint mapping between LLM and 3rd party APIs. | Python/TS | Hybrid | Web UI | [Link](https://github.com/ComposioHQ/composio) |
| **n8n** | Node-based visual workflow engine running native JS sandbox execution and asynchronous event-driven RPC triggers. | TS/Docker | Hybrid | Web UI | [Link](https://github.com/n8n-io/n8n) |
| **PydanticAI** | Type-safe middleware guaranteeing structured JSON output adherence through hardcoded schema validation and retry loops. | Python | Hybrid | Library | [Link](https://github.com/pydantic/pydantic-ai) |
| **Agent-Orchestrator** | Automated PR lifecycle controller validating diffs against test suites using headless execution inside ephemeral CI. | Python | API-based | CLI | [Link](https://github.com/ComposioHQ/agent-orchestrator) |
| **LLM Workflow Engine** | Pipeline executor processing sequential prompts and branching logic through deterministic finite automata state machines. | Python | Hybrid | Web UI | [Link](https://github.com/llm-workflow-engine/llm-workflow-engine) |
| **Bee Agent Framework** | Enterprise-grade SDK enforcing hardened guardrails, strict data plane routing, and audit-logging compliance. | TypeScript | Hybrid | Library | [Link](https://github.com/i-am-bee/bee-agent-framework) |
| **Awesome LLM Apps** | Technical boilerplate and infrastructure definitions for production RAG microservices and scalable vector integrations. | Markdown | N/A | Document | [Link](https://github.com/Shubhamsaboo/awesome-llm-apps) |

---

## 4. Ethical Hacking and Bug Hunting
Penetration testing, vulnerability analysis, and offensive routines.

| Repository | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **HexStrike AI** | Execution of native offensive dependencies. Requires root privileges for raw sockets and offers basic EDR evasion. | Python | API-based | CLI | [Link](https://github.com/0x4m4/hexstrike-ai) |
| **Claude Bug Bounty** | AST repository analyzer. Generates dry structured payloads (does not auto-execute dynamic payloads). | Python/TS | API-based | CLI | [Link](https://github.com/shuvonsec/claude-bug-bounty) |
| **PentestAgent** | Black-Box operator using network sub-processes. Unencrypted traffic detectable by standard IDS; statically auto-generated payloads. | Python | Hybrid | CLI | [Link](https://github.com/GH05TCREW/pentestagent) |
| **Pentagi** | Kill Chain execution delegated to Docker. Lacks obfuscation or native L7 firewall bypass. | Docker/Go | Hybrid | Web UI | [Link](https://github.com/vxcontrol/pentagi) |
| **CAI** | TCP/UDP services inference. Passive protocols without offensive exploitation payload generation. | Python | Hybrid | Library | [Link](https://github.com/aliasrobotics/CAI) |
| **Awesome AI Cybersecurity** | Structured references for Red Team modeling. Purely documentary passive environment. | Markdown | N/A | Document | [Link](https://github.com/ElNiak/awesome-ai-cybersecurity) |

---

## 5. OSINT (Open Source Intelligence)
Extraction, filtering, and summarization of information from public sources.

| Repository | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **OSINT AI Agent** | Continuous domain reconnaissance sequences. Executes massive queries to APIs (Shodan/Censys) susceptible to cap limits. | Python | API-based | CLI | [Link](https://github.com/dazzyddos/OSINT_AI_Agent) |
| **AI OSINT** | Automated tracking of Google Dorks syntax. Extracts extensive indexes; requires proxy rotation to evade bans. | Python | API-based | CLI | [Link](https://github.com/7WaySecurity/ai_osint) |
| **AI-Resources** | Scripts for static headless scraping (Selenium). Extracts profile networks but struggles with dynamic JS validations and CAPTCHAs. | Python | Hybrid | CLI | [Link](https://github.com/The-Osint-Toolbox/AI-Resources) |
| **Awesome Cybersecurity Agentic AI** | Compilation of repositories and passive analysis schemas for OSINT sources. | Markdown | N/A | Document | [Link](https://github.com/raphabot/awesome-cybersecurity-agentic-ai) |
| **Ubikron Graph Architecture** | Correlation of intelligence entities via graph databases. Maps iterative B2B relationships. | Graph/Neo4j | Local Inference | Web UI | [Link](https://github.com/ubikron/Awesome-AI-OSINT) |
| **Awesome OSINT Digester** | Comprehensive directory of OSINT sources for manual intelligence gathering and agentic ingestion. | Python | Hybrid | CLI | [Link](https://github.com/jivoi/awesome-osint) |

---

## 6. PC Control and Desktop Automation
Multimodal interactors for graphical interfaces via mouse and keyboard clicks.

| Repository | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Self-Operating Computer** | Mouse and keyboard management through multimodal models. | Python | API-based | CLI | [Link](https://github.com/othersideai/self-operating-computer) |
| **Agent S** | Asynchronous progressive processing for complex OS tasks. | Python | Hybrid | CLI | [Link](https://github.com/simular-ai/agent-s) |
| **Browser-use** | Direct interface between LLMs and web browser instances. | Python | API-based | CLI | [Link](https://github.com/browser-use/browser-use) |
| **CUA** | Desktop container simulation environment. | Docker/Py | Local Inference | Docker | [Link](https://github.com/trycua/cua) |
| **Bytebot** | Control of containers with natural language commands. | Python | Hybrid | Docker | [Link](https://github.com/bytebot-ai/bytebot) |
| **Agent-Desktop** | Structured native adapter for GUI applications. | Rust | Local Inference | CLI | [Link](https://github.com/lahfir/agent-desktop) |

---

## 7. Uncensored Models and Jailbreak
Red Teaming, filter evasion, and tensor alteration in base models.

| Repository | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Heretic** | Orthogonal tensor ablation. VRAM: 12GB+ (8B), 24GB+ (32B). Formats: Safetensors. Framework: HF Transformers/Native PyTorch. | Python | Local Inference | CLI | [Link](https://github.com/p-e-w/heretic) |
| **USB-Uncensored-LLM** | Encapsulated binary environment. VRAM: 8GB to 16GB. Supported formats: GGUF (Q4_K_M, Q5_K_M). Framework: llama.cpp. | Python/CPP | Local Inference | Docker | [Link](https://github.com/techjarves/USB-Uncensored-LLM) |
| **Dolphin Mixtral** | Derived MoE model weights. VRAM: 32GB+ (GGUF Q4) or 2x24GB (AWQ/GPTQ). Frameworks: vLLM (for AWQ), Ollama (GGUF). | Weights | Local Inference | Web UI | [Link](https://github.com/udbhav-44/Dolphin_uncensored) |
| **Awesome Jailbreak on LLMs** | Iterative attack vectors (GCG) and heuristic injection over model context windows. | Markdown | N/A | Document | [Link](https://github.com/yueliu1999/Awesome-Jailbreak-on-LLMs) |
| **LLM-Jailbreaks** | Logical exploits based on overflow or semantic validators and pre-prompts manipulation. | Text | Hybrid | Document | [Link](https://github.com/langgptai/LLM-Jailbreaks) |
| **Red Team AI Benchmark** | Automated pipelines for robustness evaluation and filtering across MLaaS endpoints and local nodes. | Python | Hybrid | CLI | [Link](https://github.com/toxy4ny/redteam-ai-benchmark) |
| **Geneva** | Native TCP/IP root manipulation to evade Layer 7 firewalls and Deep Packet Inspection (DPI) over LLM traffic. | Python | Local Inference | Docker | [Link](https://github.com/Kkevsterrr/geneva) |

---

## 8. Advanced Guides, Tips, and Prompts
Context architecture, design manuals, and additional directories.

| Repository | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Prompt Engineering Guide** | Exhaustive techniques for structuring LLMs and agents. | Markdown | N/A | Document | [Link](https://github.com/dair-ai/Prompt-Engineering-Guide) |
| **12-Factor Agents** | Technical specification regarding agentic state control. | Markdown | N/A | Document | [Link](https://github.com/humanlayer/12-factor-agents) |
| **Awesome LLM Skills** | Reusable functions and dependencies for pipelines. | Markdown | N/A | Document | [Link](https://github.com/Prat011/awesome-llm-skills) |
| **Useful AI Prompts** | Technical prompts aimed at programmers and deployment. | Markdown | N/A | Document | [Link](https://github.com/aj-geddes/useful-ai-prompts) |
| **AI Agent Best Practices** | Architecture and risk control of scalable systems. | Markdown | N/A | Document | [Link](https://github.com/github/awesome-copilot/blob/main/instructions/ai-prompt-engineering-safety-best-practices.instructions.md) |
| **Awesome AI Agents** | Massive E2B directory with 100+ extra repositories. | Markdown | N/A | Document | [Link](https://github.com/e2b-dev/awesome-ai-agents) |
| **Awesome Agents (Kyrolabs)** | Extensive compilation of autonomy tools. | Markdown | N/A | Document | [Link](https://github.com/kyrolabs/awesome-agents) |
| **Awesome AI Agents 2026** | List of emerging repositories and trends. | Markdown | N/A | Document | [Link](https://github.com/caramaschiHG/awesome-ai-agents-2026) |

---

## 9. GitLab and Corporate Projects
Tools focused on DevSecOps and enterprise pipeline governance.

| Project | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **GitLab Duo Agent Platform** | Agentic ecosystem integration in native CI/CD cycles. | Integration | API-based | Web UI | [Link](https://about.gitlab.com/gitlab-duo-agent-platform/) |
| **COSMOS CI Agent** | Intelligent dependency and trace analyzer in GitLab repositories. | Python | API-based | Docker | [Link](https://gitlab.com/explore/ai-catalog) |
| **Virtual Company Kernel** | Corporate structural role simulation with pure AI. | Python | Hybrid | CLI | [Link](https://gitlab.com/borrowbrain/virtual-company-kernel) |
| **Ray Agentic Core** | Base layer for distributed routing, state management, and inference execution across multi-agent node clusters. | C++/Python | Hybrid | Docker | [Link](https://github.com/ray-project/ray) |
| **Bloop AI** | Real-time active cloud container debugger and codebase navigational agent for distributed platforms. | TS/Rust | API-based | Web UI | [Link](https://github.com/BloopAI/bloop) |

---

## 10. Agent Directories and Marketplaces
Portals to compare frameworks and hosted agents.

| Repository | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **AI Agents Directory** | Categorized index of +1,300 utilities. | Web | N/A | Web UI | [Link](https://aiagentsdirectory.com/) |
| **AI Agents List** | Feature and pricing evaluation of +600 software solutions. | Web | N/A | Web UI | [Link](https://aiagentslist.com/) |
| **Hugging Face Agents** | Native integration and validated list of autonomous models. | Web | N/A | Web UI | [Link](https://huggingface.co/blog/tegridydev/open-source-ai-agents-directory) |

---

## 11. Specialized Agents
Optimized semantic processing for professional and regulated fields.

### Finance and Investment
| Project | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **FinRobot** | Ingestion and quantitative analysis of corporate documents. | Python | API-based | Library | [Link](https://github.com/ai4finance-foundation/finrobot) |
| **Dexter** | Iterative balance sheet research via reflection chains. | Python | API-based | CLI | [Link](https://github.com/virattt/dexter) |
| **TradingAgents** | Distributed environment for transaction simulation. | Python | Hybrid | Docker | [Link](https://tradingagents-ai.github.io/) |

### Medicine and Healthcare
| Project | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **AI Agents Healthcare** | Modeling for FHIR compliance and US revenue analysis. | Various | API-based | Library | [Link](https://github.com/AgenticHealthAI/Awesome-AI-Agents-for-Healthcare) |
| **OpenClaw Medical Skills** | Pre-trained operations on biomedical variables. | Python | Hybrid | Web UI | [Link](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) |
| **HealthcareAgent** | Unification of logic layers and interfaces in clinical applications. | Python/Java | API-based | Library | [Link](https://github.com/AI-Hub-Admin/HealthcareAgent) |

### Legal and Auditing
| Project | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **LawGlance** | RAG engine bounded to regulatory processing. | Python/React | Hybrid | Web UI | [Link](https://github.com/lawglance/lawglance) |
| **Octochains** | Strict execution conditionals based on regulatory risks. | TS/Python | API-based | Web UI | [Link](https://github.com/ahmadvh/octochains) |
| **LawAgent** | Sub-routines for iterative structuring of legal opinions. | Python | API-based | Web UI | [Link](https://github.com/AI-Hub-Admin/LawAgent) |

---

## 12. Memory and Persistence for Agents
Semantic hypervectorial storage persisting across context limitations.

| Repository | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Mem0** | Automatic interaction extraction into universal LTM layers. | Python | Hybrid | Web UI | [Link](https://github.com/mem0ai/mem0) |
| **MemGPT** | RAM block management in LLMs acting as structured OS memory. | Python | Hybrid | Web UI | [Link](https://github.com/deductive-ai/MemGPT) |
| **Zep** | Asynchronous collector and heuristic router for short-term memory. | Go/Docker | Hybrid | Docker | [Link](https://github.com/getzep/zep) |
| **Graphiti** | Entity compilation into dynamic graph and relation meshes. | Python | API-based | Library | [Link](https://github.com/getzep/graphiti) |
| **AgentMemory** | Indexable segmented vectors focused on code dependencies. | Python | Local Inference | CLI | [Link](https://github.com/rohitg00/agentmemory) |

---

## 13. Evaluation Benchmarks
Parameterized sets of cases for deterministic measurement.

| Benchmark | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **GAIA** | Asynchronous resolution metric via general agents. | Python/HF | N/A | Document | [Link](https://huggingface.co/datasets/gaia-benchmark/GAIA) |
| **SWE-bench** | Success ratio on repository merges and bug fixes. | Docker/Py | N/A | CLI | [Link](https://github.com/princeton-nlp/SWE-bench) |
| **AgentBench** | Synthetic agent verification across 8 types of sandbox environments. | Python | N/A | CLI | [Link](https://github.com/THUDM/AgentBench) |
| **WebArena** | Automated interactivity score across 4 cloned web microservices. | Docker/TS | N/A | CLI | [Link](https://github.com/web-arena-x/webarena) |

---

## 14. Simulations of Societies and Virtual Worlds
Experimentation on autonomous group behaviors by unifying multiple LLMs.

| Repository | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Generative Agents** | 2D social emulation based on cyclic priorities over memories. | Python | API-based | Web UI | [Link](https://github.com/joonspk-research/generative_agents) |
| **AgentSociety** | C++ orchestration for simulating metropolises of up to 30K agents. | C++/Python | Hybrid | Web UI | [Link](https://github.com/tsinghua-fib-lab/agentsociety) |
| **OASIS** | Optimized inference for virtual networks of one million entities. | Python/GPU | Hybrid | Web UI | [Link](https://github.com/camel-ai/oasis) |
| **Gamma-World** | Generative computation and regression of social and mundane variables. | Python | API-based | Web UI | [Link](https://github.com/nv-tlabs/Gamma-World) |


---

## 15. Security, Guardrails, and Alignment
Frameworks and pipelines designed to enforce policy constraints, prevent prompt injections, and align autonomous agents to specific safety protocols.

| Repository | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **NeMo Guardrails** | Configurable execution constraint mechanisms enforcing topological programmable limits via semantic similarity vectors. | Python | Hybrid | Library | [Link](https://github.com/NVIDIA/NeMo-Guardrails) |
| **Llama Guard** | Tuned safeguard classifier determining adversarial input topologies to reject unsafe conversational payloads. | Llama | API-based | Library | [Link](https://github.com/meta-llama/PurpleLlama) |
| **Garak** | Systematic vulnerability scanner probing for hallucination vectors and jailbreak surfaces in LLM agents. | Python | API-based | CLI | [Link](https://github.com/leondz/garak) |
| **Lakera Guard** | Comprehensive API-based security middleware blocking active execution attacks on agentic APIs. | Python | API-based | API | [Link](https://github.com/lakeraai) |

---

## 16. Edge and Local AI Agents (Mobile/IoT)
Small language models (SLMs) and pruned tensors optimized natively for device-edge execution on resource-constrained hardware.

| Repository | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **MLC LLM** | Universal compiler deploying LLMs with aggressive static memory allocation to iOS, Android, and WebGPU architectures. | C++/Python | Local Inference | App/Web | [Link](https://github.com/mlc-ai/mlc-llm) |
| **ExecuTorch** | PyTorch-native runtime supporting optimized quantized execution of specialized sub-agents on microcontroller environments. | C++/PyTorch | Local Inference | Embedded | [Link](https://github.com/pytorch/executorch) |
| **TinyLlama** | Highly dense 1.1B parameter checkpoint aggressively optimized for near-instant inference routing on portable devices. | Weights | Local Inference | Library | [Link](https://github.com/jzhang38/TinyLlama) |

---

## 17. Web3 and Crypto Agents
Autonomous financial agents interacting natively with blockchain nodes, executing deterministic EVM smart contracts, or trading autonomously.

| Repository | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Eliza** | Specialized multi-agent framework tailored for interacting with crypto endpoints, executing DeFi operations, and orchestrating decentralized DAOs. | TypeScript | Hybrid | Node | [Link](https://github.com/elizaOS/eliza) |
| **Rig** | Rust-native ecosystem building secure Web3 agents capable of deterministic contract execution and complex state transitions. | Rust | Hybrid | Node | [Link](https://github.com/0xPlaygrounds/rig) |
| **Goat** | The Great Open Agent Toolkit. Middleware connecting off-chain AI reasoning with on-chain EVM transactional networks. | TypeScript | Hybrid | Web UI | [Link](https://github.com/goat-sdk/goat) |

---

## 18. Voice and Real-Time Audio Agents
Frameworks and pipelines optimized for low-latency voice-to-voice communication, streaming speech recognition, and synthesized audio reasoning.

| Repository | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Pipecat** | Open-source framework for building voice and multimodal conversational agents featuring WebRTC bindings and streaming VAD. | Python/TS | API-based | Web/Node | [Link](https://github.com/pipecat-ai/pipecat) |
| **LiveKit Agents** | High-performance infrastructure explicitly designed to host real-time programmable audio agents over globally distributed WebRTC meshes. | Go/Python | API-based | SDK | [Link](https://github.com/livekit/agents) |
| **Vapi** | End-to-end voice AI platform abstraction allowing integration of interrupting, context-aware audio agents natively via SIP/WebRTC. | TypeScript | API-based | Web/App | [Link](https://github.com/VapiAI) |

---

## 19. Data Engineering and Analytics Agents
Automated systems that ingest chaotic data environments, generate complex SQL/Python transformations, and auto-orchestrate ETL pipelines.

| Repository | Description | Stack | Engine | Deployment | Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Dataherald** | Natural Language-to-SQL engine constructed over relational databases, supporting RAG-style schema alignment and determinism. | Python | Hybrid | Web UI | [Link](https://github.com/Dataherald/dataherald) |
| **PandasAI** | Conversational data analysis library that allows users to interact with their databases and dataframes using natural language. | Python | API-based | Jupyter | [Link](https://github.com/sinaptik-ai/pandas-ai) |
| **LlamaIndex** | Though a data framework, its Agentic Data Engines autonomously route, synthesis, and query disparate vector and SQL nodes. | Python/TS | Hybrid | Library | [Link](https://github.com/run-llama/llama_index) |
| **AI for Database** | Agentic AI that connects to any database (Postgres, MySQL, MongoDB) and enables natural language querying, self-refreshing dashboards, and workflow automation. | SaaS | Hybrid | Web UI | [Link](https://aifordatabase.com) |

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! We encourage the community to submit Pull Requests to expand this repository. If you have a tool or repository to suggest, please ensure it aligns with the high technical standard and format of the existing tables (specifying Stack, Engine, and Deployment accurately).

