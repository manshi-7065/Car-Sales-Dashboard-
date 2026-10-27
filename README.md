# 🚗 Car Sales Dashboard

An interactive Power BI dashboard designed to provide comprehensive insights into car sales performance, financial metrics, regional distribution, and company-wise trends[cite: 6, 7].

---

## 📊 Overview & Key Performance Indicators (KPIs)

The top-level summary cards across both pages track core metrics comparing Year-to-Date (YTD) and Month-to-Date (MTD) performance[cite: 6, 7]:
* **YTD Total Sales:** **$371.2M** *(MTD Total Sales: $54.2M | +23.59% growth)*[cite: 6, 7]
* **YTD Avg Price:** **$28K** *(MTD Avg Price: $28.26K | -$0.22K diff / -0.79%)*[cite: 6, 7]
* **YTD Cars Sold:** **13.3K** *(MTD Cars Sold: $1.92K | +19.73% growth)*[cite: 6, 7]

---

## 📑 Dashboard Pages

### 1. Overview Page
The main executive overview highlights high-level trends and geographic distribution[cite: 7]:
* **YTD Sales Weekly Trend:** A line chart tracking sales progression over the weeks[cite: 7].
* **YTD Total Sales by Body Style:** Donut chart breaking down sales across categories like SUV, Hatchback, Sedan, Passenger, and Hardtop[cite: 7].
* **YTD Total Sales by Color:** Donut chart showing customer color preferences (Pale White, Black, Red)[cite: 7].
* **YTD Cars Sold by Dealer Region:** Geographic map visualization mapping out sales distribution across regions in the United States[cite: 7].
* **Company-wise Sales Trend:** Tabular breakdown displaying metrics for various manufacturers (Cadillac, Chevrolet, Dodge, Ford, Lincoln, Oldsmobile, Saturn, Pontiac) including YTD Avg Price, YTD Cars Sold, YTD Total Sales, and % GT YTD Total Sales[cite: 7].

### 2. Details Page
A granular transaction-level view designed for deep-dive analysis[cite: 6]:
* **Data Grid:** Lists individual vehicle sales transactions containing columns for `Car_Id`, `Date`, `Customer Name`, `Dealer_Name`, `Company`, `Color`, `Model`, and `Total Sales`[cite: 6].
* **Inline Visuals:** Integrated horizontal bar representations alongside each row's `Total Sales` value for quick visual comparison[cite: 6].

---

## 🎛️ Interactive Filters & Slicers
The left-hand sidebar features global filters allowing users to slice data dynamically across the entire report[cite: 6, 7]:
* **Body Style**[cite: 6, 7]
* **Dealer_Name**[cite: 6, 7]
* **Transmission**[cite: 6, 7]
* **Engine**[cite: 6, 7]

---

## 🛠️ Built With
* **Microsoft Power BI Desktop**[cite: 6, 7]
* **DAX (Data Analysis Expressions)** for calculated measures and custom formatting
