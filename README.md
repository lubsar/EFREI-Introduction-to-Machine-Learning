# Introduction to Machine Learning
## The course is held at FEI, VSB-TU Ostrava 

Original course material by [Radek Svoboda](https://github.com/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_01.ipynb).

# 📊 Exercises
## Exercise 1
The aim of the exercise is to get an overview of the basic capabilities of the Pandas, Matplotlib and Seaborn libraries and be able to setup a Python Virtual Enviroment (`venv`)

> [Jupyter Notebook](https://github.com/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_01.ipynb)

> [Google Colab](https://colab.research.google.com/github/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_01.ipynb)

## Exercise 2
The aim of the exercise is to learn basic techniques for visualization creation and interpretation using Matplotlib and Seaborn libraries.

> [Jupyter Notebook](https://github.com/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_02.ipynb)

> [Google Colab](https://colab.research.google.com/github/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_02.ipynb)


## Exercise 3
The aim of the exercise is to learn how to use distance metrics and k-NN classifier.

> [Jupyter Notebook](https://github.com/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_03.ipynb)

> [Google Colab](https://colab.research.google.com/github/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_03.ipynb)

## Exercise 4
Goal of the excercise is to learn how to use Scikit-learn library for a regression tasks employing various linear regression models and moreover evaluate the performance of the proposed models.

> [Jupyter Notebook](https://github.com/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_04.ipynb)

> [Google Colab](https://colab.research.google.com/github/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_04.ipynb)

## Exercise 5
Goal of the excercise is to learn how to use K-means implementation in the Scikit-learn library to perform clustering and subsequent cluster analysis on a Titanic dataset.

> [Jupyter Notebook](https://github.com/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_05.ipynb)

> [Google Colab](https://colab.research.google.com/github/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_05.ipynb)

## Exercise 6
We will learn how to use another clustering algorithm - Hierarchical (or Agglomerative) clustering. 

> [Jupyter Notebook](https://github.com/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_06.ipynb)

> [Google Colab](https://colab.research.google.com/github/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_06.ipynb)

## Exercise 7
Goal of the excercise is to code selected part of the Decision tree algorithm which is focused on the optimum split part using gini index. 

After that the scikit-learn implementation of the Decision tree basic usage will be demonstrated.

> [Jupyter Notebook](https://github.com/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_07.ipynb)

> [Google Colab](https://colab.research.google.com/github/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_07.ipynb)

## Exercise 8
Goal of the excercise is to learn how to use Scikit-learn library for a classification tasks and evaluate the performance of the proposed models.

> [Jupyter Notebook](https://github.com/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_08.ipynb)

> [Google Colab](https://colab.research.google.com/github/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_08.ipynb)

## Exercise 9
Goal of the excercise is to learn how to use basic deep learning models in Scikit-learn and Keras.

> [Jupyter Notebook](https://github.com/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_09.ipynb)

> [Google Colab](https://colab.research.google.com/github/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_09.ipynb)

## Exercise 10
Goal of the excercise is to learn how to save trained models and use selected advanced libraries like Plotly or Optuna and we will also do a refresh of classfication and regression tasks.

> [Jupyter Notebook - Regression](https://github.com/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_10_regression.ipynb)

> [Google Colab - Regression](https://colab.research.google.com/github/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_10_regression.ipynb)

> [Jupyter Notebook - Classisication](https://github.com/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_10_classisication.ipynb)

> [Google Colab - Classisication](https://colab.research.google.com/github/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_10_classisication.ipynb)

> [Jupyter Notebook](https://github.com/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_10.ipynb)

> [Google Colab](https://colab.research.google.com/github/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_10.ipynb)

# 💡 Notes
## Cheat sheet for Pandas and Matplotlib/Seaborn

> [Jupyter Notebook](https://github.com/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_cheat_sheet.ipynb)

> [Google Colab](https://colab.research.google.com/github/lubsar/EFREI-Introduction-to-Machine-Learning/blob/main/iml_cheat_sheet.ipynb)


## How to create a Python Virtual Enviroment named `venv`
### Create `venv`
```
python -m venv venv
```

### Activate `venv`

* Activate `venv` in **Windows**
```
.\venv\Scripts\Activate.ps1
```

* Activate `venv` in **Linux**
```
source venv/bin/activate
```


### Intall python packages

```
pip install jupyter "jupyterlab>=3" "ipywidgets>=7.6"
pip install pandas matplotlib requests seaborn scipy scikit-learn
```

### 🚀 Run Jupyter lab

```
jupyter lab
```