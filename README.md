# Customer Segmentation - Online Retail Dataset

Project ini melakukan segmentasi pelanggan pada dataset transaksi ritel online 
menggunakan pendekatan RFM Analysis (Recency, Frequency, Monetary) yang dikombinasikan 
dengan algoritma K-Means Clustering.

## Dataset
Link Dataset : https://archive.ics.uci.edu/dataset/352/online+retail
Online Retail Dataset (UCI Machine Learning Repository) - berisi 541.909 transaksi 
dari perusahaan ritel online UK periode 2010-2011.

## Metodologi
1. Data cleaning (handling missing value, transaksi cancel, outlier)
2. Feature engineering RFM
3. Penentuan jumlah cluster optimal (Elbow Method & Silhouette Score)
4. Clustering dengan K-Means
5. Profiling dan interpretasi tiap segmen

## Tools
Python, Pandas, Scikit-learn, Matplotlib, Seaborn

## Struktur
- `customer_segmentation.ipynb` - notebook utama
- `Online_Retail.xlsx` - dataset
- `customer_segmentation_result.csv` - hasil segmentasi
