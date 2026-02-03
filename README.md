# AI Toolkit for Visual Studio Code

![Feature Highlight](https://aka.ms/ai-toolkit/feature-highlights-image)

> **🧠 Cognitive Architecture Context**: This toolkit serves as the **agent development interface layer** in the [cogpilot organization's cognitive architecture](https://github.com/cogpilot/cognitive-architecture). It embodies the "ordo ab chao" principle - transforming unstructured human intent into structured, operational AI agents. See [COGPILOT_SIGNIFICANCE.md](COGPILOT_SIGNIFICANCE.md) for architectural context.

## What is AI Toolkit

AI Toolkit is a powerful extension for Visual Studio Code that streamlines agent development. With AI Toolkit, you can:

- 🔍 **Explore and evaluate models** from a wide range of providers—including Anthropic, OpenAI, GitHub—or run models locally using ONNX and Ollama.
- ⚡ **Build and test agents in minutes** with prompt generation, quick starters, and seamless MCP tool integrations.

Complete features include:

| Feature | Description | Screenshot |
|---------|-------------|------------|
| [Model Catalog](https://code.visualstudio.com/docs/intelligentapps/models) | Browse and access AI models from various sources. Simplified discovery of GitHub, ONNX, Ollama, OpenAI, Anthropic, and Google models. | <img src="https://github.com/user-attachments/assets/e22102a2-562a-4861-8ad2-323040fde3d9" width="350"> |
| [Playground](https://code.visualstudio.com/docs/intelligentapps/playground) | Interactive environment for testing AI models. Quick experimentation with model capabilities including multi-modal support. | <img src="https://github.com/user-attachments/assets/83ee9f29-2692-43b0-bbef-ee4c063e79f0" width="350"> |
| [Prompt (Agent) Builder](https://aka.ms/AIToolkit/doc/agentbuilder) | Tools for creating and optimizing prompts. Iterative improvement of prompt engineering techniques. | <img src="https://raw.githubusercontent.com/MuyangAmigo/MuyangAmigo/main/assets/aitk_mcp_readme/mcp_debug.gif" width="350"> |
| [Bulk Run](https://code.visualstudio.com/docs/intelligentapps/bulkrun) | Execute multiple prompts across selected models. Efficient testing at scale with various inputs. | <img src="https://github.com/user-attachments/assets/1cbc5f5b-6438-4ca6-98de-36f843956baa" width="350"> |
| [Evaluate an AI model with a dataset](https://code.visualstudio.com/docs/intelligentapps/evaluation) | Test AI models against datasets using standard metrics. Measure performance with using built-in evaluators such as F1 score, relevance, similarity, and coherence or create your own evaluators. | <img src="https://github.com/user-attachments/assets/e6695e13-25ac-4741-a049-8afcf432e5b4" width="350"> |
| [Fine-tune](https://code.visualstudio.com/docs/intelligentapps/finetune) | Customize models for specific use cases. Adapt models to specialized domains and requirements. | <img src="https://github.com/user-attachments/assets/6c1e3c47-c1d9-465a-abf8-3d23dd858d99" width="350"> |

## Getting started

![Getting started](https://raw.githubusercontent.com/MuyangAmigo/MuyangAmigo/main/assets/vsc_readme/getting_started_new.gif)

We recommend starting with models hosted by GitHub.
- Follow the [installation guide](https://code.visualstudio.com/docs/intelligentapps/overview#_install-and-setup) to set up AI Toolkit for your device.
- From the extension tree view, select **CATALOG** > **Models** to explore models available. We recommend to getting started with models hosted by GitHub.
- From the model card, select **Try in Playground** to start experimenting the capability of an AI Model.

## Build AI agents

The key feature of AI Toolkit is to build AI agents. The agent builder provides a set of tools to help you create and optimize your AI agents. You can use the agent builder to:
- ✨ Generate starter prompts with natural language
- 🔁 Iterate and refine prompts based on model responses
- 🧩 Break down tasks with prompt chaining and structured outputs
- ⚡ Test integrations with real-time runs and tool use such as MCP servers
- 💡 Generate production-ready code for rapid app development
- 🧷 Use variables in prompts
- 🧪 Run agents with test cases to validate your agent easily
- 📊 Evaluate the accuracy and performance of your agent with built-in or custom metrics
- 🔗 Function calling support: Enable agents to invoke external functions dynamically
- 🗂️ Agent versioning and version comparison for evaluation results

And a lot of features are coming soon, stay tuned for:

- 🐞 Local tracing and debugging of agents
- 🚀 Deploy your models and agents to Azure AI Foundry
- ☁️ Deploy your agent to the cloud

Agents can now connect to external tools through MCP (Model Control Protocol) servers, enabling them to perform real-world actions like querying a database, accessing APIs, or executing custom logic.

| Feature | Description | Screenshot |
|---------|-------------|------------|
| Connect to an Existing MCP Server | Use tools from command(stdio) or HTTP (server-sent event) | <img src="https://raw.githubusercontent.com/MuyangAmigo/MuyangAmigo/main/assets/vsc_readme/mcp_existing.gif" width="350"> |
| Build and Scaffold a New MCP Server | Start creating your own MCP server from a simple scaffold and test in Agent Builder | <img src="https://raw.githubusercontent.com/MuyangAmigo/MuyangAmigo/main/assets/vsc_readme/scaffold_mcp.gif" width="350"> |

## 🧠 Cognitive Architecture Integration

This repository is part of the **cogpilot organization's cognitive architecture** - a distributed intelligence ecosystem where GitHub organizations function as **cognitive cities** connected by **neural transport channels**.

### Architectural Role

**VSCode AI Toolkit** serves as the **primary neural interface layer** where:
- 🎯 Human intent transforms into structured AI agents (**ordo ab chao**)
- 🔄 Multi-model support enables **particle swarm intelligence**
- 🕸️ MCP integration creates **operationalized RAG fabric**
- 🏗️ Each agent mirrors the **fractal organization** of the larger architecture

### Key Architectural Principles

1. **Ordo Ab Chao** (Order from Chaos): Natural language → Operational agents
2. **Fractal Organization**: Agents mirror cognitive city architecture
3. **Introspective Protocols**: MCP servers that create MCP servers
4. **Progressive Memory**: Agent versioning and test accumulation
5. **Distributed Intelligence**: Multi-model coordination and ensemble reasoning

### Related Repositories

- **[cognitive-architecture](https://github.com/cogpilot/cognitive-architecture)**: Foundational patterns and principles
- **particle-swarm-accelerator**: Multi-model coordination (planned)
- **operationalized-rag-fabric**: Knowledge synthesis (planned)
- **neural-transport-channels**: Cross-repo communication (planned)

### Learn More

- 📋 **[Significance Analysis](COGPILOT_SIGNIFICANCE.md)**: Deep dive into toolkit's role in cognitive architecture
- 🏗️ **[Architecture Context](.cogpilot/ARCHITECTURE_CONTEXT.md)**: Integration points and evolution roadmap
- 🌐 **[Cognitive Architecture Repo](https://github.com/cogpilot/cognitive-architecture)**: Enterprise overview and vision

**Vision**: Transform this toolkit from isolated development tool to **neural transport-aware cognitive workbench** that embodies distributed intelligence principles.

## Feedback and resources

We value your feedback to help shape our roadmap. Explore our [developer documentation](https://aka.ms/AIToolkit/doc) for more features, [open issues or share suggestions on GitHub](https://aka.ms/AIToolkit/feedback), or join our [Discord community](https://aka.ms/azureaifoundry/discord) to connect with other developers.

AI Toolkit ❤️ Developer Community.

## Data and telemetry

The AI Toolkit for Visual Studio Code collects usage data and sends it to Microsoft to help improve our products and services. Read our [privacy statement](https://privacy.microsoft.com/privacystatement) to learn more. This extension respects the `telemetry.enableTelemetry` setting which you can learn more about at [disable telemetry reporting](https://code.visualstudio.com/docs/supporting/faq#_how-to-disable-telemetry-reporting).
