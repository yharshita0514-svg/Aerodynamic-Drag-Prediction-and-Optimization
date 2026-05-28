# Aerodynamic-Drag-Prediction-and-Optimization
CFD and Machine Learning based aerodynamic drag prediction and optimization using ANSYS Fluent and Python
# AI-Based Aerodynamic Drag Prediction and Optimization

CFD and Machine Learning based aerodynamic drag prediction using ANSYS Fluent and Python.

---

## Project Overview

This project focuses on aerodynamic drag prediction and optimization using Computational Fluid Dynamics (CFD) and Machine Learning (ML).

Aerodynamic simulations were performed in ANSYS Fluent by varying:

* Inlet Velocity
* Angle of Inclination

The resulting aerodynamic drag coefficient (Cd) values obtained from CFD simulations were used to generate a dataset for Machine Learning model training.

A Random Forest Regression model was developed in Python to predict drag coefficient values for different aerodynamic conditions without performing repeated CFD simulations.

The project demonstrates how Machine Learning can accelerate aerodynamic analysis and optimization workflows.

---

## Objectives

* Perform aerodynamic CFD simulations in ANSYS Fluent
* Analyze drag behavior under varying velocities and inclination angles
* Generate a CFD-based aerodynamic dataset
* Train a Machine Learning model for drag coefficient prediction
* Predict optimized aerodynamic conditions using ML

---

## CFD Analysis

The aerodynamic model was analyzed inside a fluid enclosure using ANSYS Fluent.

### Simulation Setup

* Solver Type: Pressure-Based
* Flow Type: Steady State
* Turbulence Model: SST k-ω
* Working Fluid: Air

### Boundary Conditions

* Velocity Inlet
* Pressure Outlet
* Wall Boundary

---

## Machine Learning Model

The CFD-generated dataset was used to train a Random Forest Regression model in Python.

### Input Parameters

* Inlet Velocity
* Angle of Inclination

### Output Parameter

* Drag Coefficient (Cd)

### Libraries Used

* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## Results

The project successfully demonstrated:

* CFD-based aerodynamic analysis
* Flow visualization and drag evaluation
* ML-based drag coefficient prediction
* Aerodynamic optimization workflow

### Generated Outputs

* Residual convergence plots
* Velocity contours
* Pressure contours
* Streamline visualization
* Actual vs Predicted ML graph

---

## Tools & Technologies

* ANSYS Fluent
* Python
* Jupyter Notebook
* Scikit-learn
* Pandas
* Matplotlib

---

## Project Workflow

1. Geometry Preparation
2. Mesh Generation
3. CFD Simulation
4. Dataset Collection
5. Machine Learning Training
6. Drag Prediction & Optimization

---

## Applications

* Automotive Aerodynamics
* Electric Vehicle Design
* UAV and Drone Design
* AI-Assisted Engineering Optimization


---

## Author

Harshita Yadav

