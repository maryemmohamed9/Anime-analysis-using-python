# Anime-analysis-using-python
This project involves analyzing an anime dataset to explore various attributes such as scores, popularity, genres, and member counts. Through data cleaning, transformation, analysis, and visualization
## Dataset
The dataset used in this analysis includes 1000 rows and 21 columns with information about different anime titles.
## Data Cleaning and Preparation
**Dropped Columns**:
- Removed the *Demographics* column as it contained a significant amount of missing data and was not relevant to our analysis.

**Handling Null Values**:
- **English Column**: Filled null values in the *English* with corresponding values from the *Synonyms* column.
- **Synonyms Column**: Filled null values in the *Synonyms* with corresponding values from the *English* column.
- **Japanese Column**: For remaining null values in both the *English* and *Synonyms* columns, filled them with corresponding values from *Japanese* column.
- **Premiered and Broadcast Columns**: Filled null values in the *Premiered* and *Broadcast* columns with corresponding values from the *Start_Aired* column.
  
**Date Parsing**
- Handled date parsing issues in the *Aired* column to extract *Start_Aired* and *End_Aired*.
- Extracted year information from the *Start_Aired* column to create a new *Year* column for analysis
  
**Data Type Conversion**
- Ensured that numerical Colums (like *Score* and *Members*) were of the correct data type for analysis.
  
## Analysis and Visualizations

**The analysis includes**:
- Top 10 anime by popularity visualized with a bar plot.
- Distribution of anime scores visualized with a box plot.
- Yearwise member counts aggregated and visualized for the top 7 years.
- Top 3 anime types visualized with a pie chart.
- Top 5 genres visualized with a bar plot.
- Top 5 studios visualized with a bar plot.
- Top 4 Sources visualized with a bie plot.
  
**Technologies Used**:
- Python
- Pandas
- Matplotlib
  
**Contributing**:
Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.
