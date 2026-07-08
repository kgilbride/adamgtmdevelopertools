# GTM Developer Tools Knowledge Graph

An interactive map of **396 go-to-market (GTM) developer tools** — the coding
agents, agent builders, data/enrichment providers, and headless SaaS that a
software agent can find, access, and call to do GTM work.

The whole thing is a single self-contained `index.html` — open it in any browser,
no install. **[View the live graph »](https://kgilbride.com/adamgtmdevelopertools/)**

## Source

All tool data — categories, agent readiness, panel share-of-voice, employees, and
funding — comes from the **[GTM Developer Tools Map at adamgtm.com/gtm-dev](https://adamgtm.com/gtm-dev/)**.
This page is a visual, explorable projection of that dataset; the map and its
methodology are the work of adamgtm.com.

## What it shows

Every tool is a node, connected to the **categories** it belongs to (e.g. Data &
Enrichment, Web Search & Scraping, Orchestration) and its **type** (GTM-native vs.
broad infrastructure). Each tool also carries a few signals from the source data:

- **Agent readiness** — how usable the tool is by an agent (0–100, with a letter grade).
- **Panel SOV** — its share-of-voice in the panel.
- **Employees** and **funding**.
- **MCP** — whether it exposes a Model Context Protocol server / official agent integration (a heuristic from the source text, so treat it as a strong hint rather than gospel).

## How the graph works

- **Nodes are colored by type** — tools, categories, and GTM/Broad. Bigger nodes are more connected.
- **Click a category or type** to see all of its tools in a table you can **sort by agent readiness or panel SOV**.
- **Click any node** to highlight it and everything it connects to, and fade the rest — click empty space to reset.
- **Click a tool** to see its details: description, the source link, its signals, and the categories it links to.
- **Search** by name or tag, **filter** by type, and switch between graph **layouts** in the sidebar.

## Why this matters
- Knowledge graphs treat the connections between things as first-class data, so you can trace multi-step relationships, unify information that usually lives in separate systems, and spot structural patterns — hubs, clusters, bottlenecks — that a table hides.
- They also pair well with AI: grounding an agent's answers in explicit, traceable facts and relationships reduces hallucination.
- They're not ideal for precise numerical roll-ups or very large node counts, but for understanding how a landscape connects, they reveal what flat data can't.

## License

Code (the viewer) is released under the [MIT License](LICENSE). The underlying data
and methodology belong to [adamgtm.com/gtm-dev](https://adamgtm.com/gtm-dev/) —
please keep that attribution if you reuse it.
