# project_1
repo for our group project

Cities.csv contains the city names and population (provided by Austin)

yelpV4.ipynb is the code that performs the API calls, creates a dataframe and exports the frame to CSV

yelp_results.csv contains the data that was retrieved from the API calls. THERE IS NO POPULATION DATA HERE

clean_yelp_results.csv contains the data from the API calls AND population data. I used vlookup to assign the population from cities.csv to 

cities in yelp_results. Any city that couldn't be found in cities.csv OR was not in the US, I deleted the row. We went from 380 results to 320. 
