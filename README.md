# Variable Selection for Branching in Mixed Integer Linear Programming (MILP)
We implemented variable selection for branching in MILP as the machine learning course project. The project was based on the paper titled "Learning to Branch in Mixed Integer Programming" by Khalil et al. (2016).

## Getting Started
The implementation uses Python 2.7 along with CPLEX 12.8.

### Prerequisites
* Python 2.7
* CPLEX 12.8
	* Please follow the instructions [here](https://www.ibm.com/support/knowledgecenter/en/SSSA5P_12.6.2/ilog.odms.studio.help/Optimization_Studio/topics/COS_installing.html)
* Install Python API for CPLEX 12.8
	* The Python API for CPLEX need to be installed separately. Instructions can be found [here](https://www.ibm.com/support/knowledgecenter/SSSA5P_12.8.0/ilog.odms.cplex.help/CPLEX/GettingStarted/topics/set_up/Python_setup.html)

### Dependencies
* Pytorch 0.4.1
* SciPy 1.1.0
* Scikit Learn 0.20.1

## How to run
```
python main.py
```

## Authors
* Ravi Agrawal
* Young Shin Oh
* Christopher Abraham

## References
* Elias B. Khalil, Pierre Le Bodic, Le Song, George Nemhauser, and Bistra Dilkina. 2016. Learning to branch in Mixed Integer Programming. In Proceedings of the Thirtieth AAAI Conference on Artificial Intelligence (AAAI'16). AAAI Press 724-731.
* Graph Convolutional Networks (https://github.com/tkipf/pygcn)
* SVM Rank (https://gist.github.com/agramfort/2071994)