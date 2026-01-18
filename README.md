# Git-Docked

A Github MCP server fully dockerized that exposes proper HTTPS endpoints and access to the full MCP Server with write access and repository level management tools.

## Repository Structure

This repository contains multiple imported repositories as subdirectories, each serving different purposes in the Git-Docked ecosystem.

### Directory Layout

- **`github-mcp-server/`** - Complete GitHub MCP Server repository
  - Full source code for the MCP server
  - Documentation, build scripts, and configuration files
  - See [github-mcp-server/README.md](github-mcp-server/README.md) for more details

- **`mcpo/`** - MCPO (Model Context Protocol Orchestrator)
  - Forked from [open-webui/mcpo](https://github.com/open-webui/mcpo)
  - Python-based orchestration tools for MCP
  - See [mcpo/README.md](mcpo/README.md) for more details

- **`features/`** - Dev Container Features
  - Forked from [devcontainers/features](https://github.com/devcontainers/features)
  - Reusable development container features and configurations
  - See [features/README.md](features/README.md) for more details

## Quick Start

Refer to the [GitHub MCP Server documentation](github-mcp-server/README.md) for installation and usage instructions.
