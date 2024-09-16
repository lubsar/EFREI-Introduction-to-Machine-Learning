# Introduction to Machine Learning
## The course is held at FEI, VSB-TU Ostrava

Feel free to contact me (<radek.svoboda@vsb.cz> or office EA404, FEI) if you have any questions or want to discuss any topic from the course 😊

# 📊 Exercises
## Exercise 1
The aim of the exercise is to get an overview of the basic capabilities of the Pandas, Matplotlib and Seaborn libraries and be able to setup a Python Virtual Enviroment (`venv`)

> [Jupyter Notebook](https://github.com/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_01.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_01.ipynb)

## Exercise 2
The aim of the exercise is to learn basic techniques for visualization creation and interpretation using Matplotlib and Seaborn libraries.

> [Jupyter Notebook](https://github.com/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_02.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/EFREI-Introduction-to-Machine-Learning/blob/main/iml_02.ipynb)

# 💡 Notes
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