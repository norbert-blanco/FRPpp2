# FRPpp2 notebooks

Python/Jupyter notebooks for the FRP++2 course, converted from the original MATLAB Live Scripts. Each notebook runs directly in Google Colab with no setup, using only `numpy` and `pandas` (both preinstalled in Colab).

## Notebooks

| Notebook | Description | Open in Colab |
|---|---|---|
| `notebooks/FRPpp2_Ex0501.ipynb` | A-B-D matrices of a composite laminate | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/norbert-blanco/FRPpp2/blob/main/notebooks/FRPpp2_Ex0501.ipynb) |

## For students

Click the "Open in Colab" badge for the notebook you want. It opens directly in your browser with no installation needed.

> **Note:** When you open a notebook here in Colab, you may see a warning saying "This notebook was not authored by Google." This is a standard Colab security notice for any notebook loaded from GitHub, not a problem with the file. Click **Run anyway** to continue.

To keep your own edits, use **File > Save a copy in Drive** (or **File > Save a copy in GitHub** if you have a GitHub account) right after opening. Otherwise your changes won't be saved when you close the tab, since you're viewing the instructor's copy.

## Repository structure

```
.
├── README.md
├── requirements.txt
└── notebooks/
    └── FRPpp2_Ex0501.ipynb
```

## Running locally (optional)

If you prefer Jupyter on your own machine instead of Colab:

```bash
pip install -r requirements.txt
jupyter notebook
```

## Updating notebooks

Each notebook was generated from the corresponding MATLAB Live Script and verified to reproduce the original numerical output. When pushing an updated version, keep the filename the same so existing Colab links (and the badge above) keep working; students will see the latest committed version the next time they open or reload the link.
