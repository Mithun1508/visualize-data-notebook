 visualizing data in the notebook ✨  
 
 # Introduction to the JupyterLab and Jupyter Notebooks
This is a short introduction to two of the flagship tools created by the Jupyter Community.

# JupyterLab 🧪
JupyterLab is a next-generation web-based user interface for Project Jupyter. 
It enables you to work with documents and activities such as Jupyter notebooks, text editors, terminals, and custom components in a flexible, integrated, and extensible manner. It is the interface that you're looking at right now.

For an overview of the JupyterLab interface, see the JupyterLab Welcome Tour on this page, by going to Help -> Welcome Tour and following the prompts.

See Also: For a more in-depth tour of JupyterLab with a full environment that runs in the cloud, see the JupyterLab introduction on Binder.

# Jupyter Notebooks 📓
Jupyter Notebooks are a community standard for communicating and performing interactive computing. They are a document that blends computations, outputs, explanatory text, mathematics, images, and rich media representations of objects.

JupyterLab is one interface used to create and interact with Jupyter Notebooks.

For an overview of Jupyter Notebooks, see the JupyterLab Welcome Tour on this page, by going to Help -> Notebook Tour and following the prompts.

# An example: visualizing data in the notebook ✨
Below is an example of a code cell. We'll visualize some simple data using two popular packages in Python. We'll use NumPy to create some random data, and Matplotlib to visualize it.

Note how the code and the results of running the code are bundled together.

from matplotlib import pyplot as plt

import numpy as np

# Generate 100 random data points along 3 dimensions
x, y, scale = np.random.randn(3, 100)

fig, ax = plt.subplots()

# Map each onto a scatterplot we'll create with Matplotlib
ax.scatter(x=x, y=y, c=scale, s=np.abs(scale)*500)

ax.set(title="Some random data, created with JupyterLab!")

plt.show()
 
 
# Next steps 🏃
This is just a short introduction to JupyterLab and Jupyter Notebooks. See below for some more ways to interact with tools in the Jupyter ecosystem, and its community.

# Other notebooks in this demo
Here are some other notebooks in this demo. Each of the items below corresponds to a file or folder in the file browser to the left.

Lorenz.ipynb uses Python to demonstrate interactive visualizations and computations around the Lorenz system. It shows off basic Python functionality, including more visualizations, data structures, and scientific computing libraries.
sqlite.ipynb demonstrates how an in-browser sqlite kernel to run your own SQL commands from the notebook. It uses the jupyterlite/xeus-sqlite-kernel.

![Screenshot (88)](https://user-images.githubusercontent.com/93249038/215325295-7d7f5b52-b8a6-44b2-993f-3580d7822c9c.png)
