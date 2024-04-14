# The impact of Sixth Men

In this notebook, I am doing an in depth study of the sixth men (and bench players) from the year 1999-2023. I take a look at the different positions, ages, and statistical contributions of these players to look for trends, as well as trends in how their teams played. This data will be presented to the NC State Sports Analytics Club, and I had a great time with this. I think I will begin a blog and start posting different sports analysis projects biweekly. 


## Project Content
For all of these, I provide cell by cell analysis, so you can just read along!  
- Descriptive Statistics: Overview of basic statistics and trends (analysis/descriptive_Statistics.ipynb).
- Association Mining: Advanced analysis on patterns and associations in the data (analysis/association_mining.ipynb).
- Visualizations: File storing all the visualizations used for descriptive statistics and association mining (analysis/visualizations).

## Data
If you want to play around with the raw and processed data:  
Combined Data: Look in data/rawDataProcessing/combined for CSV files containing combined player and team data per 100 possessions.
Seasonal Data: Individual season data can be found in data/data_per_game, data/per_100_poss, and data/team_per_100.  
These files are already in CSV format, so all you have to do is download the csv file of your choice. 

## methodology
I used Python with libraries such as Pandas for data manipulation, Matplotlib and Seaborn for visualization, and techniques like association rule learning for discovering relationships within the data.  
I used stats per 100 posessions for team and player stats to keep pace a nonfactor. This allows for better comparison across generations.  
I used association rule mining to find trends in the dataset across different columns. This is generally a method for finding relationship in market analysis. 


### Recreate the project
To get started with this project:  
<ol>
  <li>Clone the Repository </li>
  <pre><code>git clone https://github.com/izyuan/Impact-of-Sixth-Men.git</code></pre>
  <li>Install the libraries</li>
  <pre><code>pip install -r requirements.txt</code></pre>
  <li>Explore the data!!</li>
</ol>

## Key Findings
#### Here are some findings I found interesting
Note: I will be refering to the top 2 bench players from each team as sixth men.
- Sixth men on top teams tend to have lower PIE (Player Impact Estimate) than sixth men on average teams, who tended to have lower PIE scores than bottom teams. 
- The average PIE score of sixth men from 2011-2023 were higher than the players from 1999-2010. 
- Average minutes played per 100 posessions for bench players decreased from the 1999-2010 to 2011-2023. 
- Average age of sixth men increases with the team's performance, suggesting that succesful teams tend to only slightly older, more experienced player, while bottom and average teams sixth men tended to be younger. 
- SGs as sixth men became increasingly more prevelent as time has gone on. They are also the most common sixth men position. 
- Top teams tend to utilize point gaurds more than average and bottom teams. 
- Top teams tend to utilize sixth men with higher offensive capabilities (compared to other sixth men) while bottom teams tend to utilize higher defensive capabilities (compared to other sixth men)
- Point guards age 24-27 are more likely to be on top 6 teams. 
- Point gaurds on top teams frequently have offensive capabilites in the top 25% of sixth men. 
- Small forwards on top teams tend to have lower PIE scores, indicating a more role focused contribution. 
- Point gaurds and Shooting guards on bottom teams were likely to have defensive capabilites in the top 25% of sixth men. 
- Bench players with top 25 percentile ORtg tend to also excel defensively on both top and bottom teams. 

## Feedback
Feel free to reach out at ieyuan1608@gmail.com or connect with me on LinkedIn for any feedback or collaboration opportunities.
Here's my linkedin: https://www.linkedin.com/in/isaac-yuan-723b422a6/


