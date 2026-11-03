# Week 1 · Model architectures for GeoAI

**Big question:** what makes an AI model *spatial*?

**Slides:** [week01-slides.pdf](week01-slides.pdf) · **Pre-reading:** [Week 1 readings](../../readings/week01-model-architectures.md) · **Lab:** [Same data, four architectures](../../labs/week01-model-architectures/)

## Learning outcomes

By the end of the lecture you can:

1. Explain what makes an AI method spatially explicit.
2. Match grids, sequences, networks and point locations to CNNs, LSTMs, graph neural networks and location encoders, and justify the choice by each architecture's inductive bias.
3. Explain how spatial autocorrelation leaks information in random cross-validation.

## Session plan

| Minutes | Segment | What you do |
| --- | --- | --- |
| 0–10 | Is this GeoAI? | Live poll on six everyday examples, then defend one answer to your neighbour |
| 10–30 | Roots, and why space is special | GeoAI's history since 1984; four tests of spatial explicitness; autocorrelation, heterogeneity and zoning; two vote-discuss-revote questions |
| 30–50 | Paper clinic | Jigsaw on the three readings: expert groups, then teach your table |
| 50–60 | Break | |
| 60–80 | Architecture tour | One architecture per data structure: CNN, U-Net, LSTM, graph neural network, location encoder, foundation model |
| 80–110 | Architecture matchmaking and design canvas | Sort eight real problems by structure and architecture, then design one solution on the GeoAI design canvas and pitch it in a minute |
| 110–120 | Wrap | Ethics minute, preview of the lab, exit ticket |

## Slide outline

| # | Slide | Type |
| --- | --- | --- |
| 1 | Model architectures for GeoAI | Title |
| 2 | Seven weeks, four arcs, one project | Course map |
| 3 | More than half of today is you talking | Session timeline |
| 4 | Is this GeoAI? Yes, no, or it depends | Poll |
| 5 | GeoAI's questions are 40 years old; its tools are new | Timeline, 1984–2025 |
| 6 | Four tests of a spatially explicit model | Concept |
| 7 | A CNN labels satellite tiles: which tests does it pass? | Peer instruction |
| 8 | Geographic data break the "independent samples" assumption | Concept, three diagrams |
| 9 | Random or spatial split: which test score is honest? | Peer instruction |
| 10 | A model that memorises places looks brilliant until it meets a new place | Key message |
| 11 | Jigsaw: become the expert, then teach your table | Paper clinic |
| 12 | Break | |
| 13 | Every architecture is a bet about structure | Overview |
| 14 | A convolution is a GIS focal operation | Diagram |
| 15 | Stacked filters see ever larger patterns | Workflow |
| 16 | An LSTM carries a memory of the catchment through time | Diagram |
| 17 | A graph neural network lets each place listen to its neighbours | Diagram |
| 18 | Teach a network to read a coordinate at many scales | Workflow |
| 19 | Pretrain once on the planet, adapt with a few labels | Workflow and discussion |
| 20 | Architecture matchmaking | Group activity |
| 21 | The GeoAI design canvas | Group activity |
| 22 | Ethics minute | Discussion |
| 23 | This afternoon: same data, four architectures | Lab preview |
| 24 | Before you go | Exit ticket and next week's reading |
| 25 | Readings and sources | References |

## Printable materials

- [GeoAI design canvas (A3)](../../resources/teaching-materials/geoai-design-canvas-A3.pdf)
- [Architecture matchmaking board (A3)](../../resources/teaching-materials/architecture-matchmaking-board-A3.pdf)
- [Scenario cards (A4, cut out)](../../resources/teaching-materials/architecture-scenario-cards-A4.pdf)
