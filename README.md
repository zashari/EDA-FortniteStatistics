# Exploratory Data Analysis on Fortnite Player Statistics

### Introduction

The project explores whether building defenses using gathered materials significantly impacts a player's performance in Fortnite, a popular battle royale game. The study aims to understand the correlation between the usage of building materials and various in-game metrics like player placement, damage taken, and damage dealt.

### Background

In Fortnite, players can gather materials to build structures, providing them with defensive advantages. This exploratory data analysis (EDA) seeks to examine the strategic aspect of material usage and its impact on gameplay. By analyzing game statistics, the study intends to shed light on the effective strategies in terms of material gathering and usage.

### Methodology

1. **Data Preparation**: The dataset was cleaned and preprocessed. This included converting the 'Accuracy' field from a percentage string to a float, mapping 'Mental State' to numeric values, and dropping irrelevant columns like 'Date' and 'Time of Day'.

2. **Data Exploration**:
   - A histogram was used to understand the distribution of player placements ('Placed') in the game.
   - A correlation heatmap was generated to analyze the relationships between various numerical factors such as eliminations, assists, materials gathered, and damage taken.
   - A scatter plot was created to directly compare 'Damage Taken' against 'Materials Used', with player placement ('Placed') as a categorical hue.

### Key Findings and Analysis

- **Distribution of Player Placement**: The histogram of the 'Placed' column indicated how frequently players landed in various placement brackets.

- **Correlation Insights**: The heatmap revealed how different gameplay aspects correlated with each other. For instance, it would be interesting to see if there's a strong correlation between 'Materials Used' and 'Damage Taken' or 'Placed'.

- **Materials Used vs. Damage Taken**: The scatter plot highlighted a trend where players who used fewer materials for building defenses tended to take more damage. This suggests that material usage for building defenses might play a crucial role in a player's survival.

- **Observation on Player Placement**: Players who used fewer materials were more likely to receive more damage and generally only survived up to the top 45 placements. This indicates a potential strategic disadvantage for players who underutilize building materials.

### Conclusion

The analysis suggests that building defenses with the materials gathered in Fortnite has a noticeable impact on a player's performance, particularly in terms of damage mitigation and overall placement in the game. Players who invest more in building defenses tend to survive longer, indicating the strategic importance of material usage. This insight can be valuable for players looking to improve their gameplay strategy in Fortnite, emphasizing the significance of gathering and efficiently using materials for building defenses.
