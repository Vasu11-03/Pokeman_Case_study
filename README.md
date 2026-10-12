Pokémon Data Visualization
A data visualization and exploratory data analysis project that explores Pokémon attributes using Python. The notebook uses Pandas to analyze the dataset and Matplotlib and Seaborn to create visualizations that reveal distributions, type comparisons, generation trends, and relationships between stats.
Project Overview
The analysis uses pokemon_data.csv, which contains Pokémon information such as primary type, generation, HP, attack, defense, special attack, special defense, speed, and total stats.
The notebook loads the dataset into a Pandas DataFrame and explores it through 10 visualizations.
Quick Start
1. Clone the Repository
git clone <your-repository-url>
cd <your-project-folder>
2. Install Dependencies
pip install numpy pandas matplotlib seaborn jupyter
3. Add the Dataset
Place pokemon_data.csv in the project directory, alongside the notebook.
4. Run the Notebook
Start Jupyter Notebook:
jupyter notebook
Open the data visualization notebook and run the cells in order.
Analysis and Visualizations
1. Distribution of HP — A histogram shows how Pokémon HP values are distributed. The notebook notes that the most common range is approximately 50–90 HP.
2. Distribution of Speed — A histogram with a KDE curve explores the distribution of Pokémon speed.
3. Pokémon Count by Primary Type — A count plot compares the number of Pokémon in each primary type. The notebook identifies Water as the most common primary type and Flying as relatively rare.
4. Average Attack by Primary Type — A bar plot compares mean attack values across primary types. The notebook identifies Fighting as having the highest average attack.
5. Speed by Primary Type — A box plot compares speed distributions across primary types, including medians and spread.
6. Pokémon Count by Generation — A count plot compares the number of Pokémon in each generation. The notebook identifies Generation 5 as having the most Pokémon in this dataset.
7. Average Total Stats by Generation — A bar plot compares mean total stats across generations. The notebook observes that later generations tend to have higher total stats on average.
8. Attack vs. Defense — A scatter plot explores the relationship between attack and defense. The notebook reports no strong linear relationship.
9. Speed vs. Total Stats — A scatter plot compares speed with total stats. The notebook observes a slight positive tendency, with a wide spread at most speed levels.
10. Correlation Heatmap — A heatmap visualizes correlations among HP, attack, defense, special attack, special defense, speed, and total stats. The notebook reports the strongest positive correlation as total and attack (0.712), and the weakest as speed and defense (0.0080).
Tech Stack
Component	Technology
Programming Language	Python
Data Manipulation	Pandas
Numerical Computing	NumPy
Visualizations	Matplotlib
Statistical Graphics	Seaborn
Development Environment	Jupyter Notebook


Project Structure
pokemon-data-visualization/
├── pokemon_data.csv
├── data_visualization.ipynb
└── README.md
File names may differ in your repository. Update the structure above to match your actual files.
Key Learning Outcomes
- Creating histograms, count plots, bar plots, box plots, scatter plots, and heatmaps.
- Grouping data and calculating averages with Pandas.
- Comparing Pokémon attributes across types and generations.
- Exploring relationships between numerical features using correlation analysis.
- Communicating findings through charts and concise observations.
Notes
- The dataset file pokemon_data.csv is required to run the notebook.
- The findings above reflect the written observations in the notebook and depend on the version of the dataset used.
- Ensure the dataset's source and usage terms are acknowledged when sharing the project.
License
Add an appropriate license if you plan to distribute this project publicly.
