# Visualizations of NASA’s APIs #

The project will get information from the NASA API’s and plot them.
It will also scrape WIkipedia and for the first paragraph of the pages about the APIs. All of those things will be put on the computer’s server through flask.

## Getting Started ##

Use this site to get a NASA API key: https://api.nasa.gov/index.html#apply-for-an-api-key

Use this site to get a plotly username and API key:
https://plot.ly/python/getting-started/

Install all of the things in the requirements.txt

### Setting up Database: ###
Before running the application, first set up the database. You can do this by running the following command: 

```
python database/populate_database.py
```

Allow the file to run entirely. It will run a number of functions and output the progress of the build to the terminal.

### Run Flask App: ###
Once the above file finished running. You can now run the following command to start up the flask application.

```
python app.py
```

The above command will start up the server and output the url where you can view the application. For your convenience this application has been set up to use host `0.0.0.0`.

## Running the tests ##

The application comes with a number of unit tests to test the database and the plots. All the tests can be found in the main directory of the application called tests.py. To run this file type:

```
python tests.py
```

## Built With ##

**Flask** - The web framework used

**Plotly** - Data visualization platform

## Authors ##
Lauren Elbaum

Jesse Barnes--Tutor--4 to 6 hours per week
