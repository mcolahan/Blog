---
layout: post
title: My Programming Background
date: 2018-4-5 14:40 +0500
description: My background in programming
img: code-blur-highlight.jpg
tags: [Blog, About, Data Science, Python]
author: Martin Colahan

---

My programming career started largely out of necessity when I could not easily do the calculations I needed in spreadsheets for my undergraduate chemical engineering assignments. Chemical engineering calculations often require iteration, a task where Excel is not well suited. As a result, I did much of those tasks trying to adapt Excel via VBA (Visual Basic for Applications) or with MATLAB which was readily available on the university's computers. 

Excel, VBA, and MATLAB suited me well until I needed a method of wrangling and plotting the laboratory data I was generating as a graduate student. I wanted a means of working on my research at home on my own computer, but purchasing a personal MATLAB license on a graduate student's budget was out of the question. When searching for an alternative, I found the Python programming language, which has a syntax like what I was used to in MATLAB and an exceptional plotting library with Matplotlib. That switch from MATLAB to Python came with a bit of a time cost as I needed to convert much of my previous code to Python, but I ultimately came out with a better, more organized codebase, especially when I discovered the wonders of the [Pandas](http://pandas.pydata.org) dataframe and the beauty of the [Jupyter Notebook](http://jupyter.org/).

<figure>
  <img src="{{site.url}}/assets/img/jupyterpreview.png" alt="Jupyter Notebook Example" class="rounded mx-auto d-block"/>
  <figcaption>Example Jupyter Notebook showing the ease in which code, images, mathematical equations, and text can be rendered to develop narrative driven documents. Image Source: <a href="http://jupyter.org/">jupyter.org</a></figcaption>
</figure>

Once I finished my Master's degree, I began to work as a research engineer in a new lab in Abu Dhabi. It was there that I really began to fully understand the power of Python in the research laboratory. As I had to churn out a lot of experimental data on top of my duties training and assisting graduate students in lab practices and their experiments, I had to develop a means of automating much of my data analysis. The data I had to wrangle consisted mostly of text files containing the data from my electrochemical measurements, so I wrote scripts to sort the data into a file system based upon the experimental conditions and the measurement type, perform calculations with [NumPy]( http://www.numpy.org/) and [SciPy](https://scipy.org/), and plot the data with [Matplotlib]( https://matplotlib.org/) to quickly summarize the results of each experiment. 

That system I developed certainly had its share of issues. For instance, to compare results across the experiments, I had to find the necessary text files in the file system and then extract the necessary data into a useable format (i.e., a pandas dataframe). It was certainly a bit of a hassle. In hindsight, I should have extracted the important data into a MySQL database from which I can run queries to access the data I need.

I am happy that I took the time to switch to Python and have since become a big proponent of the Python ecosystem. It is a fantastic language for engineers as it is easy to write and understand, incredibly versatile, and, most importantly for me, free. With it, I have written code for a variety of different applications from the control of peristaltic pumps to managing my own personal finances. If you are interested in learning more about how to learn python especially for research applications, then please feel free to leave me a message.

