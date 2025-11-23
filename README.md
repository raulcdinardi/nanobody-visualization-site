# LLM-Enabled Nanobody Design Results

An interactive visualization website showcasing the results of nanobody design experiments using Large Language Models (LLMs).

## Features

- **Interactive Performance Histogram** - Compare model performance across different metrics
- **3D Molecular Visualization** - Rotating 3D structure of the best-performing nanobody design
- **Model Filtering** - Toggle between different LLM models (DEEPSEEK REASONER, GPT-5, Claude Sonnet 4.0, Claude Haiku 4.5)
- **Academic Paper Layout** - Clean, professional design with text-wrapped figures
- **Responsive Design** - Works on desktop and mobile devices

## Live Demo

Visit the live site: [https://yourusername.github.io/nanobody-visualization-site](https://yourusername.github.io/nanobody-visualization-site)

## Data

The visualization includes:
- **17 experimental runs** across 4 different LLM models
- **ipSAE scores** and other protein interaction metrics
- **3D molecular structures** in CIF format
- **Performance comparisons** between model averages and individual runs

## Technology

- **Frontend**: HTML5, CSS3, JavaScript
- **Visualization**: D3.js for charts, NGL.js for 3D molecular structures
- **Hosting**: GitHub Pages (static site)
- **Data Format**: JavaScript modules for fast loading

## Project Structure

```
├── index.html                 # Main webpage
├── ipsae_individual_data.js   # Experiment data
├── structures/                # 3D molecular structure files
│   ├── anthropic_claude-haiku-4-5_best.cif
│   ├── anthropic_claude-sonnet-4-0_best.cif
│   ├── openai-api_deepseek-reasoner_best.cif
│   ├── openai_gpt-5_best.cif
│   └── openai_gpt-5-mini_best.cif
└── 8JA5.cif                  # Fallback structure
```

## Development

To run locally:
1. Clone this repository
2. Start a local server: `python -m http.server 8080`
3. Visit `http://localhost:8080`

## Citation

This project presents results from nanobody design experiments conducted using state-of-the-art Large Language Models for protein engineering applications.