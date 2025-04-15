# Real Madrid: Balancing Defence and Attack

This project is an exploratory data analysis of Real Madrid player statistics, aiming to assess the balance between offensive and defensive contributions within the team.

## Objective

The goal of this analysis is to examine whether Real Madrid’s current squad maintains an effective balance between attacking output and defensive responsibility. The analysis focuses on:
- Comparing tackles, interceptions, and defensive metrics among attacking players.
- Evaluating goal contributions, passing efficiency, and creative output across different positions.
- Visualizing insights through clear and informative charts, including radar plots.

## Data

The dataset is provided in an Excel file named:  
`Real_Madrid_players_stats2025.xlsx`

It includes the following information:
- Appearances, minutes played
- Goals, assists, and goal involvement
- Tackles, interceptions, duels won
- Passing accuracy, key passes, expected assists (xA)

## Methodology

1. **Data Preparation**  
   - Loaded the dataset using pandas.
   - Handled missing values and standardized player positions.

2. **Feature Engineering**  
   - Grouped players by roles (attackers, midfielders, defenders).
   - Calculated per-90 metrics and other performance indicators.

3. **Visualization**  
   - Used bar and scatter plots for comparison.
   - Created radar charts to visually represent player profiles.

4. **Tools and Libraries**  
   - Data manipulation: `pandas`, `numpy`
   - Visualization: `matplotlib`, `seaborn`
   - Preprocessing and statistics: `scikit-learn`, `statsmodels`, `scipy`

## Files

- `Real_Madrid_Balance_Defence_and_Attack.ipynb`: The main notebook containing code, analysis, and visual output.

## Output

The project includes visual examples such as radar charts to represent player performance from both attacking and defensive perspectives.

## Conclusion

This analysis provides a foundation for understanding how Real Madrid players contribute to both ends of the pitch. The insights can support decision-making by technical staff regarding squad improvements and tactical adjustments.
