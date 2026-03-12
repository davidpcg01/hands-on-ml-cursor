# Hands-On ML Cursor

This repo is a clean, minimal project for the `Cursor` hands-on forecasting exercise.

It includes only:
- the production forecasting dataset needed by the prompts
- the `Cursor` prompt library
- a short `Cursor` setup guide
- a short `Git` setup guide

## Repo Structure

```text
hands-on-ml-cursor/
  README.md
  cursor-setup-and-ai-workflow.md
  git-setup-guide.md
  cursor-prompts/
    arps-forecast-per-well.md
    forecast-dashboard-html.md
    forecast-analysis-insights.md
  data/
    well_monthly_production.csv
    well_master.csv
    data_dictionary.md
    source_notes.md
```

## What This Exercise Does
You will use `Cursor` to:
1. generate a forecasting script from the dataset
2. generate a simple HTML dashboard from the forecast outputs
3. generate an engineering analysis report from the results

## How To Get The Repo
Choose one option:

### Option 1: Download ZIP
If you have never used `Git`, you can still use this exercise:
1. Open this repo on GitHub.
2. Click the green `Code` button.
3. Click `Download ZIP`.
4. Extract the ZIP file.
5. Open the folder in `Cursor`.

### Option 2: Clone With Git
If you want to use `Git`, follow the steps in `git-setup-guide.md`.

## Recommended Workflow
1. Read `cursor-setup-and-ai-workflow.md`.
2. Open the repo in `Cursor`.
3. Open the files in `data/`.
4. Run the first prompt in `cursor-prompts/arps-forecast-per-well.md`.
5. Review the generated forecast script and outputs.
6. Run `cursor-prompts/forecast-dashboard-html.md`.
7. Run `cursor-prompts/forecast-analysis-insights.md`.

## Important Notes
- `oil_bbl`, `gas_mcf`, and `water_bbl` are monthly volumes.
- The forecast target is `oil_rate_bbl_per_day`, which is based on `days_on_prod`.
- This repo does not include precomputed outputs.
- Generated outputs should go under `results/production_forecasting/`.

## Start Here
- `cursor-setup-and-ai-workflow.md`
- `git-setup-guide.md`