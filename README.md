# NLP

A collection of notebooks used in NASSCOM NATC Deep Dive session.

`pytorch-lin-reg-sgd.ipynb`
Basic implementation of linear regression and SGD in pytorch.

Run the notebook in a python environment which has pytorch, numpy and matplotlib installed.

## Yelp reviews rationale extraction

Get the yelp review dataset from https://www.yelp.com/dataset

Prepare the data using `yelp-data.ipynb`

Rationale extraction model in `compiled-yelp-new.ipynb`. Pytorch and GPU required to train and run the model.


## DeViSE (inspired by fastai)

Get the dataset from Kaggle - Image Localization Challenge (150GB data)

Notebook is `devise-example.ipynb`. Pytorch and `nmslib` should be installed in the environment. Training requires GPU.
