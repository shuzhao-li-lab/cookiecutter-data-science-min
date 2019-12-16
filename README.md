# cookiecutter-data-science-min

_Minimal cookiecutter template for data science projects_

This is forked from https://github.com/drivendata/cookiecutter-data-science.
The rationales of the Cookiecutter Data Science project are well explained at http://drivendata.github.io/cookiecutter-data-science/.

However, not all projects involve writing a new software module. When the activity of a researcher is centered on data analysis using existing tools, a minimal project template may be more suitable. This is what this template is for. 

In these projects, all code should be in the Jupyter notebooks. If there's need for a new software module, the module should be its own software project and the data analysis project should import the said software module. 


### Requirements to use the cookiecutter template:
-----------
 - Python 2.7 or 3.5
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```


### To start a new project, run:
------------

    cookiecutter https://github.com/shuzhao-li/cookiecutter-data-science-min

cookiecutter will ask four questions:
    project_name [project_name]: 
    repo_name [project_name]: 
    author_name [Your name (or your organization/company/team)]: 
    description [A short description of the project.]: 

It's okay not to have a repo_name here.


### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
├── README.md
├── Reproducibility-check-list.txt
├── data
│   ├── external
│   ├── interim
│   ├── processed
│   └── raw
├── notebooks
├── references
└── reports
    └── figures
```

### Contributing
------------

Contributions are welcome!

### Acknowledgement
------------

Forked from https://github.com/drivendata/cookiecutter-data-science.

Inspired by:

http://drivendata.github.io/cookiecutter-data-science/

https://github.com/cookiecutter/cookiecutter
