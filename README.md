# E-Ticaret RFM Analizi

Bu proje, e-ticaret verileri üzerinde RFM (Recency, Frequency, Monetary) analizi yaparak müşterileri satın alma davranışlarına göre segmentlemeyi amaçlamaktadır. Amacımız, hedefli pazarlama stratejilerini geliştirmek için anahtar müşteri segmentlerini belirlemektir. Analiz süreci **RFM analysis.ipynb** Jupyter Notebook dosyasında belgelenmiştir.

## Proje Süreci
1. **Veri Kaynağı**: Veriler, bir e-ticaret platformuna ait işlem verilerini içeren **e-comerce.csv** dosyasından alınmıştır.
2. **RFM Analizi**: **RFM analysis.ipynb** notebook dosyası, her müşteri için RFM skorlarını hesaplayarak onları satın alma davranışlarına göre segmentlere ayırmak için Python kullanmaktadır.

## Kullanılan Teknolojiler
- **Python**: Veri analizi ve işleme için.
- **Pandas**: Veri düzenleme ve manipülasyon için.
- **Jupyter Notebook**: RFM analiz sürecini belgeleme ve yürütme için.

## Analiz İçeriği
- **Recency**: Müşterinin en son satın alma zamanını analiz eder.
- **Frequency**: Her müşterinin yaptığı satın alma sayısını hesaplar.
- **Monetary**: Her müşterinin toplam harcama tutarını hesaplar.

RFM skorlarına göre müşteriler "En İyi Müşteriler," "Risk Altında" ve "Uyuyanlar" gibi gruplara ayrılır ve bu segmentler, müşteri davranışlarını anlamaya ve hedefli pazarlama faaliyetlerine olanak tanır.

---

# E-Commerce RFM Analysis

This project involves performing an RFM (Recency, Frequency, Monetary) analysis on e-commerce data to segment customers based on their purchasing behavior. The objective is to identify key customer segments to improve targeted marketing strategies. The analysis is documented in the **RFM analysis.ipynb** Jupyter Notebook.

## Project Workflow
1. **Data Source**: The data is sourced from **e-comerce.csv**, containing transactional data from an e-commerce platform.
2. **RFM Analysis**: The **RFM analysis.ipynb** notebook uses Python to calculate RFM scores for each customer, segmenting them based on purchasing behavior.

## Technologies Used
- **Python**: For data analysis and processing.
- **Pandas**: For data manipulation.
- **Jupyter Notebook**: For documenting and running the RFM analysis process.

## Analysis Overview
- **Recency**: Analyzes the time since a customer’s last purchase.
- **Frequency**: Counts the number of purchases made by each customer.
- **Monetary**: Calculates the total amount spent by each customer.

Using RFM scores, customers are segmented into groups such as "Best Customers," "At Risk," and "Hibernating," providing insights into customer behavior and enabling targeted marketing actions.
