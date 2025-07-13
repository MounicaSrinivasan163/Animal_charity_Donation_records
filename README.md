# Animal_charity_Donation_records
# 🐾 Animal Charity Donation Records Analysis

This repository contains a cleaned dataset and analysis of **10,000 donation records** made to an animal charity. The aim is to explore donation behavior, demographics, and campaign performance through pandas-based data analysis.

---

## 📄 Dataset Overview

- **File Name:** `animal_charity_donation_records.csv`
- **Total Records:** 10,000 donations
- **Time Period:** Multiple years (ending in mid-2025)
- **Use Case:** Donor segmentation, campaign analysis, retention study, and performance insights

---

## 📊 Feature Classification: Categorical vs Continuous

| Feature Name         | Type         | Description                                      |
|----------------------|--------------|--------------------------------------------------|
| `donor_id`           | Categorical  | Unique identifier for each donor                 |
| `age_group`          | Categorical  | Donor's age group (e.g., 18–29, 30–49)           |
| `gender`             | Categorical  | Donor's gender                                   |
| `name`               | Categorical  | Donor's name (not used in analysis)              |
| `email`              | Categorical  | Donor's email (not used in analysis)             |
| `country`            | Categorical  | Donor's country                                  |
| `donation_type`      | Categorical  | Monthly or One-time donation                     |
| `donation_amount`    | **Continuous**| Amount donated in USD                            |
| `donation_date`      | Categorical  | Date of donation (used as timestamp)             |
| `payment_method`     | Categorical  | E.g., Paypal, Bank Transfer                      |
| `newsletter_opt_in`  | Categorical  | Boolean flag whether donor opted into newsletter |
| `referral_channel`   | Categorical  | Source of referral (e.g., Website, Social Media) |
| `sector`             | Categorical  | Donor’s industry or professional sector          |
| `campaign`           | Categorical  | Campaign associated with the donation            |

---

## The colab analysis contains:

-*Data Reading*

-*Data Preprocessing/cleaning*

-*Pandas Analysis*

-*Encoding*

-*Correlation Analysis*

-*Statistical Analysis*

## 📌 Key Analysis Highlights

### 🟢 Medium-Level Questions Answered:
1. Total donation amount received
2. Average donation amount by gender
3. Donation counts by type (One-time vs Monthly)
4. Top 5 countries by total donation
5. Monthly donation count trend
6. Most common payment method
7. Average donation by age group
8. Top referral channels by donation total
9. Most popular campaign by number of donations
10. Percentage of donors who opted into the newsletter

### 🔷 Complex-Level Analysis Performed:
1. **Donation retention rate** – % of repeat donors (result: 0%)
2. **Age group with highest monthly donation** – 50–65 years
3. **Monthly donation trend** – Peaks around Sep 2023 and Apr 2025
4. **Best-performing donor sector** – "Others", followed by "Finance"
5. **Newsletter opt-in impact by gender** – Opted-in males donate more on average

---

## 🛠 How to Run the Analysis

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/animal-charity-analysis.git
   cd animal-charity-analysis
