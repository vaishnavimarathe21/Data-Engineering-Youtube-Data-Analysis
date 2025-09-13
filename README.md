# AWS Data Engineering YouTube Data Analysis Project

#### Note: The QuickSight dashboards created for this project are not publicly shareable. Access is restricted to QuickSight users who have been granted permission. Screenshots and a PDF version of the dashboard have been provided in this repository for reference.

---

## 📄 Project Summary

This project showcases an end-to-end AWS data engineering solution for analyzing global YouTube trending video data. A scalable, cloud-native pipeline was built to ingest, process, and analyze large volumes of structured and semi-structured data. By integrating services like S3, Glue, Lambda, Athena, and QuickSight, the project delivers actionable insights into video performance and audience engagement trends across different regions, presented through dynamic dashboards.

---

## ✅ Project Goals Achieved

1. **Data Ingestion** — A mechanism was built to ingest data from different sources.
2. **ETL System** — Data in raw format was transformed into the proper format.
3. **Data Lake** — A centralized repository was established to store data from multiple sources.
4. **Scalability** — The system was ensured to scale with the increasing size of data.
5. **Cloud Integration** — AWS was utilized to process vast amounts of data efficiently.
6. **Reporting** — A dashboard was developed to obtain insights from the data.

---

## 🛠️ Services Utilized

1. **Amazon S3** — Object storage service was employed, ensuring scalability, data availability, security, and performance.
2. **AWS IAM** — Identity and access management was utilized to manage access to AWS services and resources securely.
3. **QuickSight** — A scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service was implemented.
4. **AWS Glue** — A serverless data integration service was utilized to discover, prepare, and combine data for analytics, machine learning, and application development.
5. **AWS Lambda** — Computing service was used to run code without creating or managing servers.
6. **AWS Athena** — Interactive query service for S3 was employed, eliminating the need to load data as it stays in S3.

---

## 📂 Dataset Employed

**Link:** [YouTube Trending Videos Dataset on Kaggle](https://www.kaggle.com/datasets/datasnaek/youtube-new)

- The dataset contains statistics on daily popular YouTube videos from multiple countries over several months.
- Up to 200 trending videos per day for each region were analyzed.
- Data fields include video title, channel title, publication time, tags, views, likes, dislikes, description, comment count, and category ID (linked via a region-specific JSON file).

---

## 🗺️ Architecture

![Architecture](https://github.com/vaishnavimarathe21/Data-Engineering-Youtube-Data-Analysis/blob/main/architecture.jpeg)

---

## 📊 Dashboard Access

The QuickSight dashboards are not publicly shareable. Screenshots and a PDF version have been included in this repository for reference.

---

## 👩‍💻 Author

**Vaishnavi Marathe**
- GitHub: [@vaishnavimarathe21](https://github.com/vaishnavimarathe21)
- Email: marathekhushi6@gmail.com

---

## 🚀 Explore

Feel free to explore this repository to view architecture diagrams, dataset details, ETL scripts, and dashboard screenshots for deeper insights into the solution.

---
