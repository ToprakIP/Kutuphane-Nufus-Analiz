# 📊 Türkiye Kütüphane ve Nüfus Analizi

Türkiye'deki illerin nüfus özellikleri ile kütüphane kullanımı arasındaki ilişkinin incelendiği veri bilimi dönem projesi.

---

## 👥 Proje Ekibi Bilgileri

| Öğrenci Numarası | Ad Soyad |
|------------------|----------|
| 1306240021 | Toprak Mayda |
| 1306240045 | Eylül Sena Baş |

| Bilgi | Detay |
|-------|-------|
| **Ders** | Veri Bilimi |
| **Teslim Tarihi** | 3 Temmuz 2026, 12:30 |
| **Çalışma Şekli** | 2 Kişilik Grup |

---

## 📂 Veri Kaynakları

| Veri Seti | Kaynak | Yıl | Lisans |
|-----------|--------|-----|--------|
| Nüfus Verisi | TÜİK - Adrese Dayalı Nüfus Kayıt Sistemi | 2025 | Kamuya Açık Veri |
| Kütüphane Verisi | TÜİK - Kütüphane İstatistikleri | 2025 | Kamuya Açık Veri |

**Veri Dosyaları:**
- `tablo_nüfus - t3.csv` - İl bazında nüfus, cinsiyet, kırsal/kentsel dağılım
- `tablo_kütüphane.xlsx - t5.csv` - İl bazında kütüphane sayısı, kitap türleri

---

## 🔍 Proje İçeriği

### Araştırma Soruları
1. Nüfus yoğunluğu ile kütüphane kullanımı arasında ilişki var mı?
2. Kişi başına düşen kitap sayısı en yüksek iller hangileri?
3. Hangi kitap türü daha baskın?

### Yapılan Analizler
- Veri yükleme ve temizleme
- Keşifsel veri analizi (EDA)
- 4 farklı görselleştirme
- Lineer regresyon modeli
- K-Means kümeleme
- Sonuçların yorumlanması

---

## 🛠️ Kullanılan Kütüphaneler

| Kütüphane | Versiyon | Kullanım Amacı |
|-----------|----------|----------------|
| pandas | 1.5.0+ | Veri işleme ve analiz |
| numpy | 1.23.0+ | Sayısal işlemler |
| matplotlib | 3.5.0+ | Veri görselleştirme |
| scikit-learn | 1.1.0+ | Modelleme (Regresyon, Kümeleme) |
| warnings | - | Uyarıları gizleme |

---

## 🚀 Projeyi Çalıştırma Talimatları

### 1. Gereksinimleri Yükleyin

```bash
pip install pandas numpy matplotlib scikit-learn