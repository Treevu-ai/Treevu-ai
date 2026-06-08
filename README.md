<div align="center">

# Ricardo Cuba

### Founder · [CLI Market](https://cli-market.dev) · [Sinapsis Innovadora](https://github.com/Treevu-ai/sinapsis-innovadora)

**Commerce infrastructure for AI agents** — one API, CLI & MCP to search, compare and buy across LATAM retail.

🇵🇪 Perú · turning shelf prices into agent decisions

<br/>

<a href="https://cli-market.dev">
  <img src="assets/cli-market-demo.gif" alt="CLI Market demo — market search, compare and checkout in the terminal" width="100%" />
</a>

<br/>

[![Website](https://img.shields.io/badge/cli--market.dev-00d75f?style=for-the-badge&logo=vercel&logoColor=white)](https://cli-market.dev)
[![Dashboard](https://img.shields.io/badge/live_moat-111111?style=for-the-badge&logo=chartdotjs&logoColor=00d75f)](https://cli-market-production.up.railway.app/dashboard)
[![PyPI](https://img.shields.io/pepy/dt/cli-market?label=downloads&color=00d75f&logo=pypi&style=for-the-badge)](https://pypi.org/project/cli-market/)
[![MCP](https://img.shields.io/badge/MCP_tools-22-00d75f?style=for-the-badge&logo=anthropic)](https://cli-market.dev/tools)
[![Pro](https://img.shields.io/badge/Pro-%2439%2Fmo-00d75f?style=for-the-badge)](https://cli-market.dev/#pro-checkout)

```bash
pip install cli-market
market search "arroz" --country PE --json
market compare "leche" --country PE
```

</div>

---

## What I'm building

| Signal | Live today |
|:---|:---|
| Shelf prices | **50,000+** verified · refresh ~4h |
| Retailers | **38** active · **68** defined |
| Platforms | VTEX · Shopify · Magento · WooCommerce |
| Countries | 8 · AR BR CL CO FR IT MX PE |
| Golden Records | **11,000+** product identities · **92%** linkage |
| Agent surface | **22** curated MCP tools · REST · CLI |

---

## Business model → repo visibility

Open where we **win adoption & B2B demos**. Private where the **data moat** lives.

| Layer | Repo | | Who it's for |
|:---|:---|:---:|:---|
| **SDK / funnel** | [cli-market-core](https://github.com/Treevu-ai/cli-market-core) | 🌐 | Devs & agents — `pip install` → register → search |
| **B2B showcase** | [procure-copilot](https://github.com/Treevu-ai/procure-copilot) | 🌐 | Procurement teams on CLI Market data |
| **Product moat** | cli-market-world | 🔒 | API, landing, MCP registry, ops |
| **Data moat** | cli-market-backend | 🔒 | Collector, connectors, billing |
| **Semantic moat** | cli-market-index | 🔒 | Golden Record entity resolution |
| **GTM ops** | cli-market-content | 🔒 | Calendar, drafts, campaign gates |

```mermaid
flowchart LR
  subgraph public["🌐 Public — adoption"]
    CORE[cli-market-core]
    PROC[procure-copilot]
  end
  subgraph private["🔒 Private — moat"]
    WORLD[cli-market-world]
    BACK[cli-market-backend]
    IDX[cli-market-index]
  end
  CORE -->|API| WORLD
  BACK -->|prices| WORLD
  IDX -->|Golden Records| WORLD
  PROC -->|powered by| WORLD
  DEV[Agent builder] --> CORE
  B2B[Enterprise buyer] --> PROC
```

> Private repos: request access via [cli-market.dev](https://cli-market.dev) · Pro **$39/mo** for alerts, full MCP & checkout.

---

## Stack

```text
Agents     MCP · tool calling · RAG · agentic workflows
Backend    Python · FastAPI · PostgreSQL
Frontend   Next.js · React · Tailwind
Commerce   VTEX APIs · PayPal · Mercado Pago · PyPI
Cloud      Railway · Cloudflare · GitHub Actions · Azure
```

<details>
<summary><b>Also shipping</b></summary>

<br/>

| Project | Focus |
|:---|:---|
| [sinapsis-innovadora](https://github.com/Treevu-ai/sinapsis-innovadora) | Agentic digital transformation studio |
| [treevu-ai-repo-landing](https://github.com/Treevu-ai/treevu-ai-repo-landing) | Company landing & product catalog |

</details>

---

<div align="center">

### GitHub

<img src="https://github-readme-stats.vercel.app/api?username=Treevu-ai&show_icons=true&theme=dark&hide_border=true&count_private=true&title_color=00d75f&icon_color=00d75f&cache_seconds=1800" alt="GitHub stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Treevu-ai&layout=compact&theme=dark&hide_border=true&title_color=00d75f&cache_seconds=1800" alt="Top languages" height="165" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ricardo_Cuba-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ricardo-antonio-cuba-alvan)
[![X](https://img.shields.io/badge/@cli__market__dev-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/cli_market_dev)
[![Email](https://img.shields.io/badge/hello@cli--market.dev-00d75f?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:hello@cli-market.dev)

<sub>Pin suggestion: <code>cli-market-core</code> · <code>procure-copilot</code> · private moat repos · <code>sinapsis-innovadora</code></sub>

<br/><br/>

*"Agents need a place to shop. We built the aisle."*

</div>