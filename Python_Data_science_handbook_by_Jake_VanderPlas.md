- [book link](https://jakevdp.github.io/PythonDataScienceHandbook/index.html)

I reccommend that you go over the jupyter notebooks / colab and play beyond.

Some questions that you can answer while doing the work are on each chapter, [you can check the solutions here](Python_Data_science_handbook_by_Jake_VanderPlas_solutions)

# Ipython

Ipython is a wonderful way to write new code interactively.
I also usually have a text editor (VIM) and Ipython window open in paralell.

| Command           | Purpose                   |
| ----------------- | ------------------------- |
| run scriptName.py | run script                |
| ?                 | shows docstrings          |
| ??                | shows full code           |
| whos              | shows variables in memory |

# 2. Numpy

Numpy arrays provide you with C-like speed for numerical operations

- What is the average height for US presidents?

# 3. Pandas

The Pandas library provides efficient storage and manipulation of dense type arrays in python.

You can define a pandas dataframe as:

- from a dict
- specify the index

Questions:

- What is the average population in the US if we only consider the states of California, Texas, New York, Florida, Illinois?

# 4. Matplotlib

Matplotlib is a plotting library that was made as a Matlab alternative

you can use a nicer style with axis style

```
plt.style.use('seaborn-white')
plt.style.use('seaborn-whitegrid') # add grid by default
plt.axis('tight')
plt.axis('equal')
```

you can also plot error bars

`plt.errorbar(x, y, yerr=dy, fmt='.k');`

As well as 3D data in 2D plots using

`plt.contour`, `plt.contourf`, and `plt.imshow`

Seaborn makes some nicer plots that matplotlib

import seaborn as sns
sns.set()

# 5. Machine learning with Scikit-Learn

- supervised learning creates models of the data by fitting the data
- unsupervised learning is when you have no data labels
