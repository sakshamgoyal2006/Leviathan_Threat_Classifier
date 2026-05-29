# Leviathan Threat Classifier

Multi-channel 2D CNN for multivariate sensor sequence classification.

## Author
Saksham Goyal  

## Project Overview
This project classifies Leviathan behavioral threat states using multivariate temporal sensor data.

The final model uses:
- Multi-channel feature engineering
- Conv2D-based architecture
- Stratified 3-Fold Cross Validation

## Features
Three input channels were used:
1. Raw normalized signals
2. Temporal difference features
3. Per-sequence z-score normalization

## Model
- Conv2D architecture
- BatchNormalization
- MaxPooling
- Dropout
- GlobalAveragePooling

## Validation Accuracy
OOF Accuracy: ~81.2%

## Files
- `leviathan_classifier.ipynb`
- `leviathan_report.pdf`

## Requirements

```bash
pip install -r requirements.txt
```
