# 🛍️ Fashion Retail Sales Insights (Simulated Real-Time)

This project performs an end-to-end analysis of a large fashion retail dataset using PySpark. It simulates a real-time streaming architecture using Kafka (described via markdown) but is executed entirely via local batch processing.

## 🔍 Key Analyses
- 💳 Payment method breakdown (Cash vs Credit Card)
- 💸 Revenue loss via credit card merchant fees
- 📈 Monthly sales trends and seasonality
- ⭐ Product rating distribution and recommendations for removal

## 🧪 Simulated Kafka Pipeline (Not Executed)
While actual Kafka streaming is not used, markdown cells show:
- Kafka Producer to emit events from CSV
- Kafka Consumer to process events with PySpark
- Architecture and code structure for real-time capability

## 🧰 Tech Stack
- **PySpark** for scalable processing
- **Matplotlib & Seaborn** for visualization
- **Parquet** as local data storage
- **Markdown** for simulated real-time explanation

## 📁 Folder Structure
