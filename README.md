# 🏢 Sistem Analizi ve Tasarımı - Proje İlerleme Raporu

Bu depo, **Sistem Analizi ve Tasarımı** dersi kapsamında geliştirilen **Apartman ve Site Yönetim Otomasyonu** projesinin haftalık gelişim sürecini takip etmek amacıyla oluşturulmuştur.

* **Ders:** Sistem Analizi ve Tasarımı
* **Proje:** Apartman ve Site Yönetim Otomasyonu
* **Geliştirici:** Safiye

---

## 📅 Haftalık Güncellemeler ve İlerleme Raporları

### Hafta 1-3: Proje Başlangıcı, Kapsam ve Fikir Analizi
* Proje fikri olarak "Apartman ve Site Yönetim Sistemi" belirlendi ve sistemin genel kapsamı analiz edildi.
* Yönetici ve sakin girişi modülleri planlanarak ihtiyaç duyulacak veri tabanı teknolojileri araştırıldı.

### Hafta 4-5: Gereksinim Analizi ve Metodolojiler
* Projede yazılım geliştirme metodolojilerinin kullanılmasına karar verildi.
* Yönetici ve sakinlerin yapabileceği işlemler listelenerek gereksinim analizi dökümanı hazırlandı.

### Hafta 6-8: Use Case (Kullanım Senaryoları) Tasarımı
* Aktörler (Yönetici ve Sakin) belirlendi.
* Sistemin Use Case (Kullanım Senaryosu) diyagramları çizilerek kullanıcı etkileşimleri modellendi.

### Hafta 9-11: ER Diyagramı ve Veritabanı Tasarımı
* Veritabanı mimarisi tasarlandı ve `SiteYönetimOtamasyonu` veritabanı oluşturuldu.
* SQL Server üzerinde şu tablolar ve aralarındaki ilişkiler (ER Diyagramı) kuruldu:
  * `dbo.Tbl_Yonetici` (KullaniciAd, Sifre, Telefon)
  * `dbo.Tbl_Sakinler` (Ad, Sifre)
  * `dbo.Tbl_Daireler`, `dbo.Tbl_Giderler`, `dbo.Tbl_Talepler`, `dbo.Tbl_Duyurular`

### Hafta 12-14: Arayüz Tasarımı, Araçlar ve Kodlama
* C# Windows Forms App kullanılarak arayüz lojistiği ve form tasarımları oluşturuldu.
* Giriş paneli (`Form1`), Yönetici Ana Formu (`FrmYöneticiAnaForm`) ve Sakin İşlemleri (`FrmSakinIslemleri`) pencereleri tasarlandı.
* Butonlar arası nesne yönelimli form geçiş kodları tamamlandı.

### Hafta 15-16: Canlı Entegrasyon, Veritabanı Bağlantısı ve Proje Teslimi
* C# arayüzü ile MS SQL Server arasında canlı bağlantı kuruldu.
* Giriş butonuna dinamik SQL sorguları eklenerek veritabanı kontrolü aktifleştirildi.
* Proje derlenerek (`.exe`) masaüstü uygulaması haline getirildi ve sunuma hazır hale getirildi.
