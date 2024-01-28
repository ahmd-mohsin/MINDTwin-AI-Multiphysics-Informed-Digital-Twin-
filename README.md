[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) [![COMSOL](https://img.shields.io/badge/COMSOL-brightgreen
)](https://scc.dipc.org/docs/software/applications/comsol/)

# MINDTwin-AI-Multiphysics-Informed-Digital-Twin-
The official repository for MINDTwin AI: Multiphysics Informed Digital-Twin for Fault Localization in Induction Motor using AI

## Details
This paper focuses on an Artificial Intelligence (AI)- based approach for fault localization in a squirrel cage threephase induction motor (TIM). A multifaceted Digital-Twin (DT) is designed by integrating physics domain knowledge with AI algorithms. The aim is to design a Multiphysics-informed hybrid DT for fault detection and localization in TIM. To achieve this, a high-fidelity computational model of an induction motor is developed using the Finite Element Analysis (FEA) in COMSOL Multiphysics. The model parameters, loading conditions, and boundary conditions are meticulously tuned with an experimental workbench using a Sparse Nonlinear Optimization (SNOPT) solver. Simulations are conducted to replicate various electrical and mechanical defects. 
[<img align="right" width="250" height="250" src="https://scc.dipc.org/docs/software/applications/comsol/images/comsol-logo.png"/>](https://scc.dipc.org/docs/software/applications/comsol/)
Additionally, the model order reduction technique is employed to generate a reduced state-space model, enabling the high-fidelity dynamic system to act as a virtual sensor exhibiting real-time capabilities. The feature fusion process leverages Canonical Correlation Analysis (CCA) within the hybrid DT modeling framework. Comparative analysis demonstrates that the Multiphysics-informed hybrid modeling approach enhances the interpretability of AI classifiers, improving real-time condition monitoring and fault localization in TIM.

## Flow Chart

[<img align="right" width="250" height="250" src="https://i.ibb.co/cFXnjTF/Flowchart.png"/>]
