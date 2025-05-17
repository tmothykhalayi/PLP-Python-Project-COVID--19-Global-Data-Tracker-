# COVID-19 Global Data Tracker

This project provides an interactive and visual analysis of global COVID-19 trends. It tracks cases, deaths, recoveries, and vaccinations across countries, offering insights on the pandemic's progression.

---

## 🛠️ Project Setup

### Prerequisites:
Make sure you have Python installed on your system. It's recommended to use a virtual environment for the project.

### 1. Clone the Repository (or Download Files)

```bash
git clone <repo_url> covid_global_data_tracker
cd covid_global_data_tracker
````

Alternatively, download the files manually.

### 2. Install Dependencies

Use the `requirements.txt` file to install the necessary Python packages.

```bash
pip install -r requirements.txt
```

### 3. Data Sources

The raw data is obtained from the following sources:

* **Our World in Data**: [GitHub](https://github.com/owid/covid-19-data/tree/master/public/data)
* **Johns Hopkins University**: [GitHub Repository](https://github.com/CSSEGISandData/COVID-19)

The raw dataset (`owid-covid-data.csv`) is loaded and cleaned to create the `cleaned_covid_data.csv` file for analysis.

---

## 📊 How to Use

### 1. Running the Jupyter Notebook

1. Open **`main.ipynb`** in VS Code or JupyterLab.
2. Run the cells to load, clean, and analyze the data.
3. Visualize the trends and insights, including:

   * Total cases over time
   * Death rate by country
   * Vaccination progress by country

### 2. Running the Python Script

You can also run the **`covid_tracker.py`** Python script in VS Code.

```bash
python covid_tracker.py
```

This script runs the same analysis as the notebook and saves the cleaned data and visualizations.

---

## 📂 Project Structure

```
covid_global_data_tracker/
│
├── 📄 main.ipynb                         # Jupyter Notebook with interactive analysis
├── 📄 README.md                          # Project overview and instructions
├── 📄 requirements.txt                   # Required Python packages
│
├── 📁 plots/
│   ├── 📄 Total Cases.png                # Example saved charts (total cases)
│   ├── 📄 Dialy Cases.png                # Example saved charts (new cases)
│   └── 📄 Case Rate.png            # Example saved charts (vaccination pie chart)
│


## 🎨 Visualizations

The project generates the following visualizations:

* **Time Series**: Track COVID-19 cases, deaths, and vaccination progress over time.
* **Comparison Charts**: Compare metrics across countries (e.g., total cases, vaccination rates).

---

## 📑 Key Insights

This project generates key insights from the COVID-19 data, such as:

* **Highest cases**: The country with the highest total cases.
* **Average death rate**: The global average case fatality rate.
* **Vaccination progress**: The highest vaccination rate in a country as of the latest data.

---

# PLP-Python-Project-COVID--19-Global-Data-Tracker-
