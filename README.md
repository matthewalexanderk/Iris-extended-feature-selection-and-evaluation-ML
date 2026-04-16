# Iris-extended-feature-selection-and-evaluation-ML
Feature selection on the iris dataset

## What to rerun / verify

Rerun this notebook end-to-end:

- `ABCA4_Advanced_Pipeline.ipynb`

This is the main pipeline notebook that includes the external-data and model-loading steps.

## Safe Hugging Face token setup

The notebook already reads `HF_TOKEN` from environment variables.

Use one of these safe options:

1. Shell/session env var:
   - `export HF_TOKEN=...`
2. Local `.env` file (recommended for local use):
   - Copy `.env.example` to `.env`
   - Put your real token in `.env`
   - Keep `.env` private (it is gitignored)
