# 🧹 Data Sweeper - Sterling Integrator

Welcome to **Data Sweeper**, a Streamlit-based data transformation and cleaning tool, designed and developed by **Vandana Chohan** as a Quarter 3 project!

This app allows you to:

- ✅ Upload CSV and Excel files
- ✅ Clean data (remove duplicates, fill missing values)
- ✅ Select specific columns
- ✅ Visualize numeric data
- ✅ Convert and download files in CSV or Excel formats

---

## 🌟 Features

- 📂 **Multi-file upload**: Accepts multiple `.csv` or `.xlsx` files.
- 🧼 **Data cleaning**:
  - Remove duplicate rows.
  - Fill missing values with mean (numeric columns).
- 👁 **Preview & Selection**:
  - View the first few rows of the uploaded file.
  - Choose which columns to keep.
- 📊 **Data Visualization**:
  - Auto-generate simple bar charts for numeric data.
- 🔁 **Convert & Download**:
  - Convert between CSV and Excel formats.
  - Instantly download the transformed file.

---

## 🚀 Getting Started

### 🛠 Prerequisites

Ensure you have Python and the following libraries installed:

```bash
pip install streamlit pandas openpyxl
