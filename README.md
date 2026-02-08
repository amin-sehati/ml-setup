# ML Development Environment Setup

My machine learning development environment configuration for reproducible ML projects.

## Quick Start

**Option 1: Conda (recommended)**
```bash
conda env create -f environment.yml
conda activate ml
```

**Option 2: pip**
```bash
python -m venv ml-env
source ml-env/bin/activate  # Windows: ml-env\Scripts\activate
pip install -r requirements.txt
```

## What's Included

- **Core ML:** NumPy, Pandas, scikit-learn, XGBoost
- **Deep Learning:** PyTorch, TensorFlow
- **Visualization:** Matplotlib, Seaborn
- **Experiment Tracking:** Weights & Biases, MLflow
- **Code Quality:** Black, Flake8, Pytest
- **Notebooks:** Jupyter, IPyKernel

## VS Code Extensions

- Python
- Jupyter
- GitLens
- Pylint

## Repo Structure
```
├── environment.yml       # Conda environment export
├── requirements.txt      # pip dependencies
└── README.md
```