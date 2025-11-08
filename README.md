# Customer Trends Analysis

This project analyzes historical transaction data to uncover customer purchase trends, identify meaningful segments and patterns in customer behaviour, and deliver actionable business insights for optimization.

## 🧰 Technologies  
- **Python** (Jupyter Notebook): data import, cleaning, exploration, and analytics  
- **SQL** (MySQL / PostgreSQL / MS SQL Server): database creation, data loading, querying  
- **Power BI**: interactive dashboards for visualization and insights delivery  

## 📁 Project Structure   
- `Customer trend analysis.pbix` – Power BI file containing interactive dashboard.  
- `Customer_Trends­-checkpoint.ipynb` – Python notebook for data import, cleaning, EDA and database integration.  
- `shopping_trends.csv` – Raw transaction dataset (customers × purchases).  
- `image.png` – Preview image of the dashboard or key findings.  
- `README.md` – Project description and usage instructions.

## 📊 Workflow & Key Steps  
1. **Data Import & Exploration**  
   - Loaded ~3,900+ customer purchase records from CSV using Pandas.  
   - Performed exploratory data analysis (EDA) using Matplotlib & Seaborn to identify seasonal trends, spending patterns, and payment mode usage.  
2. **Data Cleaning & Preparation**  
   - Addressed missing values, outliers, and inconsistent formats.  
   - Transformed data into structured format suitable for database ingestion.  
3. **Database Integration**  
   - Created a relational database in a selected SQL engine (MySQL)  
   - Loaded cleaned data from Python into the SQL database using SQLAlchemy / connectors.   
4. **Visualization & Dashboarding**  
   - Connected Power BI to the SQL database and imported curated datasets.  
   - Built interactive dashboards presenting customer segmentation, revenue trends, payment mode analysis, and other KPIs.  
   - Enabled stakeholders to filter and drill down into insights (e.g., by season, customer segment, payment mode).

## 🎯 Business Impact & Key Insights  
- Identified that PayPal accounted for ~17.4% of payment volume, highlighting an opportunity for further promotion.  
- Revealed clear seasonal buying patterns, enabling the business to align marketing campaigns and inventory planning accordingly.  
- Segment-level analysis helped uncover high-value customers and under-performing segments for targeted strategies.  
- Dashboard provided leadership with a real-time view of customer behaviour and KPIs, facilitating data-driven decision-making.

 
   ```bash
   git clone https://github.com/Neelesh57/Customer_trends_Analysing.git
