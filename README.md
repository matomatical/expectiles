# Expectile statistics

*Expectiles* are a class of summary statistics generalising the
expected value [1, 2].
They have been relatively neglected since their introduction [3].
Perhaps this is because they lacked a simple calculation procedure
and an immediate interpretation like that of the expected value or
that of quantiles.

See [`derivation.pdf`](derivation/derivation.pdf) for a review of
expectile statistics and some thoughts on their interpretation.

Note: If you are interested in expectile-based distributional
reinforcement learning, see
[issue #1](https://github.com/matomatical/expectiles/issues/1)
and
[this other repo](https://github.com/matomatical/tabular-distRL).

## Computing expectiles

This repopsitory provides an efficient implementation for computing
the expectiles of a sample without resorting to generic iterative
optimisation techniques.

See the `expectile` function in module [`expectiles.py`](expectiles.py),
the notebook [`ComputingExpectiles.ipynb`](ComputingExpectiles.ipynb)
for a brief walkthough of the method,
and
[`derivation.pdf`](derivation/derivation.pdf) for a full derivation.

---

Made with :purple_heart: by Matt.


## References

[1]
Dennis J Aigner, Takeshi Amemiya, and Dale J Poirier.
On the estimation of production frontiers: maximum likelihood estimation
of the parameters of a discontinuous density function.
*International Economic Review*, pages 377–396, 1976.

[2]
Whitney K Newey and James L Powell.
Asymmetric least squares estimation and testing.
*Econometrica: Journal of the Econometric Society*, pages 819–847, 1987.

[3]
Linda Schulze Waltrup, Fabian Sobotka, Thomas Kneib, and Göran Kauermann.
Expectile and quantile regression---david and goliath?
*Statistical Modelling*, 15(5):433–456, 2015.
