# convert_json_to_csv_color
# 📊 Postman JSON → CSV & Excel Formatter

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![pandas](https://img.shields.io/badge/pandas-✔️-orange.svg)](https://pandas.pydata.org/)
[![openpyxl](https://img.shields.io/badge/openpyxl-✔️-green.svg)](https://openpyxl.readthedocs.io/)

🚀 A simple Python script that **parses Postman test run results** (from `.postman_test_run.json` files), extracts key data like response times and status codes, and exports the results to:

- 📄 **CSV file**
- 📊 **Excel file with conditional formatting** for response times.

---

## 📁 Input

Place your Postman JSON result file in the project directory.

```python
input_file = "Functional testing.postman_test_run.json"
