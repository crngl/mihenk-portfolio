# MİHENK

**Finansal araştırma ve portföy takibi için yerel çalışma alanı.**

[English](README.en.md)

MİHENK; fiyat geçmişi, teknik göstergeler, finansal tablolar, haberler ve kişisel araştırma kayıtlarını tek çalışma alanında buluşturan, geliştirilmekte olan bir projedir. Tasarımın temel amacı, bir verinin kaynağını ve zamanını görünür tutarak araştırmayı kolaylaştırmaktır.

Bu depo, projenin CV ve portföy tanıtımıdır. Uygulamanın kaynak kodu, çalıştırılabilir paketi, erişim bilgileri ve kişisel kayıtları paylaşılmaz. Halka açık bir uygulama veya demo bağlantısı bulunmaz.

## Uygulanan özellikler

- **Tarihsel grafikler:** Desteklenen semboller için 30/90/180/365 takvim günlük günlük fiyat serileri; mum ve çizgi görünümü, mevcutsa hacim, SMA 20/50 ve RSI 14.
- **Karşılaştırma:** Tarihleri örtüşen serilerin aynı başlangıç noktasına göre karşılaştırılması.
- **Temel analiz:** Desteklenen ABD şirketleri ve BIST sembollerinde rapor dönemi ve kaynak bilgisiyle finansal tablo inceleme.
- **Türkçe haber akışı:** Yabancı haber başlıklarının Türkçeye çevrilmesi; özgün başlık, kaynak bağlantısı ve yayın zamanının korunması.
- **Kişisel çalışma alanı:** Takip listeleri, araştırma notları, portföy ve işlem defteri; yedek dışa/içe aktarma.
- **Kur görünümü:** Desteklenen kurlarla portföyün mevcut değerini TRY/USD/EUR cinsinden görüntüleme; eksik veri olduğunda kısmi toplamı belirtme.
- **Günlük referans alarmları:** Yerel sunucu açıkken 15 dakikalık kontrol ve Windows bildirimleri. Windows'un isteği kabul etmesi ile gösterim sinyali ayrı ele alınır.

## Teknik yaklaşım

| Alan | Yaklaşım |
| --- | --- |
| Arayüz | HTML, CSS ve JavaScript |
| Yerel servis | Python HTTP servisi; yalnızca yerel bilgisayardan erişim |
| Veri işleme | Sembol, kaynak, tarih, para birimi ve rapor dönemi kontrolleri |
| Arka plan kontrolü | Python iş parçacığı ve Windows bildirim API'si |
| Doğrulama | JavaScript ve Python otomatik testleri; kullanıcıyla ekran kontrolleri |
| Geliştirme süreci | Yapay zekâ destekli, aşamalı geliştirme ve doğrulama |

Eksik değerler sıfır veya örnek piyasa verisiyle doldurulmaz. Birbirinden farklı kaynaklar, para birimleri ve rapor dönemleri uygunluk kontrolü olmadan birleştirilmez. Haber çevirisi özgün metnin yerini doğrulanmış bilgi olarak almaz.

## Kapsam ve mevcut sınırlar

Proje aktif geliştirme aşamasındadır. Günlük fiyat geçmişi kullanılır; eşanlı BIST fiyatı, derinlik veya kesintisiz tick akışı sunulduğu iddia edilmez. Kaynak kapsamı sembole ve sağlayıcı erişimine bağlıdır. Bazı veri bağlantıları dış kaynakların erişilebilirliğine ve tablo şemalarına bağlıdır.

Arka plan kontrolleri için bilgisayarın uyanık ve yerel sunucunun açık olması gerekir. Windows ayarları bildirimin görünürlüğünü etkileyebilir. Uygulama gerçek alım/satım emri göndermez.

## CV için kısa açıklama

> **MİHENK — Finansal araştırma ve portföy çalışma alanı:** JavaScript ve Python ile tarihsel grafikler, Türkçe haber akışı, dönem uyumlu finansal analiz, işlem defteri ve yerel bildirim akışlarının yapay zekâ destekli geliştirilmesi. Veri kaynağı ve zamanının izlenmesi, eksik veri kontrolleri ve otomatik testlerle doğrulama.

Bu tanıtım deposu uygulamanın dağıtımı değildir. Kullanım paketi, kurulum talimatları ve kaynak kodu bu depoda yayımlanmaz.
