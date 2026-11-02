# Contributing to Bioinformatics & Multi-Omics Learning Hub

Thank you for your interest in contributing to the **Bioinformatics & Multi-Omics Learning Hub**! This project is an open-source educational platform dedicated to making life sciences, computational biology, and multi-omics data workflows transparent, accessible, and reproducible.

## How Can You Contribute?

1. **Enhancing Existing Labs**: Improve explanations, fix typos, optimize JavaScript performance, or update CLI parameters to match the latest upstream bioinformatic tool releases.
2. **Adding Interactive Calculators**: Introduce new simulators, biological visualizers, or decision logic.
3. **Proposing New Omics Modules**: Suggest or build new interactive labs (e.g. Epigenomics/ChIP-seq peaks, Single-cell RNA-seq Seurat/Scanpy, Spatial Transcriptomics).
4. **Validating Real-World Pipelines**: Verify commands against public benchmarks (e.g. NCBI SRA, EMBL-EBI, ENCODE).

## Development Setup

The project uses pure vanilla HTML5, CSS3, and modern JavaScript with zero heavy build steps.

```bash
# Clone the repo
git clone https://github.com/Angsumi/bioinformatics.git
cd bioinformatics

# Start a local static server
python3 -m http.server 8000
```

Open `http://localhost:8000` in your web browser.

## Code Guidelines

- **Vanilla Standards**: Keep client-side code self-contained without requiring node build chains, ensuring seamless GitHub Pages deployment.
- **Scientific Rigor**: Always provide accurate mathematical definitions (e.g. Lander-Waterman coverage formulas, negative binomial dispersion, pLDDT thresholds) and cite original methodology papers.
- **Responsive & Accessible**: Support both Light and Dark themes, and test across desktop and mobile screens.

## Submitting Pull Requests

1. Fork the repository and create your branch from `main`.
2. Test your changes locally.
3. Commit with concise, descriptive commit messages.
4. Submit a Pull Request describing your changes and the motivation behind them.
