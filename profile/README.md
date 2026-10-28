<p align="center">
  <a href="https://watasu.io/">
    <img src="https://raw.githubusercontent.com/watasuio/.github/main/profile/assets/watasu.svg" alt="Watasu" width="88" height="88">
  </a>
</p>

<h1 align="center">Watasu</h1>

<p align="center">
  <strong>Apps. Data. Agents. One EU-hosted cloud.</strong><br>
  Build your product. We’ll run the infrastructure.
</p>

<p align="center">
  <a href="https://dash.watasu.io/">Start building</a> ·
  <a href="https://watasu.io/">Explore Watasu</a> ·
  <a href="https://docs.watasu.io/">Documentation</a> ·
  <a href="https://watasu.io/pricing/">Pricing</a>
</p>

---

Watasu brings application hosting, isolated agent sandboxes, and managed data services together. Deploy from Git, open a sandbox over SSH, or let your assistant operate through MCP. Your code runs on European infrastructure; your workflow stays yours.

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Ship your application</h3>
      <p>Push code directly with Git, or connect your GitHub repository.</p>
      <p>Use your own Dockerfile, or rely on automatic language detection:</p>
      <p><strong>Node.js · Python · Ruby · Go · Elixir · PHP</strong></p>
      <p>Run web apps, APIs, background workers, and private services. Scale each process independently.</p>
      <p>Preview pull requests, then promote your tested build from staging to production.</p>
      <p><a href="https://docs.watasu.io/getting-started/quickstart/"><strong>Deploy your first app →</strong></a></p>
    </td>
    <td width="50%" valign="top">
      <h3>Give your agents a computer</h3>
      <p>Run code in isolated Linux sandboxes. Use the smart SSH gateway, HTTP API, or TypeScript, Python, and Rust SDKs.</p>
      <p>Prepare reusable templates, stream commands, move files, expose previews, and keep work through pause/resume, checkpoints, and persistent volumes.</p>
      <p><a href="https://watasu.io/sandboxes/"><strong>Explore hosted sandboxes →</strong></a></p>
    </td>
  </tr>
</table>

### It starts in your terminal

Deploy an app from its Git repository:

```sh
watasu login
watasu apps:create my-app
git push watasu main
```

Or open a fresh sandbox with the SSH client you already have:

```sh
ssh base@box.watasu.io
```

[Install the CLI](https://docs.watasu.io/cli/install/) · [SSH authentication and reconnecting](https://docs.watasu.io/sandboxes/ssh/)

### Your whole stack, connected

Attach a managed service and Watasu supplies the connection settings. Keep using its native clients and protocols.

| Service | Bring it to your product |
| --- | --- |
| [**PostgreSQL**](https://docs.watasu.io/addons/postgresql/) | Application data, relational queries, and transactions. |
| [**Valkey**](https://docs.watasu.io/addons/valkey/) | Redis-compatible caching, sessions, queues, and coordination. |
| [**ClickHouse**](https://docs.watasu.io/addons/clickhouse/) | Event analytics, large datasets, and fast aggregations. |
| [**Qdrant**](https://docs.watasu.io/addons/qdrant/) | Vector, sparse, and hybrid search for AI applications. |
| [**Redpanda**](https://docs.watasu.io/addons/redpanda/) | Kafka-compatible event streams, consumers, and replay. |
| [**Object storage**](https://docs.watasu.io/addons/object-storage/) | S3-compatible buckets for uploads, media, and artifacts. |

Services belong to your team and can be shared across apps. Choose the capacity and protection your workload needs, with [backups and restore workflows](https://docs.watasu.io/workflows/backups-and-restores/) on supported services and plans.

### The details that make a platform

- **A complete view of production.** Logs, Prometheus-compatible metrics, and OpenTelemetry traces in your app’s Grafana workspace. Keep dashboards in Git and investigate from the CLI. [Observability →](https://docs.watasu.io/observability/overview/)
- **Networking built in.** Custom and wildcard domains, managed TLS, private TCP/gRPC, and explicit trust between apps. [Networking →](https://docs.watasu.io/apps/private-networking/)
- **Voice and video, too.** Run WebRTC services with TURN, public UDP, and stable endpoints for each replica. [Real-time apps →](https://docs.watasu.io/apps/realtime/)
- **A path from PR to production.** GitHub deployments, disposable review apps, pipelines, release commands, and image promotion. [Team workflows →](https://docs.watasu.io/workflows/pipelines/)
- **Access that fits your team.** Team ownership and app/pipeline roles let collaborators inspect, deploy, or operate the resources they need. [Teams and access →](https://docs.watasu.io/admin/teams-and-access/)
- **Compute that fits the work.** Fixed-price or usage-billed app processes, per-second sandbox compute, and EU hosting. [Explore pricing →](https://watasu.io/pricing/)

### Work with your tools—and your assistant

Use the dashboard, CLI, API, or SDKs. Connect an AI assistant to Watasu’s [hosted MCP server](https://docs.watasu.io/workflows/mcp/) to inspect resources, diagnose builds, query observability data, and perform operations within the permissions you grant. Our plugins bring Watasu workflows to Claude Code and Codex.

| Project | What’s inside |
| --- | --- |
| [**watasu-cli**](https://github.com/watasuio/watasu-cli) | The Watasu command line for macOS, Linux, and Windows. |
| [**sdk**](https://github.com/watasuio/sdk) | TypeScript, Python, and Rust SDKs, plus code-interpreter packages. |
| [**plugins**](https://github.com/watasuio/plugins) | Watasu skills and MCP integration for Claude Code and Codex. |
| [**homebrew-watasu**](https://github.com/watasuio/homebrew-watasu) | The official Homebrew tap. |

Explore the repositories, report an issue, or contribute an improvement. We build these tools for the people using them.

---

<p align="center">
  <strong>Your next project has a place to run.</strong><br><br>
  <a href="https://dash.watasu.io/">Get started</a> ·
  <a href="https://docs.watasu.io/">Read the docs</a> ·
  <a href="https://watasu.io/blog/">What’s new</a> ·
  <a href="https://watasu.statuspage.me/">Service status</a>
</p>
