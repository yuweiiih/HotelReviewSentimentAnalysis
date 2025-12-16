# TripAdvisor Hotel Rating Prediction

A compact end to end supervised learning project that turns real guest review text into predicted hotel ratings, built on the TripAdvisor Hotel Reviews dataset.

This repo includes the full writeup, the runnable training pipeline in R, and the R Markdown source used to generate the report.

---

## What this project does

- Ingests the TripAdvisor hotel review dataset (CSV)
- Cleans and prepares text and labels for modeling
- Trains supervised models to predict rating outcomes from review content
- Documents results, tradeoffs, and next steps in a short report

---

## Repository contents

- **Hotel-prediction-proj.pdf**  
  Final report (methods, experiments, results, conclusions)

- **Hotel-prediction-proj.R**  
  Main supervised learning run script

- **Hotel prediction proj.Rmd**  
  R Markdown source for the report

---

## Dataset

This project uses the **TripAdvisor Hotel Reviews** dataset from Kaggle.

- Source / credit: Larxel  
- Kaggle page: https://www.kaggle.com/andrewmvd/trip-advisor-hotel-reviews

Place the dataset CSV in the location expected by the scripts (see the paths at the top of `Hotel-prediction-proj.R` and/or the `.Rmd`).

---

## How to run

1. Clone the repo
2. Install required R packages (listed in the scripts)
3. Run the pipeline:

```r
source("Hotel-prediction-proj.R")
