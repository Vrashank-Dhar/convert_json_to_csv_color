<h1 align="center">📊 Postman JSON Parser & Formatter</h1>

<p align="center">
  Converts Postman test run JSON files into <strong>CSV</strong> and <strong>Color-Coded Excel</strong> reports.<br>
  🔍 Perfect for analyzing API performance at scale.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/pandas-✔️-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/openpyxl-✔️-green?style=flat-square"/>
</p>

---

## 🚀 Overview

This script takes a `.postman_test_run.json` file from Postman’s CLI/Collection Runner and transforms it into:

- 📄 A clean, tabular **CSV**
- 📊 An **Excel file** with conditional formatting based on response time

Use it to quickly spot slow endpoints, failed responses, or inconsistent API behavior.

---

## 📂 Input

```bash
Functional testing.postman_test_run.json
