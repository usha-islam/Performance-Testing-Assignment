# Performance Testing Assignment (JMeter)

## 📌 Overview
This project contains performance testing scripts for the **Booking API** using Apache JMeter.  
The goal was to perform **load testing** and **stress testing** on the API with different scenarios.

---

## ✅ Prerequisites
- Install [Apache JMeter 5.6.3](https://jmeter.apache.org/)
- Install Java (JDK 8 or higher)
- Clone or download this repository

---

## ▶️ How to Run Tests
1. Open JMeter.
2. Load the test plan file: `booking.jmx`.
3. Run the test in GUI or CLI mode.

### Run from CLI:
```bash
jmeter -n -t booking.jmx -l booking.jtl -e -o report

---

## 🖼️ Screenshots

### Request Summary (Aggregate Report)
### Request Summary (Aggregate Report)
![Aggregate Report 1](screenshots/aggregate-report-1.png)
![Aggregate Report 2](screenshots/aggregate-report-2.png)

### HTML Report Statistics
![HTML Report 1](screenshots/html-report-1.png)
![HTML Report 2](screenshots/html-report-2.png)
![HTML Report 3](screenshots/html-report-3.png)
![HTML Report 3](screenshots/html-report-4.png)

### Excel Reports (Load Test & Stress Test)
![Excel Report 1](screenshots/excel-report-1.png)
![Excel Report 2](screenshots/excel-report-2.png)

---
