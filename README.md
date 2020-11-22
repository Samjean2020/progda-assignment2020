# progda-assignment2020

                                                        Introduction

This assessment is about numpy.random package in Python. It is designed to present a less robotic approach of the module, using Python language routine and novel algorithms such as PCG64 on a Jupyter Notebook. 
Jupyter Notebook is a web application with properties to create and share manuscripts containing live scripts, equations, visualisations and narrative messages. Data cleaning and transformation, numerical simulation, statistical modeling, data visualisation, machine learning are some of its attributes (jupyter.org, 2020)

                                                        Tasks
	Explaining the overarching purpose of the package
	Explaining the use of the “Simple random data” and “Permutations functions
	Explaining the use and purpose of at least five “Distributions” functions
	Explaining the use of seeds in generating pseudorandom numbers

                                                        Prerequisites 
To perform the above tasks on a Jupyter notebook, the following Python modules are required:
	NumPy
	Matplotlib.pyplot
	Pandas
	Seaborn
The above libraries must be imported. NumPy stands for Numerical Python. It provides inclusive mathematical functions, random number generators, linear algebra, Fourier transforms, to name but a few (numpy.org). NumPy can be imported as: <import numpy as np>. Matplotlib.pyplot is an interface to matplotlib based on state. It offers MATLAB-based plotting method (matplotlib.org, 2020). Matplotlib.pyplot can be imported as: <import matplotlib.pyplot as plt>. Pandas  is an open source tool for data analysis and manipulation (pandas.pydata.org, 2020). Pandas can be imported as: <import pandas as pd>.  Seaborn is a data visualisation library based on matplotlib in Python. It offers a drawing attractive and informative statistical graphics interface (seaborn.pydata.org, 2020). Seaborn can be imported as: <import seaborn as sns>.  And naturally, you have Python and Jupyter. 

                                                      About the four tasks:
                                                    1.Explaining the overarching purpose of the package: 

This part provides a definition of the numpy.random package, its different structures including simple random data, permutations, distribution and Generators and an indicative example of each sub- function: numpy.random.rand (), numpy.random shuffle(),numpy.random.dirichlet (), and  numpy.random.RandomState.pareto ().

                                                    2.Explaining the use of the “Simple random data” and “Permutations functions:

•	Simple random data (): numpy.random.randint(), numpy.random.random-sample (), numpy.random.bytes(), and numpy.random.choice()
•	Permutations (): numpy.random.shuffle(), and numpy.random.permutation().

                                                    3.Explaining the use and purpose of at least five “Distributions” functions:

•	numpy.random.normal ()
•	numpy.random.uniform()
•	numpy.random.multivariate_normal()
•	numpy.random.laplace()
•	numpy.random.poisson ()
•	numpy.random.gamma( )

                                                    4. Explaining the use of seeds in generating pseudorandom numbers: 
 Three elements are covered in this part:
    
•	Random Sate and Generators: numpy.random.RandomState (); numpy.random.seed(); 
•	Bitgenerators and PCG64 Algorithm: numpy.random.default_rng()
•	How to seed with PCG 64 Algorithm:

	simple random data: 
. numpy.random.Generator.integers()
. numpy.random.Generator.random()
. numpy.random.Generator.choice() 
. numpy.random.Generator.bytes()

	permutation: 
. numpy.random.Generator.shuffle()
. numpy.random.Generator.permutation()

	distribution: 
. numpy.random.Generator.logseries()
. numpy.random.Generator.laplace()
. numpy.random.Generator.weibull()
. numpy.random.Generator.rayleigh()
. numpy.random.Generator. zipf()

References are included in the Jupyter Notebook. 






