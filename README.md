# ICS2019
 Combustion Modeling - Iran First International Combustion School (ICS2019)

## Lessons on Combustion Modeling

### Lesson 1: Governing equations, thermodynamics, kinetics, and transport properties (~1.5 h)
* Presentation of the course, learning objectives, organization
* Transport equations
  * Continuity and momentum equations
  * Conservation of species; diffusion fluxes (Stefan-Maxwell theory, Fick diffusion, Soret effect)
  * Energy equation: enthalpy and temperature formulations
* Basics of thermodynamics, kinetics, and transport properties
  * Enthalpy and specific heats, NASA polynomial formalism
  * Kinetic parameters, reaction rate, reversible reactions, equilibrium constant, examples of kinetic mechanisms in CHEMKIN format, pressure-dependent reactions (third-body, fall-off reaction, Chebyshev formalism, PLOG formalism)
  * Kinetic theory of gases (viscosity, mass diffusion coefficients, thermal conductivity, Lewis number) 
* Introduction to the CHEMKIN formalism

### Lesson 2: Numerical algorithms for reactive flows (~2 h)
* Introduction: complexity of reacting flows and combustion
  * Detailed kinetics and combustion
  * Non-linearity, coupling, stiffness
* The 0D reacting system model
  * Governing equations
  * Numerical solution of ODE systems
  * The Jacobian matrix and the sparsity of kinetic mechanisms
* Ideal reacting systems in combustion
  * Batch Reactor
  * Shock Tube Reactor
  * Perfectly Stirred Reactor
  * Plug Flow Reactor

### Lessons 3: Numerical methods for 1D and multi-dimensional flames (~2 h)
* Introduction: Combustion and transport phenomena & laminar flames
* Numerical solution of 1D flames
  * Premixed laminar flames
    * Burner stabilized unstretched (or flat) flame
      * Governing equations and modeling aspects
      * Numerical solution
    * Freely-propagating unstretched (or flat) flame
      * Governing equations and modeling aspects
  * Counterflow diffusion flames
    * Governing equations and modeling aspects
* Multidimensional flames
  * Introduction and examples
  * Governing equations
  * Numerical algorithms for multidimensional flames
  * The operator-splitting method

### Lesson 4: Advanced techniques for reacting flows with detailed kinetics (~1.5 h)
* Acceleration of simulations by reduction of specie
  * Skeletal reduction
  * Quasi Steady-State Approximation (QSSA)
  * Dynamic Stiffness Removal (DSR)
  * Dynamic Adaptive Chemistry (DAC)
* Acceleration of simulation by reduction of reacting environments
  * Reaction Network Analysis (RNA) and Kinetic Post-Processor (KPP)
  * Dynamic Adaptive Clustering
  * ISAT (In Situ Adaptive Tabulation)
* Species bundling for diffusion coefficient reduction
* Computation Cost Minimization
* Numerical tools for analysis of kinetic mechanisms
  * Sensitivity Analysis
  * Rate of Production and Reaction Path Analyses

### Lesson 5: Introduction to numerical modeling of turbulent reacting flows (~1.5 h)
* Introduction to turbulent flows
* Statistical description of turbulent flows
  * Reynolds and Favre average
  * 2-point correlations
  * Turbulent eddies and energy cascade
* Kolmogorov’s Theory
  * Kolmogorov’s similarity hypotheses
  * Kolmogorov’s scales
  * Energy spectrum
* Transport equations for mean variables
  * Need of mean/filtered equations
  * Averaged transport equations for continuity and momentum
  * Closure models for turbulent flows: 𝜅−𝜀 model
  * Favre’s averaged transport equations for passive scalars and species
  
### Lesson 6: Turbulent combustion modeling (~2 h)
* Introduction to turbulent combustion modeling
  * Fluid dynamic and chemical time scales
  * Effects of turbulent fluctuations on chemical reactions
  * Need of turbulent combustion models
* Non-premixed combustion
  * Eddy Dissipation models: ED, ED-FR, EDC
  * Steady Laminar Flamelet model
    * Mixture fraction
    * Flamelet equations
    * Presumed PDF approach
* Premixed combustion
  * Eddy Break-Up (EBU) model
  * Bray-Libby-Moss (BLM) model
  * G-Equation
  
