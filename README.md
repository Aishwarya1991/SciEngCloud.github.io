# github.io# CloudBook ExamplesThis contains the code samples and demos for the book "Cloud Computing for Science and Engineering".   Most of these samples are Jupyter Notebooks.   If you do not have a copy of Jupyter you should download and install anaconda from Continuum Analytics [https://www.continuum.io/downloads](https://www.continuum.io/downloads ).  Another way to run Jupyter is to install Docker and run the jupyter/scipy-notebook container as followsdocker run -d -p 8888:8888 -e PASSWORD="yourword" -e USE_HTTPS=yes jupyter/scipy-notebookthen go to https://localhost:8888 or, if you started this on a remote host use the ip address of the remote host. ##chapter 6this directory contains the Dockerfile and Python source and data files for the  tiny  web server container demo.