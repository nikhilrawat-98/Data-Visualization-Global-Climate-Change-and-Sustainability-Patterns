# Data Visualization: Global Climate Change and Sustainability Patterns

This project explores global climate change actions and sustainability patterns across different countries and continents over time. The project uses data visualization techniques to highlight how countries have responded to climate change through renewable energy usage, CO2 emissions, and other key environmental metrics. The visualizations are designed to provide actionable insights for policymakers and stakeholders.

## Project Overview

- **Objective**: To analyze and visualize global patterns of climate change actions, focusing on CO2 emissions, renewable energy usage, forest depletion, and natural resource extraction.
- **Key Focus**:
  - Visualizing how climate change actions vary over time.
  - Analyzing the differences in climate-related actions across different countries.
  - Highlighting the economic and social factors influencing the effectiveness of climate actions.
- **Tech Stack**: Python (Pandas, Matplotlib, Seaborn), Choropleth maps, Time Series Analysis

## Dataset

The dataset focuses on various sustainability metrics such as CO2 emissions, renewable energy consumption, natural resource depletion, and forest conservation efforts. Data spans multiple continents and countries, allowing for a comparative analysis of regional and global trends.

### Dataset Features:
- `Country`: The country for which data is collected.
- `CO2 Damage`: The impact of CO2 emissions measured as a percentage of Gross National Income (GNI).
- `Renewable Energy Usage`: Percentage of energy consumption from renewable sources.
- `Natural Resource Depletion`: Measure of resource depletion relative to economic activity.
- `Forest Depletion`: Extent of net forest depletion over time.
- `Internet Usage`: Percentage of the population with internet access, used as a proxy for awareness.

### File Structure:
- **`WorldSustainabilityDataset.csv`**: The raw dataset containing global climate-related metrics.
- **`WorldSustainabilityDataset_Filled.csv`**: Preprocessed dataset with missing values handled.
- **`Code.ipynb`**: Jupyter notebook containing the code for generating visualizations.
- **`Report.pdf`**: Detailed report discussing the design choices, insights, and outcomes of the visualizations.
- **`PPT.pdf`**: Presentation slides summarizing the key insights and findings from the project.
- **`requirements.txt`**: Python dependencies required to run the analysis.

## Analysis Workflow

### 1. Data Preprocessing
- **Handling Missing Data**: Missing values were imputed where necessary, ensuring the dataset is complete for visualization.
- **Normalization**: Data was normalized to account for differences in country size and economic activity, ensuring fair comparisons between nations.

### 2. Visualizations

- **Time Series Line Graphs**: Used to display how sustainability metrics such as CO2 damage and renewable energy usage have changed over time for different continents. These visualizations are color-coded by continent to highlight regional differences.
- **Choropleth Maps**: Show country-level variation in climate change actions, such as CO2 emissions and renewable energy usage. Countries are shaded based on the magnitude of the metric.
- **Comparative Bar Graphs**: Used to illustrate changes in key climate metrics like CO2 emissions and renewable energy usage over two significant time periods (e.g., 2000 vs. 2018).
- **Dual-Axis Line Graphs**: Show the correlation between two different types of data, such as CO2 emissions and renewable energy consumption.

### 3. Key Insights
- **Regional Disparities**: North America and Oceania show consistently higher CO2 damage compared to other regions, while Africa has a rising trend in natural resource depletion.
- **Progress in Renewable Energy**: Countries like Indonesia and India have made significant strides in renewable energy adoption, but these gains are offset by increasing CO2 emissions.
- **Economic and Social Variables**: Wealthier nations with higher internet penetration tend to have more robust climate action initiatives, although this is not a consistent trend globally.

## Usage

The Jupyter notebook demonstrates the following:
1. **Data Preprocessing**: Handling missing values and normalizing data for visualization.
2. **Visualizations**: Creating time series line graphs, choropleth maps, comparative bar charts, and dual-axis graphs to explore the relationships between different sustainability metrics.
3. **Analysis of Trends**: Identifying key insights into how different countries and regions have responded to climate change over time.

## Installation

To run the project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Global-Climate-Change-Visualization.git
    cd Global-Climate-Change-Visualization
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook:
    ```bash
    jupyter notebook
    ```

## Acknowledgements

This project was developed as part of the MSc in Business Analytics at Bayes Business School under the module **Data Visualization**.

## License

MIT License
