# Build an ML Pipeline for Short-Term Rental Prices in NYC
## Author info
By Enrique Marin on May 23rd 2023, based on the teaching material of the Udacity "Machine Learning DevOps Engineer" nanodegree.
## Objective
Use pipelines and an MLOps tools (wandb) for an end to end machine learning project.
## Links
### WandB
https://wandb.ai/eimarinb/nyc_airbnb/
### Github
https://github.com/eimarin/build-ml-pipeline-for-short-term-rental-prices
## How to run this project

### Create environment
Make sure to have conda installed and ready, then create a new environment using the ``environment.yml``
file provided in the root of the repository and activate it:

```bash
> conda env create -f environment.yml
> conda activate nyc_airbnb_dev
```

### Get API key for Weights and Biases
Let's make sure we are logged in to Weights & Biases. Get your API key from W&B by going to 
[https://wandb.ai/authorize](https://wandb.ai/authorize) and click on the + icon (copy to clipboard), 
then paste your key into this command:

```bash
> wandb login [your API key]
```

```bash
>  mlflow run .
```