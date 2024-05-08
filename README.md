### Supervised Machine Learning Project

The project uses NBA (National Basetball Association) regular season statistics (source: https://www.basketball-reference.com/) consisting of player performances during their rookie season. The datasets of rookie statistics includes of rookies during the years 2009-2019 and consists of the following statistics: age, the number of games played, field goal percentage, three-point percentage, free throw percentage, minutes per game, points per game, total rebounds per game, and assists per game. The goal of the project is determining which NBA players, using their rookie statistics, will become future NBA Stars, which by my definition is a player that has been selected to at least one All-Star and All-NBA team. The project consists of Perceptron, Stochastic Gradient Descent, and Random Forest Classifer classification models that uses supervise learning with high accuracy to predict which NBA rookies will become future NBA stars. Also, the project desires to predict NBA players that will become only NBA All-Stars. Since NBA All-Stars are still great players, despite not making an All-NBA team, it is important to predict such players. In addition, the project tries to find various statistical trends occur for NBA Stars and All-Stars through correlation matrices and scatterplots. To search for the most important indicators in predicting future NBA Stars/All-Stars, the project contains feature graphs to identify such indicators.

## Getting Started

### Prerequisites

This program requires [Jupyter Notebook](https://docs.jupyter.org/en/latest/install/notebook-classic.html) to run it.

### Installing

Enter a directory and clone this repo:

```
git clone https://github.com/daviddang415/Supervised_Machine_Learning_Project.git
```

### Running the application

Execute all cells using Jupyter Notebook's client interface

## Built With

* [Basketball-Reference](https://www.basketball-reference.com/) - Obtain basketball player statistics of their rookie season
* [Scikit-learn](https://scikit-learn.org/0.21/documentation.html) - Create statisical graphs and acccess machine learning models
* [Numpy](https://numpy.org/doc/stable/) - Utilize multi-dimensional arrays
