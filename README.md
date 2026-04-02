# Supply-Chain-Performance-Dashboard

## Overview

This project presents an end-to-end **Supply Chain Performance Dashboard** designed to analyze delivery efficiency, sales performance, and profitability across regions, markets, and customer segments.

The solution combines **Power BI dashboards** with **Python-based analysis** to identify delivery risks, operational bottlenecks, and revenue-impacting factors within the supply chain.

The analysis is structured into two dashboards:
- Delivery Performance
- Sales Performance

---

## Objectives

- Monitor delivery performance and late shipment risks  
- Identify regions with high sales losses  
- Analyze the impact of fulfillment time on profitability  
- Understand sales distribution across regions and customer segments  
- Enable data-driven supply chain optimization  

---

## Dataset

The dataset contains historical supply chain transaction data, including:

- Order and shipping dates  
- Delivery status and shipping modes  
- Regional and market information  
- Sales and profit values  
- Customer segments and payment types  

---

## Project Structure

Supply-Chain-Performance-Dashboard/
│
├── README.md
├── Dataset/
├── Power Bi/
│   └── Supply_Chain_Performance.pbix
├── Python Analysis/
│   └── supply_chain_analysis.ipynb
└── Screenshots/
    ├── Delivery_Performance.png
    └── Sales_Performance.png

---

## Dashboard 1: Delivery Performance

![Delivery Performance](Screenshots/Delivery_Performance.png)

### Key Insights

- Late deliveries represent a significant share of total orders, highlighting fulfillment inefficiencies.
- Certain regions consistently experience higher sales losses due to cancellations and delays.
- Faster shipping modes do not always guarantee on-time delivery.
- Shorter fulfillment times are associated with higher profitability.

---

## Dashboard 2: Sales Performance

![Sales Performance](Screenshots/Sales_Performance.png)

### Key Insights

- Sales are concentrated in specific regions and markets.
- Consumer segments contribute the largest share of revenue.
- Profitability varies significantly by department and region.
- Some payment types show higher association with late delivery risk.

---

## Python-Based Analysis

Python was used for:
- Data cleaning and preprocessing  
- Feature engineering  
- Exploratory data analysis  
- Validation of Power BI insights  

---

## Business Value

This project helps organizations:
- Reduce delivery delays  
- Minimize revenue losses  
- Optimize shipping strategies  
- Improve customer satisfaction  
- Enhance overall supply chain performance  

---

## Tools & Technologies

- Power BI  
- Python (Pandas, NumPy, Matplotlib)  
- CSV datasets  
- Git & GitHub  

---

## Future Enhancements

- Predictive modeling for late delivery risk  
- Integration of customer satisfaction metrics  
- Automated alerts for high-risk orders  
- Supply chain optimization models  

---

## Conclusion

This dashboard provides a comprehensive view of supply chain performance by combining operational metrics with financial insights, enabling informed and actionable decision-making.

---

## Disclaimer

This project is for educational and analytical purposes only.
