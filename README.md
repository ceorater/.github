# CEORater

**Institutional-grade CEO performance analytics** — objective, data-driven insights into CEO Performance across shareholder returns, revenue growth, and CEO compensation efficiency.

## Start here
- Website: https://www.ceorater.com/
- API Docs: https://www.ceorater.com/api-docs.html
- Methodology: https://www.ceorater.com/methodology
- About: https://www.ceorater.com/about.html
- News: https://www.ceorater.com/news/
- Privacy: https://www.ceorater.com/privacy.html
- Support: support@ceorater.com
- Terms of Service: https://www.ceorater.com/terms.html 

---

## Products

### CEORater Web Application
A Bloomberg-style interface for analyzing CEO performance across S&P 500 companies.

- Coverage: S&P 500
- Pricing: $99/month per user (7-day free trial)
- Features: CEO rankings, comparisons, filtering by performance / compensation / founder status

### CEORater API
Programmatic access to CEO performance data for integration into trading systems, research platforms, and AI applications.

- Pricing: $99/month per user (unlimited API calls)
- Formats: JSON (UI-formatted or raw numeric values)
- Data refresh: Daily (weekdays, after market close)

---

## Proprietary metrics (high level)
- **CEORaterScore (0–100):** Composite CEO performance score based on Alpha, Compensation efficiency, and Revenue growth
- **AlphaScore:** Performance vs benchmark (tenure-adjusted)
- **RevenueCAGRScore:** Tenure-adjusted revenue growth percentile
- **CompScore:** Compensation efficiency grade (A–F)

---

## Developer & agent integration
- REST endpoints: `/v1/meta`, `/v1/companies`, `/v1/company/{ticker}`, `/v1/search?q=...`
- Auth: `Authorization: Bearer <api_key>`
- Agent discovery: `/.well-known/agent.json` (A2A) and MCP-compatible tool connections

---

## Repositories
Some CEORater codebases may be private by design. This org is the long-term home for CEORater’s public-facing repos (docs, tooling, examples, and supporting services).

## Contact
- Website: https://www.ceorater.com/
- Support: support@ceorater.com
