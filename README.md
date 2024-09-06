# Introduction to Machine Learning
## The course is held at FEI, VSB-TU Ostrava

Feel free to contact me (<radek.svoboda@vsb.cz>) if you have any questions or want to discuss any topic from the course 😊

# 📊 Exercises
## Exercise 1
The aim of the exercise is to get an overview of the basic capabilities of the Pandas, Matplotlib and Seaborn libraries and be able to setup a Python Virtual Enviroment (`venv`)

> [Jupyter Notebook](https://github.com/rasvob/EFREI-Introduction-to-Machine-Learning/blob/master/iml_01.ipynb)

> [Google Colab](https://colab.research.google.com/github/rasvob/EFREI-Introduction-to-Machine-Learning/blob/master/iml_01.ipynb)

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