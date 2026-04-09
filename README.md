# NYC Airbnb Marketplace Analysis (2019)

A comprehensive exploratory data analysis (EDA) of the New York City Airbnb ecosystem, uncovering spatial distribution, pricing hierarchies, and inventory dynamics across the five boroughs using Python.

---

## 📖 Project Background

In the highly heterogeneous marketplace of New York City, Airbnb pricing and availability are driven by complex geographical and structural factors. This project analyzes a dataset of ~49,000 listings to identify high-demand clusters, optimize listing strategies, and understand how supply varies from the luxury hubs of Manhattan to the residential corridors of the Bronx.

The goal is to provide data-driven insights into:

- **Pricing Dynamics:** Identifying the structural drivers of price across different neighborhoods.
- **Supply Concentration:** Mapping where inventory is clustered via Latitude/Longitude data.
- **Consumer Behavior:** Analyzing minimum stay requirements and room type preferences.

---

## 🔬 Data Processing & EDA Workflow

The project follows a rigorous data science workflow directly within Jupyter, handling a total of 48,895 records.

---

## 📊 Executive Summary & Visual Insights

### Pricing Trends & Distribution

The NYC market is heavily concentrated in the affordable-to-mid-range segment, with the majority of listings priced between $50 and $150. While supply thins as prices rise, there are psychological "anchor points" at $250 and $350.

![image alt](https://github.com/MostafaAlali/New-York-City-Short-Term-Rental-Insights/blob/main/images/Pricing_Distribution.png)

---

### Geographic Supply Concentration

Manhattan and Brooklyn are the undisputed leaders in supply, each hosting approximately 20,000 listings. Together, they represent a massive lead over Queens, the Bronx, and Staten Island.
![image alt](https://github.com/MostafaAlali/New-York-City-Short-Term-Rental-Insights/blob/main/images/Geographic%20Supply%20Concentration.png)

---

### Pricing Hierarchy & Variability

Manhattan maintains the highest average price point across the city. Interestingly, while it is the most expensive, its price distribution is relatively stable (less variance) compared to the wide fluctuations seen in Brooklyn and Queens.
![image alt](https://github.com/MostafaAlali/New-York-City-Short-Term-Rental-Insights/blob/main/images/Pricing%20Hierarchy.png)

---

### Inventory by Room Type

The inventory is dominated by Entire homes/apartments (52%), followed by Private rooms (45.7%). Shared rooms are effectively a niche market, representing only 2.3% of the total supply. 
![image alt](https://github.com/MostafaAlali/New-York-City-Short-Term-Rental-Insights/blob/main/images/Inventory%20by%20Room%20Type.png)

---

### Minimum Stay Behavior

Most listings target short-term stays of 1–2 nights. However, a significant spike at the 30-night mark suggests a segment of the market catering to monthly rentals, likely reflecting long-term rental behavior or regulatory compliance.
![image alt](https://github.com/MostafaAlali/New-York-City-Short-Term-Rental-Insights/blob/main/images/Minimum%20Stay%20Behavior.png)

---

## 💡 Recommendations

- **Strategic Expansion in Brooklyn:** Investors should look toward Brooklyn for a "price-location" trade-off. It offers comparable volume to Manhattan but with more varied entry points.
- **Targeted Premium Listings:** Since Manhattan has high price stability, new premium listings here face lower risk of radical price undercutting than in other boroughs.
- **Regulatory Monitoring:** The spike in 30-day minimum stays suggests a shift toward mid-term rentals. Hosts should evaluate if shifting to a "monthly" model reduces vacancy risk under NYC's strict short-term rental laws.

---

**Author:** Mostafa Alali  
**Date:** 2026-04-08
