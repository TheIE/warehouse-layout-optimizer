# 🏭 Warehouse Layout Optimization Model

## 📌 Project Overview
An Integer Linear Programming (ILP) model designed to optimize the facility layout formy senior design projects warehouse. This project mathematically determines the most efficient storage locations for thousands of individual parts to minimize travel distance, increase picking efficiency, and ensure safe routing for heavy machinery.

## 🛠️ Tech Stack & Tools
* **Language & Environment:** Python / JupyterLab
* **Mathematical Modeling:** PuLP (Integer Linear Programming)
* **Data Manipulation:** Pandas, NumPy
* **Data Storage & Tracking:** Excel, SharePoint

## ⚙️ Methodology & Process
1. **Data Tracking System:** Engineered a scalable database system using Excel and SharePoint to accurately catalog and track thousands of warehouse parts by category and frequency of use.
2. **Constraint Definition:** Defined physical and operational constraints, including prioritizing wide-aisle accessibility to allow forklifts to maneuver freely and safely.
3. **Mathematical Modeling:** Built an ILP model using the Python `PuLP` library to assign optimal storage locations based on minimizing the objective function (total travel distance).
4. **Iterative Testing:** Ran the model through JupyterLab, tweaking constraints to balance raw efficiency with real-world accessibility requirements.

## 📈 Key Findings & Business Impact
* **Efficiency Gain:** Achieved a **6% baseline improvement** in layout efficiency strictly through optimized part placement.
* **Safety & Accessibility:** Successfully routed heavy machinery paths, drastically improving forklift maneuverability without sacrificing storage capacity (a metric that further improves operational time beyond the baseline 6%).
<img width="523" height="137" alt="image" src="https://github.com/user-attachments/assets/2ce5a8e8-7a81-40b4-a9c6-4c1a7fba77aa" />

## 🚀 How to Run the Code
1. Clone this repository: `git clone https://github.com/yourusername/warehouse-optimization.git`
2. Install the required dependencies: `pip install pulp pandas numpy`
3. Launch `JupyterLab` or Jupyter Notebook to view and run the `layout_optimizer.ipynb` file.
