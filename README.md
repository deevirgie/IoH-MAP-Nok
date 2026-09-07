# NDB RAN – Nokia Site Map

Website peta lokasi berbasis Leaflet + OpenStreetMap + database Excel.

## Isi paket
- `index.html` — aplikasi web
- `data.json` — database site yang sudah dioptimalkan untuk web
- `data.csv` — backup data
- `meta.json` — metadata kolom

## Cara menjalankan
1. Tidak perlu Google Maps API Key. Peta menggunakan Leaflet + OpenStreetMap.
2. Upload seluruh isi folder ini ke repository GitHub.
3. Aktifkan GitHub Pages pada repository tersebut.

## Data
Sheet: Sheet1
Jumlah baris: 21,100
Latitude: Y_LATITUDE
Longitude: X_LONGITUDE
Site ID: SITE_ID
Site Name: SITE_NAME
Filter otomatis: PROVINCE, AREA_NAME_SUB_DISTRICT, AREA, BRANCH, SITE_OWNERSHIP, TOWER_OWNERSHIP, SITE_TYPE_GF_OR_RT_OR_MICROCELL_OR_INDOOR, BTS_COVERAGE_TYPE_MACRO_OR_MICRO_OR_IBS

## Fitur
Pencarian realtime, filter, marker clustering, detail site, Google Maps, rute,
share link, geolocation, site terdekat, responsive mobile/desktop.

### Peta
Website tidak menggunakan Google Maps API. Peta dasar memakai OpenStreetMap melalui Leaflet. Tombol Google Maps hanya membuka Google Maps di tab baru untuk lokasi/rute, sehingga tidak memerlukan Google Maps API Key.
