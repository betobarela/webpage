# Data Scientist/Machine Learning Engineer

#### Python, Data Science Tools (scikit-learn, pandas, matplotlib), SQL, Mathematica, Latex, Mathematics and Statistics

## Education
<table style="border-collapse: collapse;">
  <tr>
    <th style="text-align: right; border: none;">Ph.D., Physics</th>
    <td> São Paulo State University (<i>Current</i>)</td>
  </tr>
  <tr>
    <th style="text-align: right; border: none;">M.S., Physics</th>
    <td> São Paulo State University (<i>Feb 2020</i>)</td>
  </tr>
  <tr>
    <th style="text-align: right; border: none;">B.S., Physics</th>
    <td> Federal University of Paraná (<i>Dec 2017</i>)</td>
  </tr>
</table>

## Work Experience
**Theoretical Physicist @ São Paulo State University (_March 2018 - Present_)**
- Currently leader of two research projects and member of a third one;
- Author of two papers published on highly ranked journals in the area;
- Several more works available online.

## Projects

### Brazilian 2022 Elections

Used Python, Pandas and Scikit-learn to produce a regression model that predicts the ratings of the presidential candidates in the second round of the 2022 Brazilian Elections. Each city is an instance and the features are comprised by socioeconomical data from the last census manually scraped from the [IBGE page](https://www.ibge.gov.br/estatisticas/downloads-estatisticas.html). The winning estimator is a simple squared model on the more than 40 numerical features plus one 26 classes categorical ones (the state feature). ElasticNet is the ansatz for regularization, with an l1-ratio of 0.736 and a regularization strenght &alpha; of 
 <span style="display:inline-block;">$6.9 \times 10^{-4}$</span>. The model presents a score of around 0.85 and an average error that, cast as a distribution of the average population, can be seen below 
<p align="center">
  <img src="https://github.com/betobarela/webpage/blob/main/assets/img/error_population_plot.png?raw=true" width="64%" />
</p>

Feature importances are strongly connected to the coefficients of the polynomial model, which can be visualized below  
<p align="center">
  <img src="https://github.com/betobarela/webpage/blob/main/assets/img/feature_importances.png?raw=true" width="90%" />
</p>

### Multilayer backpropagating neural network in Mathematica
[Project's page](https://github.com/betobarela/NN-in-Mathematica)

Wrote a brute force Neural Network algorithm in Mathematica. The code is still rudimentary, and several efficiency improvements must be performed. The code is checked in its current form on the binary logical operators. 

### Higgs statistics
[Project's page](https://github.com/betobarela/Higgs-discovery-di-gamma)

Utilized the Higgs search (which culminated in one of the greatest achievements in the history of science) to illustrate a lesson in statistics. The project's execution consisted of several steps, whose major ones were the simulation, statistics and the visualization of results. The main goal of the project was to obtain the exclusion contour over the Higgs mass and the signal strength using the modified frequentist confidence level, which appears below

<p align="center">
  <img src="https://github.com/betobarela/webpage/blob/main/assets/img/Higgs_Money_Plot.png?raw=true" width="64%" />
</p>

A more detailed description of the process appears in the page of the project.

## Publications
M.W. Barela and V. Pleitez, _Trimuon production at the lhc_, [Phys. Rev. D 101(2020) 015024](https://doi.org/10.1103/PhysRevD.101.015024).

M.W. Barela and J. Montaño Domínguez, _Constraints on exotic particle masses
from flavor violating charged lepton decays and the role of interference_, [Phys.Rev. D 106 (2022) 055013](https://doi.org/10.1103/PhysRevD.106.055013).

M.W. Barela and R. Capdevilla, _Di-Higgs Signatures in Neutral Naturalness_, [Journal of High Energy Physics (to appear)](https://arxiv.org/pdf/2310.09403.pdf).

M.W. Barela, _On the 3-3-1 Landau pole_, [Nuclear Physics B (to appear)](https://arxiv.org/pdf/2305.05066.pdf).

Several additional works available online can be found in the author’s [Inspire page](https://inspirehep.net/authors/1983519)
