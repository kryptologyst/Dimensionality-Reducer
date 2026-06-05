# Dimensionality Reducer

A modern machine learning project implementing PCA, t-SNE, UMAP for Data Visualization.

## Overview

Multiple dimensionality reduction techniques

## Features

- **Modern Python**: Type hints, logging, configuration management
- **CLI Interface**: Typer-based command-line interface
- **Comprehensive Testing**: pytest with coverage
- **Visualization**: matplotlib/seaborn plots
- **Model Persistence**: Save and load trained models
- **Extensible Architecture**: Easy to customize and extend

## Quick Start

```bash
# Install dependencies
pip install -r requirements.txt

# Run the main application
python src/main.py

# Run tests
pytest tests/ -v
```

## Project Structure

```
0037 Dimensionality Reducer/
├── src/
│   ├── __init__.py
│   ├── main.py          # Entry point
│   ├── model.py         # ML model implementation
│   ├── data.py          # Data handling
│   ├── visualizer.py    # Visualization utilities
│   └── config.py        # Configuration
├── tests/
│   ├── __init__.py
│   └── test_model.py
├── outputs/
│   ├── plots/
│   └── models/
├── data/
├── requirements.txt
├── pyproject.toml
├── .gitignore
└── README.md
```

## Dependencies

- numpy>=1.26.0
- scikit-learn>=1.4.0
- matplotlib>=3.8.0
- pandas>=2.2.0
- loguru>=0.7.2
- typer>=0.12.0
- pydantic>=2.6.0

## Testing

```bash
# Run all tests
pytest

# Run with coverage
pytest --cov=src tests/

# Run specific test
pytest tests/test_model.py -v
```

## License

MIT License

# Dimensionality-Reducer
