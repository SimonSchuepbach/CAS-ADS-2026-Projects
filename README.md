# CAS-ADS-2026-Projects

This repository contains the module tasks and projects completed during modules M1–M6 of the CAS in Applied Data Science. It also includes the shared Python project configuration and source package.

## Project setup

```text
CAS-ADS-2026-Projects/
├── M1/
│   └── Readme.md
├── M2/
│   ├── Model2_presentation_ssch.pdf
│   └── ssch_project_m2.ipynb
├── M3/
│   ├── explore_line_profiles.ipynb
│   └── predict_passengers_using_randomForest_and_NN.ipynb
├── M4/
│   └── Readme.md
├── src/
│   └── cas_ads_2026_projects/
│       └── __init__.py
├── .python-version
├── pyproject.toml
└── README.md
```

### Repository folders

- **`M1/`** — Module 1 material and the module README.
- **`M2/`** — Module 2 notebook and presentation PDF.
- **`M3/`** — Module 3 Jupyter notebooks for data exploration and passenger prediction.
- **`M4/`** — Module 4 assessment README and repository setup notes.
- **`src/cas_ads_2026_projects/`** — Shared Python package source code. The package entry point is defined in `pyproject.toml`.

### Project files

- **`.python-version`** — Specifies the Python version used for the project.
- **`pyproject.toml`** — Defines the package metadata, Python requirement, optional notebook dependencies, build configuration, and command-line entry point.
- **`README.md`** — Repository overview and project structure.

## Python setup

The project requires Python 3.13 or newer and uses `uv` for package management. Optional notebook dependencies can be installed with:

```bash
uv sync --extra notebooks
```

The notebook environment includes packages for data analysis and visualization, machine learning, statistical analysis, clustering, and neural networks.
