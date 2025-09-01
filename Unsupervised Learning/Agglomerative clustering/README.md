# Hierarchical Clustering on Airline Passenger Data ✈️

## 📖 Overview
This project applies **Hierarchical Clustering** on airline passenger data to identify operational patterns, segment airlines/terminals, and provide insights for optimizing efficiency and financial health.  
The project follows the **CRISP-ML(Q)** methodology, ensuring structured delivery from business understanding to deployment.

## 🎯 Objectives
- Segment airlines and terminals using **hierarchical clustering**.
- Improve airline operational efficiency by **10–12%**.
- Achieve a **Silhouette Score ≥ 0.7** as ML success criteria.
- Provide actionable insights for **revenue growth** and **resource optimization**.

## 🛠️ Tech Stack
- **Python**: pandas, numpy, seaborn, matplotlib, scikit-learn, feature-engine  
- **SQL**: MySQL (via SQLAlchemy + PyMySQL)  
- **Visualization**: Seaborn, Matplotlib  
- **Pipeline**: Scikit-learn `Pipeline` & `ColumnTransformer`  

## 📂 Project Structure
```
├── data
│   └── AirTraffic_Passenger_Statistics.csv
├── notebooks
│   └── Hierarchical_Clustering.ipynb
├── reports
│   ├── Assignement_3.html
│   └── Project_Charter.md
├── images
│   └── plots.png
├── README.md
├── requirements.txt
└── LICENSE
```

## 📊 Key Insights
- **United Airlines** dominates passenger traffic, followed by American, SkyWest, and Delta.  
- Passenger traffic is **seasonal** with peaks in July–August and December.  
- **Terminal allocation** is uneven → potential for optimization.  
- Passenger demand grew consistently till 2015 (2016 dip due to incomplete data).  

## 📸 Sample Visualizations
- Dendrogram (Hierarchical Clustering)
- <img width="555" height="441" alt="image" src="https://github.com/user-attachments/assets/67501c15-f9ca-4a2e-944b-4ff9a442e2d1" />

- Top Airlines by Passenger Count (Pie Chart)
- <img width="613" height="409" alt="image" src="https://github.com/user-attachments/assets/cc54be94-5370-4b01-976d-7dacc6f7de3a" />

- Seasonal Trends (Bar Plot)
- <img width="554" height="453" alt="image" src="https://github.com/user-attachments/assets/d549e7ab-115e-4404-b5d3-698e9131e059" />



## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hierarchical-clustering-airline.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook notebooks/Hierarchical_Clustering.ipynb
   ```

## 📌 Future Improvements
- Add **silhouette plots** and **cluster heatmaps**.  
- Deploy clustering results into a **dashboard** (Power BI / Streamlit).  
- Automate pipeline with Airflow or MLflow for production use.  

## 📝 Author
**Anshuman Acharya**  
🔗 [LinkedIn](https://linkedin.com/in/anshuman-a-acharya) | [Portfolio](https://anshux01.github.io/Portfolio/)  
