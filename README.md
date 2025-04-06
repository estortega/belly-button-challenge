# Belly Button Biodiversity Dashboard

## Project Overview

This project is an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels.
The dashboard allows users to:

- View demographic information about individuals.
 
- Display a bar chart of the top 10 most common Operational Taxonomic Units (OTUs) found in the sample.

- Visualize a bubble chart showing the frequency of each OTU in the sample.

## Technologies Used

- **HTML**: Structure of the dashboard.
- **CSS**: Styling (Bootstrap 5 for responsive design).
- **JavaScript**: Data handling and rendering (D3.js for interactivity, Plotly.js for charts).
- **D3.js**: Used to fetch and manipulate the dataset, create dropdowns, and append metadata.
- **Plotly.js**: Used to generate interactive charts (bar and bubble charts).

## Installation

To run this project locally:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/estortega/belly-button-challenge.git
Navigate into the project directory:
cd belly-button-challenge
Open the index.html file in your browser:
You can simply double-click on index.html to open it, or open it through your preferred IDE (e.g., VS Code, Sublime Text).

## Usage

1. Dashboard Overview:
   
  - When the page loads, the dashboard will display the demographic information for the first sample in the dataset.

  - The Top 10 OTUs bar chart and the OTU Frequency bubble chart will be rendered using Plotly.

2. Interactivity:

  - The dropdown (#selDataset) allows users to select a sample by ID.

  - Once a selection is made, the demographic info, bar chart, and bubble chart will update dynamically.

3. Features:

  - Demographic Info: Displays basic information about the selected individual.

  - Top 10 OTUs Bar Chart: A horizontal bar chart showing the top 10 most common OTUs.
 
  - Bubble Chart: A bubble chart that visualizes the frequency of OTUs.

## Acknowledgements

- The dataset used in this project is provided by the University of California, Irvine.

- This project was created as part of the Data Science Bootcamp at [University or Organization Name].

- Bootstrap 5 and Plotly.js were used for responsive design and interactive charts.
