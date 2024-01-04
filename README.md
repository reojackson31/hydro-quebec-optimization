# Optimizing Hydro Quebec's Power Generation and Distribution Plan
##### *- Project for MMA MGSC662 - Decision Analytics, McGill University*

## Problem Description
Power distribution is a complex problem involving supply of electricity from generators with generating capacity ranging from 4-5,616 kWh in Quebec, supplying to 379 municipalities at different rates every
hour in a single day. Hydro Quebec’s mandate is to meet electricity demand and power municipalities at an affordable cost. To achieve this, production costs and electricity loss during transmission must be
minimized. Also, Hydro Quebec is committed to lowering greenhouse gas emissions from energy generation. To achieve this, they need to identify alternate energy sources and determine the necessary investments for these options.

## Model 1 - Power Generation and Distribution Plan for existing generators
This model optimizes power generation and distribution to minimize costs and transmission losses, subject to constraints such as generator capacity, supply-demand equilibrium, and generator stability. The outcome of this model is an operational plan for Hydro Quebec, providing an optimal framework for efficient power generation and distribution scheduling. 

## Model 2 - Setup New Generators to reduce Greenhouse gas emissions
The second model focuses on minimizing greenhouse gas emissions, while also minimizing the setup and operational costs of new plants (wind, solar, nuclear etc). The model is subject to the constraints from the previous model, in addition to budget constraints, and production thresholds for existing hydro plants. The model also provides a sensitivity analysis, exploring the trade-offs between investment in new plants and the corresponding reduction in emissions.

Refer to the [Project Report](https://github.com/reojackson31/hydro-quebec-optimization/blob/main/Project-Report.pdf) for details on the problem formulation and data sources for each model.  

