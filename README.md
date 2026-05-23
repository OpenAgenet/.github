<!-- Copyright (c) 2026 OpenAgenet contributors -->
<!--
Initial author: JINLIANG XU
Email: jlxufly@gmail.com
-->

# OpenAgenet

Open infrastructure for trusted Agent interconnection.

OpenAgenet is an infrastructure project for trusted Agent registration, governance, distribution, discovery, and pre-connection verification. It is designed to interoperate with Agent interaction protocols and tool protocols such as MCP, A2A, ANP, AIP-compatible flows, DNS-native discovery, and future Agent network routes.

## Organization Repositories

- `oan-site`: static website, public trial network pages, and developer entry points.
- `oan-trial-network`: public trial network registry, node application process, and operator-facing network materials.
- `oan-reference-services`: reference Rust services for Root, Registrar, Discovery, and CDN nodes.
- `oan-deploy`: deployment templates and operational bootstrap assets.
- `oan-agent-py`: Python Agent adapter SDK and reference Service/User Agent implementations.
- `oan-sdk-ts`: TypeScript SDKs for clients, Discovery access, and web-console helpers.
- `oan-examples`: runnable examples, integration scenarios, and interoperability demos.
- `oan-adapters`: adapters for MCP, A2A, ANP, AIP-compatible flows, and Agent framework integrations.
- `oan-web-console`: web console surfaces for Registrar, Discovery, Root status, and developer workflows.
- `oan-operator-guides`: operator guides, runbooks, and node operation procedures.
- `oan-discovery-plugins`: Discovery extensions for semantic search, ranking, directories, and indexing experiments.

## Stewardship Model

The organization hosts collaboration and product-facing repositories. Protocol control, detailed design records, release signing tools, and compatibility authority are stewarded separately in personal core repositories and public release artifacts.
