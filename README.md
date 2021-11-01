30 Day Analysis – Player Retention 

The data query created explores player who were retained past 30 days and information on where the players are, their spent on them to the system players use. This project was in collaboration with Miguel Pallas (emepemi@gmail.com).
Miguel's repository (https://github.com/MiguelPMiralles/SQL_Project)

Simulated questions how many players joined on specific day and with those players how many were retained. As well as the fractional retention of players.
Additional analysis included of players with rolling 30-day retention spend more to players who aren’t retained and if they’re in specific region. Also view of which platform/system do most player prefer.

To acquire the data to analyze the simulated questions, BigQuery and Google Sheets were used. In BigQuery, joining four different tables to connect unique keys to each other. With the JOIN function, we were able to generate a single table to gather the data needed for the questions. Function such as COUNT, PARTITION BY, MAX, and CASE WHEN were used.
SQL reference (https://github.com/riconoll/ProjectOne/blob/main/SQL_Query)

Visualization reference (https://docs.google.com/spreadsheets/d/1XM9oV8Xd0A5Rr8VV1eiGRMfex9mMm0ssCDcUUuEQjyA/edit?usp=sharing)
With all the data needed, Sheets was used for visualization. Showcasing the number of players retained of it 365-day life-cycle. In one of the visualization, scatter plot was used to a better representation of Retained VS Non-Retained players over the game life-cycle. One visualization shows a dip on the trend line for the last 31 days, due to the unknown whether the player who joined ‘late’ in the game will play after the 30 days. Taking out the outlier of the last 31 days, it shows a stable trend line rather than a decline.

Of the players that were retained another analysis was done for much were spent and in which region do they come from. A bar chart was used to visualize the difference between the retained and non-retained players spent. Total spend and Average spend for said players did show difference. As the Average spend non-retained player spent more than the retained players. This is due to there were less players and playing in a short-time frame.

This also allowed us to see if there is a preferred system of what players use. With the analysis, there wasn’t much of a difference. The numbers are very close to each other.
