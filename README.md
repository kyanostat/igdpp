# igdpp
This page provides codes for the paper:
- Title: An embedding structure of determinantal point process
- Authors: Hideitsu Hino and Keisuke Yano
- Journal: Information Geometry
- Year: 2024
- Abstract: This paper investigates the information geometrical structure of a determinantal point process (DPP). It demonstrates that a DPP is embedded in the exponential family of log-linear models.  The extent of deviation from an exponential family is analyzed using the $\mathrm{e}$-embedding curvature tensor, which identifies partially flat parameters of a DPP. On the basis of this embedding structure, an information-geometrical relationship between a marginal kernel and an $L$-ensemble kernel is discovered.

This paper provide a curved exponential family representation of the determinatal point process.
In partitucular, two key quantities are investigated:
- $\theta(u)$: an embedding structure
- $\psi(u)$: a conditional potential function
The code in this page
- shows that a curved exponential family expression actually describes the probability of DPP; and
- depicts the shape of the conditional potential function and the embedding function.
  
# Dependency

We provide the python implementation.

The program requires the following packages:

- numpy　
- pandas
- dppy

# Garallies 

Comparison of Probability

<img src="https://github.com/kyanostat/igdpp/blob/main/Figure/Prob_comp.png" width="50%">

Figure of $\theta$


<img src="https://github.com/kyanostat/igdpp/blob/main/Figure/Draw_theta.png" width="50%">
