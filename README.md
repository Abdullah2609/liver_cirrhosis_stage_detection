# Liver Cirrhosis Stage Prediction

This project uses machine learning to predict the histologic stage of liver cirrhosis based on clinical and laboratory data. The workflow includes data preprocessing, feature engineering, model training, and evaluation, all implemented in a reproducible Jupyter notebook.

## Features

- Data cleaning and exploratory analysis
- Feature engineering and encoding
- Data scaling and preparation
- Random Forest classifier for stage prediction
- Model evaluation with accuracy and classification report

## Project Structure

```
liver_cirrhosis_stage/
├── liver_cirrhosis_model.ipynb
├── liver_cirrhosis.csv
└── README.md
```

## Getting Started

1. **Clone the repository**
   ```
   git clone https://github.com/<your-username>/liver_cirrhosis_stage.git
   cd liver_cirrhosis_stage
   ```

2. **Install dependencies**
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. **Add the dataset**
   - Place `liver_cirrhosis.csv` in the project directory.

4. **Run the notebook**
   - Open `liver_cirrhosis_model.ipynb` in Jupyter or VS Code and run all cells.

## Usage

- The notebook guides you through each step, from data exploration to model evaluation.
- Modify or extend the notebook to experiment with different models or preprocessing techniques.

## Results

- The Random Forest model provides stage predictions with detailed performance metrics.
- See the notebook output for accuracy and classification report.

*Author*: Abdullah Sakeeb
*Project*: Animal Classification Model with
