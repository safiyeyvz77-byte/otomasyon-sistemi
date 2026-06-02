<!-- KARTLARIN ARKA PLANINI VE SAYFAYI DÜZENLEYEN ŞIK BİR STİL -->
<style>
  body {
    background-color: #f8f9fa !important;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif !important;
  }
  .portal-container {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
  }
  .proje-kart {
    background: #ffffff !important;
    border: 1px solid #e0e0e0 !important;
    border-radius: 12px !important;
    padding: 24px !important;
    margin-bottom: 20px !important;
    box-shadow: 0 4px 12px rgba(0,0,0,0.05) !important;
    display: flex !important;
    justify-content: space-between !important;
    align-items: center !important;
    transition: transform 0.2s ease, box-shadow 0.2s ease !important;
    cursor: pointer;
  }
  .proje-kart:hover {
    transform: translateY(-3px) !important;
    box-shadow: 0 6px 18px rgba(0,0,0,0.08) !important;
    border-color: #1a73e8 !important;
  }
  .hafta-etiket {
    background: #e8f0fe !important;
    color: #1a73e8 !important;
    padding: 6px 14px !important;
    border-radius: 20px !important;
    font-size: 13px !important;
    font-weight: 700 !important;
    display: inline-block !important;
    margin-bottom: 12px !important;
  }
  .kart-baslik {
    margin: 0 0 8px 0 !important;
    color: #202124 !important;
    font-size: 18px !important;
    font-weight: 600 !important;
  }
  .kart-liste {
    margin: 0 !important;
    padding-left: 20px !important;
    color: #5f6368 !important;
    font-size: 14.5px !important;
    line-height: 1.6 !important;
  }
  .ok-isareti {
    color: #1a73e8 !important;
    font-size: 22px !important;
    font-weight: bold !important;
    margin-left: 20px !important;
    transition: transform 0.2s ease !important;
  }
  .proje-kart:hover .ok-isareti {
    transform: translateX(4px) !important;
  }
</style>

<div class="portal-container">

  <!-- HAFTA 1-3 KUTUSU -->
  <div class="proje-kart">
    <div style="flex-grow: 1;">
      <span class="hafta-etiket">Hafta 1-3</span>
      <h3 class="kart-baslik">Proje Başlangıcı, Kapsam ve Fikir Analizi</h3>
      <ul class="kart-liste">
        <li>Apartman ve Site Yönetim Sistemi fikri belirlendi ve genel kapsam analiz edildi.</li>
        <li>Modüller planlanarak veritabanı teknolojileri araştırıldı.</li>
      </ul>
    </div>
    <div class="ok-isareti">&gt;</div>
  </div>

  <!-- HAFTA 4-5 KUTUSU -->
  <div class="proje-kart">
    <div style="flex-grow: 1;">
      <span class="hafta-etiket">Hafta 4-5</span>
      <h3 class="kart-baslik">Gereksinim Analizi ve Metodolojiler</h3>
      <ul class="kart-liste">
        <li>Projede Şelale ve V Modeli yazılım metodolojilerinin kullanılmasına karar verildi.</li>
        <li>Gereksinim analizi dökümanı detaylıca hazırlandı.</li>
      </ul>
    </div>
    <div class="ok-isareti">&gt;</div>
  </div>

  <!-- HAFTA 6-8 KUTUSU -->
  <div class="proje-kart">
    <div style="flex-grow: 1;">
      <span class="hafta-etiket">Hafta 6-8</span>
      <h3 class="kart-baslik">Use Case (Kullanım Senaryoları) Tasarımı</h3>
      <ul class="kart-liste">
        <li>Aktörler (Yönetici ve Sakin) belirlendi.</li>
        <li>Use Case diyagramları çizilerek kullanıcı etkileşimleri modellendi.</li>
      </ul>
    </div>
    <div class="ok-isareti">&gt;</div>
  </div>

  <!-- HAFTA 9-11 KUTUSU -->
  <div class="proje-kart">
    <div style="flex-grow: 1;">
      <span class="hafta-etiket">Hafta 9-11</span>
      <h3 class="kart-baslik">ER Diyagramı ve Veritabanı Tasarımı</h3>
      <ul class="kart-liste">
        <li>SQL Server üzerinde veritabanı mimarisi ve ER Diyagramı ilişkileri kuruldu.</li>
        <li>Tbl_Yonetici, Tbl_Sakinler, Tbl_Daireler ve Tbl_Giderler tabloları oluşturuldu.</li>
      </ul>
    </div>
    <div class="ok-isareti">&gt;</div>
  </div>

</div>
