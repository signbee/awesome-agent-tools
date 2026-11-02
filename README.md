# Awesome AI Agent Tools & MCP Servers (2026) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![MCP Ready](https://img.shields.io/badge/MCP-Model%20Context%20Protocol-0f172a?style=flat&logo=anthropic)](https://modelcontextprotocol.io)

> A curated directory of **90+ production-ready Model Context Protocol (MCP) servers, Claude Code Skills, Cursor Plugins, and Agent-Native APIs** that give autonomous AI agents real-world agency — from signing legal contracts and sending emails to executing code, querying databases, and moving money.

Maintained by **[Signb.ee](https://signb.ee)** — *Document signing built for AI agents (`llms.txt`, MCP, Agent Skills, and REST API).*

---

## Contents

- [Document Signing, Legal & Compliance](#document-signing-legal--compliance)
- [Email, Messaging & Voice Agents](#email-messaging--voice-agents)
- [Payments, Billing & Commerce](#payments-billing--commerce)
- [Web Search, Scraping & Browser Automation](#web-search-scraping--browser-automation)
- [Databases, Vector Stores & Memory](#databases-vector-stores--memory)
- [Code Execution, Sandboxes & Cloud Infra](#code-execution-sandboxes--cloud-infra)
- [Network Diagnostics](#network-diagnostics)
- [CRM, Scheduling & Productivity](#crm-scheduling--productivity)
- [Multi-Tool Gateways & Orchestration](#multi-tool-gateways--orchestration)
- [Contributing](#contributing)

---

## Document Signing, Legal & Compliance

Tools that enable AI agents to draft, send, verify, and execute legally binding agreements, NDAs, MSAs, and compliance workflows without human dashboard clicks.

- **[Signbee MCP (`@signbee/mcp`)](https://github.com/signbee/mcp)** — Official Model Context Protocol server for [Signb.ee](https://signb.ee). Send raw Markdown or PDFs for two-party or multi-party e-signing in a single tool call (`send_document_for_signing`), with SHA-256 cryptographic audit certificates, OTP verification, and real-time webhook events.
- **[Signbee Agent Skill (`signbee/skill`)](https://github.com/signbee/skill)** — Claude Code & autonomous agent skill for drafting, sending, tracking, and verifying NDAs, MSAs, SOWs, and sales contracts directly from terminal or agent workflows.
- **[Signbee Cursor Plugin (`signbee/cursor-plugin`)](https://github.com/signbee/cursor-plugin)** — Cursor Marketplace plugin combining the Signbee MCP server, `.mdc` rules, and contract templates for sending agreements directly from your IDE.
- **[Signb.ee Agent-Native API](https://signb.ee)** — E-signature platform engineered from the ground up for AI agents (`https://signb.ee/llms.txt`), featuring zero-UI template-free Markdown-to-PDF rendering, instant API key provisioning, and cryptographic completion certificates.
- **[Documenso](https://github.com/documenso/documenso)** — Open-source DocuSign alternative with REST API, webhooks, and self-hosted signing workflows.
- **[DocuSeal](https://github.com/docusealco/docuseal)** — Open-source document filling and e-signature platform with HTML/PDF API endpoints and embedded signing forms.
- **[OpenSign](https://github.com/OpenSignLabs/OpenSign)** — Open-source document signing and cryptographic PDF verification suite with REST API support.
- **[Ironclad API](https://ironcladapp.com)** — Enterprise contract lifecycle management (CLM) API for automated legal review and approval workflows.
- **[PandaDoc API](https://developers.pandadoc.com)** — Document automation and proposal generation API with quote-to-cash and webhook integrations.
- **[Dropbox Sign (HelloSign) API](https://developers.hellosign.com)** — Embedded e-signature API for programmatic signature requests and template workflows.
- **[uComply / Right-to-Work Verification](https://ucomply.co.uk)** — Identity and compliance verification workflows for automated onboarding.

---

## Email, Messaging & Voice Agents

Agent-native communication channels across email inboxes, transactional messaging, WhatsApp, and ultra-low-latency voice AI.

- **[AgentMail](https://agentmail.to)** — Dedicated email inboxes and API designed specifically for AI agents to send, receive, thread, and parse emails autonomously.
- **[Resend MCP](https://github.com/resend/mcp-send-email)** — Official Resend MCP server enabling Claude, Cursor, and AI agents to compose and send transactional HTML/Markdown emails directly.
- **[Postmark MCP](https://github.com/ActiveCampaign/postmark-mcp)** — Official MCP server for transactional email delivery, template rendering, and delivery analytics via Postmark.
- **[Twilio MCP](https://github.com/twilio-labs/mcp)** — Send SMS, WhatsApp messages, and trigger programmable voice calls via Twilio's Model Context Protocol server.
- **[WhatsApp Cloud API MCP](https://developers.facebook.com/docs/whatsapp/cloud-api)** — Meta WhatsApp Business Cloud API integrations for two-way conversational agents, media attachments, and interactive templates.
- **[Vapi](https://vapi.ai)** — Developer platform for building, testing, and deploying sub-500ms real-time voice AI agents over phone and WebRTC with MCP tool calling.
- **[Retell AI](https://retellai.com)** — Low-latency voice AI API for outbound/inbound phone agents with warm transfers, interruption handling, and function calling.
- **[LiveKit Agents](https://github.com/livekit/agents)** — Open-source Python and Node.js framework for building real-time multimodal voice and video AI agents on WebRTC.
- **[Bland AI](https://bland.ai)** — Enterprise conversational phone calling API with custom conversational pathways and webhook tool calls.
- **[ElevenLabs Conversational AI & MCP](https://github.com/elevenlabs/elevenlabs-mcp)** — Official ElevenLabs MCP server for ultra-realistic text-to-speech, voice cloning, and interactive voice agents.
- **[Deepgram](https://deepgram.com)** — Real-time Nova-3 speech-to-text and Aura text-to-speech API built for conversational voice pipelines.
- **[Cartesia Sonic](https://cartesia.ai)** — Ultra-low-latency streaming state-space voice synthesis API for real-time AI agents.

---

## Payments, Billing & Commerce

Financial rails, payment links, usage-based billing, and cryptographic wallets that let AI agents charge for services or pay for API resources.

- **[Stripe Agent Toolkit & MCP (`@stripe/mcp`)](https://github.com/stripe/agent-toolkit)** — Official Stripe MCP server and SDK for creating payment links, managing customers, issuing invoices, and handling subscriptions from AI agents.
- **[Polar.sh MCP](https://polar.sh)** — Developer-first merchant of record with MCP support for usage-based AI billing, license keys, and digital subscriptions.
- **[Lemon Squeezy API & MCP](https://lemonsqueezy.com)** — Global merchant of record for SaaS and digital products with webhook-driven entitlement management.
- **[PayPal Agent Toolkit & MCP](https://github.com/paypal/agent-toolkit)** — Official PayPal MCP server for generating invoices, payment links, order tracking, and dispute management.
- **[Coinbase AgentKit (`@coinbase/agentkit`)](https://github.com/coinbase/agentkit)** — Give any AI agent an on-chain crypto wallet to send USDC, swap tokens, and pay for machine-to-machine APIs (`x402`).
- **[Skyfire](https://skyfire.xyz)** — Financial identity and instant micro-payment network purpose-built for autonomous AI agents to pay for APIs and compute.
- **[Crossmint GOAT SDK](https://github.com/goat-sdk/goat)** — Great Onchain Agent Toolkit connecting AI agents to 200+ financial and smart-contract actions.
- **[Square MCP](https://github.com/square/square-mcp-server)** — Official Square MCP server for point-of-sale catalog management, orders, invoices, and payment processing.
- **[Shopify Dev MCP](https://github.com/Shopify/dev-mcp)** — Official Shopify MCP server for GraphQL Admin/Storefront API introspection, order automation, and merchant tooling.
- **[Paddle API](https://developer.paddle.com)** — B2B and SaaS merchant-of-record billing engine with global tax compliance.

---

## Web Search, Scraping & Browser Automation

High-signal neural search engines, Markdown web scrapers, and headless cloud browsers with anti-bot stealth for autonomous web navigation.

- **[Exa MCP (`exa-mcp-server`)](https://github.com/exa-labs/exa-mcp-server)** — Official MCP server for Exa's neural search engine, enabling AI agents to search live web pages, research papers, LinkedIn profiles, and GitHub repos.
- **[Firecrawl MCP (`firecrawl-mcp-server`)](https://github.com/mendableai/firecrawl-mcp-server)** — Turn any website into clean LLM-ready Markdown or structured JSON via Firecrawl's official MCP server.
- **[Brave Search MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search)** — Privacy-first web and local search MCP server powered by the independent Brave Search index.
- **[Tavily MCP (`tavily-mcp`)](https://github.com/tavily-ai/tavily-mcp)** — Real-time web search and grounded extraction API purpose-built for RAG and autonomous research agents.
- **[Browserbase & Stagehand MCP](https://github.com/browserbase/mcp-server-browserbase)** — Cloud headless browser infrastructure paired with Stagehand (`act`, `extract`, `observe`) for resilient browser automation.
- **[Playwright MCP (`@playwright/mcp`)](https://github.com/microsoft/playwright-mcp)** — Microsoft's official Playwright MCP server using accessibility snapshots (instead of fragile pixel screenshots) for fast, deterministic browser actions.
- **[Crawl4AI](https://github.com/unclecode/crawl4ai)** — Open-source LLM-friendly web crawler and scraper generating clean Markdown and structured extractions.
- **[Jina Reader (`r.jina.ai`)](https://github.com/jina-ai/reader)** — Prepend `https://r.jina.ai/` to any URL to convert complex web pages into clean LLM-friendly Markdown.
- **[Perplexity Sonar MCP](https://github.com/pplx-ai/modelcontextprotocol)** — Official Perplexity MCP server bringing citation-backed live web reasoning directly into Claude and Cursor.
- **[Steel.dev](https://github.com/steel-dev/steel-browser)** — Open-source batteries-included browser API for AI agents with session persistence, CAPTCHA solving, and proxy management.
- **[Skyvern](https://github.com/Skyvern-AI/skyvern)** — Vision-LLM and browser automation agent capable of completing multi-step web forms and procurement portals across unfamiliar websites.
- **[Hyperbrowser MCP](https://github.com/hyperbrowserai/mcp)** — Scalable headless browser sessions with stealth mode and built-in scraping tools for MCP clients.

---

## Databases, Vector Stores & Memory

Persistent relational databases, serverless SQL, vector search engines, and long-term episodic memory layers for stateful agents.

- **[Supabase MCP (`@supabase/mcp-server-supabase`)](https://github.com/supabase-community/supabase-mcp)** — Official Supabase MCP server to create projects, design schemas, run SQL migrations, inspect logs, and generate TypeScript types.
- **[Neon MCP (`@neondatabase/mcp-server-neon`)](https://github.com/neondatabase-labs/mcp-server-neon)** — Serverless Postgres with instant database branching — ideal for AI agents spinning up isolated database environments per task.
- **[PostgreSQL MCP (`@modelcontextprotocol/server-postgres`)](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres)** — Reference MCP server for schema inspection and read/write SQL queries against PostgreSQL databases.
- **[Prisma MCP](https://www.prisma.io/docs/postgres)** — Built-in Prisma CLI MCP server (`npx prisma mcp`) for provisioning databases, running schema migrations, and querying data.
- **[Upstash MCP (`@upstash/mcp-server`)](https://github.com/upstash/mcp-server)** — Manage serverless Redis caches, Vector indexes, and QStash message queues via natural language and MCP tool calls.
- **[Qdrant MCP (`mcp-server-qdrant`)](https://github.com/qdrant/mcp-server-qdrant)** — Official Qdrant vector search MCP server for semantic code and document memory retrieval.
- **[Pinecone MCP](https://github.com/pinecone-io/pinecone-mcp)** — Store, embed, and query high-dimensional vector namespaces directly from MCP-compatible agents.
- **[ClickHouse MCP (`mcp-clickhouse`)](https://github.com/ClickHouse/mcp-clickhouse)** — Official ClickHouse MCP server for real-time analytical SQL queries over massive datasets.
- **[Turso / LibSQL MCP](https://github.com/tursodatabase/turso-mcp)** — Edge-hosted SQLite/LibSQL database provisioning and per-tenant agent database isolation.
- **[Mem0 (`mem0-mcp`)](https://github.com/mem0ai/mem0-mcp)** — Universal self-improving long-term memory layer for personalized AI agents across sessions.
- **[Zep & Graphiti](https://github.com/getzep/graphiti)** — Temporal knowledge-graph memory engine for AI agents that tracks how user facts and relationships evolve over time.
- **[Letta (formerly MemGPT)](https://github.com/letta-ai/letta)** — Stateful agent framework with editable core memory blocks, archival memory, and persistent agent state.

---

## Code Execution, Sandboxes & Cloud Infra

Secure microVM sandboxes, serverless GPU containers, and cloud deployment APIs that let coding agents run untrusted code and ship applications safely.

- **[E2B Code Interpreter (`@e2b/code-interpreter`)](https://github.com/e2b-dev/code-interpreter)** — Fast Firecracker microVM sandboxes designed for AI agents to execute Python, Node.js, and shell commands securely in `<150ms`.
- **[Cloudflare MCP Servers](https://github.com/cloudflare/mcp-server-cloudflare)** — Official Cloudflare MCP suite to deploy Workers, query D1 databases, inspect R2 buckets, and analyze observability traces.
- **[Vercel MCP](https://vercel.com/docs/mcp)** — Official Vercel MCP server to inspect deployments, read build logs, manage environment variables, and ship preview/production builds.
- **[Modal](https://modal.com)** — Serverless cloud compute for running AI agent sandboxes, batch jobs, and GPU inference containers from pure Python code.
- **[Daytona](https://github.com/daytonaio/daytona)** — Secure, sub-90ms elastic infrastructure for running AI-generated code and stateful agent workspaces.
- **[Docker MCP (`mcp/docker`)](https://github.com/docker/mcp-servers)** — Official Docker MCP server catalog for running containerized MCP tools with isolated filesystem and network access.
- **[Kubernetes MCP (`mcp-server-kubernetes`)](https://github.com/Flux159/mcp-server-kubernetes)** — Inspect pods, deployments, logs, and cluster events via `kubectl` over Model Context Protocol.
- **[AWS MCP Servers (`awslabs/mcp`)](https://github.com/awslabs/mcp)** — Official AWS Labs MCP servers for CDK, Bedrock Knowledge Bases, Cost Analysis, Lambda, and Terraform infrastructure.
- **[Pulumi MCP (`@pulumi/mcp-server`)](https://github.com/pulumi/mcp-server)** — Provision, preview, and update cloud infrastructure-as-code stacks across AWS, GCP, and Azure via MCP.
- **[Fly.io Machines API](https://fly.io/docs/machines/api/)** — Fast-booting hardware-virtualized microVMs with REST API control for per-session agent environments.

---

## Network Diagnostics

Local connection checks for agents investigating failed requests and dependency downloads on the machine where they run.

- **[Kilobat CLI](https://github.com/seifip/kilobat-cli)** — Gives agents local macOS 14+ DNS, route, latency and host-connectivity diagnostics through stdio MCP (GPL-3.0-only code; Xcode 16+ source build).

---

## CRM, Scheduling & Productivity

Workspace integrations connecting AI agents to customer records, calendars, issue trackers, knowledge bases, and version control.

- **[GitHub Official MCP (`github/github-mcp-server`)](https://github.com/github/github-mcp-server)** — Official GitHub MCP server for managing repositories, opening pull requests, triaging issues, and inspecting GitHub Actions workflows.
- **[Linear MCP (`https://mcp.linear.app/sse`)](https://linear.app/docs/mcp)** — Official remote MCP server for Linear enabling agents to search, create, and update engineering issues, cycles, and projects.
- **[Notion MCP (`@notionhq/notion-mcp-server`)](https://github.com/makenotion/notion-mcp-server)** — Official Notion MCP server for querying databases, creating wiki pages, and updating structured workspace blocks.
- **[Slack MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/slack)** — Search channels, post threaded updates, and react to workspace messages via the Slack Web API.
- **[Attio MCP](https://attio.com)** — AI-native CRM with flexible object schemas, relationship intelligence, and API/MCP hooks for revenue agents.
- **[Twenty CRM](https://github.com/twentyhq/twenty)** — Open-source modern Salesforce/HubSpot alternative with GraphQL/REST APIs and custom webhook triggers.
- **[HubSpot MCP](https://developers.hubspot.com/mcp)** — Official HubSpot MCP server for querying contacts, deals, company timelines, and sales sequences.
- **[Cal.com MCP](https://cal.com)** — Open-source scheduling infrastructure with AI phone/chat booking tools, availability checks, and instant meeting links.
- **[Google Workspace CLI (`gws`) & MCP](https://github.com/googleworkspace/cli)** — Unified CLI and MCP server for Gmail, Google Calendar, Google Drive, Docs, and Sheets automation.
- **[Airtable MCP (`airtable-mcp-server`)](https://github.com/domdomegg/airtable-mcp-server)** — Read and write records, inspect table schemas, and automate operations across Airtable bases.
- **[Obsidian MCP (`mcp-obsidian`)](https://github.com/MarkusPfundstein/mcp-obsidian)** — Connect Claude and Cursor directly to a local Obsidian Second Brain vault for instant markdown note retrieval and updates.
- **[Sentry MCP (`@sentry/mcp-server`)](https://github.com/getsentry/sentry-mcp)** — Official Sentry MCP server allowing coding agents to inspect production stack traces, issue frequency, and release regressions.

---

## Multi-Tool Gateways & Orchestration

Managed tool routers, MCP registries, OAuth brokers, and multi-agent frameworks for wiring dozens of tools together reliably.

- **[Smithery (`smithery.ai`)](https://smithery.ai)** — Package registry and CLI (`npx @smithery/cli`) for discovering, installing, and hosting 4,000+ Model Context Protocol servers.
- **[Glama MCP Directory (`glama.ai/mcp`)](https://glama.ai/mcp/servers)** — Comprehensive open directory and security scanner for MCP servers with live playground testing.
- **[MCP.so (`chatmcp/mcpso`)](https://mcp.so)** — Community-driven index and hosted gateway for discovering and connecting Model Context Protocol servers.
- **[Composio](https://github.com/ComposioHQ/composio)** — Managed OAuth and tool-calling gateway with 250+ pre-built integrations for Claude, OpenAI, LangGraph, and CrewAI.
- **[Arcade.dev](https://github.com/ArcadeAI/arcade-ai)** — Authenticated tool-calling runtime handling per-user OAuth 2.0 tokens for Gmail, Slack, GitHub, and enterprise APIs.
- **[Pipedream MCP (`mcp.pipedream.com`)](https://github.com/PipedreamHQ/awesome-mcp-servers)** — Hosted MCP servers for 2,500+ APIs backed by Pipedream's managed OAuth and serverless workflow engine.
- **[Zapier MCP](https://zapier.com/mcp)** — Connect any MCP client (Claude Desktop, Cursor, Windsurf) to 7,000+ SaaS apps through Zapier actions.
- **[OpenAI Agents SDK (`openai-agents-python`)](https://github.com/openai/openai-agents-python)** — Lightweight production framework for multi-agent handoffs, guardrails, tracing, and native MCP server integration.
- **[Anthropic Claude Agent SDK & Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview)** — Official agentic coding harness supporting `.claude/skills`, slash commands, and stdio/SSE MCP servers.
- **[Vercel AI SDK](https://sdk.vercel.ai)** — TypeScript toolkit for building streaming AI applications, tool-calling loops, and MCP clients in Next.js and Node.js.
- **[LangGraph](https://github.com/langchain-ai/langgraph)** — Low-level stateful orchestration framework for durable, human-in-the-loop, cyclical multi-agent workflows.
- **[PydanticAI](https://github.com/pydantic/pydantic-ai)** — Type-safe Python agent framework by the Pydantic team with structured outputs, dependency injection, and MCP client support.
- **[CrewAI](https://github.com/crewAIInc/crewAI)** — Role-based multi-agent orchestration framework for collaborative autonomous workflows.
- **[Mastra](https://github.com/mastra-ai/mastra)** — Open-source TypeScript agent framework with workflows, RAG, evals, and unified MCP tool hosting.

---

## Contributing

Contributions are welcome! To add an MCP server, Agent Skill, Cursor Plugin, or Agent-Native API:

1. Ensure the tool is actively maintained and works with autonomous AI agents (via **MCP**, **Agent Skills**, **OpenAPI/SDK**, or **`llms.txt`**).
2. Fork this repository, add your entry alphabetically or within the most relevant category in `README.md` with a concise 1-sentence technical description, and open a Pull Request.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Signb.ee](https://signb.ee) has waived all copyright and related or neighboring rights to this work.
