The PDF file titled Report contains the final report with only the visualizations


The Source folder contains three ipynb files:
    report_with_code_and_vis.ipynb: contains the entirety of the report along with the necessary code to create the visualizations as they are in the report

    aggregating_data.ipynb: contains the creation of our CSV files – involves HTML web scraping and the retrieval of JSON formatted data from an API

    scrap_notebook.ipynb: contains preliminary analyses – a decent portion of this notebook is in report_with_code_and_vis.ipynb but there is some that did not make the final cut.  Fair warning, it is pretty hectic
    

The CSV files, briefly, are as follows:
    regular_season_2010s.csv: contains per-game box score statistics for every player for each season starting with the 2010-2011 NBA season and ending with the 2019-2020 NBA season

    playoffs_2010s.csv: contains the same statistics as in player_data.csv but is limited to only playoff games – data was collected but was not used in this project

    player_data.csv: contains player information such as salary, experience, height, and weight – 2020 only.  JSON formatted data can be accessed with the following url:
https://api.sportsdata.io/v3/nba/scores/json/Players?key=a3824595f2f740dbb21dd847e49ba332 

    team_data.csv: contains team information such as name, division, conference, and colors. JSON formatted data can be accessed with the following url:
https://api.sportsdata.io/v3/nba/scores/json/teams?key=a3824595f2f740dbb21dd847e49ba332

    stadium_data.csv: contains stadium information such as name, team, location, and geographical coordinates – data was collected but was not used in this project. JSON formatted data can be accessed with the following link:
https://api.sportsdata.io/v3/nba/scores/json/Stadiums?key=a3824595f2f740dbb21dd847e49ba332


    
Consult Source/scrap_notebook.ipynb for more information regarding the CSV data.
    

To ensure that the notebooks run correctly, do the following:
    1. Create a new folder in Jupyter
    2. Upload all CSV files within the newly created folder
    3. Upload the Source folder (leaving the three ipynb files as is) within the newly created folder
