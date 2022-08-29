# FDAP Student Resources

This repository has material that supplements what is posted on the Babson FIN 6200 Canvas page. It exists mainly to provide publicly accessible URLs for shared data files (in `/data/`) and template notebook files (in `/templates/`), a course schedule, and links to external resources.

- [Syllabus](syllabus/fin6200syllabus.pdf)
- [Course schedule](schedule)
- [Teaser/welcome video](https://youtu.be/eIX4FKDDkbI)
- [Data files](data)
- [Template notebooks](templates)

## Python

### Installation
Python notebooks can run in the cloud using [Google Colab](https://colab.research.google.com) or [Binder](https://mybinder.org), but you will probably want a local installation. I strongly recommend using the [Anaconda](https://www.anaconda.com/products/individual) Python distribution.

Anaconda includes (almost) everything you need to get going, but in line with [these recommendations](https://aeturrell.github.io/coding-for-economists/code-preliminaries.html#installing-an-integrated-development-environment-ide), I prefer to work in [Visual Studio Code](https://code.visualstudio.com) with some add-in extensions.
- [My video demo: Installing Anaconda and Visual Studio Code for Python notebooks](https://www.youtube.com/watch?v=jY0o1nkW0ow)
- Arthur Turrell's [Python with Anaconda and VS Code installation instructions](https://aeturrell.github.io/coding-for-economists/code-preliminaries.html#installing-python)
- Microsoft [Jupyter Notebooks in VS Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks) (and [video](https://channel9.msdn.com/Shows/Visual-Studio-Toolbox/Getting-Started-with-Jupyter-Notebooks-in-VS-Code))

### Packages
These are the critical packages we will rely on; if you need a package not included with Anaconda, you should *first* try to install it using `conda install` and only if that doesn’t work, install using `pip`
- [pandas](https://pandas.pydata.org) (data analysis)
- [Pandas data reader](https://pydata.github.io/pandas-datareader/) (access to sources including Yahoo Finance and FRED)
- [Seaborn](https://seaborn.pydata.org) (data visualization) and an [overview of Python visualization tools](https://pbpython.com/visualization-tools-1.html)
- [NumPy](https://numpy.org) and [SciPy](https://www.scipy.org) (scientific computing)
- [WRDS](https://github.com/wharton/wrds) (access to the authoritative source of historical financial data)

Additional packages that may be useful include [Pandas profiling](https://github.com/pandas-profiling/pandas-profiling) (automated EDA), [Pyjanitor](https://pyjanitor.readthedocs.io) (data cleaning), and [dataprep](https://pypi.org/project/dataprep/) (data cleaning and automated EDA)

### Books
- [Think Python](https://greenteapress.com/wp/think-python-2e/) (2nd ed., and [repo](https://github.com/AllenDowney/ThinkPython2)), Allen B. Downey
- [Whirlwind Tour of Python](https://jakevdp.github.io/WhirlwindTourOfPython/) (and [repo](https://github.com/jakevdp/WhirlwindTourOfPython)), Jake VanderPlas
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) (and [repo](https://github.com/jakevdp/PythonDataScienceHandbook)), Jake VanderPlas
- [Python for Data Analysis](https://amzn.to/3joJQAa) (2nd ed.), Wes McKinney
- [Coding for Economists](https://aeturrell.github.io/coding-for-economists/), Arthur Turrell
- [Introduction to Python for Econometrics, Statistics and Data Analysis](https://www.kevinsheppard.com/teaching/python/notes/) (5th ed.), Kevin Sheppard

### Other References
- Datacamp cheatsheets: [Python basics](cheatsheets/pythonbasics.pdf), [pandas basics](cheatsheets/pandasbasics.pdf), [pandas advanced](cheatsheets/pandas.pdf), [Seaborn](cheatsheets/seaborn.pdf), [NumPy](cheatsheets/numpy.pdf), and [importing data](cheatsheets/importingdata.pdf)
- [Learn Python in Y Minutes](https://learnxinyminutes.com/docs/python/)
- [pandas User Guide](https://pandas.pydata.org/pandas-docs/stable/user_guide/)
- [Kaggle Welcome to Data Visualization](https://www.kaggle.com/residentmario/welcome-to-data-visualization) (uses Python, Pandas, and Seaborn)
- [How to read most commonly used file formats in Data Science (using Python)](https://www.analyticsvidhya.com/blog/2017/03/read-commonly-used-formats-using-python/)
- [Stata to Python equivalents](http://www.danielmsullivan.com/pages/tutorial_stata_to_python.html), Daniel M. Sullivan

## Statistics and Inference

[Introduction to Modern Statistics](https://openintro-ims.netlify.app/) (1st ed., and [repo](https://github.com/openintrostat/ims), [data repo](https://github.com/OpenIntroStat/openintro)), Mine Çetinkaya-Rundel and Johanna Hardin

## Financial Data
- [Bloomberg Anywhere](https://bba.bloomberg.com)
- [Open Source Asset Pricing](https://www.openassetpricing.com/data/)
- [Wharton Research Data Services (WRDS)](http://wrds.wharton.upenn.edu/)
  - Datasets [by concept](https://wrds-www.wharton.upenn.edu/pages/browse-data-concept/) and [by product](https://wrds-www.wharton.upenn.edu/users/products/)
  - [CRSP Methodologies](http://www.crsp.org/products/documentation/crsp-calculations)

### Microsoft Excel

[Data Analytics Using Microsoft Excel With Accounting and Finance Datasets](https://students.flatworldknowledge.com/course/2598350) (v.2.0), Joseph M. Manzo


## Financial Applications

Relevant resources TBA

## Other Tools

### Markdown
- [Commonmark Markdown Tutorial](https://commonmark.org/help/tutorial/)
- [Markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/)


# Acknowledgements
Course designed with significant advice/help/inspiration from [Don Bowen](https://bowen.finance), [Michael Goldstein](https://faculty.babson.edu/goldstein/), [Grant McDermott](https://grantmcdermott.com), [Cameron Pfiffer](https://cameron.pfiffer.org), [Seth Pruitt](https://sethpruitt.net/), and [Arthur Turrell](http://aeturrell.com)
