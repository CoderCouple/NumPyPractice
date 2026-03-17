# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A learning/practice repository for Python data science fundamentals using Jupyter notebooks. Covers NumPy, Pandas, and visualizations (matplotlib).

## Environment

- Python 3.9 virtualenv at `.venv/`
- Key packages: numpy 2.0.2, pandas 2.3.3, matplotlib 3.9.4, jupyterlab 4.5.6

## Commands

```bash
# Activate virtualenv
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter lab

# Run a specific notebook from CLI
jupyter nbconvert --to notebook --execute src/numpy/01_why_is_numpy_faster_than_python_list.ipynb
```

## Structure

- `src/numpy/` - NumPy notebooks (array creation, batch ops, type conversion, arithmetic)
- `src/pandas/` - Pandas notebooks (Series, DataFrame basics)
- `src/visualizations/` - Matplotlib notebooks (placeholder)
- `data/` - Dataset storage (empty)
- `models/` - Model storage (empty)

Notebooks are numbered sequentially (00_, 01_, 02_, ...) within each topic folder. Each folder has an `__init__.py` for package-style imports.
