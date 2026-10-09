# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository state

This directory is currently an MCP (Model Context Protocol) tutorial workspace with no source code, build system, or tests yet. It is not a git repository. Update this file once code, build/test commands, or a README are added.

## MCP configuration

`.mcp.json` registers one project-scoped MCP server:

- **context7** (HTTP, `https://mcp.context7.com/mcp`): fetches up-to-date library/framework documentation. Use it when you need current API docs or setup instructions for a library, rather than relying on memory.

Add further project MCP servers to `.mcp.json` under `mcpServers`.
