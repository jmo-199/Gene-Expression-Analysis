# Gene-Expression-Analysis
Here is the updated README that includes the mention of the bar chart and histogram as per your request:

---

# Gene Expression Analysis (Assignment 3)

## Name: [Your Name Here]  
## Programming Language: Python v3.x  
## Date: [Date of Completion]

## Description:

This repository is designed to perform an exploratory data analysis (EDA) on gene expression data to identify differences between tumor and normal samples. The analysis includes visualizations like heatmaps, clustermaps, bar charts, and histograms, along with statistical computation of fold changes in gene expression. Key findings such as gene expression differences and chromosome-level insights are presented.

### Required files:

- **Gene_Expression_Data.xlsx**: Contains the gene expression data for all samples.
- **Gene_Information.csv**: Provides additional metadata for the genes being analyzed.
- **Sample_Information.tsv**: Contains metadata related to the samples in the dataset.

### Required packages:

- `pandas`: Data manipulation and analysis.
- `numpy`: Numerical computations and array manipulation
- `matplotlib`, `seaborn`: For visualizations such as heatmaps, bar charts, and histograms.
- `scipy`: For clustering in visualizations.

### Execution:

1. Clone the repository or download the notebook and data files.
2. Install the necessary Python libraries using the following command:
    ```sh
    pip install pandas matplotlib seaborn scipy
    ```
3. Ensure the required files are in the same directory as the notebook.
4. Open the notebook in Jupyter and execute the cells in the following order:
    - Preprocess the data and load the required files.
    - Perform data analysis (heatmap, clustermap, bar chart, histogram, and fold change calculations).
    - Generate results and visualizations.
5. Once execution is complete, review the visualizations and output data for insights.

### Output files:

- **Heatmaps**: Generated to display gene expression across samples.
- **Clustermap**: Shows hierarchical clustering of gene expression.
- **Bar Chart**: Visualizes the comparison of gene expression levels across different categories (e.g., tumor vs. normal).
- **Histogram**: Displays the distribution of gene expression levels.
- **Fold Change Data**: Results showing the fold change for key genes such as REG1B and KRT80.

---
