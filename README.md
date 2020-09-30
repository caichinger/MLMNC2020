# Welcome to "Machine Learning and the MNC"!

This repository comprises lecuture notes and exercises
devised for the course [Machine Learning and the MNC](https://learn.wu.ac.at/vvz/20w/1897).

The material for each session resides in a separate folder.


## Important Links

- [Directory of Classes](http://vvz.wu.ac.at/cgi-bin/vvz.pl?C=L;I=1897;LV=3;L2=S;L3=S;U=H;S=20W;LANG=DE)
- [Syllabus](https://learn.wu.ac.at/vvz/20w/1897)
- https://short.wu.ac.at/MLMNC (points to this repository)


## Sessions

...


## Reference Literature

The reference literature

- [Hands-On Machine Learning with Scikit-Learn & Tensorflow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)
  - [Notebooks 1st edition](https://github.com/ageron/handson-ml/)
  - [Notebooks 2nd edition](https://github.com/ageron/handson-ml2)
- [Introduction to Statistical Learning](http://faculty.marshall.usc.edu/gareth-james/ISL/)

is available as hard copy versions in the library (or online).


## Technical Setup and Ressources

As a workshop style course, a computing environment is needed.
Through it, you will gain hands on experience in working with data and
applying Machine Learning methods to real world data sets.
Throughout the course, the [Python](https://www.python.org/) programming
language and its rich Data Science and Machine Learning ecosystem will be used.

In the following, the technical setup is described.
It is highly advised to have established a properly functioning working
environment prior to the course. Should you experience problems with the
setup, feel free to contact Claus.

You will be given access to the (interactive) course notes and be able
to experiment with the material presented and obtain a practical
understanding of theoretical principles. Furthermore, small homework
exercises will be given from the first lecture on to gain “class
participation” points and help prepare for the group project.


### Recommended Remote/Cloud Setup (using Google Colaboratory)

[Google Colaboratory](https://colab.research.google.com/) is a free to use
cloud computing platform for machine learning education and research.
It is a [Jupyter](https://jupyter.org/) notebook environment that requires
no setup to use. In addition, documents can be edited in a collaborative
fashion (like Google Docs).

This setup is recommended for everyone with no prior experience
in setting up programming environments and as a fallback solution
in case you experience any problems.

1. Create a Google (for example Gmail) if you do not already have one.
1. Go to https://colab.research.google.com and familiarize yourself
   with the environment.
   Go through the “Introduction Colaboratory” and “Getting Started”
   sections provided by Colaboratoy.
1. To import a notebook from this repository, go to the menue bar
  1. `File`
  1. `Open notebook...`
  1. `GITHUB`, enter https://github.com/caichinger/MLMNC2020
  1. Select the notebook you want to run


### Local

As local computing environment, the [Anaconda](https://www.anaconda.com/)
Python distribution can be used. In doing so, we will (as in above setup)
use a Jupyter notebook environment.

If you chose to use this setup, you need to:

1. [Download]https://www.anaconda.com/distribution/#download-section) the appropriate Python 3.8 distribution for your operating system.
2. Go through the [Getting Started](https://docs.anaconda.com/anaconda/user-guide/getting-started/) guide and in particular arrive at the section [Run Python in a Jupyter Notebook](https://docs.anaconda.com/anaconda/user-guide/getting-started/#run-python-in-a-jupyter-notebook)
Take a look at the Google Colaboratory notes on mentioned above.

This setup is recommended for those who prefer a local configuration and who wish to experiment further.

```bash
$ git clone https://github.com/caichinger/MLMNC2020.git
$ cd MLMNC2020
$ conda env create -f env.yml
$ conda activate mlmnc
$ jupyter lab
```
