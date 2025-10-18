# Wine Quality Prediction Projesi

Bu projede, şarap kalitesini tahmin etmek amacıyla bir veri seti üzerinde çalışılmıştır. Veri seti, şarapların kimyasal özelliklerini içerir ve bu özellikler kullanılarak modeller eğitilmiştir.

Veriye ulaşmak için: [Kaggle](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)

---

## 1. Veri Analizi ve Görselleştirme

- Veri setinin basit istatistikleri (ortalama, medyan, min-max) incelenmiştir.  
- Özellikler arasındaki ilişkileri görmek için çeşitli grafikler (scatter plot, correlation heatmap) oluşturulmuştur.

---

## 2. Model Eğitimi

- İlk olarak, veri üzerinde temel bir model eğitilmiş ve sonuçlar değerlendirilmiştir.  
- Accuracy ve F1-score gibi metrikler kullanılarak modelin başarısı ölçülmüştür.

---

## 3. Feature Engineering

- Veri setine yeni özellikler eklenmiş (örneğin şeker-tuz oranı, SO₂ oranı, asit toplamı vb.).  
- Yeni özelliklerle model yeniden eğitilmiş ve önceki modele göre daha iyi sonuçlar elde edilmiştir.

---

## 4. Model Karşılaştırması

- Son olarak, üç farklı algoritma kullanılmıştır:
  - Random Forest
  - XGBoost
  - LightGBM  
- Bu modellerin performansları karşılaştırılmış ve en iyi sonuç veren model belirlenmiştir.

---

## 5. Sonuç

- Feature engineering ve model karşılaştırmaları, verinin doğru şekilde işlenmesinin ve farklı modellerin denenmesinin tahmin performansını artırdığını göstermiştir.  
- Bu çalışma, hem veri analizi hem de makine öğrenmesi modelleme süreçlerini bir arada göstermektedir.
