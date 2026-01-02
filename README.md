# Makine Öğrenmesi – Ara Sınav Mazeret Ödevi  
**Topkapı Üniversitesi**

## Dataset
- Breast Cancer Wisconsin (scikit-learn)
- 30 sayısal özellik, ikili sınıflandırma
- Eksik veri bulunmamaktadır

## Veri Ön İşleme
- Eksik değer kontrolü yapılmıştır
- Aykırı değer analizi IQR yöntemi ile gerçekleştirilmiştir
- Veriler StandardScaler kullanılarak ölçeklendirilmiştir

## Keşifsel Veri Analizi (EDA)
- İstatistiksel özetler (mean, median, std, min–max, Q1–Q3)
- Pearson korelasyon matrisi ve ısı haritası
- Boxplot grafiklerle aykırı değer eğilimleri incelenmiştir

## Veri Bölme
- %70 Eğitim (Train)
- %10 Doğrulama (Validation)
- %20 Test

## Boyut İndirgeme
- PCA: Açıklanan varyansa göre bileşen seçimi yapılmıştır
- LDA: n_components = 3 olarak uygulanmıştır
- PCA ve LDA için 2D scatter plot görselleştirmeleri yapılmıştır

## Makine Öğrenmesi Modelleri
- Logistic Regression  
- Decision Tree  
- Random Forest  
- XGBoost  
- Gaussian Naive Bayes  

Modeller; ham veri, PCA ve LDA temsilleri ile ayrı ayrı eğitilmiştir.

## Model Değerlendirme
- Validation metrikleri: Accuracy, Precision, Recall, F1-score, ROC-AUC
- En iyi model validation sonuçlarına göre seçilmiştir
- Test seti üzerinde confusion matrix ve ROC eğrisi çizilmiştir

## XAI – SHAP Analizi
- En iyi model için SHAP analizi yapılmıştır
- Summary plot ve bar plot oluşturulmuştur
- PCA ve LDA temsilleri için SHAP karşılaştırması yapılmıştır

## Not
Bu repoda tüm kodlar, grafikler, metrikler ve açıklamalar eksiksiz olarak yer almaktadır.
