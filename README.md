# 🏠 Kira Tahminleme Sistemi – DFA Teknoloji Staj Değerlendirme Projesi

Bu proje, DFA Teknoloji 2025 yaz dönemi staj başvurusu için teknik değerlendirme kapsamında hazırlanmıştır.  
Amaç, Türkiye'deki konutların özelliklerine göre kira fiyatlarını tahmin edebilen bir makine öğrenmesi modeli geliştirmektir.

## 👨‍💻 Geliştirici

**Ömer Daşçi**  
Gümüşhane Üniversitesi – Yazılım Mühendisliği  
2025 Mezunu Adayı

## 🧪 Kullanılan Teknolojiler

- Python 3
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- XGBoost

## 📊 Model Performansı (Test Verisi)

| Model                   | RMSE (₺)     | R² Skoru |
|------------------------|--------------|----------|
| Random Forest (tuned)  | 677,836.67   | 0.5977   |
| XGBoost (tuned)        | **647,896.29** | **0.6325** ✅ |

## 📁 Proje Dosyaları

| Dosya Adı        | Açıklama |
|------------------|----------|
| `DFA_Proje.ipynb` | Jupyter Notebook dosyası (asıl analiz ve modelleme).  
| `DFA_Proje_HTML_Rapor.html`  | HTML çıktısı. Tarayıcıdan incelemek için rapor.  
| `DFA_Proje_Pdf_Rapor.pdf`   | PDF çıktısı. Rapor.  
| `home_price.xlsx` | Kullanılan veri seti.  
| `.ipynb_checkpoints/` | Otomatik kayıt klasörü (göz ardı edilebilir).  

---

📌 Bu projede elde edilen çıktılar ve metodoloji, gerçek dünya problemlerine uygulanabilir sağlam bir makine öğrenmesi yaklaşımı sunmaktadır.
