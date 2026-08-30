# TabFM Crypto Benchmark

A personal machine learning project to benchmark Google's newly released **TabFM** model against other machine learning and deep learning approaches for cryptocurrency price prediction.

## About

The goal of this project is to compare different models on the same cryptocurrency dataset and evaluate how well they can predict future price values.

The project was developed by:

- **SK Sahil Jaman**
- **Sandipta Adhikary**

## Dataset

The data used in this project was collected from **Binance** and covers approximately the **last six months** of cryptocurrency market data used for the experiment.

The data was prepared and split chronologically into three sets:

- **Training set** — used to train the models
- **Development set** — used for model selection and tuning
- **Test set** — kept for the final evaluation

The chronological split is used so that future observations are not used to train the models.

## Models

The project compares TabFM with several other approaches, including:

- **TabFM**
- **LSTM**
- **XGBoost**
- **AdaBoost**

All models are evaluated on the same prediction task and their performance is compared using common regression metrics.

## Evaluation

The main evaluation metrics used in the benchmark are:

- **MAE** — Mean Absolute Error
- **RMSE** — Root Mean Squared Error
- **R²** — R-squared

The final comparison is performed on the held-out test set.

## Project Structure

At its current stage, this project is intentionally kept simple:

```text
.
├── tabfm_benchmark_github.ipynb
└── README.md
```

The notebook contains the data preparation, model training, prediction, and comparison process.

## Running the Project

The main experiment is contained in the Jupyter Notebook:

`tabfm_benchmark_github.ipynb`

Open the notebook in Jupyter Notebook, JupyterLab, or Google Colab and run the cells in order.

Some dependencies required by the notebook may need to be installed before running it.

## Purpose

This is a personal project created to explore and benchmark different approaches to cryptocurrency prediction, with a particular focus on evaluating **TabFM** against more established models.

The results should therefore be interpreted in the context of this particular dataset, time period, and experimental setup rather than as a general statement about which model is best for cryptocurrency prediction.

## Authors

**SK Sahil Jaman**  
**Sandipta Adhikary**

---

*This project is for experimentation and learning purposes and is not intended as financial advice.*
