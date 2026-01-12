# 🚢 Titanic Survival Prediction (Veri Analizi Dönem Projesi)

Bu proje, **Veri Analizi** dersi kapsamında, ünlü **Titanic veri seti** kullanılarak yolcuların hayatta kalma durumlarını tahmin etmek amacıyla geliştirilmiştir. Projede Python programlama dili ve Makine Öğrenmesi algoritmaları kullanılmıştır.

## 🎯 Projenin Amacı
Titanik faciasında yolcuların yaş, cinsiyet, bilet sınıfı gibi özelliklerini inceleyerek; bir yolcunun hayatta kalıp kalamayacağını tahmin eden bir model geliştirmek.

## 📂 Veri Seti
Projede kullanılan veri seti **Kaggle** platformundan temin edilmiştir.
* **Kaynak:** [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)
* **Problem Tipi:** Sınıflandırma (Classification)

## 🛠️ Kullanılan Teknolojiler ve Kütüphaneler
Proje **Python** dili ile **Google Colab** ortamında geliştirilmiştir.
* **Pandas & NumPy:** Veri işleme ve temizleme.
* **Matplotlib & Seaborn:** Veri görselleştirme (EDA).
* **Scikit-learn:** Makine öğrenmesi modeli (Logistic Regression) ve başarı metrikleri.

## 📊 Proje Adımları
1. **Veri Keşfi (EDA):** Veri setindeki eksik değerler (Yaş vb.) analiz edildi ve görselleştirildi.
2. **Ön İşleme:**
   * Eksik yaş değerleri ortalama ile dolduruldu.
   * Kategorik veriler (Cinsiyet: Kadın/Erkek) sayısal verilere (0/1) dönüştürüldü.
3. **Model Kurulumu:** `LogisticRegression` algoritması kullanılarak model eğitildi.
4. **Değerlendirme:** Modelin başarısı test verisi üzerinde ölçüldü.

## 📈 Sonuçlar
Model, test veri seti üzerinde yapılan değerlendirmede yaklaşık **%80** doğruluk (accuracy) oranına ulaşmıştır. Ayrıca karmaşıklık matrisi (confusion matrix) ile modelin performansı görselleştirilmiştir.

## 🚀 Nasıl Çalıştırılır?
1. Bu repodaki `.ipynb` uzantılı dosyayı indirin.
2. [Google Colab](https://colab.research.google.com/) adresine gidin.
3. Dosyayı yükleyin (`File` > `Upload Notebook`).
4. Kod hücrelerini sırasıyla çalıştırın.

---
**Hazırlayan:** [Mehmet Bekir Sürmeli]
