# 🧠 driverMasterData\_database\_table

🚛 **Production-ready Master Data Table for Drivers** in mobility platforms
📊 **Validated, Automated & Optimized** using SQL, Airflow & Python
🛠️ Designed and implemented with industry-grade data engineering practices

---

## 📌 Overview

The `driverMasterData_database_table` project is a robust, production-level pipeline to generate a **single source of truth** for all driver-level attributes across multiple raw and processed data systems.

This repository showcases the **end-to-end ownership** of a critical data table in a real business environment — from validation and data ingestion to automation and fault detection, this project is used to **standardize driver data** for analytics, alerts, and platform-level logic.

---

## ✨ Features

* 🛠️ **SQL Indexing** for fast query performance
* 🔄 **Daily Updates** via Airflow DAGs and Cronjobs
* 🔍 **Input Validations** for schema and value consistency
* 🚨 **Triggers for Falacy Detection** and anomaly reporting
* 🧩 **Modular Design** with plug-and-play data inputs
* 📈 **Compatible with Slack bots**, alert systems, and analytics pipelines

---

## 📂 Project Structure

```bash
.
├── driverMasterData.ipynb       # Core notebook for transformation and integration
├── requirements.txt             # All required Python libraries
├── LICENSE                      # AGPL-3.0 License
├── README.md                    # You're here!
```

---

## ⚙️ Tech Stack

| Layer          | Tools/Technologies                        |
| -------------- | ----------------------------------------- |
| 💻 Programming | Python, SQL (PostgreSQL/MySQL)            |
| 🔄 Automation  | Apache Airflow, CronJob                   |
| 🧪 Validation  | Pandas, Custom Assertions & Schema Checks |
| 📤 Reporting   | Slack API (for alerts), Email Triggers    |
| 🏷️ Storage    | Cloud Data Warehouse / RDS (optional)     |

---

## 🚀 How It Works

1. 🔁 **Daily Ingestion** of multiple raw input sources (driver metadata, ops history, etc.)
2. 🧼 **Pre-processing & Validation** using `pandas`, ensuring only clean data enters pipeline
3. 🧮 **SQL-Optimized Merge** operations into production master table with proper indexing
4. 📅 **Airflow DAG** schedules the job and logs execution metrics
5. 🔔 **Slack Alerts/Email Triggers** notify of anomalies or missing data

---

## 🧪 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/SartHak-0-Sach/driverMasterData_database_table.git
cd driverMasterData_database_table
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

```bash
jupyter notebook driverMasterData.ipynb
```

---

## 📸 Screenshots (Optional)

*Add sample snapshots of the input, final table, or Airflow DAG view here.*

---

## 🧠 Author & Ownership

> Developed end-to-end by **Sarthak Sachdev** as part of the Driver Issues Team at **Battery Smart**.
> I owned this project individually — from initial design to production deployment — and used it in real-world data automation and alerting pipelines.
> Connect with me on [LinkedIn](https://www.linkedin.com/in/sarthak2004/)

---

## 📃 License

This project is licensed under the **AGPL-3.0** License.

---

## ⭐ Want to Support?

If you find this useful or want to reference it for your own production pipeline designs, consider giving it a ⭐!

---

Let me know if you'd like this converted into a `README.md` file directly or pushed to your repo!
