<div align="center">

<img src="assets/wordmark.svg" alt="Treevu" width="72" />

# Ricardo Cuba

### Founder · [CLI Market](https://cli-market.dev) · [Sinapsis Innovadora](https://github.com/Treevu-ai/sinapsis-innovadora)

**Commerce infrastructure for AI agents** — one API, CLI & MCP to search, compare and buy across LatAm retail.

🇵🇪 Lima, Perú · turning shelf prices into agent decisions, live in 20+ countries

<br/>

<!-- readme-hero -->
<a href="https://cli-market.dev">
  <img src="assets/readme-hero.svg" alt="CLI Market demo — search, compare and optimize a basket across 6 retailers in one call" width="100%" />
</a>

<br/><br/>

[![Website](https://img.shields.io/badge/cli--market.dev-00d75f?style=for-the-badge&logo=vercel&logoColor=white)](https://cli-market.dev)
[![PyPI](https://img.shields.io/pepy/dt/cli-market?label=downloads&color=00d75f&logo=pypi&style=for-the-badge)](https://pypi.org/project/cli-market/)
[![Core](https://img.shields.io/badge/cli--market--core-PyPI-00d75f?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org/project/cli-market-core/)
[![MCP](https://img.shields.io/badge/MCP_tools-68-00d75f?style=for-the-badge&logo=terminal&logoColor=white)](https://cli-market.dev/tools)
[![Pro](https://img.shields.io/badge/Pro-%2439%2Fmo-00d75f?style=for-the-badge)](https://cli-market.dev/#pro-checkout)

```bash
pip install cli-market
market search "arroz" --country PE --json
market optimize "leche(2) arroz(1) aceite(1)" --country PE
```

</div>

---

## What's live right now

*Pulled straight from the moat, not a slide deck.*

| Signal | Live today |
|:---|:---|
| Shelf prices tracked | **180,000+** snapshots · refresh every ~4h |
| Retailers | **320+** indexed · VTEX · Shopify · WooCommerce · Magento · Bsale |
| Countries | **20+** — 🇵🇪🇦🇷🇧🇷🇨🇱🇨🇴🇲🇽🇪🇨🇬🇹🇺🇾🇨🇷🇵🇦🇧🇴🇵🇾 + 🇪🇸🇮🇹🇫🇷🇩🇪🇳🇱🇬🇧🇺🇸 |
| Product identities | **150,000+** resolved · golden-record cross-store linkage |
| Agent surface | **68** MCP tools · REST API · CLI |
| Basket optimizer | 1 call → best split across retailers, TCO, substitutes, checkout links |

---

## Business model → repo visibility

Open where we **win adoption & B2B demos**. Private where the **data moat** lives.

| Layer | Repo | | Who it's for |
|:---|:---|:---:|:---|
| **Product / API / ops** | [cli-market-world](https://github.com/Treevu-ai/cli-market-world) | 🌐 | The canonical monorepo — API, MCP registry, collector, landing |
| **B2B showcase** | [sinapsis-innovadora](https://github.com/Treevu-ai/sinapsis-innovadora) | 🌐 | Agentic transformation studio & client work |
| **Intelligence layer** | cli-market-core | 🔒 → [PyPI](https://pypi.org/project/cli-market-core/) | Source private, package public — `pip install` still works |
| **Procurement control plane** | procure-copilot | 🔒 | Approval workflows & checkout for LatAm procurement teams |
| **Semantic moat** | cli-market-index | 🔒 | Golden Record entity resolution |
| **GTM ops** | cli-market-content | 🔒 | Calendar, drafts, campaign gates |

```mermaid
flowchart LR
  subgraph public["🌐 Public"]
    WORLD[cli-market-world]
    SIN[sinapsis-innovadora]
  end
  subgraph private["🔒 Private source, public artifacts"]
    CORE[cli-market-core]
    IDX[cli-market-index]
    PROC[procure-copilot]
  end
  CORE -->|"PyPI package"| WORLD
  IDX -->|Golden Records| WORLD
  WORLD -->|"powers"| PROC
  DEV[Agent builder] -->|"pip install"| CORE
  B2B[Enterprise buyer] --> PROC
  WORLD -->|MCP · REST · CLI| AGENTS[AI agents]
```

> Private repos: request access via [cli-market.dev](https://cli-market.dev) · Pro **$39/mo** for alerts, full MCP & checkout.

---

## Stack

```text
Agents     MCP · tool calling · agentic workflows · RAG
Backend    Python · FastAPI · PostgreSQL
Frontend   Next.js · React · Tailwind
Commerce   VTEX · Shopify · WooCommerce APIs · PayPal · Mercado Pago
Cloud      Fly.io · Cloudflare · GitHub Actions
```

<details>
<summary><b>Also shipping</b></summary>

<br/>

| Project | Focus |
|:---|:---|
| [sinapsis-innovadora](https://github.com/Treevu-ai/sinapsis-innovadora) | Agentic digital transformation studio |
| [treevu-ai-repo-landing](https://github.com/Treevu-ai/treevu-ai-repo-landing) | Company landing & product catalog |
| [invisible-hand](https://github.com/Treevu-ai/invisible-hand) | Market automation engine — signal-driven microservices |

</details>

---

<div align="center">

### GitHub

<img src="https://github-readme-stats.vercel.app/api?username=Treevu-ai&show_icons=true&theme=dark&hide_border=true&count_private=true&title_color=00d75f&icon_color=00d75f&cache_seconds=1800" alt="GitHub stats" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Treevu-ai&layout=compact&theme=dark&hide_border=true&title_color=00d75f&cache_seconds=1800" alt="Top languages" height="165" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ricardo_Cuba-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ricardo-antonio-cuba-alvan)
[![X](https://img.shields.io/badge/@cli__market__dev-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/cli_market_dev)
[![Email](https://img.shields.io/badge/hello@cli--market.dev-00d75f?style=for-the-badge)](mailto:hello@cli-market.dev)

<sub>Pin suggestion: <code>cli-market-world</code> · <code>sinapsis-innovadora</code> · private moat repos on request</sub>

<br/><br/>

*"Agents need a place to shop. We built the aisle."*

</div>
