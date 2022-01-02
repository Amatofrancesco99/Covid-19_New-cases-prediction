<h1> Covid-19_New-cases-prediction</h1>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Amatofrancesco99/Covid-19_New-positives-prediction/blob/main/LICENSE)
![](https://komarev.com/ghpvc/?username=Covid-19New-cases-prediction&label=Views&style=plastic&color=brightgreen)

![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
<br>

<h4><em>“Numbers have an important story to tell. They rely on you to give them a voice.”</em>–Stephen Few</h4>

***

<h3>🇮🇹📈 Project description:</h3>

**[Covid-19](https://www.who.int/health-topics/coronavirus#tab=tab_1) fourth wave it's close** in Italy, but how we can know when the situation starts to be critical?
<br>
Since past events we know that the new cases growth is almost an exponential, when a wave starts, so we want to predict the future trend, with a **good model**, knowing what happened in previous days.
<br>
We also know that new cases, intensive care unit admissions and deaths are strictly correlated. When one increases, also the others are increasing in the same order of magnitde.
<br>
Building a good model is essential in order to **avoid** taking **bad decisions** (for example lockdown when not needed, or no restrictions when needed).
<br>
Obviously the prediction is really complicated, because a **lot of variables have to be take into account**.
<br>An example: the third vaccination may produce a decrease effect in future trend (especially deaths).
<br><br>
As you may understood by the previous lines, the aim of this project is finding a good model to predict future trend, using **statistical learning theory**.
<br>
The regression functions that have been used are the following one:
 *  *[Linear Regression](https://en.wikipedia.org/wiki/Linear_regression)*
 *  *[Polynomial Regression](https://en.wikipedia.org/wiki/Polynomial_regression)*
 *  *[Lasso Regression](https://en.wikipedia.org/wiki/Lasso_(statistics))*
 *  *[Ridge Regression](https://www.mygreatlearning.com/blog/what-is-ridge-regression/)*
 *  *[Natural Cubic Splines](https://towardsdatascience.com/numerical-interpolation-natural-cubic-spline-52c1157b98ac)*
 
***

<h3>💾👨🏻‍💻 Data origin </h3>

All data are public and provided by the [Dipartimento della Protezione Civile (DPC)](https://www.protezionecivile.gov.it/it/).
<br>
You can also find them at this [github link](https://github.com/pcm-dpc/COVID-19).

***

<h3> 🚀💻 Workplace configuration </h3>

Before downloading the [source code](https://github.com/Amatofrancesco99/Covid-19_New-positives-prediction/blob/main/Covid-19%20Italy%20trend.ipynb), you should enable the dark theme on your jupyter notebook, in order to see graphs and other items in a proper way.
<br>
So you have to run the following lines of code in your terminal/command prompt:
```
pip install jupyterthemes
jt -t chesterish
```

Finally, you have to run the following code snippet, in order to get all the libraries that have been used in the project:
```
pip install DateTime
pip install ipywidgets
pip install python-math
pip install matplotlib
pip install numpy
pip install pandas
pip install patsy
pip install -U scikit-learn
```

***

<h3>📚🤔 Deepening:</h3>

Are you interested about this argument? 
 * Read this beautiful book: [The Elements of Statistical Learning](https://web.stanford.edu/~hastie/Papers/ESLII.pdf).
 * You can also see another project: [Gas consumption prediction](https://github.com/Amatofrancesco99/Gas_consumption-prediction)
