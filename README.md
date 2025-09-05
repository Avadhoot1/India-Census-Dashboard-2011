## 📊 India Census Dashboard 2011

An interactive dashboard built with Python, Streamlit, and Plotly to analyze and visualize India’s Census 2011 data.
The dashboard helps users explore literacy, gender ratio, education statistics, and other demographic insights at both state and district levels through an interactive map.

## 📝 Problem Statement

Census data is large, complex, and difficult to interpret for policymakers and researchers.
Traditional tables fail to highlight regional variations in literacy, gender ratio, and education.
This project solves the problem by creating a Streamlit-based interactive dashboard, allowing users to explore trends, compare regions, and extract insights quickly.

## 🚀 Features

🌍 Interactive map-based visualization of census data (district-level)

🔎 Select primary and secondary parameters to explore correlations

📊 View data for Overall India or filter by individual states

🖱️ District-level insights with hover tooltips

💾 Download filtered datasets as CSV

⚡ User-friendly dashboard built with Streamlit

## 🛠️ Tech Stack

Python

Pandas, NumPy — Data cleaning & preprocessing

Plotly — Interactive map and visualizations

Streamlit — Web application framework

## 📊 Dataset

The project uses India Census 2011 data with the following columns:

State

District

Latitude, Longitude

Population, Literacy Rate, Male/Female counts, Education stats, etc.


## ⚡ Installation & Usage

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/<your-username>/India-Census-Dashboard-2011.git
cd India-Census-Dashboard-2011
```

### 2️⃣ Create Virtual Environment (optional but recommended)

```bash
python -m venv venv
# Activate
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the App

```bash
streamlit run app.py
```

The app will open in your browser at `http://localhost:8501/`.

---

## 🌍 Deployment

You can easily deploy the app on **[Streamlit Cloud](https://streamlit.io/cloud)**:

1. Push this repo to GitHub.
2. Go to Streamlit Cloud → New App → Connect repo.
3. Set `app.py` as the main file.
4. (Optional) Add a **Mapbox Token** in Streamlit **Secrets** if you want custom map styles.

---

## 📌 Example Usage

* Select **State = Maharashtra** → explore literacy vs. population
* Select **Overall India** → visualize gender ratio vs. literacy across all districts

## ⚡ Challenges Faced & Solutions

Data Complexity & Size

    Challenge: Large dataset with unstructured values made analysis slow.

    Solution: Cleaned, preprocessed, and optimized using Pandas & NumPy.

Regional Visualization

    Challenge: Hard to represent literacy and gender data clearly at state level.

    Solution: Used Plotly maps with hover tooltips for state & district insights.

User Accessibility

    Challenge: Raw tables were not interpretable for non-technical users.

    Solution: Designed Streamlit dashboard with KPIs & filters for easy exploration.


## 🔮 Future Enhancements

* Choropleth maps with state-level GeoJSON
* Advanced filters (population range, literacy rate thresholds)
* Time-series comparisons with multiple census years


---

👨‍💻 **Author:** Avadhoot Wamane

📧 Email: avadhootwamane461@gmail.com

LinkedIn: https://www.linkedin.com/in/avadhoot-wamane/
