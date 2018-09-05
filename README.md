# Evaluating IR Metrics for Top-N Recommendation

Source code of the experiments of:

> [Daniel Valcarce](http://www.dc.fi.udc.es/~dvalcarce), [Alejandro Bellogín](http://ir.ii.uam.es/~alejandro), [Javier Parapar](http://www.dc.fi.udc.es/~parapar), [Pablo Castells](http://ir.ii.uam.es/castells): [On the Robustness and Discriminative Power of IR Metrics for Top-N Recommendation](http://www.dc.fi.udc.es/~dvalcarce/pubs/valcarce-etal-recsys2018.pdf). In _Proceedings of the 12th ACM Conference on Recommender Systems_, RecSys 2018, Vancouver, Canada, 2-7 October, 2018. DOI [10.1145/3240323.3240347](http://dx.doi.org/10.1145/3240323.3240347).

## Code

The code of the experiments can be found in the following Jupyter notebooks:
- `correlation-among-metrics.ipynb`: measures ranking correlations among metrics.
- `discrimination-analysis.ipynb`: measures discriminative power of metrics.
- `pop-correlation.ipynb`: measures robustness to popularity bias of metrics.
- `sparse-correlation.ipynb`: measures robustness to sparsity bias of metrics.

## Data

We ran 21 recommender systems on three datasets (BeerAdvocate, LibraryThing and MovieLens 1M).

## Author

The code was implemented by Daniel Valcarce of the [Information Retrieval Lab](http://irlab.org) of the [University of A Coruña](https://www.udc.es) during his stay at the [Information Retrieval Group](http://ir.ii.uam.es) of the [Universidad Autónoma de Madrid](http://uam.es). If you have any comment or question, do not hesitate to write an email to daniel [DOT] valcarce [AT] udc [DOT] es.
