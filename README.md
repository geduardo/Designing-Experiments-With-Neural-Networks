# Designing-Experiments-With-Neural-Networks

This is the repository for the project of my Master Thesis at ETH Zürich.

## Contents

- In `modules/` you can find the `*.py` files that contains the source code
for the different environments, the Experimenter agents, and the Analyzers. 
  **(Ongoing)**
- In `report/` you can find the LaTeX files and the figures of the report, as
well as the PDF of the thesis.   **(Ongoing)**

- In `figures/` you can find all the figures used in this project.

- In the rest of the folders you can find each of the individual experiments 
to test the architecture. They contain a Python Jupyter Notebook with the
orchestration and the files generated from a run of all cells.   **(Ongoing)**

  - **Pendulum**: simplest architecture possible, good to geta feeling the basic
  functioning principle of the architecture.
  - **Multi-Armed bandit**: abstract generalization of the pendulum example to 
  an arbitrary number of actions and arbitrary relation.
  - **Spring Bullet**: similar structure than pendulum, but with several
  inputs to the Analyzer.
  - **Two Sensors (Simple)**: a more complex experiment where the experimenter
  needs to develop a dynamical strategy for the experiment.
  - **Two Sensors (Double)**: same environment but with a more sophisticated
  experimenter to improve performance.
  - **Two Sensors (Simple)**: a more complex experiment where the experimenter
  needs to develop a dynamical strategy for the experiment.
  - **Two Sensors (Continuous)**: variation of Two Sensors in which the space
  of actions is continuous. This experiment is a toy example to try different
  parameter based RL agents like Actor-Critic.

## TODO

- [ ] Fix paths for modules and inserted images in the notebooks
- [ ] Organize and label correctly the `*.csv` files.
- [ ] Add link to the Online Documentation when ready.
- [ ] Add description to Pendulum notebook.
- [ ] Refactor Multiarm Bandit notebook to a clean version.
- [ ] Upload notebook for Spring-Bullet.
- [ ] Finish notebook for the Continous version and add Actor-Critic agents to the module.
- [ ] Add all agents and environments to the modules and more analyzers
- [ ] Review code to adapt to the oficial styleguide and correct for errors.

## TODO (Thesis Report)

- [ ] Trancribe the handwritten notes of Machine Learning and Reinforcement Learning to LaTeX.
- [ ] Transcribe all notebooks to LaTeX.
- [ ] Finish Minimal model for science (Unlikely) or add a section explaining the Scientific Method less abstractly. 
- [ ] Review Theory section and refactor.
- [ ] Write Conclusion section and for further work.
- [ ] Review, abstract, preface and add Thesis structure.
- [ ] Add more experiments if there's time.
