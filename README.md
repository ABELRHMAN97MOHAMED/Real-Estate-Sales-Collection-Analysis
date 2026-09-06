# Real Estate Sales & Collection Analysis

## Project Overview

This Power BI project provides an end-to-end analysis of real estate sales, installment collections, outstanding payments, and financing performance.

The dashboard transforms raw customer and installment data into actionable insights, helping track project performance, collection efficiency, and cash vs. bank financing.

## Tools Used

- Power BI
- Power Query
- DAX
- Figma
- ## Data Cleaning & Transformation

The raw dataset was cleaned and transformed using Power Query to prepare it for analysis.

Key transformation steps included:

- Cleaned and standardized customer and financial data.
- Corrected data types for dates, numeric values, and financial amounts.
- Handled null values, errors, and inconsistent records.
- Standardized bank names and financing categories.
- Separated control and summary rows from actual customer records.
- Restructured 7 installment columns using Unpivot transformation.
- Created installment numbers and sorting logic for correct installment order.
- Extracted paid amounts from text-based installment records.
- Classified installments into Paid, Not Paid, and Not Due.
- Segmented transactions into Cash and Bank Financing.
- Prepared the transformed data for DAX calculations and dashboard analysis.
- ## Data Modeling & DAX Measures

After preparing the data, I built the required calculations and business KPIs using DAX.

Key measures include:

- Total / Adopted Units
- Sold Units
- Project Completion %
- Issued Invoices
- Collected Invoices
- Outstanding Invoices
- Collection Rate %
- Outstanding %
- Invoiced Amount
- Collected Amount
- Outstanding Amount
- Bank Financing Amount
- Records in Current Segment
- Old vs. New Records based on the selected date range

The measures were designed to respond dynamically to report filters and slicers while maintaining accurate calculations across the transformed installment data.
## Dashboard Pages & Analysis

The dashboard was divided into multiple interactive pages to provide different levels of analysis:

### Home Page
- Provides a professional landing page for the report.
- Includes navigation buttons for easy access to all analytical pages.

### Overall Analysis
- Provides a high-level overview of the project's performance.
- Tracks total units, sold records, and project completion.
- Analyzes installment performance across 7 installment stages.
- Compares issued, collected, and outstanding invoices.
- Tracks invoiced, collected, and outstanding amounts.
- Measures collection and outstanding rates.

### Bank Analysis
- Focuses on customers using bank financing.
- Analyzes financed amounts and collection performance.
- Tracks outstanding payments related to bank-financed transactions.

### Cash Analysis
- Focuses on cash-based transactions.
- Provides a separate view of sales and collection performance for cash customers.

### Bank-Wise Analysis
- Compares performance across different banks.
- Helps identify differences in financing and collection performance between banks.

## Dashboard Features

- Interactive filters and slicers
- Dynamic KPI cards
- Installment-level analysis
- Date-based segmentation
- Cash vs. Bank Financing analysis
- Interactive page navigation
- Consistent dashboard design across all report pages
- UI layout designed in Figma and implemented in Power BI

- ## Dashboard Demo

A screen recording of the interactive Power BI dashboard is available below.

The demo showcases:
- Dashboard navigation
- Interactive filters and slicers
- Overall project performance
- Installment collection analysis
- Cash and bank financing analysis
- Bank-wise performance analysis
