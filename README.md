# 🚗 Car Sales Dashboard — Power BI

> An interactive Power BI dashboard analyzing **23,664 car sales transactions** across 2022–2023, covering **30 brands**, **154 models**, **28 dealers**, and **7 regions** — delivering insights on revenue trends, customer demographics, and dealer performance.

---

## 📁 Project Structure

```
car-sales-dashboard/
│
├── Car_Sales_Dashboard.pbix     ← Main Power BI dashboard file
├── Car_Sales_Cleaned.csv        ← Cleaned dataset (23,664 records)
└── README.md                    ← Project documentation
```

---

## 🗂️ Dataset Overview

| Column | Description |
|---|---|
| `Car_id` | Unique identifier for each sale |
| `Date` | Date of transaction (2022–2023) |
| `Customer_Name` | Buyer's name |
| `Gender` | Customer gender — Male / Female |
| `Annual_Income` | Customer's annual income ($) |
| `Dealer_Name` | Name of the dealership (28 dealers) |
| `Company` | Car manufacturer / brand (30 brands) |
| `Model` | Car model name (154 models) |
| `Engine` | Engine type — Overhead Camshaft / Double Overhead Camshaft |
| `Transmission` | Auto / Manual |
| `Color` | Pale White / Black / Red |
| `Price` | Sale price ($) |
| `Body_Style` | SUV / Sedan / Hatchback / Hardtop / Passenger |
| `Dealer_Region` | Geographic region of dealer (7 regions) |
| `Price_Category` | Low / Mid / High price tier |
| `Affordability_Ratio` | Ratio of car price to customer annual income |
| `Year` | Sale year — 2022 or 2023 |
| `Month_Name` | Month of sale |
| `Income_Category` | Low Income / Mid Income / High Income |

**Total Records:** 23,664 &nbsp;|&nbsp; **Period:** Jan 2022 – Dec 2023 &nbsp;|&nbsp; **Brands:** 30 &nbsp;|&nbsp; **Models:** 154 &nbsp;|&nbsp; **Dealers:** 28 &nbsp;|&nbsp; **Regions:** 7

---

## 📈 Key KPI Metrics

| Metric | Value |
|---|---|
| 💰 Total Sales Revenue | $651,550,154 |
| 🚘 Total Cars Sold | 23,664 units |
| 📦 Average Car Price | $27,533 |
| 👤 Average Customer Income | $830,193 |
| 📅 2022 Revenue | $291,609,271 |
| 📅 2023 Revenue | $359,940,883 |
| 📈 Year-over-Year Growth | +23.4% |

---

## 📊 Dashboard Visuals

### 1. KPI Summary Cards
Four headline metrics at the top — Total Revenue, Cars Sold, Avg Price, YoY Growth.

---

### 2. Monthly Sales Trend (Line / Bar Chart)
X axis → Month &nbsp;|&nbsp; Y axis → Total Sales ($)

| Month | Sales ($) |
|---|---|
| January | 20,958,717 |
| February | 19,631,044 |
| March | 40,718,869 |
| April | 45,042,431 |
| May | 51,676,536 |
| June | 47,443,397 |
| July | 47,039,928 |
| August | 47,730,334 |
| **September** | **90,885,223** |
| October | 50,541,106 |
| **November** | **94,025,119** |
| **December** | **95,857,450** |

---

### 3. Top Companies by Revenue (Bar Chart)
X axis → Company &nbsp;|&nbsp; Y axis → Total Sales ($)

| Rank | Company | Revenue ($) |
|---|---|---|
| 1 | Ford | 47,231,583 |
| 2 | Chevrolet | 44,783,008 |
| 3 | Dodge | 44,124,996 |
| 4 | Oldsmobile | 35,434,512 |
| 5 | Volkswagen | 34,082,881 |

---

### 4. Sales by Body Style (Donut / Bar Chart)

| Body Style | Revenue ($) | Share |
|---|---|---|
| SUV | 165,920,635 | 25.5% |
| Hatchback | 160,913,358 | 24.7% |
| Sedan | 133,889,619 | 20.5% |
| Passenger | 107,145,644 | 16.4% |
| Hardtop | 83,680,898 | 12.8% |

---

### 5. Sales by Dealer Region (Map / Bar Chart)
X axis → Region &nbsp;|&nbsp; Y axis → Total Sales ($)

| Region | Revenue ($) |
|---|---|
| Austin | 113,727,970 |
| Janesville | 103,315,374 |
| Scottsdale | 93,901,118 |
| Aurora | 85,873,873 |
| Pasco | 85,476,208 |
| Greenville | 84,696,042 |
| Middletown | 84,559,569 |

