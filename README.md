Data Engineering Internship Project: World Happiness Data Pipeline
Internship Context
Position: Data Engineering Intern
Organization: Yasmeen AI
Affiliation: Syrian Community for Data Science and AI
Parent Organization: Alrifai Consulting Group
An automated ETL (Extract, Transform, Load) pipeline that orchestrates data flow from Kaggle to a Supabase PostgreSQL database using Prefect Cloud.

## 🚀 Overview
This project automates the processing of the World Happiness Report. It demonstrates modern data engineering practices including workflow orchestration, cloud-native storage, and automated data cleanup.

## 🛠️ Tech Stack
- **Orchestration:** Prefect Cloud (Task management, state monitoring)
- **Database:** Supabase (PostgreSQL)
- **Language:** Python (Pandas for transformation)
- **Environment:** Google Colab / Linux

## ⚙️ Pipeline Architecture
1. **Cleanup:** Idempotent task that clears existing records in Supabase to prevent duplicates.
2. **Extract:** Programmatic download of 2016 Happiness data via KaggleHub.
3. **Transform:** Data cleaning and mapping to match the PostgreSQL schema.
4. **Load:** Bulk insertion of processed JSON records into the cloud database.

## 📈 Monitoring
The pipeline is monitored via Prefect Cloud, providing real-time visibility into task success, execution time (Gantt charts), and error handling.

---
*Developed as a demonstration of cloud-integrated data orchestration.*
