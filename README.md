# MATH 269A: Building, Analyzing and Stress-testing ODE Solvers

## How to reproduce the results in this project

In this README, you will be guided to reproduce results in this repository regarding building, analyzing and stress-testing ODE solvers. In particular, this document should allow you to reproduce all experiments involved from Stages 1 to 8 of the final. 

### Stage 1: Baseline Euler and Error Verification
### Stage 2: Higher-Order One-Step Methods and Validation
### Stage 3: Stability and Timestep Selection via the Model Problem
### Stage 4: Systems: Correctness and Diagnostics
### Stage 5: Implicit Methods and Nonlinear Solves
### Stage 6: Stiﬀness Study with Explicit vs. Implicit
### Stage 7: Adaptive Stepsize with Local and Global Control
### Stage 8: Linear Multistep Methods and Zero-Stability

# Project Description
Over the entire quarter, you will build a small but serious ODE solver toolkit, validate it theoretically and empirically, and use it to study nontrivial differential equations. Your deliverable is one comprehensive final report with an appendix containing your figures, data tables, and implementation notes. The work must be conducted independently. A polished user interface is encouraged but not required; likewise, it is encouraged (not required) that your final program accept a broad class of user-defined problems and automatically perform all analyses specified below. 

The project is organized into staged tasks that follow the same intellectural arc as the lectures: from first-order Initial-Value Problems (IVPs) and one-step methods, through error bounds and stability, to systems, stiffness, implicit methods and nonlinear solves, adaptive stepsize control, and linear multistep methods. Each stage below names the concrete derivations, experiments and plots you must produce, together with (optional) examples you can use to test your work. These stages mirror the material developed in class so that, when completed in order, your report will naturally accumulate the theory, algorithms, and evidence expected in this course. 

# Deliverables
1. LaTeX Report (Theoretical Derivations, Algorithms, Experiments, Validation)
2. Python Source Code
3. README, MIT License, .gitignore
4. Deadline: 10th December, 2025

# Capstone Integration
Integrate your components into a small solver toolkit that, given f(t, y), t_0, T, y_0, a method choice, and an error tolerance, will:
1. Run the method (explicit or implicit) optionally with adaptavity, and automatically generate: a stepsize history, error estimates, a final error report, workprecision data, and standard visualizations (time series, phase plots for 2D systems).
2. For linear systems y' = Ay, optionally report eigenvalues of A, and explain predicted stability vs. observed behavior.

This automation is not required, but it will make your report stronger and save you time during experimentation.


This course was taken in Fall 2025, instructed by Professor of Mathematics, Chenfanfu Jiang

For any issues, please contact aryandalal@ucla.edu (aryandalal [at] ucla [dot] edu).