---

### 6. Transmission Split (Donut Chart)

| Transmission | Count | Share |
|---|---|---|
| Auto | 12,553 | 53% |
| Manual | 11,111 | 47% |

---

### 7. Engine Type Split (Donut Chart)

| Engine | Count | Share |
|---|---|---|
| Double Overhead Camshaft | 12,553 | 53% |
| Overhead Camshaft | 11,111 | 47% |

---

### 8. Car Color Distribution (Bar / Donut Chart)

| Color | Count | Share |
|---|---|---|
| Pale White | 11,186 | 47.3% |
| Black | 7,766 | 32.8% |
| Red | 4,712 | 19.9% |

---

### 9. Customer Gender Split (Donut Chart)

| Gender | Count | Share |
|---|---|---|
| Male | 18,630 | 78.7% |
| Female | 5,034 | 21.3% |

---

### 10. Price Category Distribution (Bar Chart)

| Category | Count | Share |
|---|---|---|
| Low | 13,683 | 57.8% |
| Mid | 8,177 | 34.6% |
| High | 1,804 | 7.6% |

---

### 11. Top Models by Revenue (Horizontal Bar Chart)
X axis → Revenue ($) &nbsp;|&nbsp; Y axis → Model

| Model | Revenue ($) |
|---|---|
| LS400 | 14,263,424 |
| Jetta | 12,287,736 |
| Silhouette | 12,271,849 |
| Montero Sport | 11,472,231 |
| Ram Pickup | 10,655,391 |

---

### 12. Top Dealers by Revenue (Bar Chart)

| Dealer | Revenue ($) |
|---|---|
| Rabun Used Car Sales | 36,649,452 |
| Progressive Shippers | 35,591,557 |
| U-Haul CO | 34,968,086 |
| Race Car Help | 34,210,203 |
| Saab-Belle Dodge | 34,108,261 |

---

## 💡 Business Insights

1. **23.4% YoY Revenue Growth** — 2023 ($359.9M) significantly outperformed 2022 ($291.6M), indicating strong market expansion.
2. **Q4 dominates sales** — September, November, and December alone contribute over 43% of total annual revenue, pointing to strong seasonal demand.
3. **Ford, Chevrolet, and Dodge lead revenue** — American brands dominate the top 3 spots, capturing a major share of the market.
4. **SUVs and Hatchbacks are most popular** — together they account for over 50% of total revenue; inventory should prioritize these body styles.
5. **Austin is the top-performing region** at $113.7M — 34% ahead of the lowest-performing region (Middletown at $84.5M).
6. **Pale White preferred by nearly half of buyers** (47.3%) — stocking more white-colored cars can reduce inventory wait times.
7. **78.7% of buyers are male** — marketing strategies could be diversified to better attract female customers.
8. **57.8% of sales fall in the Low price tier** — most customers are budget-focused; promoting EMI and financing options could help upsell to mid and high tiers.
9. **Auto and Manual transmissions are nearly equal** (53% vs 47%) — both variants should be stocked evenly across dealerships.
10. **LS400 is the top revenue model** at $14.26M — Lexus premium buyers represent a high-value customer segment worth targeting.

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard building and visualization |
| DAX | KPI measures, YoY growth, affordability ratio calculations |
| Power Query | Data cleaning and transformation |
| CSV | Source data format |

---

## 🚀 How to Open

1. Install **Power BI Desktop** (free) → [powerbi.microsoft.com](https://powerbi.microsoft.com/desktop)
2. Clone this repository
   ```bash
   git clone https://github.com/your-username/car-sales-dashboard.git
   ```
3. Open `Car_Sales_Dashboard.pbix` in Power BI Desktop
4. Update the data source path to point to `Car_Sales_Cleaned.csv` if prompted
5. Click **Refresh** to load the data

---

## 📌 How to Use the Dashboard

- Use **slicers** to filter by Year, Region, Company, Body Style, Gender, or Transmission
- Click any **bar or donut slice** to cross-filter all other visuals on the page
- Hover over any chart for **exact values in tooltips**
- Use the **map visual** to explore regional dealer performance geographically
- Toggle between **2022 and 2023** to compare year-over-year performance

---

## 👤 Author

NANDAN R
[LinkedIn]https://www.linkedin.com/in/nandan-r-010564224/ |
[GitHub]https://github.com/NandanR75|
[Portfolio](#)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
