# **Surfs_Up_Analysis**

## **Overview of Project**

The project has the functionality to show how a basic website can be run through Jupyter Notebook and SQLite, using databases that have .squile format known as `flat files`."You can compare SQLite databases to a CSV or Excel file: each SQLite database can have one or more tables with columns and rows, and it is stored as a file on your computer. The key difference between SQLite databases and a CSV or Excel file is that we can write queries for it." - Washington University of St. Louise.
Using VS Code in this module is going to help to develope a [Flask application](https://flask.palletsprojects.com/en/2.0.x/).


## **Results**

Pandas Dataframes [Pandas](https://pandas.pydata.org/), was applied to make possible esential calculations which information can bring clearer insights about the databse. 
On the other hand, `create_engine()` was used as a function that prepares the data in order to connect with it later. "This function will typically have one parameter, which is the location of the SQLite database file." `engine = create_engine("sqlite:///hawaii.sqlite")`.

- **Practice Results**
The data was plot using Matplotlib to determine weather trends and the statistics of the data. And finally, create a Flask Dependency to create a 

Graph visualization - Weather Trends
![Plot]()

Dataframe visualization - Main Statistics
![Statistics]()

Create a Flask route `@app.route()` in order to create a function, in the practice case: `hello_world()` so that we display in the localhost:5000 "Hello World"

Localhost looks like this:
![local](resources/app.py_Hello%20World!.png)
![local2](resources/app2.py_Hawaii%20APIs.png)


## **Summary**

In the challenge, we deteremined the statistics for June and December.Using Python, Pandas functions and methods, and SQLAlchemy, we filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. Then we converted those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

June Temps - Analysis Results
![June]()

December Temps - Analysis Results
![December]()

Based on the `hawaii.sqlite` data, we can state as a high-level summary of results that Standard deviation is 3.25 in June and 3.75 in December, making a 0.5 difference between both seasons. This concludes that the performing weather data for June and December provide results to decide how we would like to build the shop and what areas would make this location attractive to visitors to stop by and have a successful business.
