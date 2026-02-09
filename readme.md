<div align="center">

<!--lint ignore no-dead-urls-->

# Awesome Kimi CLI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/lfglabs-dev/awesome-kimi-cli/actions/workflows/lint.yaml/badge.svg)](https://github.com/lfglabs-dev/awesome-kimi-cli/actions/workflows/lint.yaml)

A curated list of awesome resources, tools, extensions, and integrations for Kimi Code CLI.

<img src="https://img.shields.io/github/stars/MoonshotAI/kimi-cli?style=social" alt="Kimi CLI Stars" />

Kimi Code CLI is an open-source AI coding agent that runs in your terminal, helping you complete software development tasks through code editing, shell commands, and autonomous planning.

</div>

## Contents

- [Official Resources](#official-resources)
- [IDE Extensions](#ide-extensions)
- [Shell Plugins](#shell-plugins)
- [Neovim Plugins](#neovim-plugins)
- [MCP Servers](#mcp-servers)
- [Models](#models)
- [API Providers](#api-providers)
- [Tutorials and Guides](#tutorials-and-guides)
- [Community Projects](#community-projects)
- [Related Projects](#related-projects)
- [Community](#community)
- [Follow](#follow)

## Official Resources

- [Kimi Code CLI](https://github.com/MoonshotAI/kimi-cli) - The official Kimi Code CLI repository by Moonshot AI.
- [Kimi CLI Documentation](https://moonshotai.github.io/kimi-cli/) - Official documentation with guides, configuration, and reference.
- [Kimi Code Website](https://www.kimi.com/code/en) - Official Kimi Code product page.
- [Moonshot AI Open Platform](https://platform.moonshot.ai/) - Official API platform for Kimi models.
- [PyPI Package](https://pypi.org/project/kimi-cli/) - Install Kimi CLI via pip/uv.

## IDE Extensions

- [Kimi Code VS Code Extension](https://marketplace.visualstudio.com/items?itemName=moonshot-ai.kimi-code) - Official VS Code extension with native chat panel, MCP support, and diff view.
- [Kimi Code Open VSX](https://open-vsx.org/extension/moonshot-ai/kimi-code) - Kimi Code extension on the Open VSX Registry for VS Code alternatives.
- [Kimi CLI Zed Extension](https://github.com/MoonshotAI/kimi-code-zed-extension) - Official Zed editor extension with ACP integration.
- [Kimi Commits IntelliJ](https://plugins.jetbrains.com/plugin/23629-kimi-commits) - Generate smart Git commit messages with Kimi AI for JetBrains IDEs.

## Shell Plugins

- [zsh-kimi-cli](https://github.com/MoonshotAI/zsh-kimi-cli) - Official Zsh plugin to launch Kimi CLI with Ctrl-X.

## Neovim Plugins

- [llm.nvim](https://github.com/Kurama622/llm.nvim) - Neovim LLM plugin with native Kimi support alongside ChatGPT, DeepSeek, and others.
- [avante.nvim](https://github.com/yetone/avante.nvim) - Cursor-like AI IDE experience for Neovim with ACP support for Kimi CLI.
- [sidekick.nvim](https://github.com/folke/sidekick.nvim) - Neovim AI sidekick with built-in terminal for AI CLIs including Kimi.
- [pi.nvim](https://github.com/pablopunk/pi.nvim) - Minimal coding agent for Neovim supporting Kimi models via OpenRouter.
- [codecompanion.nvim](https://github.com/olimorris/codecompanion.nvim) - Neovim AI companion with kimi_cli adapter support.

## MCP Servers

Kimi CLI supports MCP (Model Context Protocol) servers to extend AI capabilities. Manage servers with `kimi mcp` commands.

- [MCP Official Servers](https://github.com/modelcontextprotocol/servers) - Reference MCP server implementations for filesystem, databases, and more.
- [Ultimate MCP Server](https://github.com/Dicklesworthstone/ultimate_mcp_server) - Unified MCP server providing access to a wide variety of tools.

## Models

### Official Models

- [Kimi-K2.5](https://huggingface.co/moonshotai/Kimi-K2.5) - Native multimodal agentic model with vision and text understanding.
- [Kimi-K2-Instruct](https://huggingface.co/moonshotai/Kimi-K2-Instruct) - General-purpose chat and agentic model with 1T total parameters.
- [Kimi-K2-Thinking](https://huggingface.co/moonshotai/Kimi-K2-Thinking) - Thinking model that reasons step-by-step while invoking tools.
- [Kimi-K2 Repository](https://github.com/MoonshotAI/Kimi-K2) - Official Kimi K2 model series repository.
- [Kimi-K2.5 Repository](https://github.com/MoonshotAI/Kimi-K2.5) - Official Kimi K2.5 repository with model code and documentation.

### Quantized Models

- [Kimi-K2-Instruct-GGUF](https://huggingface.co/ubergarm/Kimi-K2-Instruct-GGUF) - GGUF quantized versions for local inference.
- [Kimi-K2-Thinking-GGUF](https://huggingface.co/ubergarm/Kimi-K2-Thinking-GGUF) - GGUF quantized thinking model.
- [Kimi K2 on Ollama](https://ollama.com/library/kimi-k2-thinking) - Run Kimi K2 models locally with Ollama.
- [Kimi K2.5 on Ollama](https://ollama.com/library/kimi-k2.5) - Run Kimi K2.5 multimodal model with Ollama.

## API Providers

- [NVIDIA NIM](https://build.nvidia.com/moonshotai/kimi-k2.5) - Free Kimi K2.5 API access through NVIDIA.
- [OpenRouter](https://openrouter.ai/moonshotai/kimi-k2.5) - Access Kimi models through OpenRouter's unified API.
- [Together AI](https://www.together.ai/models/kimi-k2-5) - Kimi K2.5 API on Together AI platform.

## Tutorials and Guides

- [Getting Started Guide](https://moonshotai.github.io/kimi-cli/en/guides/getting-started.html) - Official getting started documentation.
- [IDE Integration Guide](https://www.kimi.com/code/docs/en/kimi-cli/guides/ides.html) - Using Kimi CLI with various IDEs.
- [MCP Configuration Guide](https://moonshotai.github.io/kimi-cli/en/customization/mcp.html) - Setting up MCP servers with Kimi CLI.
- [Tool Integrations Guide](https://moonshotai.github.io/kimi-cli/en/guides/integrations.html) - Integrating Kimi CLI with external tools.
- [How to Use Kimi CLI](https://apidog.com/blog/how-to-use-kimi-cli/) - Comprehensive usage tutorial by Apidog.

## Community Projects

- [kimi-cli-nvidia](https://github.com/notsointresting/kimi-cli-nvidia) - Kimi CLI fork with NVIDIA API integration.
- [kimi-commits-intellij](https://github.com/ConnectAI-E/kimi-commits-intellij) - Open-source Kimi commit message generator for JetBrains IDEs.
- [Kimi-Dev](https://github.com/MoonshotAI/Kimi-Dev) - Open-source coding LLM optimized for software engineering tasks.
- [Kimi-Audio](https://github.com/MoonshotAI/Kimi-Audio) - Audio foundation model for understanding, generation, and conversation.
- [Mooncake](https://github.com/kvcache-ai/Mooncake) - KV-centric disaggregated LLM serving, Best Paper at FAST 2025.

## Related Projects

- [Claude Code](https://github.com/anthropics/claude-code) - Anthropic's CLI coding agent.
- [Gemini CLI](https://github.com/google-gemini/gemini-cli) - Google's Gemini CLI tool.
- [Aider](https://github.com/paul-gauthier/aider) - AI pair programming in your terminal.
- [Continue](https://github.com/continuedev/continue) - Open-source AI code assistant.
- [sandboxed.sh](https://github.com/Th0rgal/sandboxed.sh) - Isolated container workspaces for AI coding agents.

## Community

- 💬 [Relens Community](https://relens.ai/community) - Join the AI coding agents community to share tips, tricks, and workflows.

## Follow

- [Moonshot AI GitHub](https://github.com/MoonshotAI) - Official Moonshot AI organization on GitHub.
- [Kimi on X/Twitter](https://x.com/Kimi_Moonshot) - Official Kimi Twitter account.

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/lfglabs-dev/awesome-kimi-cli/graphs/contributors)!
