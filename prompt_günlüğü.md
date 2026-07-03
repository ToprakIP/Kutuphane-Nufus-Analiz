# 📋 PROMPT GÜNLÜĞÜ

## Geliştirme Sürecinde Kullanılan Promptlar

**Proje:** Türkiye Kütüphane ve Nüfus Analizi  
**Takım:** [Adınız] & [Arkadaşınızın Adı]  
**Tarih:** 3 Temmuz 2026

---

### 1. Veri Yükleme (Başlangıç)

> **Prompt:** "Try Jupyter'da Excel dosyasını nasıl okurum? xlrd hatası alıyorum."

**Alınan Çıktı:** CSV'ye dönüştürme yöntemi ve pandas ile okuma kodu önerildi.

---

### 2. Veri Dönüştürme (Veri Hazırlama)

> **Prompt:** "Excel'den CSV'ye manuel nasıl dönüştürürüm?"

**Alınan Çıktı:** Excel'de Farklı Kaydet > CSV UTF-8 adımları anlatıldı.

---

### 3. Veri Temizleme (Veri Ön İşleme)

> **Prompt:** "CSV'deki sayısal değerlerdeki boşlukları nasıl temizlerim?"

**Alınan Çıktı:** `str.replace(' ', '').str.replace(',', '')` kullanımı gösterildi.

---

### 4. Veri Temizleme (Veri Ön İşleme)

> **Prompt:** "Türkiye ve Toplam-Total satırlarını nasıl çıkarırım?"

**Alınan Çıktı:** `df_pop[df_pop['İl'] != 'Toplam-Total']` kullanımı gösterildi.

---

### 5. Feature Engineering (Veri Ön İşleme)

> **Prompt:** "Kişi başı kitap sayısı nasıl hesaplanır?"

**Alınan Çıktı:** `df_merged['Kisi_Basi_Kitap'] = Toplam_Kitap / Toplam_Nüfus` formülü verildi.

---

### 6. Görselleştirme (EDA)

> **Prompt:** "Nüfus ve kütüphane kullanımı arasındaki ilişkiyi nasıl görselleştirebilirim?"

**Alınan Çıktı:** Scatter plot (log-log ölçeği) kodu önerildi.

---

### 7. Korelasyon Analizi (EDA)

> **Prompt:** "İki değişken arasındaki korelasyonu nasıl hesaplarım?"

**Alınan Çıktı:** `df_merged['X'].corr(df_merged['Y'])` metodu gösterildi.

---

### 8. Görselleştirme (EDA)

> **Prompt:** "Kitap türlerini bar plot ile nasıl gösteririm?"

**Alınan Çıktı:** matplotlib bar chart kodu verildi.

---

### 9. Modelleme (Makine Öğrenmesi)

> **Prompt:** "Lineer regresyon modeli nasıl kurulur?"

**Alınan Çıktı:** sklearn LinearRegression kullanımı gösterildi.

---

### 10. Model Değerlendirme (Makine Öğrenmesi)

> **Prompt:** "Model performansını nasıl ölçerim?"

**Alınan Çıktı:** R², MSE, RMSE metrikleri ve kodları verildi.

---

### 11. Kümeleme (Makine Öğrenmesi)

> **Prompt:** "K-Means ile illeri kütüphane kullanımına göre nasıl gruplarım?"

**Alınan Çıktı:** sklearn KMeans ve 4 küme oluşturma kodu gösterildi.

---

### 12. Kümeleme (Makine Öğrenmesi)

> **Prompt:** "K-Means sonuçlarını nasıl yorumlarım?"

**Alınan Çıktı:** Küme istatistikleri ve örnek iller ile yorumlama yöntemi anlatıldı.
