# Car Price Prediction App

--> A Machine Learning Web App that can predict the prices of cars based on factors such as year of purchase, type of model and so on. It is created with Flask and is currently deployed on Heroku platform.

Visit: https://carprice-generator.herokuapp.com/

## A glimpse of the web app:

 ![GIF](readme_resources/ipl-first-innings-score-web-app.gif)
 

## Directory Tree
--> Here are some details of the subdirectories and files that the repository contains. 
```
├── static 
│   ├── car-favicon.ico
│   ├── styles.css
├── template
│   ├── index.html
├── Car_Prediction.ipynb
├── Procfile
├── README.md
├── app.py
├── car data.csv
├── random_forest_regression_model.pkl
├── requirements.txt
```
## Description
* Static Folder contains the favicon as well as the css file which describes the HTML elements of the web app.
* Template folder contains the html file which depicts the format of the web page.
* Car_Prediction.ipynb is a notebook document created by Jupyter Notebook that contains all the notebook code and the execution results that has helped in generating the model for the web app.
* Procfile includes the code ``` web: gunicorn app:app ``` which depicts that gunicorn commands are run by the application's containers on the platform. To create a procfile run the following command on command prompt. ``` echo web: gunicorn app:app > Procfile ```
* README.md includes the stucture that provides a detailed description of my GitHub project.
* app.py includes the all the routes and functions to perform the actions of web app. This file is the root of the Flask application which we will run in the command line prompt.
* car data.csv is the dataset file which is in the csv format.
* random_forest_regression_model.pkl is the random forest regression model that has been improved using the hyperprameter tuning. It is the core of the web application.
* Requirements.txt file includes all the libraries that has been used to create the web app. After installing all the required packages, ``` pip freeze > requirements.txt ``` command was run on the command prompt to create the requirements.txt file

## Libraries Used
--> This section contains the list of the libraries that have been used to create the web app. 
```
argon2-cffi==21.3.0
argon2-cffi-bindings==21.2.0
attrs==21.4.0
backcall==0.2.0
bleach==4.1.0
certifi==2020.6.20
cffi==1.15.0
charset-normalizer==2.0.11
click==8.0.3
cycler==0.11.0
decorator==4.4.2
defusedxml==0.7.1
entrypoints==0.4
Flask==2.0.2
fonttools==4.29.1
idna==3.3
importlib-resources==5.4.0
ipython_genutils==0.2.0
ipywidgets==7.6.5
itsdangerous==2.0.1
Jinja2==3.0.3
joblib==1.1.0
jsonify==0.5
jsonschema==4.4.0
jupyter==1.0.0
jupyter-console==6.4.0
jupyter-core==4.6.3
jupyterlab-pygments==0.1.2
jupyterlab-widgets==1.0.2
kiwisolver==1.3.2
MarkupSafe==2.0.1
matplotlib==3.5.1
mistune==0.8.4
nbclient==0.5.10
nbconvert==6.4.1
nbformat==5.1.3
nest-asyncio==1.5.4
notebook==6.4.8
numpy==1.22.2
packaging==21.3
pandas==1.4.0
pandocfilters==1.5.0
pickleshare==0.7.5
Pillow==9.0.1
prometheus-client==0.13.1
pycparser==2.21
pyparsing==3.0.7
pyrsistent==0.18.1
python-dateutil==2.8.1
pytz==2021.3
pyzmq==19.0.2
qtconsole==5.2.2
QtPy==2.0.1
requests==2.27.1
scikit-learn==1.0.2
scipy==1.8.0
seaborn==0.11.2
Send2Trash==1.8.0
six==1.15.0
sklearn==0.0
terminado==0.13.1
testpath==0.5.0
threadpoolctl==3.1.0
tornado==6.1
urllib3==1.26.8
webencodings==0.5.1
Werkzeug==2.0.2
widgetsnbextension==3.5.2
wincertstore==0.2
zipp==3.7.0
gunicorn
```



