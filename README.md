# 📄 DDDS – Acceptance Test Report

🛠️ **Project**: Driver Drowsiness Detection System (DDDS)  
🎓 **Course**: Computer Engineering – Graduation Project  
👨‍💻 **Prepared by**: Khaled Alrefai  
👩‍🏫 **Advisor**: Prof. Emel Koç  
📅 **Submitted**: April 14, 2025

---

## 📘 What This Repo Contains

This repository includes the full Acceptance Test Report and accompanying modular test breakdowns for the DDDS project.

It complements the core [DDDS implementation repo](https://github.com/Kaldx5/Driver-Drowsiness-Detection-System) by focusing on:
- System verification  
- Modular testing methodology  
- IEEE 829-style documentation

---

## 📂 Folder Structure

| Folder | Contents |
|--------|----------|
| `/report/` | Final test report in PDF format |
| `/test-results/` | Stage-by-stage Markdown summaries (Capture, Processing, Alerting) |

---

## ✅ Test Overview

| Metric       | Value      |
|--------------|------------|
| Total Tests  | 14         |
| ✅ Pass      | 11         |
| ⚠️ Partial   | 1          |
| ⏳ Pending   | 1          |
| ❌ Fail      | 1          |
| **Success Rate** | **78.6%** |

> These results reflect real-time validation from live testing and simulated integration steps.

---

## 🔍 Key Validated Features

- 📷 Real-time frame capture using OpenCV  
- 🧠 Eye state detection with trained CNN (Keras `.h5`)  
- 🚨 Drowsiness alert after sustained eye closure  
- 🚫 Blink suppression logic (tolerant of short blinks)  
- ✅ Offline-ready (no cloud/API dependencies)

---

## 🔗 Related Repository

For source code, ML model, and system diagrams:  
👉 [Driver-Drowsiness-Detection-System](https://github.com/Kaldx5/Driver-Drowsiness-Detection-System)

---

## 🧩 Final Notes

This report reflects not just functionality, but **the engineering mindset** behind every tested component — planning, experimentation, debugging, and adaptation. For more context, see the related [Graduation Project Booklet](#) _(coming soon)_.

---
