# Public Complaints Classification (DistilBERT)

Deep learning project that classifies public complaints into the correct
government department using a fine-tuned DistilBERT model.

## Project Structure

- notebooks/ : Training notebook + dataset
- src/ : (reserved for future scripts)
- docs/ : Project documentation / report
- models/best_model/ : Saved fine-tuned model + tokenizer
- assets/screenshots/ : Result screenshots
- requirements.txt
- README.md

## Overview

- Model: distilbert-base-uncased (last 2 transformer layers fine-tuned)
- Task: Multi-class text classification
- Input: Free-text public complaint
- Output: Predicted department

## How to Run

1. Install dependencies: pip install -r requirements.txt
2. Open notebooks/Public_Complaints_Classification.ipynb in Jupyter or Colab.
3. Update dataset_path to point to your local copy of complaints_dataset.csv.
4. Run all cells to reproduce training and evaluation.

## Author

P. Amrutha Varsini
