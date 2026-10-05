# interactor-tool-rotten-tomatoes-01

A declarative training experiment that predicts whether a critic's review recommends a film, from the review text and film metadata.

## What it is for

It trains a binary classifier on a table of reviews. The review text goes through a 4-bit quantised open language model with a low-rank adapter, and genres, rating, runtime and the top-critic flag enter as tabular features.

## Build and run

```sh
python build.py
```

It needs the `ludwig` and `pandas` Python packages.

## Licence

The licence is not stated.
