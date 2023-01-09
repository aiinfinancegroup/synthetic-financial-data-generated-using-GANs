# Synthetic datasets for exchange rate
This repo containns synthetic financial datasets generated using four machine learning models
- GaussianCopula
- CTGAN
- TVAE
- CopulaGAN 

## Data Cleaning
The original data (exchange rates) was transformed to obatin the returns for each currency using the relation 
$$S_t - B_t>0, \forall t,$$ 
where $S_t$ is the selling value, $B_t$ is the buying value of the currency, and $t$ is the time.

## Usage
The synthetic financial data provided in this repo has been evaluated and validated to be close to the real data. It can thus be used to test or evaluate trading strategies or models in a controlled environment.

- Backtesting
- Training
- Stress testing
- Forecasting the volatility of the currency returns

The example notebook can be cloned and used to generate more synthetic datasets especially using the TVAE model that outperformed all the other models during our experiments.

## Citation
If you're using these materials for your research, please cite using

@manual{
    aiinfinance,
    title = {Generating Tabular Financial Datasets using Machine Learning Approaches},
    organization = {AI in Finance Research at Makerere University},
    year = {2023},
    month = {1},
    url = {[https://github.com/aiinfinancegroup/synthetic_exchange_rate/](https://github.com/aiinfinancegroup/synthetic_exchange_rate/)}
}

