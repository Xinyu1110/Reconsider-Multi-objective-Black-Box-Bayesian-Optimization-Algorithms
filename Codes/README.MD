# Reconsider Multi-objective Black Box Bayesian Optimization Algorithms

This project briefly summarized some classical and cutting-edge
Multi-objective Black-box Bayesian optimization methods.
Then discussed the performance of MESMO, qNEHVI, qE-
HVI, ParEGO and random search algorithms on synthetic
and real-world multi-objective problems

bortorch_modified_2.ipynb contains the algorithms: qNEHVI, qEHVI, ParEGO and random search, which are completed based on Botorch Framework. (BoTorch: A Framework for Efficient Monte-Carlo Bayesian Optimization
@inproceedings{balandat2020botorch,
  title = {{BoTorch: A Framework for Efficient Monte-Carlo Bayesian Optimization}},
  author = {Balandat, Maximilian and Karrer, Brian and Jiang, Daniel R. and Daulton, Samuel and Letham, Benjamin and Wilson, Andrew Gordon and Bakshy, Eytan},
  booktitle = {Advances in Neural Information Processing Systems 33},
  year = 2020,
  url = {http://arxiv.org/abs/1910.06403}
})


MESMO.ipynb is code of MESMO methods. (https://github.com/belakaria/MESMO)

MultiObjectives_version2.ipynb is code source for diverse test functions.

PlotResults2.ipynb is utlized to plot the results shown in report.

Main-mcmccour02.ipynb is a sample main for runing the different algorithms to save the checkpoints of Pareto Fronts and Hypervolume Improvement. The results are saved in corresponding folders. 
