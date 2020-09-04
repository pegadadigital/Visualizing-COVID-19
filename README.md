
# Visualizing COVID-19
<p float="left">
  <img src="https://github.com/pegadadigital/Visualizing-COVID-19/blob/master/Images/1.jpg" width="300" />
</p>
This content is from a Guided Project in [Datacamp](https://learn.datacamp.com/projects/870).


### Starting Docker container

The project has a **Docker** folder with composer yaml file based on [stefanproell](https://github.com/stefanproell/jupyter-notebook-docker-compose) scripts. Follow the instructions bellow to start the container:
* Generate the password token and put it in **.env** file:\
`generate_token.py -p S-E-C-R-E-T` 
* Generet cert file or use the one in SSLCERT folder:\
`openssl req -x509 -nodes -newkey rsa:2048 -keyout jupyter.pem -out jupyter.pem`
* Adapt **.env** variables, alter variables directories:
    * LOCAL_WORKING_DIR
    * ACCESS_TOKEN
    * PORT
    * LOCAL_DATASETS
    * LOCAL_MODULES
    * LOCAL_SSL_CERTS
* Start the container:\
`docker-compose up --build`
* Acess Jupyter
https://localhost:8888

### The content

The **Notebook** folder has the source files in Jupyter:
* notebook.ipynb

And the **dataset** folder with csv data.
It's organized in topics:
 1. From epidemic to pandemic
 2. Confirmed cases throughout the world
 3. China compared to the rest of the world
 4. Let's annotate!
 5. Adding a trend line to China
 6. And the rest of the world?
 7. Adding a logarithmic scale
 8. Which countries outside of China have been hit hardest?
 9. Plotting hardest hit countries as of Mid-March 2020
 
Graphs

<p float="left">
    <img src="https://github.com/pegadadigital/Visualizing-COVID-19/blob/master/Images/2.png" width="300" />
    <img src="https://github.com/pegadadigital/Visualizing-COVID-19/blob/master/Images/3.png" width="300" />
    <img src="https://github.com/pegadadigital/Visualizing-COVID-19/blob/master/Images/4.png" width="300" />
    <img src="https://github.com/pegadadigital/Visualizing-COVID-19/blob/master/Images/5.png" width="300" />
    <img src="https://github.com/pegadadigital/Visualizing-COVID-19/blob/master/Images/6.png" width="300" />
    <img src="https://github.com/pegadadigital/Visualizing-COVID-19/blob/master/Images/7.png" width="300" />
    <img src="https://github.com/pegadadigital/Visualizing-COVID-19/blob/master/Images/8.png" width="300" />
</p>
