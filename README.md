
# NBA Performance Analysis

## Project Overview
This project aims to analyze the performance of NBA teams using a dataset of historical game records. By exploring various performance metrics, trends, and insights, the analysis provides a comprehensive overview of team performances across different seasons.

## Dataset
The dataset used in this analysis is `nba_games.csv`, which can be downloaded directly from the following link:

[Download NBA Games Dataset](https://drive.usercontent.google.com/download?id=10uPrEUqhe1uxShKiiZciRJViYqhJcre6&export=download&authuser=0)

### Dataset Features
The dataset typically includes the following columns:
- `date`: The date when the game was played.
- `team`: The name of the NBA team.
- `opponent`: The opposing team's name.
- `points`: Points scored by the team.
- `opponent_points`: Points scored by the opponent team.
- Additional columns may include `location`, `win_loss`, etc.

## Features of the Project
- **Data Cleaning**: Sorting the dataset, handling missing values, and preparing it for analysis.
- **Exploratory Data Analysis (EDA)**: Analyzing team performance metrics, including scoring, wins, losses, and trends over time.
- **Visualization**: Plotting key metrics and trends using graphs and charts for better insights.

## Prerequisites
To run the analysis, make sure you have the following Python libraries installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

Install the dependencies using the following command:
```bash
pip install pandas numpy matplotlib seaborn
```

## Usage
1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   ```
2. **Navigate to the project directory**:
   ```bash
   cd nba-performance-analysis
   ```
3. **Download the dataset** and place it in the project directory, or let the notebook access it directly via the provided link.
4. **Open and run the Jupyter Notebook**:
   ```bash
   jupyter notebook nba_performance_analysis.ipynb
   ```
5. **Execute the cells** sequentially to perform the data analysis.

## Results
The analysis will provide insights such as:
- Detailed statistics of NBA teams, including average points scored, win rates, and performance against different opponents.
- Visualizations showing trends in scoring, win/loss ratios, and other key metrics across seasons.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
