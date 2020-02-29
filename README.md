# Cookiecutter Data Science & Docker

_Simplified version of [Cookiecutter Data Science](http://drivendata.github.io/cookiecutter-data-science/) that includes [Docker Jupyter Image](https://hub.docker.com/u/jupyter/)._



### Requirements to use the cookiecutter template:
-----------
 - Python 3.7
 - Docker
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

### To start a new project, run:
------------

    cookiecutter https://github.com/kikejimenez/cookiecutter-docker-data-science

### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
├── MIT LICENSE
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
├── presentation       <- Presentation slides
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, 
│
└── src                <- Source code for use in this project.
    ├── __init__.py    <- Makes src a Python module
 ```

### To start Jupyter Lab:
-----------
- Enter command 'docker-compose up'

### Credits
------------

[Enrique Jimenez](https://github.com/kikejimenez)
