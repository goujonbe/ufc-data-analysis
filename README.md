# UFC data analysis

![UFC Logo](https://upload.wikimedia.org/wikipedia/commons/0/0d/UFC_logo.svg)

## Introduction

The [UFC](https://en.wikipedia.org/wiki/Ultimate_Fighting_Championship) is the largest MMA organization in the world. The roster of high-level fighters is awesome. [Conor McGregor](http://www.ufc.com/fighter/Conor-McGregor), [Ronda Rousey](https://www.ufc.com/fighter/Ronda-Rousey) and [Georges Saint-Pierre](https://www.ufc.com/fighter/Georges-St-Pierre) are known around the world. At a first glance, it may seem very brutal but mixed martial arts are extremely technical and strategical.

Conor McGregor | Ronda Rousey | Georges Saint-Pierre 
--------------- | -------------- | ---------------------
![Conor McGregor](http://imagec.ufc.com/http%253A%252F%252Fmedia.ufc.tv%252Fgenerated_images_sorted%252FFighter%252FConor-McGregor%252FConor-McGregor_302601_medium_thumbnail.jpg?mw300-mh300-tc1) | ![Ronda Rousey](http://imagec.ufc.com/http%253A%252F%252Fmedia.ufc.tv%252Fgenerated_images_sorted%252FFighter%252FRonda-Rousey%252FRonda-Rousey_241883_medium_thumbnail.jpg?mw300-mh300-tc1) | ![George Saint-Pierre](http://imagec.ufc.com/http%253A%252F%252Fmedia.ufc.tv%252Fgenerated_images_sorted%252FFighter%252FGeorges-St-Pierre%252FGeorges-St-Pierre_318_medium_thumbnail.jpg?mw300-mh300-tc1)

As in many sports, data is essential. It is primordial for fighters of course but for many others too: journalists/analysts, gamblers, and fans.

I fought this topic was interesting because there was no data set at the time I began this project.

So, it was an end-to-end data science project from data acquisition to result communication through data wrangling and of course data analysis.

## Repo architecture

The notebooks directory contains documented python code and conclusions from the analysis in the form of Jupyter notebooks.

The data directory contains the data sets used for this project.

## Get the data

Prior to that analysis there were no data set available, so I built my own using the [UFC public data API](http://ufc-data-api.ufc.com/). Thanks to that RESTful API, I could have data on fighters, events and even UFC news. 

## Results

I invite you to read the notebooks in the [notebooks directory](https://github.com/goujonbe/ufc-data-analysis/tree/master/notebooks), espescially the notebook called "data analysis". You will find some insights on the evolution of mixed martial arts, information about legends of this sport and a bit of history for those who are curious.

## How to access this work?

If you want to run it, you can clone the repository but you may have some troubles with the python version I used and the different libraries I chose. So I would recommend to simply visualize the results with the notebook viewer available [here](http://jupyter.org/) or to load it into colab, the new tool from Google that allows you to run notebooks directly in the cloud.

## Setup

For this project, I used [Anaconda](https://www.anaconda.com/), a popular data science platform for Python. I espescially used conda as a package manager.

Python version: **3.6.6**

I am a huge fan of **jupyter notebooks** and I tried the new environment **Jupyter lab**. More details about jupyter lab [here](https://blog.jupyter.org/jupyterlab-is-ready-for-users-5a6f039b8906).

Modules used and versions (most of them were installed by default):

Name | Version
---- | --------
appnope                   |0.1.0            
asn1crypto                |0.24.0          
backcall                  |0.1.0            
blas                      |1.0             
bleach                    |2.1.3            
ca-certificates           |2018.03.07      
certifi                   |2018.4.16       
cffi                      |1.11.5          
chardet                   |3.0.4           
cryptography              |2.2.2           
cycler                    |0.10.0          
decorator                 |4.3.0            
entrypoints               |0.2.3            
freetype                  |2.8             
html5lib                  |1.0.1            
idna                      |2.7             
intel-openmp              |2018.0.3        
ipykernel                 |4.8.2            
ipython                   |6.4.0            
ipython_genutils          |0.2.0            
jedi                      |0.12.0           
jinja2                    |2.10             
jpeg                      |9c               
jsonschema                |2.6.0            
jupyter_client            |5.2.3            
jupyter_core              |4.4.0            
jupyterlab                |0.32.1           
jupyterlab_launcher       |0.10.5           
kiwisolver                |1.0.1             
libcxx                    |4.0.1             
libcxxabi                 |4.0.1             
libedit                   |3.1.20170329      
libffi                    |3.2.1             
libgfortran               |3.0.1             
libpng                    |1.6.34            
libsodium                 |1.0.16          
libtiff                   |4.0.9           
markupsafe                |1.0             
matplotlib                |2.2.2            
mistune                   |0.8.3           
mkl                       |2018.0.3         
mkl_fft                   |1.0.1            
mkl_random                |1.0.1            
nbconvert                 |5.3.1           
nbformat                  |4.4.0           
ncurses                   |6.1              
notebook                  |5.5.0           
numpy                     |1.14.5           
numpy-base                |1.14.5           
olefile                   |0.45.1          
openssl                   |1.0.2o           
pandas                    |0.23.1           
pandoc                    |2.2.1                
pandocfilters             |1.4.2                
parso                     |0.3.0                
pexpect                   |4.6.0                
pickleshare               |0.7.4                
pip                       |10.0.1           
prompt_toolkit            |1.0.15               
ptyprocess                |0.6.0                
pycparser                 |2.18             
pygments                  |2.2.0                
pyopenssl                 |18.0.0           
pyparsing                 |2.2.0            
pysocks                   |1.6.8            
python                    |3.6.6            
python-dateutil           |2.7.3                
pytz                      |2018.5           
pyzmq                     |17.0.0               
readline                  |7.0              
requests                  |2.19.1           
send2trash                |1.5.0                
setuptools                |39.2.0           
simplegeneric             |0.8.1                
six                       |1.11.0               
sqlite                    |3.24.0           
terminado                 |0.8.1             
testpath                  |0.3.1             
tk                        |8.6.7                
tornado                   |5.0.2    
traitlets                 |4.3.2    
urllib3                   |1.23                 
wcwidth                   |0.1.7    
webencodings              |0.5.1    
wheel                     |0.31.1               
xz                        |5.2.4                
zeromq                    |4.2.5    
zlib                      |1.2.11              

## What's next?

If you want to take my data set to analyze it yourself, you're free to go and I would be happy to see what you can do with it. As far as I'm concerned, I will come back to this project as soon as possible, there is still a lot of room for improvement! If you have any comment, please tell me!