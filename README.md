# ⚾ Major League Baseball (MLB) SQL Data Analytics Project

## 📌 Project Overview

This project simulates a real-world data analytics task for **Major League Baseball (MLB)**. I gained access to historical player data and was assigned to analyze trends in player statistics, school contributions, salaries, and team affiliations using **advanced SQL techniques**.

The analysis was performed using **MySQL** and queries were written and executed in **MySQL Workbench**.

---

## 🧠 The Situation

MLB has recently acquired a vast dataset containing decades worth of player statistics, including:
- Schools attended
- Salaries
- Teams played for
- Physical attributes like height and weight

As a data analyst, our assignment was to dig into the data and generate valuable insights using SQL.

---

## 🎯 Objectives

The main goal of this project was to use **advanced SQL querying techniques** to uncover:
- How player stats have changed over time
- Which schools and teams have contributed the most
- Trends in player demographics and career trajectories

---

## 📁 Dataset Tables Used
- `players`
- `schools`
- `schooldetails`
- `salaries`

---

## 📊 Sections and Tasks

### ✅ PART I: SCHOOL ANALYSIS
- **TASK 1**: View the `schools` and `schooldetails` tables
- **TASK 2**: Count of schools that produced players by decade (using Numeric Functions)
- **TASK 3**: Top 5 schools that produced the most players (using Joins)
- **TASK 4**: Top 3 schools per decade with the most players (using Window Functions)

---

### ✅ PART II: SALARY ANALYSIS
- **TASK 1**: Explore the `salaries` table
- **TASK 2**: Identify top 20% teams by average annual spending (Window Functions)
- **TASK 3**: Show cumulative spending over years per team (Rolling Calculations)
- **TASK 4**: Identify the first year each team crossed 1 billion in spending (Min/Max Value Filtering)

---

### ✅ PART III: PLAYER CAREER ANALYSIS
- **TASK 1**: View total number of players in the `players` table
- **TASK 2**: Calculate each player’s age at debut and final game
- **TASK 3**: Identify the starting and ending teams for each player (Joins)
- **TASK 4**: Count players who started & ended on the same team and played for over a decade

---

### ✅ PART IV: PLAYER COMPARISON ANALYSIS
- **TASK 1**: View player data from `players` table
- **TASK 2**: Identify players with the same birthdays (using GROUP_CONCAT / STRING_AGG)
- **TASK 3**: Create a pivot-style summary of batting orientation by team
- **TASK 4**: Analyze how average debut height and weight changed over time (Window Functions)

---

## 🛠️ Tools & Technologies
- **SQL** (MySQL)
- **MySQL Workbench**

---


## 📢 Notes
This project demonstrates strong proficiency in:
- Writing optimized SQL queries
- Using advanced functions like `WINDOW`, `ROLLING`, `PIVOT`,`Joins` and aggregation functions
- Extracting actionable insights from structured relational data

---

