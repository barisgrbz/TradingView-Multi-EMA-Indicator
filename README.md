# TradingView-Multi-EMA-Indicator

**TradingView-Multi-EMA-Indicator**, TradingView platformu üzerinde çoklu EMA hesaplamalarını ve her EMA için ayrı smoothing (yumuşatma) ayarlarını destekleyen, modifiye edilmiş bir Pine Script indikatörüdür. Bu script, TradingView’ın yerleşik EMA göstergesinin temel alınarak, farklı EMA kombinasyonlarını tek bir grafikte gösterme imkanı sunar.

## Özellikler

- **Çoklu EMA Hesaplaması:** Tek bir grafikte aynı anda 8 adet EMA (EMA1 - EMA8) hesaplanabilir.
- **Her EMA için Ayrı Smoothing Ayarları:** Her EMA'nın smoothing türü (None, SMA, SMA+BB, EMA, SMMA (RMA), WMA, VWMA) ayrı olarak belirlenebilir.
- **Inline Ayarlar:** EMA parametreleri (enable, length, offset, renk) inline olarak düzenlenmiş olup, istenmeyen inputların panelde görünmemesi için `display.none` kullanılmıştır.
- **Otomatik Smoothing Uzunluğu:** Her EMA'nın smoothing uzunluğu, ilgili EMA'nın uzunluğu ile otomatik olarak eşleştirilmiştir.
- **Özelleştirilebilir:** Renk, offset ve smoothing ayarları kullanıcı tarafından kolayca değiştirilebilir.

## Kullanım

1. **TradingView Pine Editor'e Yapıştırın:**  
   TradingView Pine Editor'ünü açın ve bu scripti yeni bir indikatör olarak yapıştırın.
2. **Kaydedin ve Grafiğe Ekleyin:**  
   Scripti kaydettikten sonra, grafiğe ekleyerek EMA ve smoothing hesaplamalarını görüntüleyin.
3. **Ayarları Düzenleyin:**  
   İhtiyaçlarınıza göre EMA ve smoothing parametrelerini TradingView ayar panelinden düzenleyin.

## Gereksinimler

- TradingView hesabı
- Pine Script Version 6 desteği (bu script version 6’ya göre yazılmıştır)

## Lisans

Bu proje, [GNU General Public License v2.0](LICENSE) altında lisanslanmıştır.

## Katkıda Bulunma

Katkılarınız, geri bildirimleriniz ve hata raporlarınız memnuniyetle karşılanmaktadır. Lütfen [issue](https://github.com/[kullanici-adiniz]/TradingView-Multi-EMA-Indicator/issues) sayfasından bildirin veya doğrudan pull request gönderin.


  Bu script, TradingView’ın yerleşik EMA göstergesinin modifiye edilmiş versiyonu olarak oluşturulmuştur.

---
