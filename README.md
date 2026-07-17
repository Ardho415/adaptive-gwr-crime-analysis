# 📍 Spatial Crime Analysis using Geographically Weighted Regression (GWR)

This project analyzes regional crime patterns in **Central Java** and **East Java** using **Geographically Weighted Regression (GWR)** with an **Adaptive Gaussian Kernel**. Unlike global regression models, GWR captures spatial heterogeneity by estimating local regression coefficients for each geographic location.

The notebook compares Ordinary Least Squares (OLS) and GWR models to demonstrate the advantages of local spatial modeling in explaining crime distribution.

---

## 🚀 Features

- Spatial crime data analysis
- Exploratory spatial data visualization
- Local Indicators of Spatial Association (LISA) analysis
- Ordinary Least Squares (OLS) regression
- Geographically Weighted Regression (GWR)
- Adaptive Gaussian Kernel selection
- Local parameter estimation
- Model comparison between OLS and GWR
- Visualization of spatial regression results

---

## 📂 Project Structure

```
.
├── Efficiency_of_GWR_Adaptive_Gaussian_Kernel_for_Crime_Analysis_in_Central_and_East_Java.ipynb
├── dataset/
├── figures/
└── README.md
```

---

## 🧠 Methodology

The project follows these main steps:

1. Data Collection
   - Crime statistics
   - Socio-economic indicators
   - Geographic coordinates

2. Data Preprocessing
   - Cleaning and normalization
   - Spatial data preparation

3. Exploratory Spatial Analysis
   - Distribution visualization
   - Spatial relationship analysis

4. Local Indicators of Spatial Association (LISA)
   - Identify spatial clusters
   - Detect hotspot and coldspot regions

5. Ordinary Least Squares (OLS)
   - Build a global regression model
   - Evaluate baseline performance

6. Geographically Weighted Regression (GWR)
   - Adaptive Gaussian Kernel
   - Bandwidth selection
   - Local coefficient estimation

7. Model Evaluation
   - Compare OLS and GWR
   - Interpret spatially varying relationships

---

## 🛠 Technologies

- Python
- Pandas
- NumPy
- GeoPandas
- Matplotlib
- Seaborn
- MGWR / PySAL
- SciPy
- Jupyter Notebook

---

## 📊 Analysis Workflow

```
Crime Dataset
        │
        ▼
Data Preprocessing
        │
        ▼
Exploratory Spatial Analysis
        │
        ▼
LISA Analysis
        │
        ├────────► OLS Regression
        │
        └────────► GWR
                     │
                     ▼
Adaptive Gaussian Kernel
                     │
                     ▼
Local Parameter Estimation
                     │
                     ▼
Model Comparison
```

---

## 📈 Results

The notebook evaluates the effectiveness of Geographically Weighted Regression by comparing it with the traditional OLS model. The analysis highlights how GWR captures local spatial variations that cannot be explained by a single global regression equation.

Key outputs include:

- Spatial distribution of crime
- LISA cluster maps
- OLS regression results
- GWR local coefficients
- Model performance comparison
- Spatial interpretation of influential variables

---

## 🎯 Applications

This project can be applied to:

- Crime hotspot analysis
- Urban planning
- Public safety policy
- Spatial decision support systems
- Regional socio-economic studies
- Geographic data science research

---

## 💡 Future Improvements

- Incorporate temporal crime trends
- Compare multiple kernel functions
- Build an interactive GIS dashboard
- Extend analysis to all Indonesian provinces
- Integrate machine learning with spatial regression

---

## 👥 Authors

- Ardho Masiech Firdaus
- Team Project
