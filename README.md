<div align="center">
  <a href="https://github.com/qnity" target="_blank">
    <picture>
      <img src="images/OSM_logo.jpeg" width=280 alt="Logo"/>
    </picture>
  </a>
</div>

<h1 align="center" style="border-botom: none">
  <b>
    🐍 Actuarial procedures in Jupyter Notebooks 🐍     
  </b>
</h1>

</br>

<p align="center">
  Collection of notebooks that actuaries use in model validation and when interacting with the European regulator. 
</p>

## Procedures available

| Procedure                             | Source                                    | Description                                                                    |
| --------------------------------------| ------------------------------------------| -------------------------------------------------------------------------------|
| [EIOPA RFR technical information]     | [EIOPA RFR monthly tests]                 | Each monthly submission is recalculated to make sure the given curve is correct|
| [Metropolis Hastings likelihood test] | [Metropolis-Hastings parameter estimation]| Bayesian maximum likelihood of a Black Sholes stochastic scenario generator    |
| [Youtube lecture]                     | [# Scenarios check]                       | Checks if # of stochastic scenarios is large enough to cover term structure    |


[Metropolis Hastings likelihood test]:https://en.wikipedia.org/wiki/Metropolis%E2%80%93Hastings_algorithm
[EIOPA RFR technical information]:https://www.eiopa.europa.eu/tools-and-data/risk-free-interest-rate-term-structures_en
[EIOPA RFR monthly tests]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/EIOPA_smith_wilson_test
[Metropolis-Hastings parameter estimation]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/Metropolis_Hastings_Black_Sholes_ESG
[Youtube lecture]:https://www.youtube.com/watch?v=BIZdwUDbnDo
[# Scenarios check]:https://github.com/open-source-modelling/insurance_jupyter/tree/main/enough_stochastic_scenarios



## Procedures planned

| Algorithm                                |  Description                                                                                         |
| -----------------------------------------|  ----------------------------------------------------------------------------------------------------|
| Validation of Deterministic scenarios    |  Validation of the deterministic scenario with monthly steps                                         |
| Validation of stochastic scenarios       | Validation of the stochastic risk neutral scenario with monthly steps and a single source of noise   |

<b> New suggestions are welcome. </b>

<b> If anybody is interested in publishing something they implemented, or help with the project, contact us and we will make it happen. </b>

Queries and suggestions; gregor@osmodelling.com
