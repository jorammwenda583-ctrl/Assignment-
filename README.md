# Assignment-
AI based student academic performance predictions system 
# 🎓 AI-Powered Student Performance Prediction System

An end-to-end web application built with **Spring Boot** and **Weka** to predict student academic outcomes and generate intervention reports.

## 🌟 Key Features
* **Performance Prediction:** Uses Weka (J48 Decision Tree) to forecast student grades.
* **Data Analysis:** Python-based preprocessing using **NumPy** and **Scikit-learn**.
* **Automated Reporting:** Generates student performance PDFs using **iText**.
* **Persistent Storage:** Student records and results managed via **MySQL & JDBC**.

## 🛠️ Tech Stack
* **Backend:** Java 17, Spring Boot, Maven
* **Machine Learning:** Weka (Java), Scikit-learn (Python)
* **Database:** MySQL
* **Frontend:** HTML5, CSS3, JavaScript
* **Reporting:** iText PDF library

## ⚙️ Quick Start
1. **Database Setup:** Run `src/main/resources/schema.sql` in your MySQL Workbench.
2. **Install Dependencies:** ```bash
   mvn clean install
   
