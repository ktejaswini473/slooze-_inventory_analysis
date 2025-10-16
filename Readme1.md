SLOOZE TAKE-HOME CHALLENGE — DATA SCIENCE & ANALYTICS


==========================================================
PROJECT OVERVIEW
==========================================================
This project analyzes sales, purchases, and inventory data
for a retail wine & spirits company operating across multiple
locations. The goal is to use data-driven insights to optimize
inventory control, forecast demand, and assess supplier
performance to reduce inefficiencies and financial loss.

----------------------------------------------------------
 OBJECTIVES
----------------------------------------------------------
• Inventory Optimization → Determine ideal stock levels.
• Sales & Purchase Insights → Identify trends & top products.
• Process Improvement → Optimize procurement cycles.

==========================================================
 INCLUDED FILES
==========================================================
• Slooze_Take_Home_Analysis_Deepak.ipynb   → Main Jupyter Notebook
• README.txt                               → Instructions to run

==========================================================
HOW TO RUN
==========================================================
Step 1: Install dependencies  
---------------------------------
Use a terminal or Anaconda prompt:

    pip install pandas numpy matplotlib seaborn scipy statsmodels prophet xgboost

Step 2: Launch Jupyter Notebook  
---------------------------------
Inside this project folder, run:

    jupyter notebook Slooze_Take_Home_Analysis_Deepak.ipynb

Step 3: Execute all cells  
---------------------------------
Run each cell sequentially (Shift + Enter).  
All analysis outputs, charts, and insights will appear inline.

==========================================================
ANALYSIS PERFORMED
==========================================================
Demand Forecasting — Predicted future demand using time-series trend.  
ABC Analysis — Classified products into A (high-value), B (medium), C (low).  
Economic Order Quantity (EOQ) — Found optimal order quantity to minimize cost.  
Reorder Point (ROP) — Calculated reorder thresholds using lead time.  
Lead Time Analysis — Evaluated supplier efficiency and delivery speed.  
Additional Insights — Top products, top stores, price comparison, and fast/slow-moving inventory.

==========================================================
KEY RESULTS
==========================================================
• EOQ (Optimal Order Quantity): 11,070.61 units  
• Average Lead Time: 7.62 days  
• Reorder Point: 51,476 units  
• Safety Stock: 299 units  
• A-Class Products: 1,126  
• Fastest Supplier: Truett Hurst (~5 days)  
• Slowest Supplier: Flavor Essence Inc (~13 days)

==========================================================
INSIGHTS & RECOMMENDATIONS
==========================================================
• Focus inventory control on A-class products — top 20% of SKUs drive ~80% of revenue.  
• Negotiate better terms with slower suppliers (>9 days lead time).  
• Maintain ROP near 51k units to prevent stockouts.  
• Use EOQ ≈ 11k units per purchase cycle for cost-efficient ordering.  
• Review C-class products quarterly to reduce excess stock.  
• Apply time-series forecasting (Prophet/ARIMA) for proactive restocking.

==========================================================
DATASET NOTE
==========================================================
If any CSV exceeds GitHub's 25 MB upload limit,
please download the original dataset from Kaggle:
https://www.kaggle.com/datasets/sloozecareers/slooze-challenge

