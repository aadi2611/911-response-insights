
# 🚨 911 Calls EDA & ML Project

This project explores 911 emergency call data from Montgomery County, PA. It applies **exploratory data analysis (EDA)**, **machine learning**, **clustering**, and **interactive visualizations** to uncover insights into emergency response trends.

---

## 📌 Project Highlights

- 🔍 Feature engineering from timestamp, location, and type of call
- 🧠 Classification model to predict emergency type (EMS, Fire, Traffic)
- 📍 Clustering using KMeans to detect high-risk geographic zones
- 📊 Interactive Plotly visualizations for data storytelling

---

## 📁 Dataset Info

The dataset contains real 911 call records with:
- `lat`, `lng`: Coordinates of the call
- `desc`: Call description
- `zip`, `twp`, `addr`: Location details
- `title`: Call type, e.g., EMS: BACK PAINS
- `timeStamp`: Date and time of call

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Plotly (for interactive plots)
- Jupyter Notebook

---

## 📈 Machine Learning

A Random Forest Classifier is used to predict the type of emergency call based on:
- Time of call (hour, day, month)
- Zip code
- Township (encoded)

> Achieves strong performance and provides insights into emergency response patterns.

---

## 📍 Clustering

We apply **KMeans Clustering** on latitude and longitude to:
- Identify 5 geographical clusters
- Visualize hotspots of emergency activity

---

## 🌐 Interactive Visuals

Using **Plotly**, we build:
- Interactive scatter plots of emergency type by hour and zip code
- Ready for dashboard integration (e.g., Streamlit or Dash)

---

## ▶️ Getting Started

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/911-calls-eda-ml.git
   ```
2. Install requirements:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch the notebook:
   ```
   jupyter notebook notebook/911_Calls_Final_CV_Project.ipynb
   ```

---

## 📊 File Structure

```
📦911-calls-eda-ml
 ┣ 📄 README.md
 ┣ 📄 requirements.txt
 ┗ 📁 notebook/
     ┗ 📄 911_Calls_Final_CV_Project.ipynb
```

---

## ✍️ Author

**Your Name**  
Data Science Enthusiast  
[LinkedIn](#) | [GitHub](#)

---

> A data science capstone demonstrating practical EDA, machine learning, and interactive storytelling using real-world data.

