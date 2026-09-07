# NDB RAN — Nokia Site Intelligence Map

Versi gratis tanpa Google Maps API Key.

## Fitur
- Leaflet + OpenStreetMap
- Database 21,100 site
- Pencarian seluruh kolom
- 5 filter dinamis
- Marker site
- Detail lengkap
- Google Maps untuk lokasi
- Google Maps untuk rute
- Copy koordinat
- Share link site
- Geolocation dan site terdekat
- Responsive desktop/mobile
- GitHub Pages ready

## Upload ke GitHub
Upload `index.html`, `data.json`, `data.csv`, dan `meta.json` ke repository. Aktifkan GitHub Pages.

Tidak ada Google Maps API Key yang diperlukan.

## Catatan performa
Untuk database sangat besar, versi produksi berikutnya dapat memakai vector tiles/server-side spatial index agar marker tidak perlu dimuat seluruhnya sekaligus.


## Mode cepat
Versi ini dioptimalkan untuk database sekitar 21 ribu site:
- memakai Canvas `circleMarker`, bukan ribuan DOM marker;
- maksimal 3.000 marker dirender sekaligus;
- pencarian/filter tetap bekerja pada seluruh database;
- daftar site dibatasi 250 item agar browser tetap responsif;
- tidak membutuhkan Google Maps API Key.
