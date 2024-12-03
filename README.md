
# KrediKartFraudTahmini![image-112](https://github.com/user-attachments/assets/a34c5b4c-4080-4aaf-9601-35d999060689)

Dolandırıcılık Tespiti Projesi
Bu proje, ödeme işlemleri verilerini analiz ederek dolandırıcılık (fraud) işlemlerini tespit etmeyi amaçlayan bir makine öğrenimi sistemidir. Veri seti üzerindeki modelleme ve analiz aşamalarıyla, dolandırıcılık işlemlerini doğru bir şekilde tahmin etmek hedeflenmiştir.
# Proje Aşamaları
# 1. Problem Tanımı
Hedef: Ödeme işlemlerinde dolandırıcılık olup olmadığını tahmin etmek.
Hedef Değişken: Fraud (1: Dolandırıcılık, 0: Normal İşlem)
Veri Tipi: Ödeme işlemleri, kullanıcı etkinlik verileri ve geçmiş dolandırıcılık kayıtları.
# 2. Veri Yükleme ve Keşifsel Veri Analizi (EDA)
Veri seti yüklendi ve genel özellikleri incelendi.
Sınıf dengesizliği problemi tespit edildi. Dolandırıcılık işlemleri azınlık sınıf olarak gözlendi.
Verinin özellik dağılımları ve ilişkileri görselleştirildi.
# 3. Veri Ön İşleme
Eksik değerler kontrol edildi ve gerekirse temizlendi.
Kategorik değişkenler One-Hot Encoding yöntemiyle dönüştürüldü.
Sayısal özellikler MinMaxScaler ile ölçeklendirildi.
Sınıf dengesizliği için SMOTE yöntemi uygulandı.
# 4. Modelleme
Kullanılan Algoritma:
Random Forest
# Model Tanımlama: Random Forest modeli, dolandırıcılık işlemlerini tespit etmek için eğitildi.
# Performans Metrikleri:
Kesinlik (Precision)
Geri Çağırma (Recall)
F1 Skoru
ROC-AUC Skoru
# 5. Sonuçlar
Model, dolandırıcılık işlemlerini başarılı bir şekilde tahmin etti ve performans metrikleriyle doğrulandı.
Kullanılan Teknikler
Veri Analizi: Pandas, Numpy
Görselleştirme: Matplotlib, Seaborn
Makine Öğrenimi: Scikit-learn (Random Forest)
Veri Dengesi: SMOTE (Synthetic Minority Oversampling Technique)
# Kaggle :https://www.kaggle.com/code/muhammedhanolu/credit-card-fraud-prediction

