# 🌍 Regional Tourism Insights Dashboard                                                                                                                              DATE : 25/07/2025

An interactive Tableau dashboard that analyzes regional tourism trends, revenue patterns, and tourist behavior across multiple regions and tour categories.

---

## 📌 Project Overview

This project presents a comprehensive **tourism analytics dashboard** built in Tableau, designed to help tourism boards, travel agencies, and policymakers understand tourist flow, spending behavior, and regional performance.

The dashboard leverages a rich dataset spanning multiple years, regions, and tour types to surface meaningful insights — from seasonal tourist trends to high-revenue tour categories and regional profit breakdowns.

This project is output of my 15 days ibm skillbuild online internship which was done in the july 2025 .

---

## 📊 Dashboard Features

The dashboard consists of **5 interactive views** with cross-filtering support:

| Visual                             | Description                                                                                                    |
| ---------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| 🥧**Categories in Tours**    | Pie chart showing distribution of tourists across tour types (Adventure, Beach, Cultural, Religious, Wildlife) |
| 💰**Profit KPI Card**        | Total profit metric updated dynamically based on applied filters                                               |
| 📊**Spend per Tourist**      | Horizontal bar chart comparing average spend per tourist by tour type                                          |
| 📈**Trend Line of Tourists** | Monthly line chart showing tourist volume fluctuations throughout the year                                     |
| 🗺️**Revenue by Region**    | Bar chart comparing total revenue across East, North, South, and West regions                                  |

---

## 🔍 Key Insights

- **Total Profit (All Regions):** ₹22,483,364 across all tour types and regions
- **Highest Avg. Spend:** Adventure tours lead at **₹107,457** per tourist, followed by Wildlife at **₹106,489**
- **Peak Tourist Month:** April sees the highest footfall (~5,433 tourists), while August dips to the lowest (~2,888)
- **Top Revenue Region:** East region generates the highest total revenue (~₹14,500K), followed closely by North (~₹14,000K)
- **Most Popular Tour Type:** Wildlife (10,824 tourists) narrowly edges out Adventure (9,894 tourists)

---

## 🗂️ Dataset Description

The dataset contains tourism records with the following columns:

| Column                    | Description                                                    |
| ------------------------- | -------------------------------------------------------------- |
| `Date`                  | Date of the tour record                                        |
| `Region`                | Geographic region (East, West, North, South)                   |
| `Tour_Type`             | Type of tour (Adventure, Beach, Cultural, Religious, Wildlife) |
| `Accommodation_Type`    | Where tourists stayed (Resort, Hostel, Camping, Homestay)      |
| `Season`                | Travel season (Peak, Off-Peak, Shoulder)                       |
| `Number_of_Tourists`    | Count of tourists per record                                   |
| `Avg_Spend_Per_Tourist` | Average spending per tourist in local currency                 |
| `Total_Revenue`         | Total revenue generated (Tourists × Avg Spend)                |
| `Expense`               | Operational expenses incurred                                  |
| `Profit`                | Net profit (Revenue − Expense)                                |
| `Year`                  | Year of the record (2023, 2024, ...)                           |
| `Currency`              | Currency of the transaction (INR, EUR, USD)                    |
| `Month`                 | Month of the record (Jan–Dec)                                 |

**Sample Records:**

```
Date         Region  Tour_Type  Accommodation  Season    Tourists  Avg_Spend   Revenue      Expense     Profit      Year  Currency  Month
2023-01-16   South   Wildlife   Camping        Off-Peak  17        125.55      2,134.35     952.43      1,181.92    2023  INR       Jan
2023-02-19   West    Cultural   Resort         Off-Peak  184       622.97      114,626.48   71,453.15   43,173.33   2023  EUR       Feb
2024-01-23   North   Religious  Hostel         Peak      198       287.22      56,869.56    42,121.26   14,748.30   2024  EUR       Jan
```

---

## 🛠️ Tools & Technologies

- **Tableau Desktop / Tableau Public** — Dashboard creation and visualization
- **Microsoft Excel / CSV** — Data source format
- **Data Prep** — Basic cleaning and structuring of the dataset

---

## 🚀 How to Use

### Option 1: View on Tableau Public

> *(Add your Tableau Public link here once published)*
>
> 🔗 [View Live Dashboard](#)

### Option 2: Open Locally in Tableau

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/regional-tourism-dashboard.git
   cd regional-tourism-dashboard
   ```
2. Open Tableau Desktop (version 2022.1 or higher recommended)
3. Open the `.twbx` file from the repo:
   ```
   File → Open → regional_tourism_dashboard.twbx
   ```
4. The workbook loads with embedded data — no additional setup needed

### Option 3: Connect to Your Own Data

1. Open the `.twb` file (without embedded data)
2. Reconnect to the provided Excel/CSV dataset in the `/data` folder
3. Ensure column names match exactly as described in the Dataset section above

---

## 📁 Repository Structure

```
regional-tourism-dashboard/
│
├──  tourism_data.xlsx          # Source dataset
│
├── 📂 screenshots/
│   
├── regional_tourism_dashboard.twbx  # Tableau packaged workbook (with data)
└── README.md
```

---

## 🔄 Dashboard Interactivity

All charts in the dashboard act as **interactive filters**. Clicking on any element updates the entire dashboard:

- Click a **pie slice** → filters all charts to that tour type only
- Click a **region bar** → filters to show only that region's data
- Hover over **trend line points** → shows exact tourist count for that month

---

### 🎯 Use Cases

This dashboard is valuable for:

- **Tourism Boards** tracking region-wise performance and setting promotional priorities
- **Travel Agencies** identifying high-spend tour types to focus marketing efforts
- **Policy Makers** analyzing seasonal patterns to plan infrastructure and staffing
- **Researchers & Students** studying tourism data analytics and Tableau dashboard design

---

## 📬 Contact

**Created by:** Shlok Panchal

**LinkedIn:** www.linkedin.com/in/panchalshlok

**Tableau Public:** https://public.tableau.com/app/profile/shlok.panchal1895 

**Email:** shlokpanchal1812@gmail.com

---

## ⭐ If you found this useful, please star the repo!

```
git clone https://github.com/your-username/regional-tourism-dashboard.git
```
