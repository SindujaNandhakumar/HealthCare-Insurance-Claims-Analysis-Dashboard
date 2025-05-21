# HealthCare-Insurance-Claims-Analysis-Dashboard

📘 Project Overview

This project focuses on analyzing healthcare claims data from patients enrolled in ABC Healthcare’s Accountable Care Organization (ACO) using a High Deductible Health Plan (HDHP). The purpose is to evaluate how healthcare costs are distributed between insurance providers and patients, and how these costs vary by state, provider specialty, product line (Commercial vs Medicare), and over time.

A Tableau dashboard has been developed to visualize and summarize key patterns, trends, and outliers in the data.

📂 Dataset Description

The dashboard is built using a claims dataset with the following fields:
Field Name	Description
CLAIM_ID	Unique ID for each insurance claim
PATIENT_ID	De-identified patient identifier
PATIENT_STATE	U.S. state of patient residence
PRODUCT_LINE	Type of insurance plan (Commercial / Medicare)
DATE_OF_SERVICE	Date when medical service was provided
CPT_CODE	Current Procedural Terminology code for the service
CPT_DESCRIPTION	Description of the medical service provided
PROVIDER_NPI	National Provider Identifier for each provider
PROVIDER_SPECIALTY	Provider’s area of medical specialization
TOTAL_PAID_BY_INSURANCE	Amount paid by the insurance provider for the claim
PATIENT_DEDUCTIBLE	Patient’s out-of-pocket deductible for the claim

📊 Dashboard Visualizations & Key Findings
1. Provider Specialty Payment Analysis (Horizontal Bar Chart)

    Goal: Identify top provider specialties by insurance spending.

    Insight:

        Highest-paid specialties are:

            Internal Medicine

            Nurse Practitioner

2. Product Line Cost Trend Over Time (Line Chart)

    Goal: Compare insurance payments over time between Commercial and Medicare product lines.

    Insights:

        Medicare consistently costs more than Commercial plans.

        February 2018 shows a noticeable outlier in Medicare costs (unusually high).

3. Insurance vs Patient Deductible (Scatter Plot)

    Goal: Examine the relationship between what patients pay vs. what insurance pays.

    Data Filtering: Removed outliers where insurance paid > $2,000.

    Insight:

        A weak negative correlation exists—The relation is negative because as the amount paid by the patient increase, the total paid by insurance decreases.

4. Quarterly State-wise Insurance Spending (Bubble Timeline Chart)

    Goal: Analyze insurance spending across states over quarterly periods.

    Insight:

        Massachusetts (MA) had the highest insurance payout in Q3 of 2017.
        Massachusetts(MA)  had the highest insurance payout in Q2 of 2018.



