**Telecom Customer Churn Prediction**

Bu projede bir telekom şirketinin müşteri kaybını (churn) tahmin etmek için uçtan uca bir makine öğrenmesi modeli geliştirdim.

**Amaç:**

Müşterinin hizmeti bırakma olasılığını tahmin ederek:

Riskli müşterileri belirlemek

Kampanyalar geliştirmek

Gelir kaybını azaltmak

için karar destek modeli oluşturmak.

**Veri Seti:**

Bu projede [Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn) veri seti kullanılmıştır.


**Veri Hazırlama:**

Eksik değer temizleme

Kategorik değişken kodlama (Label Encoding + One-Hot Encoding)

Feature engineering (NumServices, MonthlyChargeRatio, LongTenure, IsAutoPay…)

Outlier analizi

Train-test split (%80–20)

**Kullanılan Modeller:**

Logistic Regression

Random Forest

XGBoost

GridSearchCV ile hiperparametre optimizasyonu

Class imbalance için class_weight ve threshold selection

**Sonuçlar:**

En başarılı model: Random Forest

ROC-AUC, precision, recall, f1-score ile performans ölçüldü

Threshold ayarı ile recall artırıldı

Churn eden müşteri profili çıkarıldı (aylık sözleşme, kısa tenure, yüksek ücret, auto-pay kullanmayanlar…)

**İş Çıktısı:**

Yüksek riskli müşteri segmentleri belirlendi

Sadakat programı, fiyat optimizasyonu ve hedefli kampanya önerileri geliştirildi

İş birimleri için anlamlı öngörüler sunuldu
