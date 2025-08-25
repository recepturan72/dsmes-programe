# DSMES Programı Web Uygulaması

Bu proje, **Diyabet Öz Yönetim Eğitim ve Destek (DSMES) Programı** için hazırlanmış bir web uygulamasıdır.  
Katılımcılar, hemşireler ve araştırmacılar için ayrı bölümler içerir.

---

## 📂 Dosya Yapısı

- **index.html**  
  - Ana sayfa (12 modül, eğitim içerikleri, ADCES7 yaklaşımı)  
  - Video ve ödev bağlantıları  

- **odevler.html**  
  - Katılımcıların ödevlerini takip edebileceği sayfa  
  - Toplam 36 ödev (12 modül × 3 ödev)  
  - İlerleme yüzdesi otomatik kaydedilir  

- **nurse_panel.html**  
  - Hemşire takip paneli  
  - Katılımcı ekleme, düzenleme, ilerleme görüntüleme  
  - Mesajlaşma ve not alma özellikleri  

- **raporlar.html**  
  - Detaylı rapor ve analiz sayfası  
  - Katılımcı istatistikleri (tamamlanma oranları, yaş grupları, dağılımlar)  
  - Chart.js ile grafikler  
  - Excel, PDF export ve yazdırma özelliği  

---

## 🚀 Kullanım

1. Tüm dosyaları aynı klasörde bulundur.  
2. **index.html** dosyasını tarayıcıda açarak kullanmaya başla.  
3. İlerlemeler tarayıcıda **localStorage** ile kaydedilir.  
4. Hemşireler için **nurse_panel.html**, raporlar için **raporlar.html** kullanılabilir.  

---

## 🌐 Yayınlama
Proje statik dosyalardan oluşur. Bu yüzden kolayca yayınlanabilir:
- **GitHub Pages**
- **Netlify**
- **Vercel**

---

## 👩‍⚕️ Geliştirici Notları
- Mobil uyumlu (responsive) tasarım yapılmıştır.  
- Dosya tabanlı çalıştığı için sunucu gerekmez.  
- Export fonksiyonlarında sadece şablon uyarıları vardır, geliştirmeye açıktır.  
