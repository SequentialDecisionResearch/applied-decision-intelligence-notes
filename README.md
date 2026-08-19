# Applied Decision Intelligence - Research Notes

A public archive of research notes from **Applied Decision Intelligence** on reinforcement learning, sequential decision-making, Bayesian methods, operations research, and applied decision systems.

The purpose of this repository is to keep conceptual research notes separate from code-heavy reproducible projects. Some notes begin as frameworks or research questions and may later develop into dedicated repositories with code, data, experiments, and formal papers.

## Research notes

### 01. How Reinforcement Learning Fits into Quantitative Investing

**Subtitle:** *From prediction to adaptive portfolio decisions*

This note asks where reinforcement learning fits in a quantitative investment process and where simpler methods may be enough. It treats a long-horizon portfolio as a running example and separates prediction, constrained optimization, sequential control, and uncertainty-aware decisions.

The main idea is that RL is most useful **after prediction**, when today's action changes the state from which tomorrow's decision will be made. The note also treats **no trade** as a valid action and argues that RL should be compared against strong operations-research and model-predictive-control baselines rather than assumed to be superior.

[Read the research note](01-how-rl-fits-into-quantitative-investing/README.md)  
[Open the PDF](01-how-rl-fits-into-quantitative-investing/How_Reinforcement_Learning_Fits_into_Quantitative_Investing.pdf)

![Cover of How Reinforcement Learning Fits into Quantitative Investing](01-how-rl-fits-into-quantitative-investing/assets/cover.png)

## Repository structure

```text
applied-decision-intelligence-notes/
├── README.md
└── 01-how-rl-fits-into-quantitative-investing/
    ├── README.md
    ├── How_Reinforcement_Learning_Fits_into_Quantitative_Investing.pdf
    ├── CITATION.md
    └── assets/
        └── cover.png
```

## Scope

This repository is for **research notes, conceptual frameworks, and early-stage research directions**. A note may contain equations, proposed experiments, testable hypotheses, or practical decision frameworks without yet having a codebase or dataset.

When a note develops into a reproducible research project, the code, data-processing pipeline, experiments, and formal working paper can live in a separate project repository and link back here.

## Research boundary

The material in this repository is for research and educational use. Investment-related notes describe decision frameworks and research questions; they are not investment advice or claims of trading performance.

## Author

**Shenggang Li**  
Applied Decision Intelligence

## Copyright

Unless otherwise stated, written materials in this repository are copyright © 2026 Shenggang Li. No open-content license is granted by default. Individual future projects may use separate licenses for code, data, or written materials.
