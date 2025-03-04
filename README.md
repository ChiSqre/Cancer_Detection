# README

This is my project submission. I’m Andrew Farell, and the materials in this repository pertain to the *Histopathologic Cancer Detection* competition on Kaggle.

## Directory Structure

```
.
├── cancer.ipynb                  # Main Jupyter Notebook for data exploration and modeling
├── histopathologic-cancer-detection
│   ├── sample_submission.csv     # Template for Kaggle submissions
│   ├── test                      # Folder with unlabeled test images
│   ├── train                     # Folder with labeled training images
│   └── train_labels.csv          # CSV containing ground-truth labels for train images
└── my_submission.csv             # Example output file for final test predictions
```

## Downloading the Dataset

1. **Sign in to Kaggle**  
   If you haven’t already, create an account at [Kaggle](https://www.kaggle.com).

2. **Install Kaggle CLI** (if using command line)  
   ```bash
   pip install kaggle
   ```
   Make sure your [Kaggle API credentials](https://www.kaggle.com/docs/api) are set up in `~/.kaggle/kaggle.json`.

3. **Access the Competition**  
   Go to the [Histopathologic Cancer Detection](https://www.kaggle.com/competitions/histopathologic-cancer-detection) competition page.

4. **Download the Data**  
   - From the competition’s *Data* section, click *Download All*  
   **or**  
   - Use the CLI:
     ```bash
     kaggle competitions download -c histopathologic-cancer-detection
     ```

5. **Unzip the File**  
   ```bash
   unzip histopathologic-cancer-detection.zip -d histopathologic-cancer-detection
   ```
   You should see `train/`, `test/`, and CSV files inside the `histopathologic-cancer-detection/` folder.

With the dataset prepared, you can run `cancer.ipynb` or any additional scripts to train and evaluate your models. All final predictions for submission to Kaggle should follow the format in `my_submission.csv`.