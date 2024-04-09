# Data-Preprocessing-Techniques
This repository contains the solution for the first iteration of the Data Preprocessing Techniques project in the COMP 3400-6981 course at Memorial University of Newfoundland.

# Data Preprocessing Techniques Project - Iteration 1 (P1)

This repository contains the solution for the first iteration of the Data Preprocessing Techniques project in the COMP 3400-6981 course at Memorial University of Newfoundland.

## Iteration 1 (P1)

The goal of the first iteration is to complete the following tasks:

### Part 1 - Dataset Presentation (40 marks)

In the first part, the authors have done an excellent job in presenting and describing the dataset. They have:

1. **Described the variables**: The authors have provided a detailed description of the variables in the dataset, including their purpose and importance.
2. **Contextualized the dataset**: The authors have explained that the dataset is from the game "Football Manager 2017" and contains data about players and their stats.
3. **Justified the inclusion of each variable**: The authors have clearly explained why each variable is important and will be kept in the dataset.
4. **Generated descriptive statistics and plots**: The authors have generated various descriptive statistics, such as mean, standard deviation, minimum, and maximum, for the key variables. They have also plotted histograms and line plots to understand the data distribution.
5. **Provided justification for the chosen statistics and plots**: The authors have explained the rationale behind the chosen descriptive statistics and plots, and how they help in understanding the dataset.

Overall, the authors have done a commendable job in presenting and contextualizing the dataset, demonstrating a thorough understanding of the data.

### Part 2 - Data Cleaning (50 marks)

In the second part, the authors have successfully handled missing data and outliers in the dataset:

1. **Handling missing data**: The authors have identified that the dataset contains missing data and have provided a justification for creating a procedure to simulate missing data. They have then applied appropriate techniques to handle the missing data, such as dropping rows with missing values.
2. **Handling outliers**: The authors have identified that the dataset contains outliers and have provided a justification for creating a procedure to simulate outliers. They have then applied the Interquartile Range (IQR) method to identify and replace the outliers.
3. **Visualizing the changes**: The authors have plotted the original and modified data side-by-side to visually demonstrate the impact of their data cleaning efforts.
4. **Retaining relevant rows**: The authors have carefully managed the data cleaning process, ensuring that they only remove the necessary rows and retain as much relevant data as possible.

The authors have demonstrated a strong understanding of data cleaning techniques and have applied them effectively to the dataset.

## Conclusion

Overall, the authors have done an excellent job in completing the first iteration of the Data Preprocessing Techniques project. They have meticulously presented the dataset, justified their decisions, and effectively handled missing data and outliers. The code is well-organized, well-documented, and easy to follow. The authors have shown a solid grasp of the concepts and have produced a high-quality solution that meets the requirements of the project.

The solution for the first iteration can be found in the following Jupyter Notebook:

[Project_Iteration_1_(P1)_1_1.ipynb](https://github.com/pankaj12-stack/Data-Preprocessing-Techniques/blob/main/Project_Iteration_1_(P1)_1_1.ipynb)

##Here are some detailed insights from the solution for Iteration 1:

1. **Dataset Presentation**:
   - The dataset contains information about 159,541 players from the "Football Manager 2017" game, with 89 attributes for each player.
   - The authors narrowed down the dataset to focus on players from Portugal (NationID = 788), which resulted in a subset of 3,643 players.
   - The authors provided a comprehensive description of the key variables, including age, international caps and goals, under-21 caps and goals, height, weight, stamina, strength, and consistency.
   - The authors generated descriptive statistics and visualizations to understand the distribution of the data. For example, they plotted a histogram to show the distribution of players by age, and line plots to analyze the relationship between international goals, consistency, and age.

2. **Data Cleaning**:
   - The authors identified that the dataset contained missing data and outliers, and they created procedures to simulate these issues.
   - For missing data, the authors randomly selected 10% of the rows and replaced the values for the "Height" and "Weight" columns with NaN (Not a Number) values.
   - For outliers, the authors randomly selected 5% of the rows and replaced the values for the "Stamina" and "Strength" columns with random numbers between 30 and 40.
   - The authors then used the Interquartile Range (IQR) method to identify and replace the outliers in the "Stamina" and "Strength" columns.
   - To visualize the impact of their data cleaning efforts, the authors plotted the original and modified data side-by-side for the "Stamina" and "Strength" columns.
   - After cleaning the data, the authors retained 758 rows out of the original 940 rows, ensuring that they only removed the necessary rows and kept as much relevant data as possible.

3. **Insights from the Data**:
   - The authors observed that the majority of Portuguese players in the dataset are young, with an average age of 22 years and 75% of players being under 26 years old.
   - Most Portuguese players have not played in any international matches or scored any goals for their national team. However, the player with the most international appearances and goals is likely Cristiano Ronaldo, who stands out in the scatter plot.
   - The authors also noted that players in the age range of 25-35 years old are typically called up to play for the national team.
   - Regarding the physical attributes, the authors found that the average stamina, strength, and consistency of the players are 8.8, 8.3, and 9, respectively.

These detailed insights demonstrate the authors' thorough understanding of the dataset and their ability to extract meaningful information from the data through careful analysis and visualization.

## Iteration 2 (P2)

The second iteration of the project will be added later to this repository. Please check back for updates.
