# 🚗 Urban Routes – Requirements Analysis & Test Design

## 🗓️ Project Details

- **Type:** QA Bootcamp Project (TripleTen LatAm)  
- **Execution Date:** February 2025  
- **Status:** Completed and Approved

---

## 📌 Project Overview

This project focuses on **requirements analysis and test design** for the **Car Sharing** feature in the **Urban Routes** application.  
The objective was to analyze incomplete requirements, identify gray areas, and design structured QA artifacts **before test execution**, applying industry-standard QA techniques.

---

## 🛠️ Tools & QA Techniques

### Tools
- Google Sheets – Test design and equivalence classes  
- Draw.io – Mind maps and flowcharts  
- Google Drive – Documentation storage  

### QA Techniques
- Requirements Analysis  
- Equivalence Class Partitioning (ECP)  
- Boundary Value Analysis (BVA)  
- Flowchart Modeling  

---

## 🧠 Mind Map – “Add Driver License” Feature

A **mind map** was created to visually decompose the **“Add Driver License”** field and its modal window, focusing on:

- UI elements
- Valid and invalid inputs
- Negative scenarios
- Identified gray areas in requirements

<img width="1456" height="742" alt="driver-license-mindmap" src="https://github.com/user-attachments/assets/f27cba19-2cc6-4544-aad4-659e056bd2d3" />

🔗 **Mind Map (PDF):**  
👉 *[[Insert Google Drive link]](https://shorturl.at/ITKKX)*

---

## 🔁 Flowchart – Speed Selection Logic

A **flowchart** was designed to represent how the system selects the **vehicle speed** based on the **departure time**.  
Only the decision logic was modeled, not the full application flow.

<img width="587" height="826" alt="flow-chart-speed-logic" src="https://github.com/user-attachments/assets/07753637-c708-4bd0-aff8-67561e27ed46" />

🔗 **Flowchart (PDF):**  
👉 *https://shorturl.at/CSnKp*

---

## 🧪 Equivalence Class Partitioning

### Part 1 – Driver License Form (Name & Last Name)

Equivalence classes and boundaries were defined to cover:

- Latin and non-Latin characters  
- Spaces, hyphens, numbers, punctuation  
- Valid length (2–14 characters)  
- Invalid length (<2 and ≥15 characters)  
- Empty field validation  

🔗 **Equivalence Classes – Part 1 (Google Sheets):**  
👉 *https://docs.google.com/spreadsheets/d/1HaRHgA_14NaaBFu6sEmgLX52liU9s86t/edit?usp=sharing&ouid=110773353333564353107&rtpof=true&sd=true*

---

### Part 2 – Trip Calculation Logic

Equivalence classes were defined for:

- **Distance:** 0 and > 0  
- **Departure time intervals:**  
  - 00:01–08:00  
  - 08:01–12:00  
  - 12:01–18:00  
  - 18:01–22:00  
  - 22:01–00:00  

🔗 **Equivalence Classes – Part 2 (Google Sheets):**  
👉 *https://docs.google.com/spreadsheets/d/1HaRHgA_14NaaBFu6sEmgLX52liU9s86t/edit?usp=sharing&ouid=110773353333564353107&rtpof=true&sd=true*

---

## 🧾 Test Case Design

Test cases were designed to validate **trip duration and pricing logic** using the following formulas:

Trip Duration = Distance/Speed
Price = Trip Duration x Price per Minute


Scenarios include boundary conditions and the edge case where **distance = 0**.

🔗 **Test Cases – Price & Duration (Google Sheets):**  
👉 *https://docs.google.com/spreadsheets/d/1HaRHgA_14NaaBFu6sEmgLX52liU9s86t/edit?usp=sharing&ouid=110773353333564353107&rtpof=true&sd=true*

---

## 🎯 Key Takeaways

- Strong focus on **QA thinking before execution**
- Clear requirement decomposition and visualization
- Proper application of ECP, BVA, and flow modeling
- Real-world QA documentation aligned with industry practices

## 🌐 Language Note (Important)

> ⚠️ **Documentation Language Notice**  
All test cases and bug reports for this project were originally created and delivered in **Spanish**, as required by the project guidelines at the time of execution.

To preserve authenticity and avoid misinterpretation, the original documents have been kept in Spanish.  
This README provides a **clear English summary** of the scope, execution, and results for international reviewers.


