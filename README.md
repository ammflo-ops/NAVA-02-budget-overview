# 02 Budget Performance
> <i>Budget Monitoring & Variance Analysis</i>

This repository contains the **Budget Performance** analytical module of the [**NAVA Business Intelligence Portfolio**](https://github.com/ammflo-ops/NAVA-Business-Intelligence-Portfolio/blob/main/README.md).

Powered by a shared [SQL architecture](https://github.com/ammflo-ops/NAVA-00-Technical-Foundation/blob/main/README.md), it compares budgeted and actual performance across departments and countries, enabling stakeholders to monitor financial execution, identify variances and support better resource allocation.

---

# 📖 Overview

## Business Objective

Monitor budget execution, identify spending variances and evaluate financial performance to support cost control and strategic decision-making.

## Dashboard Overview

The dashboard provides an interactive view of budget performance through financial KPIs and variance analysis.

<p align="center">
  <img src="dashboard/budget_performance_dashboard.png" width="900">
</p>

Explore the interactive dashboard on Tableau Public:  
[**View Dashboard**](https://YOUR_TABLEAU_PUBLIC_LINK)

### Key Performance Indicators

- Budget
- Actual
- Budget Variance
- Budget Utilization

### Analytical Focus

- Country Performance
- Department Performance
- Cost Category Analysis
- Budget Consumption
- Monthly Budget Tracking

---

# 📖 Budget Monitoring & Variance Analysis

## Summary of Insights

- Budget execution remained under control across most departments.
- Several cost categories exceeded their allocated budgets.
- Operational spending increased faster than planned in selected business areas.
- Budget utilization varied significantly across countries.

## Recommendations & Next Steps

- Investigate recurring budget overruns by department.
- Strengthen monitoring of high-growth cost categories.
- Improve forecasting accuracy for operational expenses.
- Reallocate resources towards higher-value business activities.

---

# 📂 Repository Structure

```text
02_Budget_Performance
│
├── dashboard/
│   ├── budget_performance.twbx         # Tableau workbook
│   └── budget_dashboard.png            # Dashboard preview
│
├── sql/
│   └── vw_budget_vs_actual.sql         # Business-ready analytical view
│
└── README.md                           # Project overview
```

---

# 💡 About this Project

This repository contains the **Budget Performance** analytical module of the [**NAVA Business Intelligence Portfolio**](https://github.com/ammflo-ops/NAVA-Business-Intelligence-Portfolio/blob/main/README.md).

It demonstrates how business-ready SQL views can be transformed into interactive dashboards to monitor budget execution, analyze financial performance and support data-driven decision-making.

The dashboard is powered by the shared SQL architecture available in the [**00 Technical Foundation**](https://github.com/ammflo-ops/NAVA-00-Technical-Foundation/blob/main/README.md) repository.
