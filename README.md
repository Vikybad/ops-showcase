# Operations Showcase

Two compact, browser-only prototypes for data exploration and incident review.

## Energy Mix Monitor

- A small interactive dashboard comparing renewable energy as a share of total final energy consumption for India, Bangladesh, Pakistan, Sri Lanka, Nepal, and Indonesia.
- The embedded World Bank World Development Indicators snapshot uses `EG.FEC.RNEW.ZS`, sourced from IEA Energy Statistics. Values are annual, 2000–2021; the latest non-empty year varies. The percentage is not an electricity-only measure.
- The dashboard has a country spotlight, trend comparison, latest-observation ranking, and an interpretation note.
- Source and license are linked in the app: World Bank WDI / CC BY 4.0.

## Traceboard

- A fictional incident timeline builder with event entry, chronological sorting, severity filtering, and a copyable handoff summary.
- Events are held in page memory only. No server, storage, integrations, or customer/production data are used.
- The handoff separates observed events from a confirmed root cause.

Both apps are static pages with no dependencies or external runtime requests.
