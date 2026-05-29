
# Physically Constrained Ensemble Gaussian Process Modelling for Expensive Quantum Systems with Heteroskedastic Noise 

**Arpan Biswas**, Surtirtha Paul, Joseph Agada, Matthias Thamm, **Adrian Del Maestro** 

### Abstract
Accurate modeling of quantum many-body systems often requires computationally expensive simulations such as Density Matrix Renormalization Group (DMRG) or Quantum Monte Carlo (QMC) calculations. These methods, while precise, impose significant time and resource constraints, limiting their use in exhaustive parameter exploration. Moreover, these expensive simulations can contain variable error over the large unknown parameter space, which needs to be quantified and propagated. Thus, predictive modelling is required to estimate the functional space accurately over scarcely sampled data with heteroskedastic noise, while preserving the physical relevance of the estimation. Therefore, we present a Physically Constrained Ensemble Gaussian Process (pc-EGP) framework designed to efficiently model complex and noisy quantum systems under physical consistency constraints. The proposed method first enforces physical constraints as a user controlled weighted penalty to the data-driven loss function of the Gaussian Process (GP) surrogates. Then an ensemble of such GP models is trained with variable noisy simulations via numerical quadrature method where these multiple GP(s) at different nodes are integrated as a quadrature weighted average. We first demonstrate the framework on synthetically generated data before applying to quantum systems.  In the first case study, we leverage DMRG simulations of the Bose-Hubbard Model to predict the critical interaction parameter U_c governing the superfluid-to-Mott-insulator transition. In the second case study, we demonstrate our method on QMC simulations, of a quantum liquid confined inside a nanoporous silicate with the goal of optimizing a chemical environment to realize a one-dimensional superfluid. Compared to conventional GP, pc-EGP achieves a better balance of accuracy and physically meaningful predictions. The proposed approach establishes a route towards robust and domain-informed autonomous and physically interpretable surrogate modeling of any computationally expensive system.


### Description
This repository includes links, code, scripts, and data to generate the figures in a paper. 

### Data
We leverage **DMRG simulations data** of the Bose-Hubbard Model to predict the critical interaction parameter U_c governing the superfluid-to-Mott-insulator transition, and on **QMC simulations** of a quantum liquid confined inside a nanoporous silicate with the goal of optimizing a chemical environment to realize a one-dimensional superfluid. More information on the dataset is provided in the main paper and notebook. 

### Support

This research was primarily supported by the National Science Foundation Materials Research Science and Engineering Center program through the UT Knoxville Center for Advanced Materials and Manufacturing (DMR-2309083). The authors acknowledge the use of facilities and instrumentation at the UT Knoxville Institute for Advanced Materials and Manufacturing (IAMM) and the Shull Wollan Center (SWC) supported in part by the National Science Foundation Materials Research Science and Engineering Center program through the UT Knoxville Center for Advanced Materials and Manufacturing [DMR-2309083](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2309083&HistoricalAwards=false). AFM imaging was performed at the Center for Nanophase Materials Sciences (CNMS), which is a US Department of Energy, Office of Science User Facility at ORNL.



