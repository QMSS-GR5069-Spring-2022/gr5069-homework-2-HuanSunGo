# This folder contains past homework files in another class I have produced in the past.

## Scenario

Imagine you are the data scientist at a respected media outlet -- say the "New York Times". For the Winter Olympics coverage, your editor-in-chief asks you to analyze some data on the history of `Winter Olympics Medals by Year, Country, Event and Gender` and prepare some data visualizations in which you outline the main patterns around which to base the story.

## Tasks

#### 1. Medal Counts over Time

a) Combine the information in the three spreadsheets `athletes_and_events.csv`, `noc_regions.csv`, and  `gdp_pop.csv`. Note, that the `noc_regions.csv` is the set all NOC regions, while `gdp_pop.csv` only contains a snapshot of the current set of countries. 

b) Calculate a summary of how many winter games each country competed in, and how many medals of each type the country won. Use that summary to provide a **visual comparison of medal count by country**. 

#### 2. Medal Counts adjusted by Population, GDP

There are different ways to calculate "success". Consider the following variants and choose one (and make sure your choice is clear in the visualization):  
  - Just consider gold medals.  
  - Simply add up the number of medals of different types.    
  - Create an index in which medals are valued differently. (gold=3, silver=2, bronze=1).   
  - A reasonable other way that you prefer.
  
Now, adjust the ranking of medal success by (a) GDP per capita and (b) population. You have now three rankings: unadjusted ranking, adjusted by GDP per capita, and adjusted by population.

Visualize how these rankings differ. Try to highlight a specific pattern (e.g. "South Korea -- specialization reaps benefits" or "The superpowers losing their grip").

#### 3. Host Country Advantage

Until the 2014 Sochi Winter Olympics (our data for Winter Olympics end here), there were 19 host cities. Calculate whether the host nation had an advantage. That is calculate whether the host country did win more medals when the Winter Olympics was in their country compared to other times. 

Provide a visualization of the host country advantage (or absence thereof).

#### 4. Most successful athletes

a) Now, let's look at the most successful athletes. Provide a visual display of the most successful Winte Olympics athletes of all time.

b) Chose of of the athlete specific dimensions (e.g. gender, height, weight) and visualize an interesting pattern in the data.

#### 5. Make two plots interactive

Choose 2 of the plots you created above and add interactivity. One of the plots needs to be written in `plotly` rather than just using the `ggplotly` automation. Briefly describe to the editor why interactivity in these visualization is particularly helpful for a reader.

#### 6. Data Table

Prepare a selected data set and add a `datatable` to the output. Make sure the columns are clearly labelled. Select the appropriate options for the data table (e.g. search bar, sorting, column filters etc.). Suggest to the editor which kind of information you would like to provide in a data table in the online version of the article and why.

