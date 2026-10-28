#  Blinkit Retail Analytics Dashboard

An interactive retail analytics project built with Python, Pandas, NumPy, Matplotlib, Seaborn, and Streamlit. The project demonstrates a workflow for generating sample retail data, cleaning it, exploring sales patterns, and viewing insights through an interactive dashboard.

 **Data note:** This is a learning project using synthetic Blinkit-style retail data. It is not official Blinkit company data.

##  Features

- Generate synthetic raw retail data.
- Clean and organise data with Python.
- Switch between raw and cleaned datasets.
- Filter by item type, outlet type, outlet location tier, and fat content.
- View key metrics:
  - Total sales
  - Number of records
  - Average sales
  - Average item MRP
- Explore visualisations:
  - Sales by item type
  - Average sales by outlet
  - Sales distribution
  - Sales by location
  - Item MRP vs. sales
  - Numeric-feature correlation heatmap
  - Sales by fat content
  - Sales by outlet establishment year
  - Record count by item type
  - Sales by discount
  - Outlet type and location heatmap
  - Sales share by outlet
- Review missing values, duplicate rows, and descriptive statistics.
- Download filtered data as a CSV file.

##  Tech Stack

- **Language:** Python
- **Data processing:** Pandas, NumPy
- **Visualisation:** Matplotlib, Seaborn
- **Dashboard:** Streamlit

##  Project Structure

```text
Blinkit-Data-Cleaning/
├── data/
│   ├── blinkit_raw_data.csv
│   └── blinkit_clean_data.csv
├── 1_generate_data.py
├── 2_clean_data.py
├── 4_streamlit_dashboard.py
├── requirements.txt
├── README.md
└── .gitignore
```

*The files shown above should match the files in your repository. The `data/` CSV files may be generated when you run the project, depending on your scripts.*

##  Setup and Installation

### 1. Clone the repository

Replace `YOUR-USERNAME` with your GitHub username:

```bash
git clone https://github.com/YOUR-USERNAME/Blinkit-Data-Cleaning.git
cd Blinkit-Data-Cleaning
```

### 2. (Recommended) Create a virtual environment

**Windows:**

```bash
python -m venv .venv
.venv\Scripts\activate
```

**macOS/Linux:**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

Create a `requirements.txt` file containing:

```text
pandas
numpy
streamlit
matplotlib
seaborn
```

Then run:

```bash
pip install -r requirements.txt
```

## ▶ Run the Project

Run these commands from the project root, in order:

```bash
python 1_generate_data.py
python 2_clean_data.py
streamlit run 4_streamlit_dashboard.py
```

The dashboard should open in your browser. If your scripts already generate or clean the data automatically, follow the instructions in those scripts and use the dashboard's sidebar controls.

##  How to Use the Dashboard

1. Choose **Cleaned data** or **Raw data** in the sidebar.
2. Use the filters to select item type, outlet type, location tier, and fat content.
3. Review the sales KPI cards and quick insight.
4. Select a chart from the visualisation dropdown.
5. Expand **Data quality and summary** to inspect missing values, duplicates, and descriptive statistics.
6. Download the filtered records as a CSV when needed.

##  Project Goals

- Practise a complete data preparation and visualisation workflow.
- Explore retail sales performance across product and outlet categories.
- Build an interactive dashboard for exploratory data analysis.
- Present data analytics work in a GitHub portfolio.

##  Possible Improvements

- Add a date-range filter if the dataset contains a suitable date column.
- Add automated data-quality tests.
- Add a dashboard screenshot to this README.
- Deploy the dashboard with Streamlit Community Cloud.
- Add a findings section after validating insights against the generated dataset.

##  Deployment

To publish the dashboard, push the project to GitHub and deploy the repository through [Streamlit Community Cloud](https://share.streamlit.io/). Select `4_streamlit_dashboard.py` as the app's main file.

Ensure all required scripts and data files are available in the deployed repository. Do not commit credentials, private data, or unnecessary large files.

##  Author

**Dishant Rana**  
Aspiring Data Analyst | Python | SQL | Excel | Power BI

- GitHub: [dishant1305-star](https://github.com/dishant1305-star)

---

If you find this project useful, consider giving the repository a ⭐ on GitHub.
