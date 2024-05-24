# Designing-Experiments-With-Neural-Networks

This is the repository for the project of my Master Thesis at ETH Zürich.

## Contents

- In `modules/` you can find the `*.py` files that contains the source code
for the different environments, the Experimenter agents, and the Analyzers. 
- In `report/` you can find the LaTeX files and the figures of the report, as
well as the PDF of the thesis.
- In `figures/` you can find all the figures used in this project.

- In the rest of the folders you can find each of the individual experiments 
to test the architecture. They contain a Python Jupyter Notebook with the
orchestration and the files generated from a run of all cells.   **(Ongoing)**

  - **Pendulum**: simplest architecture possible, good to geta feeling the basic
  functioning principle of the architecture.
  - **Multi-Armed bandit**: abstract generalization of the pendulum example to 
  an arbitrary number of actions and arbitrary relation.
  - **Two Sensors (Simple)**: a more complex experiment where the experimenter
  needs to develop a dynamical strategy for the experiment.
  - **Two Sensors (Double)**: same environment but with a more sophisticated
  experimenter to improve performance.
  - **Two Sensors (Simple)**: a more complex experiment where the experimenter
  needs to develop a dynamical strategy for the experiment.
  - **Two Sensors (Continuous)**: variation of Two Sensors in which the space
  of actions is continuous. This experiment is a toy example to try different
  parameter based RL agents like Actor-Critic.



