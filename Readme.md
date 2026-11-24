# 🚗 Auto Insurance Performance Analytics Dashboard

## 📌 Project Overview
An interactive **Microsoft Power BI** multi-page dashboard designed to analyze auto insurance policies, customer demographics, claims distribution, and regional revenue performance. Using the `AutoInsurance` dataset (covering **9,134 customers**, **9 policy types**, and **4 sales channels**), this report enables stakeholders to track income generation, evaluate claim risks, and monitor Customer Lifetime Value (CLV) across segments.

---

## 🎯 Key Performance Indicators (KPIs)
* **Total Income:** `344M`
* **Total Policies:** `9`
* **Sales Channels:** `4` (Agent, Branch, Call Center, Web)
* **Total Customers:** `9,134`
* **Total Claim Amount:** `3.96M`

---

## 📑 Dashboard Pages & Visual Breakdown

### 1. Overall Performance (`OVERALL`)
Provides an executive summary of company-wide revenue, customer value, and claim volume:
* **KPI Cards:** High-level metrics for Total Income (`344M`), Total Policies (`9`), Sales Channels (`4`), Total Customers (`9,134`), and Total Claim Amount (`3.96M`).
* **Income by Employee Status:** Horizontal bar chart highlighting that **Employed** customers generate the vast majority of income (`321M`), followed by Medical Leave (`9M`), Disabled (`8M`), and Retired (`6M`).
* **Income by Marital Status:** Funnel chart breaking down income across **Married** (`202M`), **Single** (`93M`), and **Divorced** (`50M`) policyholders.
* **Lifetime Value by Employment Status:** Line chart comparing Customer Lifetime Value across employment categories, led by Employed (`46.83M`) and Unemployed (`17.69M`).
* **Claim by No. of Policies:** Column chart showing how total claim amounts distribute based on the number of active policies held by customers (peaking at 1 policy with `1.49M`).
* **Claim by Sales Channel:** Trend chart tracking claims across acquisition channels, with **Agent** (`1.52M`) and **Branch** (`1.11M`) accounting for the highest claim amounts.
* **Top 5 Policies by Claim Amount:** Donut chart displaying claim share by policy tier, led by **Personal L3** (`42.76%`) and **Personal L2** (`25.28%`).

---

### 2. Gender & Customer Segment Performance (`GENDER`)
Focuses on demographic filtering, high-value customers, and vehicle-level claim risk:
* **Interactive Slicers & Navigation:** Filter by **Gender** (`M` / `F`), **Month**, **Policy Type**, **Vehicle Size**, and **Policy**, plus custom page navigation buttons (`OVERALL`, `GENDER`, `PLACE`).
* **Income by Employee Status:** Filtered income distribution across employment groups.
* **Top 5 Customers by Claim:** Donut chart identifying individual policyholders generating the highest claim payouts.
* **Top 5 Customers by Lifetime Value:** Column chart ranking top customers by total CLV.
* **Top 4 Customers by Premium:** Line chart tracking highest monthly premium contributors.
* **Claim on the Basis of Coverage:** Treemap comparing total claims across **Basic**, **Extended**, and **Premium** coverage tiers.
* **Claim by Vehicle:** Line chart analyzing total claim amounts across vehicle classes (**Four-Door Car**, **SUV**, **Two-Door Car**, **Sports Car**, **Luxury SUV**, **Luxury Car**).

---

### 3. Regional & State Performance (`PLACE`)
Evaluates geographic performance across key US states (**California**, **Oregon**, **Arizona**, **Nevada**, and **Washington**):
* **Income by State:** Bar chart showing **California** (`118M`) and **Oregon** (`91M`) as the top revenue-generating states, followed by Arizona (`64M`), Nevada (`34M`), and Washington (`33M`).
* **Top 5 States by Claim:** Donut chart displaying proportional claim distribution across states.
* **Top 5 States by Lifetime Value:** Column chart ranking states by cumulative Customer Lifetime Value.
* **Top 4 States by Premium:** Line chart comparing total monthly premiums collected across California, Oregon, Arizona, and Nevada.
* **Claim on the Basis of Coverage and State:** Hierarchical treemap breaking down claim volume by coverage type (`Basic`, `Extended`, `Premium`) within each state.
* **Claim of Vehicle on the Basis of State:** Line chart tracking regional claim trends across states.

---

## 🛠️ Tools & Features Used
* **Microsoft Power BI Desktop:** Multi-page interactive dashboard design, custom shape containers, and KPI cards.
* **Custom Navigation & Slicers:** Interactive page navigation buttons (`OVERALL`, `GENDER`, `PLACE`) and dynamic slicers (`Month`, `Gender`, `State`, `Policy Type`, `Vehicle Size`, `Policy`).
* **Data Modeling & Aggregation:** Structured analysis across customer demographics, policy tiers, coverage levels, and regional dimensions (`AutoInsurance` table).

---

## 📸 Dashboard Previews
*(Add your exported PNG screenshots to the repository using these filenames)*
* **Overall View:** `overall_performance.png`
* **Gender View:** `gender_performance.png`
* **Place View:** `place_performance.png`

---

## 📂 Repository Structure
```text
├── Auto_Insurance_Performance.pbix   # Interactive Power BI Desktop report
├── AutoInsurance.xlsx                # Underlying dataset
├── overall_performance.png           # Screenshot of Page 1 (Overall)
├── gender_performance.png            # Screenshot of Page 2 (Gender)
├── place_performance.png             # Screenshot of Page 3 (Place)
└── README.md                         # Project documentation and insights
```

---

## 🚀 How to Use
1. Download **`Auto_Insurance_Performance.pbix`** from this repository.
2. Open it in **Microsoft Power BI Desktop**.
3. Use the bottom-right navigation buttons (**OVERALL**, **GENDER**, **PLACE**) to switch between report views, and apply the top/bottom slicers to filter by state, gender, month, or policy attributes.
