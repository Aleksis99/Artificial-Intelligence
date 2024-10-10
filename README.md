# Artificial Intelligence 
## Repository with examples for the "Artificial Intelligence" course given by me @ Faculty of Mathematics and Informatics, Sofia University

## Exercises' Topics

- Problem Solving and Search
    - Uninformed _(Blind)_ Search
    - Informed _(Heuristic)_ Search
    - Constraint Satisfaction Problems
    - Genetic Algorithms
    - Games
- Machine Learning
    - _k_ - Nearest Neighbors
    - Naïve Bayes Classifier
    - Decision Tree
    - _k_ Means
    - Neural Networks

## Environment

The course python version is 12.
In the requirements.txt file you will find all the necessary libraries to run the notebooks.
You can install them with pip.

      pip install requirements.txt

[Conda](https://docs.conda.io/projects/conda/en/latest/index.html#) is recommended for managing you environment. 

1. To create an environment:
    ```
      conda create --name <my-env> python=3.12
    ```
   Replace ``<my-env>`` with the name of your environment.

2. When conda asks you to proceed, type ``y``:

      ``proceed ([y]/n)?``

   This creates the myenv environment in ``/envs/``. No
   packages will be installed in this environment.

3. Then you need to activate your environment :
    ```
      conda activate <my-env>
    ```
4. Then you can install the necessary libraries :
    ```
      pip install -r requirements.txt
    ```
