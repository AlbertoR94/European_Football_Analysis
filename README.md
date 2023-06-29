# European_Football_Analysis
Football database analysis using PySpark and SQL

## Description
In this project I analyze the Football Database that can be downloaded at the following [link](https://www.kaggle.com/datasets/davidcariboo/player-scores). This database that contains information about football games, players, games events, and competitions during the period 2012-2022, can be used to reveal meaningful insights about the main football leagues in Europe. 

Football is the most popular sport in the world with an estimated of 250 million active players according to [Wikipedia](https://en.wikipedia.org/wiki/Association_football). Furthermore, millions of tv spectators watch football matches of their favorite club playing both domestic and international competitions. Each competition, club, and player provide an incredible amount of data that can be processed and analyzed to reveal hidden patterns. 

To analyze the information in this database I will use mainly PySpark and SQL and also some other libraries to build some visualizations. PySpark is the Python API for Apache Spark and is a powerful tool for working with Big Data. Although this database is not large enough or complex to be considered as Big Data, it provides a good starting point for learning PySpark and SQL.

The final results were written into a CSV file "football_league_performance.csv" to create a Tableau [dashboard](https://public.tableau.com/views/EuropeanFootballLeagues_16879911046350/Dashboard1?:language=es-ES&:display_count=n&:origin=viz_share_linkv).

## Running notebook
Running the notebook requires installing PySpark and downloading the database from [link](https://www.kaggle.com/datasets/davidcariboo/player-scores) and creating a "files" folder inside the repository folder..
