# Project Analysis Report: Hotel Reservation Analytics

**Prepared By**: Salapu Vijay  
**Date**: July 1, 2026  
**Tool Used**: Microsoft Power BI Desktop & Service  

---

## 📄 Abstract
This report presents a data-driven analysis of the global hospitality market using a dataset of 10,000 reservations. By developing an interactive Power BI dashboard, we explored visitor behavior, booking channels, guest segments, and monthly patterns. The findings reveal a heavily TA/TO-reliant distribution channel model, a high concentration of transient customers, and notable winter seasonality peaks. The report provides hotel management with actionable strategies to optimize capacity and improve yield management.

---

## 1. Introduction
In the hospitality industry, managing room inventory, anticipating guest volume, and optimizing distribution channels are critical factors for profitability. This project utilizes data visualization to analyze reservation trends, geographical distributions, and customer booking traits to help hotel managers make strategic choices regarding pricing, marketing, and staffing.

---

## 2. Methodology & Preprocessing
The analysis was performed on a dataset containing 10,000 booking records. 
- **Data Source**: `hotel_bookings.csv`
- **Data Processing**: Using Power BI's Power Query Editor, columns were validated, and missing values in guest demographics and room classes were handled.
- **Modeling**: Key performance indicators (KPIs) were modeled using DAX measures to aggregate counts of arrivals, adults, and child passengers.

---

## 3. Analytical Findings & Insights

### 👥 A. Guest Demographics
- **Total Arrivals**: 20,000 visitors
- **Adults**: 19,000 (95%)
- **Children**: 1,288 (5%)
- *Insight*: The overwhelming majority of visitors are adults. Marketing campaigns and room packages should continue focusing on couples, business travelers, and adult group packages, while maintaining a minor capacity for family amenities.

### 📡 B. Distribution Channel Performance
- **TA/TO (Travel Agents/Tour Operators)**: **16.2K** bookings
- **Direct Bookings**: **3.7K** bookings
- *Insight*: Third-party operators drive over **80%** of hotel bookings. While TA/TO channels provide consistent volume, they carry commission costs. Hotel managers should launch loyalty programs and direct-booking incentives to shift bookings directly to their own site and increase profit margins.

### 👤 C. Customer Segmentation
- **Transient**: **15.4K** bookings (77%)
- **Transient-Party**: **3.4K** bookings (17%)
- **Contract & Group**: Combined **1K** bookings (6%)
- *Insight*: Transient guests represent the dominant demographic, meaning bookings are mostly short-term and individual. Dynamic pricing algorithms can be leveraged to maximize revenue from these flexible, last-minute travelers.

### 📅 D. Seasonality & Trends
- **Peak Months**: **November (1,762)** and **October (1,758)**.
- **Low Season**: Steady decline towards **April (1,519)**.
- *Insight*: The dashboard indicates clear winter seasonality. Additional marketing efforts, discounts, and corporate retreats should be targeted during the spring/summer low season to balance room occupancy rates.

---

## 4. Managerial Recommendations

1. **Optimize Channel Mix**: Launch direct-booking campaigns (e.g., free breakfast, flexible cancellation policies) to reduce TA/TO commission costs.
2. **Dynamic Pricing for Transient Guests**: Adjust pricing dynamically in October and November to capitalize on high winter demand, while offering promotional packages in spring/summer to boost low-season occupancy.
3. **Targeted Regional Marketing**: Focus regional campaigns on the top-performing countries and cities (such as India/Portugal/Norway regions) as identified in the destination grid.
