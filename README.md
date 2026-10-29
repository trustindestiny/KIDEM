# Kıdem — Anestezi ve Reanimasyon

Anestezi ve Reanimasyon personeli için kıdem ve beş yıllık geri sayım PWA'sı.

## Özellikler
- Başlangıç listesinde 17 personel ve işe başlama tarihleri hazır gelir.
- Kıdem, bugünün tarihine göre her açılışta yeniden hesaplanır.
- Beş yıllık hedef için yıl/ay/gün geri sayımı gösterilir.
- Kıdem düşümleri mazeret, açıklama ve yıl/ay/gün olarak eklenebilir, düzenlenebilir ve silinebilir.
- Düşüm hesabı: 1 yıl = 365 gün, 1 ay = 30 gün; boş veya 0 girilen alanlar sıfırdır.
- Doğum gününden bir gün önce ve doğum gününde kırmızı pasta simgeli duyuru.
- JSON yedek alma ve geri yükleme.
- Çevrimdışı kullanım için PWA manifesti ve service worker.

## GitHub Pages
Depoda Settings → Pages bölümünü açın. Build and deployment altında Deploy from a branch seçin; branch olarak main, klasör olarak /(root) seçip kaydedin. Yayınlama tamamlanınca uygulama şu adreste açılır:

https://trustindestiny.github.io/KIDEM/

## Veri saklama
Personel kayıtları tarayıcının yerel depolamasında saklanır. Başka cihazda kullanmak için uygulamadaki Yedek al ve Yükle işlevlerini kullanın. Personel kayıtlarını herkese açık depodaki kaynak koduna eklemeyin.

## Telefona uygulama olarak yükleme

Önce GitHub Pages yayınının etkin olduğundan emin olun: Settings → Pages → Deploy from a branch → `main` ve `/(root)`.

- **iPhone (Safari):** Yayınlanan uygulama bağlantısını Safari'de açın → Paylaş → Ana Ekrana Ekle. Uygulama adı ve ana ekran ikonu kullanılır.
- **Android (Chrome):** Uygulama bağlantısını Chrome'da açın → menü → Uygulamayı yükle veya Ana ekrana ekle.

Kurulumdan sonra uygulama simgesi ana ekranda görünür. Veriler cihazın tarayıcı depolamasında tutulur; cihazlar arası otomatik senkronizasyon yoktur. Verileri taşımak için uygulamadaki JSON yedekleme ve geri yükleme seçeneklerini kullanın.
