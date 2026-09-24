# Korolevstvo Portable Plugin

This repository contains the public OpenAI/Codex plugin adapter for the Korolevstvo production MCP.

KorGameMcp is authoritative for live tool names, descriptions, schemas, capabilities and command outcomes. The public plugin repository does not duplicate that live MCP contract.

## Production MCP

The plugin declares one OAuth-protected remote MCP dependency:

    https://auth-4-184-168-137.sslip.io/kor-game/mcp/oauth

The package does not contain provider executables, local MCP endpoints, persistent game credentials or bearer tokens.

## Marketplace installation

Use this Git repository as the marketplace source:

    https://github.com/orleaavitall-hue/Korolevstvo.Plugin

The marketplace manifest is:

    .agents/plugins/marketplace.json

The public plugin package is:

    plugins/korolevstvo/plugin.json
    plugins/korolevstvo/mcp.json
    plugins/korolevstvo/provenance.json
