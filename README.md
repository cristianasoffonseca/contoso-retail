# Business Intelligence & Analytics Projects

This repository contains Business Intelligence and Analytics work developed using **Power BI** and **Python**, covering data modeling, reporting, and predictive analytics.

---

## Project Structure

```text
├── ContosoSelfServiceBI.pbix
│
├── images/
│
└── README.md
```

---

## 1. Contoso Self-Service BI

**File:** `ContosoSelfServiceBI.pbix`

A Power BI report built on the Contoso Retail dataset, integrating multiple data sources into a structured analytical model.

### Work performed
- Designed a star-schema data model with fact and dimension tables.
- Defined relationships across sales, products, dates, stores, channels, promotions, and geography.
- Implemented calendar and fiscal date structures.
- Created product, location, and channel hierarchies.
- Developed DAX measures to analyse sales, quantities, profit, and profit per day.
- Designed interactive reports with slicers and drill-down capabilities.

### Data Model
![Contoso Data Model](images/ContosoModel.png)

### Reports & Visuals

**Product Sales by Quarter**  
![Product Sales by Quarter](images/ProductsSalesByQuarter.png)

**Sales by Channel**  
![Sales by Channel](images/SalesByChannel.png)

**Sales by Calendar**  
![Sales by Calendar](images/SalesByCalendar.png)

**Sales by Fiscal Period**  
![Sales by Fiscal](images/SalesByFiscal.png)

> Note: When opening the PBIX file in a different environment, data source paths may need to be updated (data is not provided)

## Tools & Technologies
- Power BI Desktop

## Author
Cristiana Fonseca