# Chokepoints.ai

Interactive visualization of the AI compute value chain — a 580-node taxonomy mapping every layer from raw materials to applications, with the full dependency web between them.

## Live Demo

Open `index.html` in any modern browser. No server or build step required — it's a single self-contained HTML file.

## Features

**Four visualization modes:**

- **Dependency Map** — Force-directed graph showing how nodes relate across layers. Hover any node to trace its dependency chain back to raw materials.
- **Opportunity Matrix** — Scatter plot positioning nodes by investment score vs. value capture potential.
- **Company Treemap** — Area-proportional view of companies mapped to each node in the taxonomy.
- **Value-Chain Wheel** — Radial layout of the full value chain with cross-layer links.

**Interactive controls:**

- **Search** — Filter nodes and companies by name.
- **Depth selector** (L1 / L2 / L3 / All) — Control how deep into the taxonomy you drill.
- **Size lens** — Resize nodes by company count, investment score, or value capture.
- **Color lens** — Recolor by layer, criticality, score, value capture, market structure, maturity, AI potential, or investment angle.
- **Choke only** — Isolate chokepoint nodes (high-criticality bottlenecks).
- **Scored only** — Show only nodes with an investment score.
- **Click any node** to open a detail panel with metrics, upstream/downstream dependencies, and mapped companies.

## Taxonomy Layers

| Layer | Name |
|-------|------|
| L0 | Raw Materials & Extraction |
| L1 | Semiconductor Manufacturing & Supply Chain |
| L2 | Compute Hardware & Components |
| L3 | Power Generation & Supply Chain |
| L4 | Transmission, Grid & Interconnection |
| L5 | Data Centre Physical |
| L6 | Cloud & Infrastructure Software |
| L7 | Models & Foundation Labs |
| L8 | Applications & Inference (Demand Side) |
| LX | Cross-Cutting Enablers & Services |

## Requirements

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No dependencies to install — D3.js and fonts load from CDNs

## Usage

```bash
# Clone the repo
git clone https://github.com/romildepala/chokepoints.ai.git

# Open in your browser
open chokepoints.ai/index.html
```

Or simply double-click `index.html` from your file manager.

## License

Proprietary. All rights reserved.
