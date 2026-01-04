# Student Performance Analysis

Bu projede Kaggle platformundan alınan “Students Performance” veri seti kullanılarak öğrencilerin matematik sınavı başarılarının tahmin edilmesi amaçlanmıştır. Veri seti 1000 gözlem ve 8 değişkenden oluşmaktadır. Eksik veri bulunmamaktadır. Cinsiyet, ebeveyn eğitim seviyesi gibi faktörlerin öğrencilerin performansındaki etkileri araştırılmıştır.

## Kullanılan Adımlar
- Veri Keşfi ve Ön İşleme (Eksik veri kontrolü, kategorik değişkenlerin sayısallaştırılması)
- Eğitim ve test setlerinin ayrılması (%80 / %20)
- Görselleştirme (Matplotlib ve Seaborn ile dağılım ve korelasyon grafikleri)
- Linear Regression Modeli
- Model Değerlendirme (MSE, R² Score)  

## Kullanılan Teknolojiler
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Sonuçlar
- Model test verisi üzerinde R² skoru 0.88, MSE değeri 29.09 olarak elde edilmiştir.
- Model matematik puanlarını yüksek doğrulukla tahmin edebilmektedir.
- Analizler, cinsiyet ve ebeveyn eğitim seviyesi gibi faktörlerin öğrencilerin performansında önemli rol oynadığını ortaya koymaktadır.
- Elde edilen bulgular eğitim alanında veri odaklı karar verme süreçlerini destekleyebilir.
- Gelecekte farklı makine öğrenmesi algoritmaları ile model performansı karşılaştırılabilir.
