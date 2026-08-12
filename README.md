# Physiological Signal Analysis

Analysis of respiration and heart rate variability (HRV) from human subject recordings, from a biomedical engineering laboratory course (BME 235, Arizona State University).

## What it does

- Loads raw respiration and cardiac recordings from a lab session
- Cleans the signals and detects peaks using NeuroKit2
- Computes breathing rate and HRV metrics from the processed signals
- Plots the processed signals and computed results

## Viewing and running

The notebook is committed with its outputs, so all figures and results render directly on GitHub — no setup needed to read it.

To run it yourself, use the Colab badge above, or locally:

```
pip install neurokit2 pandas numpy matplotlib
jupyter notebook Physiological_Signal_Analysis.ipynb
```

## Data

The recordings analyzed here are my own, collected during the lab session. <!-- Adjust this line if the notebook expects a data file: say where it lives and how to point the notebook at it. -->

## Context

This analysis accompanied a formal laboratory write-up; the notebook contains the full processing pipeline behind the reported results.
