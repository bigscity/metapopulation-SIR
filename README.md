# Metapopulation SIR Model

An implementation of Metapopulation SIR model for forecasting epidemic transmission.

## Installation

All required packages are list in `environment.yml` which is available from [Anaconda](https://anaconda.org/). Install with:

```
conda env create -f environment.yml
```

## Get started

Read the notebook in `code/`, which contains a sample for modelling epidemic transmission across multiple countries using metapopulation SIR model. Key points are commented in code. Other directories are functioning as 

- `objs/` contains dictionaries storing the transmission between different metapopulation. Provide samples of aviation transmisstion of 100 countries.
- `data/` contains the population and cumulative confirmed cases of COVID-19 of each metapopulation.

## References

Related paper of this model. 

```
@inproceedings{wang2018inferring,
  title={Inferring metapopulation propagation network for intra-city epidemic control and prevention},
  author={Wang, Jingyuan and Wang, Xiaojian and Wu, Junjie},
  booktitle={Proceedings of the 24th ACM SIGKDD International Conference on Knowledge Discovery \& Data Mining},
  pages={830--838},
  year={2018}
}
```

