# Data_visualization-techniques
# Lung Cancer Data Visualization

This repository demonstrates various visualization techniques to analyze and interpret a lung cancer dataset. The project utilizes Python libraries such as Matplotlib, Seaborn, and Plotly to create insightful visualizations, providing a better understanding of the data.

## Dataset

The dataset, `survey lung cancer.csv`, contains information about patients, including factors like age, smoking habits, and lung cancer status.

### Key Columns in the Dataset:
- **AGE**: The age of the patients.
- **SMOKING**: A numerical value indicating the smoking level.
- **LUNG_CANCER**: Indicates if the patient has lung cancer (`YES` or `NO`).

## Features

The project includes the following visualizations:
1. **Line Chart**: Displays the relationship between age and lung cancer occurrences.
2. **Scatter Plot**: Shows the distribution of smoking levels against age, with lung cancer status as a hue.
3. **Heatmap**: Highlights correlations between numerical variables in the dataset.
4. **3D Scatter Plot**: Visualizes the interaction between age, smoking, and lung cancer status in three dimensions.

## How to Run

### Prerequisites:
- Python 3.7+
- Jupyter Notebook or Google Colab
- Required libraries: `matplotlib`, `seaborn`, `plotly`, `pandas`, `numpy`

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Lung-Cancer-Data-Visualization.git
  ### **Steps for Uploading to GitHub**
1. **Create a GitHub Repository:**
   - Go to [GitHub](https://github.com/).
   - Click on "New" to create a repository.
   - Name it `Lung-Cancer-Data-Visualization`.
   - Add a description (e.g., "Visualizing lung cancer data using Python libraries").
   - Initialize with a `.gitignore` for Python (optional).

2. **Upload Files:**
   - Include the following files:
     - `visualization.ipynb`: Your notebook file.
     - `survey lung cancer.csv`: The dataset.
     - `README.md`: The project documentation.

3. **Push Files from Local Machine (Optional):**
   ```bash
   git init
   git add .
   git commit -m "Initial commit for Lung Cancer Data Visualization"
   git branch -M main
   git remote add origin https://github.com/yourusername/Lung-Cancer-Data-Visualization.git
   git push -u origin main
