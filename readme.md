# 🍔 Food Delivery Business Analysis Dashboard

Interactive Power BI dashboard for analyzing operational performance, customer satisfaction, delivery efficiency, and promotional effectiveness in a food delivery business.

---

## 📊 Dashboard Preview

### Business Analysis

![Business Analysis](images/business_analysis.png)

### Operational Analysis

![Operational Analysis](images/operational_analysis.png)

## 🎯 Project Objectives

This project aims to:

- Monitor key business and operational KPIs
- Analyze delivery performance across menu categories
- Evaluate promotional campaign effectiveness
- Identify factors affecting customer satisfaction
- Support data-driven business decisions

---

## 🛠️ Tools & Technologies

- Power BI Desktop
- Microsoft Excel
- DAX (Data Analysis Expressions)

---

## 📂 Dataset Information

The dataset contains food delivery transaction records with customer feedback and operational metrics.

### Main Features

| Feature | Description |
|----------|------------|
| ID_Pesanan | Unique order ID |
| Harga_Pesanan | Order value |
| Kategori_Menu | Menu category |
| Jam_Transaksi | Transaction hour |
| Waktu_Tunggu_Menit | Delivery waiting time |
| Rating_Pelanggan | Customer rating |
| Status_Promo | Promotion status |
| Tingkat_Keluhan | Complaint severity |
| Status_Pesanan | Order status |
| Jarak_Kirim_KM | Delivery distance |

---

## 📈 Dashboard Pages

### 1. Operational Analysis

Focuses on operational efficiency and delivery performance.

#### Key Visualizations

- Peak Order Hours
- Complaint Level vs Waiting Time
- Customer Complaint Distribution
- Waiting Time vs Customer Rating

#### Business Questions

- When do customers place the most orders?
- How does waiting time affect customer satisfaction?
- Which complaint levels are associated with longer delivery times?

---

### 2. Business Analysis

Focuses on business performance and customer experience.

#### KPI Cards

| KPI | Description |
|-------|------------|
| Total Orders | Total number of orders |
| Avg Waiting Time | Average delivery waiting time |
| Avg Customer Rating | Average customer rating |
| Total Complaints | Total customer complaints |

#### Key Visualizations

- Menu Performance
- Promotion Effectiveness
- Interactive KPI Monitoring

#### Interactive Filters

- Menu Category
- Promotion Status
- Complaint Level

---

## 📌 DAX Measures

### Total Orders

```DAX
Total Orders =
COUNT(Sheet1[ID_Pesanan])
```

### Average Waiting Time

```DAX
Avg Waiting Time =
AVERAGE(Sheet1[Waktu_Tunggu_Menit])
```

### Average Customer Rating

```DAX
Avg Customer Rating =
AVERAGE(Sheet1[Rating_Pelanggan])
```

### Total Complaints

```DAX
Total Complaints =
COUNT(Sheet1[Tingkat_Keluhan])
```

---

## 🔍 Key Findings

### Menu Performance

- Mie recorded the highest average waiting time.
- Ayam showed the fastest delivery performance.

### Promotion Effectiveness

- Average customer ratings remain similar between promoted and non-promoted orders.
- Promotional campaigns alone may not significantly improve customer satisfaction.

### Customer Experience

- Longer waiting times tend to be associated with lower customer satisfaction.
- Complaint levels increase as waiting times become longer.

---

## 📈 Business Recommendations

### Operational Improvements

- Reduce delivery waiting time during peak hours.
- Improve dispatch efficiency for high-demand menu categories.

### Customer Satisfaction

- Focus on service quality improvements before expanding promotional campaigns.
- Monitor complaint trends continuously.

### Performance Monitoring

- Track KPI metrics regularly using dashboard filters.
- Use complaint levels as an early warning indicator of service issues.

---

## 🚀 How to Use

1. Open the `.pbix` file in Power BI Desktop.
2. Navigate between dashboard pages:
   - Operational Analysis
   - Business Analysis
3. Use slicers to filter:
   - Menu Category
   - Promotion Status
   - Complaint Level
4. Explore KPI changes and visual interactions.

---

## 📁 Repository Structure

```text
food-delivery-dashboard/
│
├── Dashboard/
│   └── Food-Delivery-Analysis.pbix
│
├── Dataset/
│   └── food_delivery_dataset.xlsx
│
├── Images/
│   └── dashboard.png
│
└── README.md
```

---

## 👨‍💻 Author

Dafazra Hermawan

Data Analytics & Business Intelligence Project

---

## ⭐ Project Highlights

✔ Interactive Power BI Dashboard

✔ KPI Monitoring

✔ Business Performance Analysis

✔ Operational Performance Analysis

✔ Customer Satisfaction Insights

✔ Data-Driven Decision Support