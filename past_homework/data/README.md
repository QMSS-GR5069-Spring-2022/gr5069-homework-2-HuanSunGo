# Data

## The main data is provided as an excel sheet, containing the following variables on all participating athletes in all olympics from 1896 to 2016 (sadly, the original source of the data no longer updates beyond that year):

  - `ID`: a unique indentifier of the entry
  - `Name`: name of the athlete
  - `Sex`: sex of the athlete
  - `Age`: age of the athlete
  - `Height`: height of the athlete
  - `Weight`: weight of the athlete
  - `Team`: usually the country team of the athlete, with the exception of political accomodations, e.g. the "Refugee Olympic Athletes" team.
  - `NOC`: national olympic comittee abbreviation.
  - `Games`: year and season of games.
  - `Year`: year of games
  - `Season`: season of games.
  - `City`: host city
  - `Sport`: a grouping of disciplines
  - `Event`: the particular event / competition  
  - `Medal`: the particular event / competition  

For example, an `event` is a competition in a sport or discipline that gives rise to a ranking. Thus `Alpine Skiing` is the discipline, and `Alpine Skiing Women's Downhills` is a particular event.

In addition, you are provided with some additional information about the countries in a separate spreadsheet, including the `IOC Country	Code`, `Population`, and `GDP per capita`.