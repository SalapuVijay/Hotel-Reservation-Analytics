# 🏨 Hotel Reservation Analytics Dashboard (Power BI)

An interactive, data-driven **Hotel Reservation Analytics Dashboard** built in Microsoft Power BI. The dashboard analyzes passenger arrival patterns, booking distribution channels, customer demographics (adults vs. children), and seasonal trends across various countries and cities. 📊🌍

---

## 🌐 Live Interactive Dashboard

Check out the live interactive dashboard directly in your browser:  
👉 **[Live Power BI Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiMzY0ZmI1MDYtODg0ZC00NDZjLTliZDQtODZmNDY3ZTRiODgyIiwidCI6ImUxNGU3M2ViLTUyNTEtNDM4OC04ZDY3LThmOWYyZTJkNWE0NiIsImMiOjEwfQ%3D%3D)** ⚡🚀

---

## 📈 Key Metrics & KPIs

- 👥 **Total Arrivals**: `20,000` (20K)
- 👨‍👩‍👧‍👦 **Total Adults**: `19,000` (19K)
- 👶 **Total Children**: `1,288`

---

## 📊 Dashboard Visualizations & Insights

### 1. 🌍 Arrivals by Country Map
An interactive geographical filled world map visualizing booking volumes from global regions including North America, Europe, Africa, South America, Asia, and Australia.

### 2. 📡 Arrivals by Distribution Channel
A column chart detailing how reservations are made:
- **TA/TO (Travel Agents / Tour Operators)**: The leading channel with **16.2K** arrivals.
- **Direct Bookings**: Accounting for **3.7K** arrivals.

### 3. 👤 Arrivals by Customer Type
An area line chart showing the segments of visiting guests:
- **Transient**: **15.4K** guests.
- **Transient-Party**: **3.4K** guests.
- **Contract**: **0.6K** guests.
- **Group**: **0.4K** guests.

### 📅 4. Total Arrivals by Month
An area chart tracking seasonal changes over time. Peak bookings occur in **November (1,762)** and **October (1,758)**, with a steady decline towards **April (1,519)**.

### 📋 5. Tourist Destination Grid
A detailed data table mapping tourist counts by country and city combinations (e.g., Portugal/Ahmedabad: 177, Norway/Ahmedabad: 147, Italy/Ahmedabad: 137).

---

## 🗂️ Project Repository Contents

- 📊 **`Hotel Reservation Analytics Dashboard.pbix`**: The primary Power BI dashboard file containing datasets, visual designs, and filters.
- 💾 **`hotel_bookings.csv`**: The raw dataset containing 10,000 reservation rows, detailing guest stays, room types, distribution channels, and booking cancellation statuses.
- 📝 **`README.md`**: Project overview, live links, and metric analysis.

---

## 💾 Dataset Columns Breakdown

| Column | Description |
|---|---|
| `Tourist_Country` | Origin country of the traveler |
| `Cities` | Destination city of the traveler |
| `Adults` / `Children` | Demographics of registered guests |
| `is_canceled` | Cancellation status (0 for active, 1 for canceled) |
| `Lead_time` | Days between booking and arrival |
| `Total_Stay_Days` | Combined stay length (weekend & week nights) |
| `Market_segment` / `Distribution_channel` | Segment classifications (Direct, Corporate, TA/TO) |
| `Room Class` / `Room Cost` | Assigned room classes and cost per night |
| `Overall Cost` | Total booking valuation including meal choices |

---

## 🚀 How to Run Locally

### Prerequisites
Make sure you have **Power BI Desktop** installed on your computer.

### Steps:
1. Clone this repository:
   ```bash
   git clone https://github.com/SalapuVijay/Hotel-Reservation-Analytics.git
   cd Hotel-Reservation-Analytics
   ```
2. Double-click the **`Hotel Reservation Analytics Dashboard.pbix`** file to open the dashboard locally in Power BI Desktop.
