# Crime Trends in New Zealand: An Analysis of Demographics and Offense Types

## Description
This project analyzes crime trends in New Zealand using data from the Recorded Crime Offenders Statistics (RCOS) dataset. It examines how demographic factors such as age, gender, and ethnicity influence criminal activities from July 2022 to July 2024. The study aims to identify common offense types and demographic groups involved in criminal proceedings, providing actionable insights to inform crime prevention strategies and interventions.

---

## Tools and Libraries Used

### Tools
- **RStudio**: IDE for coding and analysis in R.
- **Quarto**: For generating a PDF report and structuring documentation.

### Libraries
- **ggplot2**: For creating visualizations like bar charts, boxplots, and stacked charts.
- **dplyr**: For data manipulation, grouping, and summarizing.
- **knitr**: For formatting tables and generating reports.
- **RColorBrewer**: For applying color palettes to enhance visualizations.

---

## Main Functions Used

### Data Preparation
- **`read.csv()`**: Load the dataset.
- **`as.factor()`**: Convert categorical variables for proper analysis.

### Data Analysis
- **`group_by()`**, **`summarise()`**: Aggregate data by demographic groups and offense types.
- **`slice_max()`**: Select the most common offenses for each ethnic group.
- **`arrange()`**: Sort data for analysis and visualization.

### Visualization
- **`geom_bar()`**: Create bar charts to display summarized data.
- **`geom_boxplot()`**: Generate boxplots to visualize data spread and outliers.
- **`coord_flip()`**: Flip axes for horizontal charts.
- **`scale_fill_brewer()`**: Apply color palettes for better visuals.

---

## Tasks Completed
- **Data Preparation**: Loaded and cleaned the dataset, ensuring proper handling of categorical variables.
- **Summarization**:
  - Total proceedings by gender, ethnicity, and offense types.
  - Most common offenses for each ethnic group.
- **Visualization**:
  - Highlighted patterns in age, gender, and ethnicity involvement in crimes.
- **Statistical Analysis**:
  - Generated descriptive statistics including mean, median, and variance.
- **Documentation**:
  - Compiled findings into a Quarto document with graphs and tables.

---

## Output

### Visualizations
- **Bar Charts**:
  - Total proceedings by offense type.
  - Proceedings by gender, ethnicity, and age groups.
- **Stacked Charts**:
  - Most common crimes by ethnic group.
- **Boxplots**:
  - Spread of proceedings by ethnicity.

### Descriptive Statistics
- Summary statistics for the number of proceedings, including:
  - Mean
  - Median
  - Variance


