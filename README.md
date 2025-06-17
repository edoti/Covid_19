# 🧠 CORD-19 Veri Seti ile COVID-19 Bilgi Madenciliği

Bu projede, COVID-19 ile ilgili bilimsel makalelerin yer aldığı CORD-19 veri seti kullanılarak **metin madenciliği ve konu modelleme** işlemleri gerçekleştirilmiştir. Projenin amacı, araştırmacıların **öncelikli konuları**, **sıklıkla geçen kavramları** ve **COVID-19 ile ilişkili ilaç isimlerini** analiz edebilecekleri bir temel sunmaktır.

---

## 📦 Kullanılan Veri Seti

- 📍 [CORD-19: COVID-19 Open Research Dataset](https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge)
- ✅ Yayın başlıkları, özetler ve yayın tarihi gibi sütunları içermektedir.
- ⏳ Veri kümesi düzenli olarak güncellenen 100.000+ bilimsel makale bilgisi içerir.

---

## 🎯 Proje Amacı

- Bilimsel makale özetlerinden anahtar kelimeleri çıkarmak
- Konuları kümelere ayırmak (unsupervised learning)
- Zaman içinde yayımlanan makale trendlerini analiz etmek
- COVID-19 ile ilgili **ilaç isimlerini otomatik olarak tespit etmek**

---

## ⚙️ Kullanılan Kütüphaneler

```python
pandas, numpy, matplotlib, seaborn, nltk, re, wordcloud
sklearn.feature_extraction.text.TfidfVectorizer
sklearn.decomposition.PCA
sklearn.cluster.KMeans
