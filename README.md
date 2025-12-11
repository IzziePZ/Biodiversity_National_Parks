# Biodiversity in National Parks

## Project Overview

This project analyzes biodiversity data from four national parks to investigate species observations and conservation statuses. The goal is to identify patterns in endangered species, understand which categories are most at risk, and explore observation trends across different parks.

This is a portfolio project based on the Codecademy Data Science course.

## Data Sources

The analysis uses two CSV files:

- **`observations.csv`**: Contains observation counts for various species across four national parks.
- **`species_info.csv`**: Provides information on species categories, scientific names, and conservation statuses.

## Analysis

The Jupyter notebook (`biodiversity.ipynb`) performs the following:

- Data loading and merging
- Exploratory data analysis (EDA) including summary statistics and missing value checks
- Visualization of conservation status distributions, observations by park, and category comparisons
- Identification of top categories for endangered, threatened, and species of concern

Key findings include:
- Yellowstone has the highest number of observations
- Vascular plants dominate observations, followed by birds
- Mammals have the most endangered species, while birds have the most species of concern

## Requirements

To run this project, you'll need:

- Python 3.x
- Jupyter Notebook
- Required libraries:
  - pandas
  - matplotlib
  - seaborn
  - numpy

Install dependencies with:
```
pip install pandas matplotlib seaborn numpy
```

## Usage

1. Clone or download the repository.
2. Ensure the CSV files (`observations.csv` and `species_info.csv`) are in the same directory as the notebook.
3. Open `biodiversity.ipynb` in Jupyter Notebook.
4. Run the cells sequentially to reproduce the analysis.

## Visualizations

The notebook includes several plots:
- Distribution of observations by conservation status
- Observations by park name
- Category vs. conservation status
- Boxplot of observations vs. conservation status
- Observations of categories by park

## Conclusion

The analysis highlights the importance of conservation efforts, particularly for mammals and birds, and underscores the biodiversity richness of national parks like Yellowstone.

## License

This project is for educational purposes. 
