# Coastal-Based-Sales-Analysis
Google Sheets üzerinde raporlama
# 🌊 Kıyı Bazlı Satış Analizi (Coastal-Based Sales Analysis)

Bu proje, **Google Sheets** kullanılarak satış verilerinin **kıyı bazlı** analiz edilmesini amaçlayan bir veri analizi ve raporlama çalışmasıdır.  
Satış ve müşteri verileri CSV dosyalarından **IMPORTDATA** fonksiyonu ile içe aktarılmış, veriler temizlenmiş, tablolar **XLOOKUP** ile birleştirilmiş ve sonuçlar pivot tablolar ve grafiklerle raporlanmıştır.

---

##  Proje Amacı
- Satış performansını **kıyı bölgeleri** bazında analiz etmek  
- Müşteri ve satış verilerini tek bir rapor dosyasında birleştirmek  
- Google Sheets fonksiyonlarını kullanarak uçtan uca bir analiz süreci yürütmek  
- Satış ekibi için anlamlı ve yorumlanabilir çıktılar üretmek  

---

##  Kullanılan Araçlar
- **Google Sheets**
- **IMPORTDATA** – CSV veri aktarımı
- **XLOOKUP** – Tablo eşleştirme
- **Pivot Table**
- **Charts (Bar / Column Chart)**

---

##  Sayfa Yapısı ve İçerik

###  1. Sales Analysis For Sales Team (Kapak Sayfası)
- Proje özeti ve görsel
---

###  2. Sources >>
Veri kaynaklarının bulunduğu bölüm.

####  Sales
- Satış verileri
- `IMPORTDATA("URL")` ile CSV dosyasından aktarılmıştır.

####  Customers
- Müşteri bilgileri
- `IMPORTDATA("URL")` ile CSV dosyasından aktarılmıştır.
- 
###  KPI’lar

| KPI | Açıklama |
|----|---------|
| Satış Miktarı | Şehir ve kıyı bazında satılan toplam ürün miktarı |
| Haftasonu Etkisi | Haftaiçi ve haftasonu satışlarının karşılaştırılması |
| Kıyı Karşılaştırması | Doğu ve Batı kıyılarındaki satış performanslarının analizi |

---

###  Analiz Bulguları

- Toplam satışlar **en yüksek Batı Kıyısı** bölgelerinde görülmektedir.
- **Haftasonu satışları**, özellikle **Batı Kıyısı** bölgelerinde belirgin şekilde daha yüksektir.
- **Doğu Kıyısı** satışları daha dengeli bir dağılım göstermektedir ancak **en düşük satışlar haftasonu Doğu Kıyısı’nda** gözlemlenmiştir.
- Doğu Kıyısı’nda haftasonu satışlarını artırmak için **kampanya ve promosyonlar** uygulanabilir.
- Batı Kıyısı’nda ise haftaiçi satışları artırmaya yönelik **farklı satış stratejileri** geliştirilebilir.


