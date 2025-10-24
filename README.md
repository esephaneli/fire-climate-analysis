# fire-climate-analysis
“NASA &amp; NOAA data analysis — Turkey 2024 wildfires and temperature correlation”

# 🔥 Yangın ve İklim Analizi — Türkiye 2024

Bu proje, **küresel sıcaklık anomalileri (NOAA GISTEMP)** ile  
**orman yangını olayları (NASA VIIRS)** arasındaki ilişkiyi 2024 yılı Türkiye verileri üzerinden analiz eder.  
Amaç, küresel ısınmanın yangın sıklığı üzerindeki etkisini veri bilimi yöntemleriyle incelemektir. 🌡️🌳

---

## 📊 Kullanılan Modeller
- **Doğrusal Regresyon (Linear Regression)**
- **Polinom Regresyon (Polynomial Regression)**
- **Rastgele Orman Regresyonu (Random Forest Regressor)**

---

## 🚀 Temel Bulgular
- Basit doğrusal modeller ilişkiyi açıklayamadı (**R² < 0**)  
- Polinom modeller doğrusal olmayan ilişkiyi de yakalayamadı  
- 🌳 **Random Forest modeli R² = 0.56** değeriyle en yüksek performansı gösterdi  
- Bu sonuç, sıcaklık artışının yangın sayısını **doğrusal değil, belirli bir eşik sonrası hızla artırdığını** gösteriyor

---

## 🧠 Kullanılan Araçlar ve Kütüphaneler
- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Scikit-learn  
- Folium  

---

## 🌍 Veri Kaynakları
- **NASA FIRMS (VIIRS Fire Data)** — Uydu tabanlı yangın gözlemleri  
- **NOAA GISTEMP (Global Temperature Anomalies)** — Küresel sıcaklık anomali verisi  

---

## 📈 Proje Adımları
1. NASA VIIRS verilerinden Türkiye’ye ait yangın kayıtlarının alınması  
2. NOAA sıcaklık anomalisi verilerinin 2024 yılına göre filtrelenmesi  
3. Aylık bazda yangın sayısı ve sıcaklık değerlerinin birleştirilmesi  
4. Doğrusal, polinom ve rastgele orman modelleriyle analiz yapılması  
5. Model performanslarının (R², MAE, RMSE) karşılaştırılması  
6. Bulguların görselleştirilmesi ve yorumlanması  

---

## 🧩 Öne Çıkan Bulgular
> 🔹 Basit modeller ilişkiyi gösteremedi, çünkü yangın oluşumları sıcaklığa doğrusal tepki vermiyor.  
> 🔹 Random Forest modeli, sıcaklık ve ay etkileşimini yakalayarak karmaşık örüntüyü ortaya çıkardı.  
> 🔹 2024 yılında Türkiye genelinde yaklaşık **47.000 yangın tespiti** yapıldı.  

---

## 🧾 Sonuç
Bu proje, küresel ısınmanın yangın sıklığı üzerindeki etkisini **veriye dayalı** biçimde incelemektedir.  
Elde edilen sonuçlar, doğadaki süreçlerin genellikle **çok faktörlü ve doğrusal olmayan** bir yapıya sahip olduğunu göstermektedir.  

> “Doğa düz çizgiler takip etmez — iklim etkileri de öyle.”  

---

Veriler NASA ve NOAA tarafından kamuya açık olarak sağlanmaktadır.
