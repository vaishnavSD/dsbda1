# DSBDA Practical Exercises

A collection of Python scripts and practical notes for **Data Science and Big Data Analytics (DSBDA)**. Each text file contains notebook-style Python code for a particular data preparation, preprocessing, or analysis exercise.

## Topics Covered

The scripts currently show practical work involving:

- Loading datasets with pandas and inspecting DataFrames.
- Data type inspection and feature selection.
- Data preprocessing and normalization with scikit-learn.
- Encoding categorical values using Label Encoding, One-Hot Encoding and pandas dummy variables.
- Detecting and handling missing values.
- Imputing missing values using mean, median, standard deviation, minimum and maximum values.
- Exploratory data analysis and visualization.
- Box plots, scatter plots and histograms.
- Log transformation of numerical data.

Datasets referenced in the scripts include the Iris dataset and student performance / placement-style data.

## Repository Structure

```
dsbda1/
├── dsbda1.txt
├── dsbda2.txt
├── dsbda3.txt
├── dsbda4.txt
├── dsbda5.txt
├── dsbda6.txt
├── dsbda7.txt
├── dsbda8.txt
├── dsbda9.txt
└── dsbda10.txt
```

The files are plain-text Python exercise scripts rather than a single installable package.

## Technology Stack

- Python 3
- pandas
- NumPy
- scikit-learn
- Matplotlib
- Seaborn (where required)

## Running an Exercise

1. Clone the repository:
   ```bash
   git clone https://github.com/vaishnavSD/dsbda1.git
   cd dsbda1
   ```
2. Install the common dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. Open a `.txt` file, copy the Python code into a `.py` file or notebook, and update the dataset paths.
4. Run the script:
   ```bash
   python exercise.py
   ```

## Important

The original exercises contain machine-specific dataset paths (for example, local desktop or notebook paths). Replace those paths with the location of your own CSV files before execution. Install only the dependencies needed by the exercise being run.

## Author

**Vaishnav Dhanwate** · [GitHub](https://github.com/vaishnavSD)
