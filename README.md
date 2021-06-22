# Spatial statistics applied to synthetic datasets
Additional spatial statistics applied to synthetic datasets

This repository contains additional spatial statistics calculated for three synthetic datasets. The datasets considered here are:

<ul>
  <li> Time series data (over 100 hours) for our agent-based model of macrophage infiltration. Results presented here are averaged over 5 simulations with the same parameter set, for varying values of the chemotaxis parameter &#x3C7;. Lighter colours indicate early timepoints, darker colours indicate later timepoints (0, 20, 40, 60, 80, 100 hours respectively).
  <li> The "2RingsExamplePointcloud". This refers to the two rings point cloud used elsewhere in the paper.
  <li> The "3RingsExamplePointcloud". This refers to the three rings point cloud used elsewhere in the paper.
</ul>
  
For each of these datasets, we present figures showing four different spatial statistics:
<ul>
  <li> The pair correlation function (PCF), g(r),
  <li> The CDF of the spherical contact distribution (SCD), F(r),
  <li> The CDF of the nearest-neighbour distribution (NN), G(r),
  <li> The J-function, J(r).
</ul>   
  
For a full definition of each of these statistics, we refer the interested reader to: Bull, J.A., Macklin, P.S., Quaiser, T. et al. Combining multiple spatial statistics enhances the description of immune cell localisation within tumours. Sci Rep 10, 18624 (2020). https://doi.org/10.1038/s41598-020-75180-9
