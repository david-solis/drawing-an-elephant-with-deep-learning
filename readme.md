# Drawing an Elephant with Deep Learning

Python notebook that solves [Carlos Ruiz's (Colegio de Matemáticas Bourbaki) challenge.](https://www.linkedin.com/pulse/sobrejuste-de-elefantes-%2525C3%2525A0-la-von-neumann-y-una-beca-carlos-ruiz--jhxgc/)

## Objective.
Using advanced mathematical modeling, construct and analyze a dataset to parameterize the curve from Mayer et al.'s paper ([Drawing an elephant with four complex parameters.](https://pubs.aip.org/aapt/ajp/article-abstract/78/6/648/1042069/Drawing-an-elephant-with-four-complex-parameters))

## Specification

### Dataset
Create a dataset comprising at least 1,000 records.
#### Explanatory Variable
Include one explanatory variable, denoted as t, which ranges from 0 to 2 * pi.
#### Dependent Variables

Incorporate two dependent variables labeled as x and y using the following functions:

* x = -60 *cos(t) - 30 *sin(t) + 8 *sin(2t) - 10 *sin(3t)
* y = -50*sin(t) - 18 *sin(2t) - 12*cos(3t) + 14 *cos(5t)

#### Data Modification
Introduce random noise to the dependent variables x and y. This noise should not follow a predictable pattern and should vary randomly across the dataset.

#### Model Development
Develop a model that fits the dataset and accurately parameterizes the curve defined by the functions for x and y. You may choose from neural networks, kernel functions, Gaussian regression, or any other suitable mathematical model.


