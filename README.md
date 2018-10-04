# Quantopian Models
This Github repository is a collection statistical and ML financial models to trade US equities at a profit. All models are coded on the Quantopian platform in Python in Jupyter research notebooks.

Most, if not all, of the datasets are obtained from Quantopian's platform. This includes asset and ticker data, fundamentals, and trader sentiment data from StockTwits. 

There will be a collection of various and diverse trading models in this repository, some experimental. All models will perform statistical or machine learning techniques on the datasets in order to glean insights and use this information to trade equities at a profit.

All backtesting is executed on the Quantopian platform. Results will be documented in this file.

## Quant Workflow
The workflow of how these models are built from scratch, deployed, tested, and iterated upon is listed at this [site](https://blog.quantopian.com/a-professional-quant-equity-workflow/). 

## Machine Learning Workflow
In order to generate the alpha signals to decide what equities to go long or short on, some models will use machine learning algorithms. Although there are plenty of machine learning techniques, the workflow boils down to:

Collect Data --> Data Preprocessing --> Feature Engineering --> Model Selection, Iteration, and Testing --> Model Deployment and Testing on Real Data
