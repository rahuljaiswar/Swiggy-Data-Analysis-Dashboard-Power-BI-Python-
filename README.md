# Swiggy Data Analysis Dashboard (Power BI + Python)

This project analyzes and visualizes restaurant order data (inspired by Swiggy) using **Python** for data preparation and **Power BI** for dashboard visualization.

---
### 📂 Download the Full Dataset

Due to GitHub's file size limitations, the full dataset files (`Master.csv` and raw CSVs) are hosted externally.

> 📦 **Download from Google Drive**  
> 🔗 [Click here to access the dataset](https://drive.google.com/drive/folders/1haio_Hl5gjGrtlj-t_Tb2ivQgIyiKyGr?usp=sharing)


---
## Dataset Overview

The project uses 5 CSV files:
| File | Description |
|------|-------------|
| `Users.csv` | User demographic and profile data |
| `Restaurant.csv` | Restaurant details including ratings and location |
| `Food.csv` | Food items and type |
| `Menu.csv` | Menu details mapping food to restaurants |
| `Orders.csv` | Order transactions with quantity, sales, and date |

---

## Data Cleaning & Merging (Python)

Python was used to:
- Load all 5 CSV files
- Handle missing values (`Restaurant_id` in `Orders.csv`)
- Merge all tables into a single **Master DataFrame**
- Export to `swiggy_master.csv` for Power BI

---

## Power BI Dashboard
Currently working on it..
