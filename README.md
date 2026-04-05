# loan-interest-prediction
Data Mining project for loan risk classification using MATLAB
# Loan Interest Rate Prediction

# Kredi Faiz Oranı Tahmini

Bu proje, makine öğrenmesi yöntemleri kullanılarak müşterilerin kredi faiz oranı kategorisinin tahmin edilmesini amaçlamaktadır.

Veri Seti
- 164,309 gözlem
- 14 değişken
- Hedef değişken: Interest_Rate (çok sınıflı)

Kullanılan Yöntemler
- Veri ön işleme (eksik veri temizleme, log dönüşümü)
- One-hot encoding
- Normalizasyon
- Lojistik Regresyon (temel model)
- Random Forest (geliştirilmiş model)

Sonuçlar
- Lojistik Regresyon Doğruluğu: %33.96
- Random Forest Doğruluğu: %49.59

 Önemli Bulgular
- Veri setinde sınıf dengesizliği bulunmaktadır
- Random Forest modeli, lineer modellere göre daha başarılı sonuç vermektedir
- Veri ön işleme adımları model performansını doğrudan etkilemektedir

Kullanılan Araçlar
- MATLAB

English Below
This project aims to predict loan interest rate categories using machine learning techniques.

Dataset
- 164,309 observations
- 14 features
- Target: Interest_Rate (multiclass)

Methods
- Data preprocessing (missing values, log transformation)
- One-hot encoding
- Normalization
- Logistic Regression (baseline)
- Random Forest (improved model)

 Results
- Logistic Regression Accuracy: 33.96%
- Random Forest Accuracy: 49.59%

 Key Insights
- Class imbalance significantly affects performance
- Random Forest performs better than linear models
- Preprocessing is critical for model success

 Tools
- MATLAB

- 
