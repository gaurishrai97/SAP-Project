# SAP ABAP Project — Custom ALV Report

## GSR Motor Private Limited

**SAP ABAP Project Report**
KIIT University
Submitted by: Gaurish Rai 
Roll no.:23052321
Session: 2025–2026

---

## Overview

This project demonstrates the development of a **Custom ALV (ABAP List Viewer) Report** in SAP ABAP for a fictitious company, **GSR Motor Private Limited**, a remote control car manufacturing organization.

The report provides a consolidated and interactive view of sales order data using SAP standard tables and ALV Grid functionality.

---

## Project Objective

The objective of this project is to:

* Develop a custom ALV report for sales order analysis
* Extract and display data from SAP tables
* Provide dynamic filtering using selection screen
* Enable data visualization with ALV Grid
* Implement business logic for order status

---

## Technologies Used

* SAP ABAP
* ALV Grid (CL_GUI_ALV_GRID)
* SAP Tables: VBAK, VBAP, KNA1

---

## Key Features

* Sales order summary report

* Dynamic selection screen filters:

  * Order Date
  * Sales Organization
  * Customer
  * Material
  * Order Type

* ALV Grid Display:

  * Sorting, filtering, and grouping
  * Automatic column optimization
  * Zebra layout

* Business Logic:

  * Status mapping (Open, In Process, Delivered, Billed)

* Aggregation:

  * Total Net Value calculation

* Export:

  * Excel export support (via ALV)

---

## SAP Tables Used

| Table | Description        |
| ----- | ------------------ |
| VBAK  | Sales Order Header |
| VBAP  | Sales Order Item   |
| KNA1  | Customer Master    |

---

## Program Details

* **Program Name:** ZGSR_SALES_ALV
* **Transaction Code:** ZGSR_SO
* **Type:** Executable Report
* **ALV Type:** OO ALV Grid

---

## How It Works

1. User enters filters in selection screen
2. Data is fetched from VBAK and VBAP
3. Customer data is retrieved from KNA1
4. Internal table is prepared
5. ALV Grid displays the output

---

## Sample Output

The report displays:

* Sales Order Number
* Order Date
* Customer Name
* Material
* Quantity
* Net Value
* Currency
* Status

---

## Business Scenario

The Sales Manager requires a detailed and flexible report beyond standard SAP transactions to:

* Analyze sales orders
* Monitor order status
* Export reports for meetings
* Improve decision-making

---

## Enhancements Implemented

* Status-based classification
* Optimized data retrieval
* Structured modular coding

---

## Notes

* This program is designed to run inside an SAP environment (SAP GUI / NetWeaver)
* It cannot be executed locally

---

## Conclusion

This project demonstrates real-world SAP ABAP development using ALV reporting techniques, showcasing data extraction, business logic implementation, and user-friendly output presentation.

---

## References

* SAP Help Portal
* SAP ABAP Documentation
* SAP Data Dictionary (SE11)
* KIIT SAP ABAP Course Material

---


