# Congressional Stock Trading Party Prediction

This project explores whether U.S. congressional stock trading behavior can help predict political party affiliation. I analyzed trading disclosures using features such as filing delays, trade timing, transaction type, trade size, chamber, state, and ticker activity.
I cleaned the dataset, created visualizations, and built machine learning models to classify trades as Democratic or Republican. The goal was to identify patterns in congressional trading behavior, not to suggest causation or misconduct.

## Built With
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-learn
* TensorFlow/Keras
* Jupyter Notebook

## Files
* `data-cleaning.ipynb` — cleans and prepares the dataset
* `EDAPlotsFinal.ipynb` — explores trends and visualizations
* `ML_Modeling_Final_Project.ipynb` — trains and evaluates models
* `RNN.ipynb` — tests a sequence-based model
* `prepared_congress_trading_dataset.csv` — cleaned dataset

## Usage
Install the required packages:
```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn tensorflow
```

Run the notebooks in this order:
```text
1. data-cleaning.ipynb
2. EDAPlotsFinal.ipynb
3. ML_Modeling_Final_Project.ipynb
4. RNN.ipynb
```

## Results
The strongest predictors were timing-based features, especially the number of days between the trade date and the filing date. The Random Forest model performed best, reaching about 76% test accuracy.
