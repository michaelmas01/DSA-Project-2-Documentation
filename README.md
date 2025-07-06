# DSA-Project-2-Documentation
This is the second project I did for the completion of my Data Analysis Training with DSA - Incubator Hub

# 🧩 Palmora Group HR Analysis

## 📁 Case Study Overview

**Palmoria Group**, a manufacturing company based in Nigeria, has recently come under public scrutiny following a media report titled *“Palmoria, the Manufacturing Patriarchy.”* This spotlight raised serious concerns about **gender inequality**, **gender pay gaps**, and overall **HR practices** across its three regions: Lagos, Abuja, and Kaduna.

In response, the CEO, **Mr. Ayodeji Chukwuma**, assigned the CHRO, **Mr. Yunus Shofoluwe**, to investigate and resolve these emerging issues. As the **HR Analytics consultant**, I was tasked with analyzing Palmoria's HR data and uncovering insights that would support fair, data-driven decisions.

---

## 🎯 Objectives

- Clean and prepare HR datasets for analysis
- Identify patterns and disparities in gender representation, salaries, and performance
- Evaluate compliance with new labor regulations
- Recommend data-backed strategies to improve fairness and equity
- Visualize key insights using **Power BI**

---

## 🧹 Data Cleaning Requirements

The dataset required preprocessing to ensure accuracy and relevance:
- Missing genders were assigned a generic value
- Employees without a salary were removed (no longer with the company)
- Records with `"NULL"` departments were excluded
- Ratings and salary data were cleaned for consistency and formatting

---

## 🧭 Key Insights

### 1️⃣ Gender Distribution (Company-wide, by Region & Department)
- **Overall:** 53.55% Male, 46.45% Female
- **By Region:**
  - Kaduna: 54.11% Male | 45.89% Female
  - Abuja: 52.62% Male | 47.38% Female
  - Lagos: 52.65% Male | 47.35% Female

📌 *Insight:* While fairly balanced, female representation is consistently lower across all regions. Proactive regional hiring and retention policies could support gender parity.

---

### 2️⃣ Performance Ratings by Gender
- "Good" ratings are nearly equal: 89 Male vs. 88 Female
- "Very Good" ratings show higher female performance: 49 Female vs. 41 Male
- "Very Poor" is skewed male: 34 Male vs. 20 Female

📌 *Insight:* Female employees slightly outperform in higher ratings while more male employees fall into lower performance tiers. This could help challenge performance-related gender bias.

---

### 3️⃣ Gender Pay Gap Analysis
- **Average Salary:**
  - Male: `$75,072.93`
  - Female: `$72,135.69`
- **Gap:** `$2,937` (≈ 4.1% more for males)

📌 *Insight:* A measurable pay gap exists. Management should investigate departments and regions with the largest disparities.

📌 *Recommendation:* Break down salaries by **gender + department/region** to guide pay equity adjustments.

---

### 4️⃣ Minimum Salary Compliance ($90,000 Threshold)

#### ❌ **Palmoria is Non-Compliant**
- **654 employees** earn **below $90,000**

#### 📊 Salary Distribution by $10K Bands:
- Most **Abuja** employees fall in the $60K–$80K band
- **Lagos** has more employees earning **$90K+**
- **Kaduna** shows concentration below $90K

📌 *Insight:* A large portion of the workforce falls below the regulatory salary requirement, with regional disparities in pay levels.

---

### 5️⃣ Bonus Allocation (Based on Rating & Department)

- **Highest bonus:** `$9,802.80`
- **Lowest bonus:** `$141.65`

📌 *Insight:* Bonus amounts vary widely, driven by salary and rating. The structure is performance-based but may require review to ensure motivational equity across departments and locations.

---

### 6️⃣ Total Compensation (Salary + Bonus)

- **Lowest Total Pay:** `$28,160`
- **Highest Total Pay:** `$127,096.85`

📌 *Insight:* The wide pay range reflects role and performance diversity. However, large gaps within similar job levels could raise internal equity concerns.

📌 *Recommendation:* Analyze total compensation distribution across **genders, departments, and regions** to improve fairness and retention.

---

### 7️⃣ Total Payout by Region & Company-Wide

- **Company-Wide Total:** `$71.92 million`
- **By Region:**
  - **Kaduna:** 42% of total compensation (highest)
  - **Lagos:** Lowest payout (smaller headcount and fewer high-performing roles)

📌 *Insight:* Kaduna’s high share may reflect department concentration or performance clustering. Further investigation could optimize regional resource distribution.

---

## 📊 Tools Used

- **Power BI** for data modeling, calculations, and interactive dashboards
- **DAX** for custom measures (e.g., bonus, total pay, compliance checks)
- **Power Query** for data transformation
- **Excel** (initial inspection and formatting)

---

## 📁 File Structure
