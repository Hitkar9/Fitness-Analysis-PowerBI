# 🏋️ Fitness Analysis Dashboard | Power BI

An interactive **Power BI dashboard for analyzing gym business performance, membership trends, member progress, and personalized fitness metrics**.

The project combines business KPIs, membership analytics, member-level tracking, and an interactive fitness calculator using **Power BI, DAX, and Power Query**.

---

## 📊 Dashboard Preview

### 🏠 Home Page
![Home Page](Images/1st_page_%28home%29.png)

### 📊 Overall Dashboard
![Overall Dashboard](Images/2nd_page_%28overall%29.png)

### 🧮 Fitness Calculator
![Fitness Calculator](Images/3rd_page_%28calculator%29.png)

### 👥 Members Analysis
![Members Analysis](Images/4th_page_%28members%29.png)

## 🎯 Project Objectives

The dashboard was designed to provide a centralized view of gym operations and answer questions around:

- How many members does the gym have?
- How are memberships distributed across plans?
- How many members are active or expired?
- How are revenue, expenses, and profit changing?
- How is individual membership progress?
- What are a member's BMI, BMR, and TDEE?
- What calorie targets correspond to different fitness goals?

---

## 🚀 Key Features

### 💰 Business Performance Analytics

Tracks core gym business KPIs:

- Total Members
- Total Revenue
- Total Expenses
- Total Profit
- Monthly Membership Trends
- Monthly Financial Performance

### 👥 Membership Analytics

Analyzes membership plans and status:

- Platinum
- Gold
- Silver
- Active Members
- Expired Members
- Membership Distribution
- Monthly Member Trends

### 📈 Member Progress Tracking

Uses DAX to dynamically calculate:

- Completed Membership Days
- Remaining Membership Days
- Total Membership Duration
- Membership Progress %

A custom **DAX-generated SVG progress bar** is used to visualize membership completion.

### 🧮 Interactive Fitness Calculator

Users can select:

- Age
- Weight
- Height
- Gender
- Activity Level

The dashboard dynamically calculates:

- BMI
- BMI Category
- BMR (Basal Metabolic Rate)
- TDEE (Total Daily Energy Expenditure)
- Maintenance Calories
- Mild Weight Loss Calories
- Weight Loss Calories
- Extreme Weight Loss Calories

---

## 📑 Dashboard Pages

| Page | Description |
|---|---|
| 🏠 **Home** | Landing and navigation page |
| 📊 **Overall** | Business KPIs, membership trends, revenue, expenses, and profit |
| 🧮 **Fitness Calculator** | BMI, BMR, TDEE, and calorie target calculations |
| 👥 **Members** | Detailed member, membership, demographic, and progress analysis |

---

## 🧠 DAX Implementation

The project uses DAX measures for business metrics, membership analytics, dynamic calculations, and custom visual elements.

### Business KPIs

- `Users_Count`
- `Revenue`
- `Expanses`
- `Profit`

### Membership Analytics

- `Max_users`
- `Min_users`
- `User_Platinum`
- `User_Gold`
- `User_Silver`
- Active/Expired member measures

### Membership Progress

- `Complete_Days`
- `RemainingDays`
- `Left_Days_Count`
- `Total_Days`
- `ProgressPercent`
- `SVG_BarChart1`

### Fitness Calculations

- `BMI`
- `BMI Color`
- `BMI Color Label`
- `BMR`
- `TDEE`
- `Maintain Calories`
- `Mild Weight Loss Calories`
- `Weight Loss Calories`
- `Extreme Weight Loss Calories`

The complete DAX measures are available in:

**`DAX Measures/Fitness Dashboard DAX Measures.txt`**

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **DAX**
- **Power Query**
- **Data Transformation**
- **Data Visualization**
- **Interactive Dashboard Design**

---

## 📂 Repository Structure

```text
Fitness-Analysis-PowerBI/
│
├── FitnessDashboard.pbix
├── README.md
│
├── DAX Measures/
│   └── Fitness Dashboard DAX Measures.txt
│
└── Images/
    ├── Overview.png
    ├── Home_Page.png
    ├── Calculator.png
    └── Member.png
```

---

## ▶️ How to Use

1. Clone or download this repository.
2. Open `FitnessDashboard.pbix` using **Microsoft Power BI Desktop**.
3. Navigate through the dashboard pages.
4. Use slicers and interactive controls to explore the analysis.
5. Use the Fitness Calculator to explore BMI, BMR, TDEE, and calorie targets.

> **Note:** Power BI Desktop is required to open and interact with the `.pbix` file.

---

## 📌 Project Highlights

- Built a multi-page interactive Power BI dashboard.
- Created DAX measures for business and fitness KPIs.
- Implemented membership lifecycle and progress calculations.
- Developed an interactive BMI, BMR, and TDEE calculator.
- Created a custom SVG-based membership progress visualization using DAX.
- Designed KPI cards, charts, slicers, filters, and interactive navigation.

---

## 👤 Author

**Himanshu Hitkar**

B.Tech — Electronics & Communication Engineering  
National Institute of Technology, Patna

[GitHub](https://github.com/Hitkar9)
