

## Development

You have `environment.yml`, you can use it to create your `conda` env: 

```bash
conda env create -f environment.yml
```

Do not foget to update the `environment.yml`

```bash
```

### Init

How we did create this repository and its configuration:

```bash
conda create -n se_ml_stocks_and_currencies

conda activate se_ml_stocks_and_currencies

conda install -c fastai nbdev


```