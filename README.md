# Human Activity Recognition (HAR)

## Overview
Multi-class sequence classification using accelerometer and gyroscope sensor data. Implemented models include RNN, LSTM, Bi-LSTM, and 1D-CNN for sequence classification.

## Dataset
Sensor dataset with six activity classes: walking, walking upstairs, walking downstairs, sitting, standing, laying. Features include 3-axis linear acceleration and 3-axis angular velocity. The notebook assumes data files are placed in a `data/` folder as described.

## Methodology
1. Data loading, segmentation/windowing (if applied), and preprocessing  
2. Normalization and sequence formatting  
3. Model training: RNN/LSTM/Bi-LSTM/1D-CNN with early stopping  
4. Evaluation using Accuracy, Precision, Recall, AUROC, and confusion matrices

## How to run
1. Place dataset files in the `data/` directory as described in the notebook.  
2. Create and activate a Python virtual environment.  
3. Install dependencies:
```
pip install -r requirements.txt
```
4. Open and run:
`har-sequence-classification.ipynb`

## Notes & Recommendations
- Evaluate models only on the test set for final reporting.  
- Provide any preprocessing scripts used to generate sequences.  
- Cite any external code and note modifications.

## Repository structure
- `har-sequence-classification.ipynb` — main notebook  
- `requirements.txt` — dependencies
