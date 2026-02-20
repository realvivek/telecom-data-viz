# Data viz — tech stack and costs (initial)

## Reference competitor capabilities (for build-vs-buy decisions)
- Power BI markets “Power BI Embedded” as a pay-as-you-go PaaS to embed interactive reports into apps. Source: https://www.microsoft.com/en-us/power-platform/products/power-bi/
- Grafana OSS is positioned as an open-source visualization and monitoring solution with plugins + dashboards. Source: https://grafana.com/oss/grafana/

## Suggested modern web stack (build-first)
### Frontend
- Next.js (React) + TypeScript
- Visualization: D3 / Observable Plot / ECharts; Mapbox/Deck.gl for geospatial

### Backend / data layer
- Postgres + PostGIS for geo
- ELT: dbt + scheduled ingestion (Airflow-lite / cron)
- API: FastAPI (Python) or Node (NestJS) + caching (Redis)

### Hosting (indicative)
- Vercel pricing page shows included quotas and usage-based pricing components (Edge Requests, Fast Data Transfer, Functions, etc.). Use as baseline for serverless hosting cost structure. Source: https://vercel.com/pricing

## Notes / next data to add
- Add concrete monthly cost examples for 3 tiers (hobby, small team, paid SaaS) across compute + DB + storage + observability.
- Add alternative: all-in-one hosted BI (Metabase Cloud / Preset for Superset).
