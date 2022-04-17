# PySR Showcase

Below is a showcase of papers which have used PySR to discover
or rediscover a symbolic model.

If you have used PySR in your research,
please submit a pull request to add your paper to [this file](https://github.com/MilesCranmer/PySR/blob/master/docs/papers.md).


<div class="row"><div class="image_column">

![](images/economic_theory_gravity.png)

</div><div class="text_column"><div class="center">

[Machine Learning the Gravity Equation for International Trade](https://papers.ssrn.com/abstract=4053795)<br>
Sergiy Verstyuk<sup>1</sup>, Michael R. Douglas<sup>1</sup>.<br>*<sup>1</sup>Harvard University

</div>

**Abstract:** Machine learning (ML) is becoming more and more important throughout the mathematical and theoretical sciences. In this work we apply modern ML methods to gravity models of pairwise interactions in international economics. We explain the formulation of graphical neural networks (GNNs), models for graph-structured data that respect the properties of exchangeability and locality. GNNs are a natural and theoretically appealing class of models for international trade, which we demonstrate empirically by fitting them to a large panel of annual-frequency country-level data. We then use a symbolic regression algorithm to turn our fits into interpretable models with performance comparable to state of the art hand-crafted models motivated by economic theory. The resulting symbolic models contain objects resembling market access functions, which were developed in modern structural literature, but in our analysis arise ab initio without being explicitly postulated. Along the way, we also produce several model-consistent and model-agnostic ML-based measures of bilateral trade accessibility.

</div></div>



https://arxiv.org/abs/2109.10414v2 - particle physics paper, where they use PySR to discover new analytic formulae from one of the inference pipelines built for analyzing LHC (Large Hadron Collider) data.

https://doi.org/10.1007/JHEP06(2021)040 - high-energy physics paper, where they discover a formula for the "hyperbolic volume" of a "knot". This is a really interesting paper, although I note I'm not versed in high-energy physics so am unable to explain the specific problem.

https://arxiv.org/abs/2111.02422v1 - astrophysics paper, where they discover a better way for predicting galaxy properties using properties of the surrounding dark matter halo using PySR.

https://arxiv.org/abs/2109.04484v1 - astrophysics paper, where they use PySR to discover a more accurate model for the properties of dark matter subhalos in an interpretable way.

https://arxiv.org/abs/2012.00111 - astrophysics paper, where they use PySR to model assembly bias, and recover a new interpretable model for doing so.

<style>
.row {
  display: flex;
}
.row:after {
  content: "";
  display: table;
  clear: both;
}
.image_column {
  flex: 25%;
  float: left;
  padding: 10px;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.text_column {
  flex: 65%;
  padding: 10px;
}
.center {
  text-align: center;
}
</style>