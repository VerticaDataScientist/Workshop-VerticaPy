# Workshop-VerticaPy

Disclaimer: This workshop does not introduce the best steps for the machine learning cycle or explain the models and the techniques used, it assumes that you are already familiar with building machine learning models. Our scope is to introduce the VerticaPy features as much as possible, providing the tools for every cycle step: data loading/reading, data exploration, data preparation, feature engineering, training models, evaluating models, and deployment and management of the models.


<h1 align="center">
  <br>
  <a href="http://www.amitmerchant.com/electron-markdownify"><img src="https://raw.githubusercontent.com/vertica/VerticaPy/master/img/logo.png" alt="Markdownify" width="200"></a>
  <br>
  VerticaPy
  <br>
</h1>

<h4 align="center">A powerful Python library for in-database machine learning <a href="https://www.vertica.com/python/documentation_last/" target="_blank">VerticaPy</a>.</h4>


<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#Workshops">Workshops</a> •
  <a href="#Emailware">Emailware</a> •
  <a href="#related">Related</a> •

</p>


## Key Features

* Connect/View/Modify Vertica Database
* Read/Load/Drop Data
* vDataFrame
* Machine Learning
* Automated Machine Learning 
* User-Defined Functions
* Geospatial Functions
* Statistics
* Respoonsive/static visualizations
* SQL Magic
* Data Preparation Fumnctions
* Feature Engineering Functions
* Model Management and Deployment

## How To Use

You need to install Vertica database or use [CE version](https://www.vertica.com/blog/how-to-run-vertica-ce-in-windows-10-using-docker/), then install VerticaPy package and connect with database.



```python
# install VerticaPy
pip3 install verticapy[all]

# Connect with database
verticapy.new_connection({"host": "your_host",
                        "port": "your_port",
                        "database": "database_name",
                        "password": "your_password",
                        "user": "dbadmin"},
                        name="connection_name")

```

> **Note**
> All the steps are explained in the notebooks.

In case you there is issue to install `verticapy[all]` (with previous versions), please run these commands before installing VerticaPy.
```bash
pip install pipwin
pipwin install gdal
pipwin install fiona
``` 


## Workshops

The workshop goes trough the following steps:
 * Workshop 1: Instalation, Database connection, Data Loading/reading, and ingestion
 * Workshop 2: Data Exploration and Visualization
 * Workshop 3: Data Preparation and Features Engineering
 * Workshop 4: Model Training and Evaluation
 * Workshop 5: Model Management and Deployment
 

## Emailware

If you liked using this tool or it has helped you in any way, we'd like you send us an email at <abdelhak.zabour@microfocus.com> or <matteo.monaldi@vertica.com> about anything you'd want to say about this tool. we'd really appreciate it!


## Related

[VerticaPy](https://github.com/vertica/VerticaPy) - We are open source, please feel free to contact us.

[VerticaPy Machine Learning Cheat Sheet](https://github.com/vertica/VerticaPy/blob/master/cheat_sheet/VerticaPy%20Machine%20Learning%20Cheat%20Sheet.docx)

---
