# Group4AMLProject
This project aims to replicate the experiments carried out in "Mohr, Felix, and Jan N. van Rijn. "Towards Model Selection using Learning Curve Cross-Validation." 8th ICML Workshop on Automated Machine Learning (AutoML). 2021." using the learning curve models and the predictive termination criterion described in "Domhan, Tobias, Jost Tobias Springenberg, and Frank Hutter. "Speeding up automatic hyperparameter optimization of deep neural networks by extrapolation of learning curves." Twenty-fourth international joint conference on artificial intelligence. 2015."

In order to do this, we used the code from https://github.com/automl/pylearningcurvepredictor and changed it to be compatible with Python 3, machine learning models from Sklearn, and OpenML datasets.

To run the experiments it is sufficient to run all the cells of PTC.ipynb.

Note that a single run takes a considerable amount of time due to the non-parallelizable learners of Sklearn and the original code by Domhan was originally intended for deep neural networks only!
