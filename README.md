# Introduction to Machine Learning
## The course is held at FEI, VSB-TU Ostrava

Feel free to contact me (<radek.svoboda@vsb.cz> or office EA404, FEI) if you have any questions or want to discuss any topic from the course 😊

# 📌 Data Classification Project Information
* You can get up to **30** points
* Project are done in **groups of 3** students
* 💡 [Click here](https://github.com/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/cls_project.md) for the details

# 📌 Important news
* In the lecture on the **30th October** there will be a **exam** and **project** will be assigned
* Exam will take **45 - 60 minutes** and it is a written exam (paper, no internet)

The skills to be assessed:
* Ability to differentiate between supervised and unsupervised learning based on examples of scenarios
* Ability to apply linear regression to predict outcomes, analyze and assess model performance
* Ability to apply KMeans clustering on a dataset and determine the optimal number of clusters
* Ability to interpret and present the clustering result
* Ability to implement KNN on a dataset considering appropriate parameters (e.g., k)

* 💡 We will go through some [examples](https://github.com/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/misc/example_exam.pdf) of such tasks in the next lecture 😊

# 📊 Exercises
## Exercise 1
The aim of the exercise is to get an overview of the basic capabilities of the Pandas, Matplotlib and Seaborn libraries and be able to setup a Python Virtual Enviroment (`venv`)

> [Jupyter Notebook](https://github.com/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_01.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_01.ipynb)

## Exercise 2
The aim of the exercise is to learn basic techniques for visualization creation and interpretation using Matplotlib and Seaborn libraries.

> [Jupyter Notebook](https://github.com/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_02.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_02.ipynb)

### More advanced concepts like subplots or correlation matrices can be found in Jupyter notebook below

> [Jupyter Notebook](https://github.com/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_02_advanced.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_02_advanced.ipynb)

## Exercise 3
The aim of the exercise is to learn how to use distance metrics and k-NN classifier.

> [Jupyter Notebook](https://github.com/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_03.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_03.ipynb)

## Exercise 4
Goal of the excercise is to learn how to use Scikit-learn library for a regression tasks employing various linear regression models and moreover evaluate the performance of the proposed models.

> [Jupyter Notebook](https://github.com/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_04.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_04.ipynb)

## Exercise 5
Goal of the excercise is to learn how to use K-means implementation in the Scikit-learn library to perform clustering and subsequent cluster analysis on a Titanic dataset.

> [Jupyter Notebook](https://github.com/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_05.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_05.ipynb)

## Exercise 6
We will learn how to use another clustering algorithm - Hierarchical (or Agglomerative) clustering. 

> [Jupyter Notebook](https://github.com/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_06.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_06.ipynb)

# 💡 Notes
## Cheat sheet for Pandas and Matplotlib/Seaborn

> [Jupyter Notebook](https://github.com/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_cheat_sheet.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_cheat_sheet.ipynb)



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