<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/risingwavelabs/risingwave/main/.github/RisingWave-logo-dark.svg">
  <img alt="RisingWave" src="https://raw.githubusercontent.com/risingwavelabs/risingwave/main/.github/RisingWave-logo-light.svg">
</picture>

## Live Data. Smarter Agents.

We build [RisingWave](https://github.com/risingwavelabs/risingwave), a PostgreSQL-compatible event streaming platform that helps you ingest, transform, and serve live data to your applications and AI agents.

## Built for the Age of Agents

AI agents are only as smart as the data they see. If your data is stale, your agents make stale decisions.

RisingWave keeps your data always fresh, always ready. The moment something happens in your systems, your agents know about it.

## What RisingWave Does

- Ingest millions of events per second from any source
- Transform and enrich data with familiar SQL
- Serve results with sub-second latency
- Write directly to Apache Iceberg and build a real-time Lakehouse

No Kafka. No Flink. Just SQL.

## RisingWave MCP

The [RisingWave MCP Server](https://github.com/risingwavelabs/risingwave-mcp) brings your event streams directly into AI assistants like Claude and GitHub Copilot. With 100+ tools, your agents can query tables, inspect materialized views, monitor streaming jobs, and manage the full lifecycle of your data pipelines — all through natural language.

```json
{
  "mcpServers": {
    "risingwave": {
      "command": "python",
      "args": ["src/main.py"],
      "env": { "RW_CONNECTION_STRING": "postgresql://root@localhost:4566/dev" }
    }
  }
}
```

## Agent Skills

[Agent Skills](https://github.com/risingwavelabs/agent-skills) are ready-made skill packages that teach AI coding agents how to work with RisingWave. Install them with a single command and your agent instantly knows how to design schemas, write streaming SQL, configure CDC pipelines, and follow best practices.

```bash
npx skills add risingwavelabs/agent-skills
```

Compatible with Claude Code, GitHub Copilot, Cursor, Windsurf, Gemini CLI, and 18+ other AI agents.

## Deploy RisingWave

| Mode | How |
|---|---|
| **Standalone** | `curl -L https://risingwave.com/sh \| sh` |
| **Cloud** | Fully managed on [RisingWave Cloud](https://cloud.risingwave.com) — free tier available |
| **Docker** | `docker run -it --pull=always -p 4566:4566 risingwavelabs/risingwave:latest single_node` |
| **Kubernetes** | [Helm Charts](https://github.com/risingwavelabs/helm-charts) or [Operator](https://github.com/risingwavelabs/risingwave-operator) |

## Get Started

New to RisingWave? [Try the quickstart](https://docs.risingwave.com/get-started/quickstart) and run your first streaming query in minutes.

Full documentation is available at [docs.risingwave.com](https://docs.risingwave.com).

## Join the Community

Our Slack community is where users discuss real-world deployments, ask technical questions, and get direct access to the RisingWave engineering team.

[![Join our Slack](https://img.shields.io/badge/Slack-Join%20Us-4A154B?logo=slack&logoColor=white)](https://go.risingwave.com/slack)
