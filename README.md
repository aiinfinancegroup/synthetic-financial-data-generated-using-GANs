# synthetic exchange rate datasets
This repo containns synthetic financial datasets generated using four machine learning models
- GaussianCopula
- CTGAN
- TVAE
- CopulaGAN 

## Data Cleaning
The original data (exchange rates) was transformed to obatin the returns for reach currency returns using the relation 
$$S_t - B_t \forall t,$$ 
where $S_t$ is the selling value, $B_t$ is the buying value of the currency, and $t$ is the time.

