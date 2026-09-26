# Real-Time QRS Detection & HRV Calculation

**Biomedical Engineering | University of Sydney | 2026**

A MATLAB algorithm for real-time cardiac monitoring — detecting QRS complexes from ECG signals and computing heart rate variability (HRV) metrics, validated on unseen test data.

## Overview

QRS detection is the foundational step in ECG signal analysis. This project implements a robust detection pipeline and HRV calculation suite suitable for real-time monitoring applications, evaluated against a held-out test set.

## Performance

| Metric | Result |
|---|---|
| F1 Score (unseen test set) | **98.79%** |
| Average MAPE | 13.68% |

## Pipeline

1. ECG signal preprocessing and noise filtering
2. QRS complex detection algorithm
3. RR-interval extraction
4. HRV metric calculation (time-domain)
5. Performance evaluation on held-out data

## Tech Stack

`MATLAB` `Signal Processing Toolbox` `ECG Analysis`

## Files

- `qrs_detection.m` — Main detection algorithm
- `hrv_calculation.m` — HRV metric computation
- `evaluate.m` — Test set evaluation script
- `report.pdf` — Full project report

## Key Takeaways

- Achieved 98.79% F1 on unseen test data, demonstrating strong generalisation
- Real-time capable pipeline architecture, suitable for monitoring applications
- MAPE of 13.68% reflects variability in RR-interval estimation across edge-case beats
