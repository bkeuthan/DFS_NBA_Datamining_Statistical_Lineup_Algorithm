# DFS_NBA_Datamining_Statistical_Lineup_Algorithm

Project designed to optimize Daily Fantasy Sports NBA Daily Picks.

* Applications Used: 
        1) Python
        2) Jupyter Notebook
        3) Pandas
        4) MatplotLib (Research & Statistical Analysis Only)
        5) HTML Beautiful Soup
        6) HTML Chrome Driver
        7) Microsoft Excel
        8) SQL Alchemy 

### Datasets:
    1. DraftKings.com 
            *Daily contest player pool w/salaries - exported to a .csv file - MANUAL Extract.
            
    2. NBA.com 
            *Daily lineups + inactivate player pool - exported via Chrome Driver & Beautiful Soup.
            
    3. Basketball-Reference.com
            *Beautiful Soup extract into Pandas to compile schedule - exported to Microsoft Excel to clean data and build the logic to loop through all boxscores
            *Imported cleaned schedule back into pandas
            *Beautiful Soup extract looping through every box score based on the link logic applied - extracting 4 tables - Home Basic, Home Adv, Visior Basic, Visitor                Adv.
            *Took these extracted tables and merged Basic/Adv statistics together using Pandas.
            *Uploading into a SQL Alchemy Database to store all data.

### Data Sourcing:
    * draftkings.com
    * nba.com
    * basketball-reference.com
