# Visual Analytics Project: University Rankings

Welcome to the Visual Analytics Project for University Rankings! This project is part of a data visualization and analytics course and aims to explore, analyze, and visualize global university rankings using Python and interactive visualization libraries.

---

## Table of Contents
- [About the Project](#about-the-project)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

---

## About the Project
The goal of this project is to analyze university rankings data and present it through interactive dashboards and visualizations. By leveraging Python and libraries such as Pandas, Plotly, and Dash, we provide insights into factors affecting university rankings and trends over time.

---

## Features
- Data preprocessing and cleaning for university ranking datasets.
- Interactive dashboards for filtering and exploring rankings data.
- Visualizations of:
  - Top-ranked universities by country and region.
  - Trends in rankings over time.
  - Correlation between ranking factors and overall score.
- Exportable insights and visuals.

---

## Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - Pandas (Data manipulation)
  - NumPy (Numerical computation)
  - Plotly (Interactive visualizations)
  - Dash (Web-based dashboards)
  - Seaborn/Matplotlib (Static visualizations)
- **Jupyter Notebooks** for prototyping and analysis.

---

## Dataset
The project uses publicly available university rankings datasets, such as:
- QS World University Rankings
- Times Higher Education Rankings
- Academic Ranking of World Universities (ARWU)

**Note:** The dataset is preprocessed and included in the repository under the `data/` folder. Ensure proper attribution when using the dataset for external purposes.

---

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MarawanHassaan/visual-analytics-project-university-rankings.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd visual-analytics-project-university-rankings
   ```

3. **Set up a virtual environment (optional):**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # For Windows: venv\Scripts\activate
   ```

4. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage

1. **Run the Dash application:**
   ```bash
   python app.py
   ```

2. Open your web browser and go to `http://127.0.0.1:8050/` to interact with the dashboards.

---

## Project Structure
```
visual-analytics-project-university-rankings/
├── app.py                  # Main application script
├── data/                   # Folder containing datasets
├── notebooks/              # Jupyter notebooks for exploratory analysis
├── static/                 # Static assets (CSS, images, etc.)
├── templates/              # HTML templates (if needed)
├── requirements.txt        # Dependencies
└── README.md               # Project documentation (this file)
```

