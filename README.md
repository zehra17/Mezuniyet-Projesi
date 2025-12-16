# 📚 EduPath: Eğitimde Fırsat Eşitsizliği Simülatörü  
### *Görünmez Engelleri Görünür Kılmak*

## 🚀 Genel Bakış

**EduPath**, Birleşmiş Milletler **Sürdürülebilir Kalkınma Hedefi 4 (Nitelikli Eğitim)** kapsamında geliştirilmiş, **interaktif ve veri odaklı** bir simülasyon aracıdır.

Proje; öğrencilerin **sosyo-ekonomik arka planı**, **teknolojik erişimi** ve **aile desteği** gibi kritik faktörlerin akademik potansiyel üzerindeki etkisini somut bir **Fırsat Puanı** üzerinden ölçer ve görselleştirir.

Kullanıcıyı doğrudan bu eşitsizliğin içine yerleştirerek, soyut kavramları **ölçülebilir ve karşılaştırılabilir** hale getirmeyi amaçlar.

---

## ✨ Özellikler

- **10 Kritik Faktör**  
  Öğrencinin çevresel ve ekonomik koşullarını belirleyen 10 ana değişken.

- **Fırsat Puanı Hesaplaması**  
  Seçimlere göre **100 üzerinden normalize edilmiş** bir skor üretimi.

- **Detaylı Metrik Raporu**  
  Fırsat Puanını şu metriklere dönüştürür:
  - Etkili Çalışma Süresi  
  - Kaynak Erişim İmkânı  
  - Akademik Başarı İhtimali  

- **Karşılaştırmalı Analiz**  
  Kullanıcı profili, ideal koşullara sahip bir öğrenci profiliyle kıyaslanır.

- **Çözüm Odaklı Yaklaşım**  
  Sadece farkındalık değil, **yapısal sorunlara yönelik somut eylem önerileri** sunar.

- **Tek Sayfalık Uygulama (SPA)**  
  HTML, CSS (Bootstrap) ve **Vanilla JavaScript** kullanılarak **tek dosya** halinde geliştirilmiştir.

---

## 🛠️ Kullanım ve Kurulum

EduPath, **tamamen bağımsız** çalışır.  
Sunucu, framework veya ek kurulum gerektirmez.

### Adımlar

1. **Projeyi İndirin**  
   `edupath_simulation.html` dosyasını bilgisayarınıza indirin.

2. **Çalıştırın**  
   Dosyayı çift tıklayarak herhangi bir modern tarayıcıda açın  
   (Chrome, Firefox, Edge vb.).

3. **Başlatın**  
   Ana ekrandaki **“Deneyimi Başlat”** butonuna tıklayarak  
   10 soruluk simülasyona girin.

---

## ⚙️ Teknik Yapı

| Bileşen     | Kullanım Amacı                                                  | Notlar                         |
|------------|------------------------------------------------------------------|--------------------------------|
| **HTML**   | Sayfa yapısı ve 4 ana modül (Giriş, Simülasyon, Sonuçlar, Çözümler) | Tek dosya (SPA)                |
| **CSS**    | Tasarım ve duyarlılık (Responsive Design)                        | Bootstrap 5.3 CDN              |
| **JavaScript** | Sayfa geçişleri, puanlama ve metrik hesaplamaları              | Vanilla JS                     |

### Temel Fonksiyonlar

- `calculateScore()`  
- `renderMetrics()`  
- `SCORE_MAPPING` → Faktör ağırlıklarının yönetimi

---

## 📊 Puanlama Mekanizması

Nihai **Fırsat Puanı**, kullanıcının her soruda yaptığı seçimlere atanmış puanların toplamı ile hesaplanır.

- Maksimum skor: **100**
- Yüksek ağırlıklı faktörler:
  - Aile Geliri  
  - Ebeveyn Eğitimi  
  - İnternet Erişimi  

Bu yapı, gerçek dünyadaki eşitsizliklerin **orantısal etkisini** yansıtmayı hedefler.

---

## 💡 Katkı ve İletişim

EduPath, eğitimde fırsat eşitliği konusunda **farkındalık oluşturmayı** amaçlayan açık ve geliştirilebilir bir projedir.

- Hata bildirimleri  
- Özellik önerileri  
- Yapısal iyileştirme fikirleri  

için katkı sağlamaktan çekinmeyin.

> Eğitim bir ayrıcalık değil, temel bir haktır.

---

