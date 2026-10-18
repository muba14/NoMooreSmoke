# NoMooreSmoke (Web)


<p align="center">
  <img src="screenshots/icon.png" alt="NoMooreSmoke simgesi" width="120">
</p>

<h1 align="center">NoMooreSmoke</h1>

<p align="center">Sigarasız geçen süreni, cebinde kalan parayı ve sağlığındaki iyileşmeyi takip et.</p>

## Ekran görüntüleri

<table>
  <tr>
    <td align="center"><img src="screenshots/01-ana-sayfa.png" width="220"><br><b>Ana Sayfa</b></td>
    <td align="center"><img src="screenshots/02-saglik.png" width="220"><br><b>Diş ve akciğer sağlığı</b></td>
    <td align="center"><img src="screenshots/03-hikayeler.png" width="220"><br><b>Hikayeler</b></td>
  </tr>
  <tr>
    <td align="center"><img src="screenshots/04-sozler.png" width="220"><br><b>Sözler</b></td>
    <td align="center"><img src="screenshots/05-bilgilerim.png" width="220"><br><b>Bilgilerim</b></td>
    <td align="center"><img src="screenshots/06-sifirlama.png" width="220"><br><b>Sıfırlama penceresi</b></td>
  </tr>
  <tr>
    <td align="center"><img src="screenshots/07-sifirlama-okkali.png" width="220"><br><b>Okkalı mod</b></td>
    <td></td>
    <td></td>
  </tr>
</table>


iPhone ve Android'de ana ekrana eklenebilen, internetsiz de açılan sigara bırakma uygulaması.

## Dosyalar
- `index.html` – uygulamanın kendisi
- `manifest.webmanifest` – ad, simge ve tam ekran ayarı
- `sw.js` – internetsiz açılmayı sağlar
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` – simgeler

## GitHub Pages ile yayınlama
1. github.com'da **New repository** → adı `NoMooreSmoke` → **Public** → **Create repository**.
2. Açılan sayfada **uploading an existing file** bağlantısına tıkla, bu klasördeki tüm dosyaları sürükleyip bırak → **Commit changes**.
3. Repo'da **Settings → Pages** → *Source*: **Deploy from a branch**, *Branch*: **main** / **(root)** → **Save**.
4. 1-2 dakika sonra adres hazır olur: `https://KULLANICI-ADIN.github.io/NoMooreSmoke/`

## iPhone'a kurma
1. Linki **Safari** ile aç (Chrome'da ana ekrana ekleme sınırlı).
2. Alttaki **Paylaş** düğmesi → **Ana Ekrana Ekle** → **Ekle**.
3. Ana ekrandaki NoMooreSmoke simgesinden aç; tam ekran uygulama gibi çalışır.

## Android'e kurma
Chrome'da linki aç → sağ üst menü → **Ana ekrana ekle** (veya **Uygulamayı yükle**).

## Notlar
- Girilen bilgiler yalnızca o telefonda saklanır, hiçbir yere gönderilmez.
- Safari'nin geçmiş/site verilerini silmek uygulamadaki bilgileri de siler.
- Güncelleme yapınca dosyaları repoya tekrar yükle; uygulama bir sonraki açılışta yeni sürümü alır.
