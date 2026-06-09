# Cognitive Load Behavioral Analysis

## Overview

This project explores cognitive load through behavioral data collected from computer interactions. Using keystroke dynamics, mouse movement data, inactivity records, and user-reported stress labels, the project investigates how user behavior changes during computer usage.

The analysis focuses on feature engineering, exploratory data analysis (EDA), visualization, and behavioral interpretation using Python.

---

## Project Objective

The goal of this project is to examine whether common computer interaction patterns can provide insights into cognitive load and user behavior without requiring specialized hardware or physiological sensors.

---

## Dataset

Dataset used in this project:

**Stress Detection by Keystroke, App & Mouse Changes**

Source:
https://www.kaggle.com/datasets/chaminduweerasinghe/stress-detection-by-keystrokeapp-mouse-changes

The dataset contains behavioral logs from two users, including:

* Keystroke activity
* Mouse movement data
* Mouse speed records
* Application usage logs
* Inactivity periods
* Self-reported stress and condition labels

The original dataset is publicly available on Kaggle and is therefore not included directly in this repository.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Feature Engineering

The following features were extracted from raw behavioral logs:

### Keystroke Features

* Average key duration
* Average inter-key interval
* Typing speed

### Mouse Features

* Average mouse speed
* Total mouse movement distance

### Inactivity Features

* Average inactivity duration
* Maximum inactivity duration
* Total inactivity duration

### User Condition Features

* Average stress score

---

## Exploratory Data Analysis

The project includes visualizations for:

* Stress distribution
* Inter-key timing patterns
* Mouse speed trends
* Inactivity duration distribution
* Active application frequency
* Cumulative mouse movement distance

---

## Repository Structure

```text
code_final.py
Working_Paper.pdf
EDA Plots.zip
README.md
```

---

## Current Status

Research in Progress

The included paper is a working draft and has not been formally published or peer-reviewed. The project currently focuses on behavioral analysis, feature engineering, and exploratory data analysis.

---

## Future Work

* Analysis using larger participant datasets
* Statistical hypothesis testing
* Additional behavioral feature engineering
* Predictive modeling and machine learning approaches
* Real-time cognitive load monitoring systems

---

## Author

Adit Madan
