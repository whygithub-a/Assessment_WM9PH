# How to Use This Repository

This repository contains the notebook and files for the WM9PH coursework.

## Run the final test directly

1. Open `Assessment_5758139.ipynb`.

2. Run the first setup cells in the notebook to import libraries and set file paths.

3. Go to `data/processed/`.

4. Unzip these three files in the same folder:

   - `train_set_binary_balanced.zip`
   - `validation_set_binary.zip`
   - `test_set_binary.zip`

5. After unzipping, keep the extracted files inside `data/processed/`.

6. Go to the final model loading and testing section (15) of the notebook.

7. Run that section to load the saved model from the `models/` folder and reproduce the final test results.

## Run the full notebook from raw data

The raw CICIDS2017 CSV files are not included because they are too large.

To run the full notebook from the beginning:

1. Download the CICIDS2017 MachineLearningCSV files from:

   https://www.unb.ca/cic/datasets/ids-2017.html

2. Put the raw CSV files into:

   `data/raw/`

3. Open `Assessment_5758139.ipynb`.

4. Run the notebook from the beginning.

## Notes

The processed data files in `data/processed/` are compressed to reduce file size. They must be unzipped before running the final test section.

The reported results were produced using the recommended Python environment for this module. Small differences may occur if different package versions are used.