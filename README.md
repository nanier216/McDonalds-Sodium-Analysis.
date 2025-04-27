# McDonald's Nutritional Analysis

This project performs an in-depth analysis of McDonald's menu items, focusing on sodium content and other nutritional aspects like protein, total fat, and sugar. The analysis is based on a dataset containing nutritional information for a variety of McDonald's products.

## Files

- **mcdonals.db**: SQLite database containing detailed nutritional information about McDonald's menu items.
- **menu.csv**: CSV file containing the raw data about the menu items (including nutritional data such as sodium, protein, fat, and sugar).
- **analysis/mcdonalds_sodium_analysis.ipynb**: Jupyter notebook that contains the full analysis of sodium content in McDonald's menu items. It includes data cleaning, visualizations, and insights.
- **images/jointplot_protein_totalfat.png**: PNG file showing a joint plot visualizing the relationship between protein and total fat content in McDonald's menu items.
- **images/boxplot_sugar.png**: PNG file showing a box plot of the sugar content across different McDonald's menu categories.
- **images/swarmplot_sodium.png**: PNG file showing a swarm plot of sodium content across McDonald's menu categories.

## Project Overview

This project explores various aspects of the nutritional data of McDonald's menu items, with a particular focus on sodium content. The analysis includes data cleaning, statistical exploration, and multiple visualizations that help highlight patterns, trends, and outliers.

### Key Insights

- **Sodium Content**: The analysis explores the sodium content in McDonald's menu items, focusing on the variation and categories with the highest sodium values. For instance, "Chicken McNuggets (40 piece)" is identified as one of the highest contributors to sodium intake.
- **Protein and Fat**: Using a joint plot, the relationship between protein and total fat in the items is examined to understand the nutritional balance.
- **Sugar Content**: A box plot helps identify how the sugar content varies across different categories of McDonald's menu items.

## Requirements

To run the Jupyter notebook and replicate the analysis on your own machine, you will need:

- Python 3.x
- pandas
- seaborn
- matplotlib
- sqlite3 (for interacting with the `mcdonals.db` database)

You can install the necessary dependencies using pip:

```bash
pip install pandas seaborn matplotlib
```

## How to Run the Analysis

1. Clone this repository or download the project files.
2. Open the `mcdonalds_sodium_analysis.ipynb` Jupyter notebook.
3. Ensure that the `menu.csv` file and `mcdonals.db` are in the same directory as the notebook.
4. Run the cells in the notebook to perform the analysis and generate visualizations.

## Visualizations

The following visualizations are included in the project:

- **Swarm Plot of Sodium Content**: Displays the sodium content across different menu categories.
- **Joint Plot of Protein vs. Total Fat**: Shows the correlation between protein and total fat content.
- **Box Plot of Sugar Content**: Illustrates the distribution of sugar content across various menu categories.

## Conclusion

This project provides a comprehensive look at the nutritional content of McDonald's menu items. By analyzing key nutrients such as sodium, sugar, protein, and fat, we can better understand the nutritional quality of McDonald's offerings. This analysis can help consumers make informed decisions about their food choices.

---

Feel free to open an issue or submit a pull request if you have suggestions or improvements to this project.
