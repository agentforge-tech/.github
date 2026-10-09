# AgentForge

**One Core. Multiple Agent Experiences.**

Open-source AI Agent infrastructure for building, running, and evolving intelligent agents.

AgentForge is dedicated to building a unified, reusable, and extensible foundation for AI Agent systems. Our goal is to power different Agent experiences through a shared core runtime, rather than rebuilding foundational capabilities for every product.

## Architecture

```text
                    AgentForge Core
                          |
                 LLM Model Protocol
                          |
                    ReAct Agent
                          |
                    Harness Agent
                          |
          +---------------+---------------+
          |               |               |
          v               v               v
        Service          CLI            Desktop
```

## Core Infrastructure

**LLM Model Protocol**

A provider-independent model abstraction designed to support multiple LLM providers, unified messaging, streaming, and tool calling.

**ReAct Agent Runtime**

A reusable Agent runtime built around reasoning, tool execution, context management, memory, streaming, and lifecycle management.

**Harness Agent**

An execution layer focused on permissions, human approval, pause and resume, sandboxing, state management, and observability.

## Ecosystem

| Project | Description | Status |
|---|---|---|
| [AgentForge](https://github.com/agentforge-tech/AgentForge) | Core Agent framework and runtime | In Development |
| AgentForge-Service | Agent service platform and API infrastructure | Planned |
| AgentForge-CLI | Terminal-based Agent experiences | Planned |
| AgentForge-Desktop | Local desktop Agent workspace | Planned |

## Design Principles

- **Unified Core** — One foundation shared across different Agent products.
- **Provider Independent** — Decouple Agent capabilities from specific LLM providers.
- **Composable Architecture** — Build extensible components with clear boundaries.
- **Production Oriented** — Focus on execution control, reliability, and observability.
- **Open Source** — Encourage collaboration and long-term evolution.

## Get Started

Explore our core framework:

**[AgentForge on GitHub](https://github.com/agentforge-tech/AgentForge)**

Contributions, discussions, and feedback are welcome.

---

**AgentForge-Tech** — Building the foundation for the next generation of AI Agents.
