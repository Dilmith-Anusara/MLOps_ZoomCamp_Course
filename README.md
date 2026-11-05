# MLOps Zoomcamp 2026

My coursework for the [DataTalks.Club MLOps Zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp).

## Structure

| Folder | Content |
|---|---|
| `01-intro` | Environment setup, first model |
| `02-experiment-tracking` | MLflow |
| `03-orchestration` | Pipelines |
| `04-deployment` | Batch / web service / streaming |
| `05-monitoring` | Evidently, Grafana |
| `06-best-practices` | Tests, CI/CD, IaC |
| `Data/` | Dictionaries (parquet files are git-ignored) |

## Setup

    conda create -n mlops python=3.10
    conda activate mlops
    pip install -r requirements.txt

## Data

Download NYC taxi trip data from the
[TLC trip record page](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
into `Data/`.
