# Elden Ring Boss EDA

The objective of this project is to conduct Exploratory Data Analysis (EDA) on the Elden Ring Boss Dataset. The dataset used for this analysis is obtained from Kaggle and can be found [here](https://www.kaggle.com/datasets/robikscube/elden-ring-ultimate-dataset). The dataset specifically includes the "bosses.csv" file, which contains information about the bosses in Elden Ring.

## Dataset Information

The dataset used for this analysis is taken from Kaggle and consists of the "bosses.csv" file. The file contains 8 columns and 106 rows. The columns in the dataset include:

- name: The name of the boss.
- region: The region where the boss is located.
- healthPoints: The health points of the boss.
- attackPoints: The attack points of the boss.
- defensePoints: The defense points of the boss.
- soulsAwarded: The number of souls awarded for defeating the boss.
- image: The image of the boss.
- description: The description of the boss.

## Requirements

To run this project, you need the following dependencies:

- Python 3.x
- pandas
- matplotlib
- seaborn
- regex
- numpy

## How to Run

1. Download or clone the project repository from GitHub.
2. Install the required dependencies as mentioned above.
3. Place the "bosses.csv" file in the project directory.
4. Open the "Elden Ring EDA.ipynb" file using Jupyter Notebook or any compatible IDE.
5. Run the notebook cells to perform the Exploratory Data Analysis on the Elden Ring Boss Dataset.

## Conclusions with Plots and Images

The analysis of the Elden Ring Boss Dataset includes various visualizations and insights regarding the bosses in the game. The following conclusions were drawn from the analysis:

1. The dataset revealed missing data in the image, description, and healthPoints columns. However, missing information in the image and description columns did not affect the analytical data.

2. The number of bosses in each region was analyzed, revealing discrepancies due to spelling mistakes. The dataset was corrected to provide accurate information about the number of bosses in each region.

3. Average health of bosses in each region was calculated, providing insights into the difficulty level of different regions.

4. An investigation was conducted on specific bosses with the highest health points, showcasing their significance and potential challenges they pose to players.

The conclusions are supported by relevant plots and images included in the notebook.

Please refer to the "Elden Ring EDA.ipynb" notebook for visualizations, detailed analysis and code implementation.

Note: The dataset and analysis are based on Elden Ring, a fantasy world created by Hidetaka Miyazaki and George R. R. Martin. The analysis focuses on the bosses in the game and their characteristics.
