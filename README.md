# Identifying non-monotonicity in Empirical Learning Curves using performance differences

This repository contains all the code to run experiments and generate plots for the *Prevalence of non-monotonicity in empirical learning curves* research project. This paper has been produced as part of the CSE3000 - Research Project course at Delft University of Technology, The Netherlands.

This research builds on top of the LCDB repository, which can be found [here](https://github.com/fmohr/lcdb).


**Author:** Dinu Gafton *(D.Gafton@student.tudelft.nl)*

### 1. Install dependencies
To install dependencies, run the following commands. Python 3.9 and Pip are required to run the experiments. 

**Note:** You need to be in the root of the repository as cd to run the commands.
```bash
pip install lcdb
pip install func-timeout
```


### 2. Running the Experiments
To run the experiments, first open the Jupyter Notebook file in any IDE of your choice (i.e PyCharm). Simply run the cells in the notebook to get the experimental results. If you encounter errors while importing modules, try to install the models through the IDE.

**Note:** Running experiment 3 requires access to the algorithm of Codrin Socol, found [here](https://github.com/CodrinSocol/cse3000-research-project). The results be replicated by re-running Experiment3.ipynb and comparing the output to the results of Codrin Socol, found in file "Socol_algorithm_results.csv". 