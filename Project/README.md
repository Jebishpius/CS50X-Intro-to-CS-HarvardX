# Covid-19 Web Application using Streamlit
## By: Abish Pius & Jebish Pius

Hello, World! <br>
<br>
We would like to introduce our CS50 Course Project, a web dashboard that 
lets you see an overview on the number of Covid-19 cases in the United States.
<br>
<br>
We were inspired to create an easy to follow tool that could track how well individual's counties or states were doing on flattening the curve. 
<br>
<br>
## Overview of the Project:
### Part1: Track Prevalent Cases in the United States
In the first interactive plot, we designed a tunable geographical plot that allows individuals to see areas in the United States that have a number of prevalent cases greater than a chosen threshold. We define prevalent cases based on the standard criteria for symptoms of the disease lasting two weeks.

### Part2: See Cases by State
In the second interactive geographical plot, we allow the user to select a State or Territory within the US and have the plot automatically zoom into that region and display hexagonal bins over counties with heights proportional to the number of cases per county.

### Part3: Observe the trajectory of Cases within a selected time frame
From the State/Territory chosen by the user in Part2, the user is able to select a range of days and observe the trajectory of the cases. This feature can be used to see the rate of new cases and identify when the curve flattens.

### Part4: Top 5 States by Cases
In the final section, we present the top five States with the most number of cummulative confirmed cases.

#### Works Cited:
Data Source: https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset?select=time_series_covid_19_confirmed_US.csv
Packages used: <br>
Numpy (https://numpy.org/doc/) <br>
Pandas (https://pandas.pydata.org/) <br>
Streamlit (https://docs.streamlit.io/en/latest/) <br>
Plotly (https://plotly.com/python/)

#### Disclaimer:
The web application will only be hosted from 6/10/20 - 6/13/20. Note, if you plan on hosting the application yourself you will need to generate an API Key on Mapbox (https://www.mapbox.com/) and you will need to update the filepaths in the script.
