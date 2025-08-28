# GMNS Incentive Reporting & Insights Automation  

This project automates **incentive reporting, attainment tracking, and performance insights** for Global Merchant & Network Services (GMNS).  
It integrates MySQL, Python (Pandas), and visualization tools to build a transparent and automated reporting engine for leadership and sales teams.  

---

## 🚀 Features
- Automated **incentive calculation engine** (rule-based commissions & attainment %).
- **Regional performance leaderboards** with revenue, quota attainment, and payouts.
- Data pipeline from **MySQL → Pandas → MySQL/Excel**.
- Export-ready **Excel reports** for leadership decks.
- Future-ready integration with **Tableau / Power BI dashboards**.

---

## 🏗️ Architecture
1. **Data Layer**:  
   - `Incentives` table → revenue by salesperson.  
   - `QuotasTargets` table → quota & targets.  
   - Joins ensure **real-time attainment calculations**.  

2. **Processing Layer (Python + Pandas)**:  
   - Data pulled from MySQL.  
   - Incentive calculation applied (configurable rules).  
   - Aggregation into **regional insights & leaderboards**.  

3. **Output Layer**:  
   - Results written back to MySQL (`IncentiveResults`).  
   - Excel/CSV exports for easy sharing.  
   - Optional Power BI/Tableau connection.  

---

## ⚙️ Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/your-username/gmns-incentive-automation.git
cd gmns-incentive-automation
