# Titanic

The titanic challenge and the associated dataset is a famed one, often the first step for beginners into machine learning.
Check out the challenge [here](https://www.kaggle.com/c/titanic/overview).

The contemporary solutions use steps like dropping missing values, encoding categorical variables, feature engineering, transforming the values and using various classification models like Logistic regression, SVC all the way to Gradient Boosting Machines. While the aptness of each method varies from a case by case basis, the models can be made pretty accurate by tuning their hyperparameters and careful feature engineering.
Contrasted to this, a Genetic Model is not exactly a machine learning algorithm, but a "machine-crunching" algorithm. Think of the usual ML models as intelligent students who know what to study and from where, while the Genetic algorithm is an hard-working student, who goes through all available textbooks and then selects the one that gives him the score closest to the correct and then repeats this for all questions. The drawback here is that while effective, calling it efficient would be a stretch both from the coding perspective as well the machine's resource perspective.
Read [this](https://medium.com/analytics-vidhya/understanding-genetic-algorithms-in-the-artificial-intelligence-spectrum-7021b7cc25e7) to know more about the Genetic algorithms

![image](https://user-images.githubusercontent.com/58383734/80512533-417f0100-899b-11ea-9b54-9b48578bd8ee.png)

(PS: Setting up the genetic function is an extremely frustrating and detail oriented activity, and it leaves you with a whacky looking piece of code too. But if that grinds your gears, then by all means go ahead)
## Prerequisities
 - ***titanic_train.csv*** - Training dataset. This file contains the survival state or the "ground truth".
 - ***titanic_test.csv*** - Test dataset. We make predictions on this dataset.

### Libraries
Since this was a Jupyter notebook implemetation, no libraries need to be installed, other than the pre-installed ones:  
 - *numpy*  
 - *pandas*
 - *sys*  
 - *sklearn*
 - *matplotlib.pyplot*
 - *sympy*

License
------
Apache 2.0 
