# 🌤️ Weather Data Analytics – Python ile Hava Durumu Analizi

Bu proje, farklı şehirlerden toplanan hava durumu verilerini Python kullanarak analiz etmeyi amaçlamaktadır. Pandas ve NumPy kütüphaneleri yardımıyla veri keşfi, filtreleme, sıralama, gruplama ve temel istatistiksel hesaplamalar adım adım uygulanmıştır.

Çalışma, veri analitiğine giriş seviyesinde yapılabilecek işlemleri kapsayarak hem öğrenme hem de pratik yapma odaklı olarak hazırlanmıştır.

---

## 📌 Projede Yapılanlar


## 🔧 1. Temel Kurulum ve Veri Yükleme
- Pandas ve NumPy projeye dahil edildi  
- `weather_data.csv` DataFrame’e aktarıldı  

---

## 🔍 2. Veri Keşfi
Veri seti üzerinde ilk kontrol adımları gerçekleştirildi:

- İlk ve son satırların incelenmesi (`head()`, `tail()`)  
- Sayısal sütunlara ait özet istatistiklerin görüntülenmesi (`describe()`)  

---

## 🧩 3. Sütunlarla Çalışma
- Date, City, Temperature sütunları seçilerek yeni bir görünüm oluşturuldu  
- City–Temperature ikilileri birlikte listelendi  

---

## 🔎 4. Basit Filtreleme İşlemleri
Veri belirli koşullara göre süzülerek farklı alt kümeler oluşturuldu:

- 30°C üzerindeki sıcaklık değerleri  
- Sadece Bursa şehrine ait kayıtlar  

---

## 🧠 5. Mantıksal Operatörlerle Gelişmiş Filtreleme
Birden fazla koşul bir arada kullanılarak daha detaylı sorgular oluşturuldu:

- İstanbul **AND** Humidity > 60  
- Ankara **OR** Temperature < 5  
- Temperature < 10 **OR** Humidity > 70  

---

## 📊 6. Sıralama (Sorting)
Veriler farklı sütunlara göre yeniden sıralandı:

- Sıcaklığa göre azalan sıralama  
- Neme göre azalan sıralama  
- Şehir isimlerine göre alfabetik sıralama  

---

## ➕ 7. Yeni Sütun Oluşturma
Veri setine iki yeni özellik eklendi:

- **Temperature_F** → Fahrenheit sıcaklık  
- **FeelsLike** → Hissedilen sıcaklık  

---

## 📚 8. Gruplama ve Analiz
Veriler şehir bazında gruplanarak anlamlı özet tablolar çıkarıldı:

- Her şehrin kaç kayıt içerdiği  
- Ortalama sıcaklık değerleri  

---

## 🏆 9. En Yüksek/Düşük Değer Analizi
- En yüksek sıcaklık değerine sahip satır  
- En düşük nem oranına sahip satır  

---

## 💾 10. Dışa Aktarma
Şehirlere göre hazırlanan ortalama sıcaklık tablosu **`sehir_sicakliklari.xlsx`** dosyasına aktarıldı.

---

## 📦 Kullanılan Kütüphaneler
pandas          
numpy       
