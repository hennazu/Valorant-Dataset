# Valorant Dataset

The dataset for this project can be found on Kaggle. 
The author of this dataset scrapped together the data from spike.gg. 

# Objectives

The main objective of this project is: 
Develop a strategy guide for new Valorant players that maximizes their chances of winning by analysing map performance, agent effectiveness, and player statistics.

To achieve this objective, we can break it down into a few specific goals:

1. Identify the most successful agents on each map.
2. Analyse player performance to highlight key skills and strategies.
3. Combine these insights to create actionable recommendations for new players.

# Data Dictionary

Agents Dataset
agent: Name of the agent.
pick_rate: Percentage of matches the agent was picked in.
rounds: Number of rounds played with the agent.
rating, ACS, K/D, ADR, KPR, DPR, APR: Various performance metrics.
FBPR, FDPR, HS%, FBSR%: First blood performance and headshot percentages.
Maps Dataset
map: Name of the map.
played: Number of times the map was played.
avg_spike_plant: Average spike plant time.
rounds: Number of rounds played on the map.
atk_win_rate, def_win_rate: Win rates for attacking and defending sides.
pistol_atk_win_rate, pistol_def_win_rate: Pistol round win rates.
second_round_conversion_atk, second_round_conversion_def: Conversion rates for winning the second round after a pistol win.
Players Dataset
player: Name of the player.
country: Player's country.
team: Player's team.
rounds: Number of rounds played.
rating, ACS, K/D, ADR, KPR, DPR, APR: Various performance metrics.
FBPR, FDPR, HS%, FBSR%: First blood performance and headshot percentages.
Teams Dataset
team: Name of the team.
country: Team's country.
maps_played, maps_won, maps_won%: Number of maps played and won, and win percentage.
atk_played, atk_won, atk_won%: Number of attacking rounds played and won, and win percentage.
def_played, def_won, def_won%: Number of defending rounds played and won, and win percentage.
pistol_played, pistol_won, pistol_won%: Number of pistol rounds played and won, and win percentage.



# Main insights

# Engineered Features

# Model Selection 
