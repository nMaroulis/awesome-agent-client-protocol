# Awesome Agent Client Protocol (ACP)

A curated list of awesome frameworks, tools, agents, and resources for the [Agent Client Protocol (ACP)](https://agentclientprotocol.com/), the open standard for IDE-Agent interoperability.

The Agent Client Protocol (ACP) does for AI agents what the Language Server Protocol (LSP) did for code intelligence: it completely decouples the code editor from the AI agent. Build your agent once, and let users run it in Zed, IntelliJ, PyCharm, WebStorm, and any future ACP-compatible editor.

## Contents

* [Official Resources](#official-resources)
* [Editors & IDEs](#editors--ides)
* [Agents](#agents)
* [Cloud & Hybrid Agents](#cloud--hybrid-agents)
* [Local & Open-Source Agents](#local--open-source-agents)


* [Frameworks & SDKs](#frameworks--sdks)
* [Model Context Protocol (MCP) Integration](#model-context-protocol-mcp-integration)

## Official Resources

* [ACP Official Website](https://agentclientprotocol.com/) - The core documentation, guides, and specification for the protocol.
* [ACP GitHub Repository](https://github.com/agentclientprotocol/agent-client-protocol) - The core repository maintained by the creators (JetBrains and Zed).
* [The ACP Registry](https://github.com/agentclientprotocol/registry) - The official JSON registry where developers can publish their agents for discovery inside IDEs.

## Editors & IDEs

Code editors that natively support the Agent Client Protocol as clients.

* [Zed](https://zed.dev/) - A high-performance, multiplayer code editor from the creators of Atom. Features native, visually rich ACP integration.
* [JetBrains IDEs](https://www.jetbrains.com/acp/) - Full ACP support via the official JetBrains AI tooling (IntelliJ IDEA, PyCharm, WebStorm, Rider, etc.).

## Agents

Autonomous coding assistants that implement the ACP server specification.

### Cloud & Hybrid Agents

* [Claude Agent](https://github.com/agentclientprotocol/registry) - Anthropic's reference implementation bringing Claude's orchestration into the IDE.
* [Gemini CLI](https://github.com/agentclientprotocol/registry) - Google's reference implementation showing the full potential of ACP agent integration.
* [Augment Code](https://www.augmentcode.com/) - High-performance AI agent built for enterprise codebases.
* [Mistral Vibe](https://mistral.ai/) - An AI coding agent powered by state-of-the-art Mistral coding models.

### Local & Open-Source Agents

Agents designed to run locally, prioritizing privacy and local LLM inference (Ollama, LM Studio).

* [Cline](https://github.com/cline/cline) - The gold standard open-source autonomous coding agent. Supports massive multi-tool orchestration, local models, and seamless ACP integration.
* [Goose](https://block.github.io/goose/) - A local, extensible, open-source AI agent built by Block. Designed to run offline and seamlessly plug into IDEs via ACP.
* [DeepAgents](https://github.com/langchain-ai/deepagentsjs) - A batteries-included AI coding agent framework powered by LangChain, natively supporting ACP and multi-agent routing.
* [ProtoAgent](https://github.com/yourusername/protoagent) *(Work in Progress)* - A Python-based, open-source orchestration layer specifically built to route ACP requests to local LLMs (Ollama) with integrated MCP tool support.

## Frameworks & SDKs

Libraries and tools to help you build your own ACP-compatible agent.

* **[Python SDK](https://github.com/agentclientprotocol/agent-client-protocol/tree/main/sdk/python)** - The official Python software development kit for building ACP servers.
* **[TypeScript SDK](https://github.com/agentclientprotocol/agent-client-protocol/tree/main/sdk/typescript)** - The official TypeScript library for Node.js agent development.
* **[Rust Crate](https://crates.io/crates/agent-client-protocol)** - The core Rust types and primitives for ACP.
* **[Kotlin SDK](https://github.com/agentclientprotocol/agent-client-protocol/tree/main/sdk/kotlin)** - JVM support for building agents.

## Model Context Protocol (MCP) Integration

ACP and MCP are designed to work together. Use ACP to connect the Agent to the IDE, and use MCP to connect the Agent to the outside world (Databases, Git, APIs).

* [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) - The open standard that allows ACP agents to securely access external data sources and tools.
* [MCP Servers Directory](https://github.com/modelcontextprotocol/servers) - A repository of pre-built MCP tools (GitHub, Postgres, Slack, Google Drive) that can be exposed to your ACP agents.

---

## Contributing

Contributions are very welcome! If you have built an agent, written a tutorial, or know of a tool that uses the Agent Client Protocol, please open a Pull Request.

Please read the [Contribution Guidelines](CONTRIBUTING.md) before submitting.

---

*This list is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).*
