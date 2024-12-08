# WebGIS - Pemetaan Lokasi Gedung dan Infrastruktur ITERA

## Deskripsi

Proyek **WebGIS** ini bertujuan untuk menampilkan peta interaktif dengan berbagai **lokasi gedung** dan infrastruktur penting di **Institut Teknologi Sumatera (ITERA)**. Dengan menggunakan **Leaflet.js** dan **JavaScript**, aplikasi ini menyediakan **peta interaktif** yang memungkinkan pengguna untuk menavigasi berbagai lokasi penting, seperti **gedung kampus**, **masjid**, dan **kantin**. Aplikasi ini memanfaatkan **OpenStreetMap** dan **Esri World Imagery** sebagai peta dasar serta berbagai fitur interaktif lainnya seperti **MiniMap**, **Layer Control**, dan **deteksi lokasi pengguna**.

Fitur utama dari aplikasi ini meliputi:
- Penambahan **marker** pada lokasi gedung dan infrastruktur.
- Penambahan **circle** dan **polygon** untuk menandai area tertentu di peta.
- Penggunaan **MiniMap** untuk tampilan peta mini di sudut layar.
- Penggunaan **deteksi lokasi pengguna** untuk memandu pengguna ke lokasi mereka.
- **Layer Control** untuk memilih antara berbagai peta dasar (OSM, ESRI, dll).

## Fitur

### 1. **Peta Interaktif**
   - Peta interaktif dengan marker untuk lokasi gedung dan infrastruktur ITERA.
   - Pilihan **basemap** menggunakan **OpenStreetMap** dan **Esri World Imagery**.
   
### 2. **Marker Lokasi**
   - Menambahkan **marker** pada lokasi gedung, masjid, kantin, dan asrama di ITERA.
   
### 3. **Kontrol Layer**
   - Menyediakan kontrol untuk memilih antara **OpenStreetMap** dan **Esri World Imagery**.
   
### 4. **MiniMap**
   - Menambahkan **MiniMap** untuk melihat gambaran keseluruhan peta dalam ukuran kecil, membantu navigasi.
   
### 5. **Deteksi Lokasi Pengguna**
   - Menambahkan fitur deteksi lokasi pengguna untuk menampilkan posisi mereka di peta secara otomatis.

### 6. **Poligon dan Lingkaran**
   - Menandai area tertentu seperti **gedung** atau **bundaran** menggunakan **polygon** dan **circle**.

### 7. **Popup dan Info**
   - Menampilkan informasi pada **popup** saat pengguna mengklik marker atau area yang ditandai.

## Teknologi yang Digunakan

- **Leaflet.js**: Library JavaScript untuk membuat peta interaktif.
- **JavaScript**: Bahasa pemrograman untuk logika interaktif dan manipulasi DOM.
- **HTML5**: Untuk struktur halaman web.
- **CSS3**: Untuk styling halaman web.
- **OpenStreetMap**: Peta dasar sumber terbuka.
- **ESRI World Imagery**: Peta dasar satelit dari **Esri**.
- **Leaflet MiniMap**: Plugin untuk menambahkan tampilan mini peta.

## Instalasi

Untuk menjalankan aplikasi WebGIS ini di mesin lokal, ikuti langkah-langkah berikut:

### 1. Clone Repositori
Clone repositori ini ke komputer lokal Anda menggunakan Git:
```bash
git clone https://github.com/username/webgis-iteraproject.git
2. Buka Proyek
Masuk ke folder proyek:

bash
Copy code
cd webgis-iteraproject
3. Buka file index.html
Untuk melihat aplikasi WebGIS, buka file index.html di browser Anda, atau jalankan menggunakan server lokal seperti Live Server di VS Code atau XAMPP.

bash
Copy code
# Jika menggunakan Live Server di VS Code, cukup klik kanan pada file `index.html` dan pilih "Open with Live Server"
4. Mengedit Kode
Anda dapat mengedit dan menambahkan marker atau fitur baru dalam script.js atau index.html sesuai kebutuhan.

5. Menambahkan Marker atau Fitur Baru
Untuk menambahkan marker atau overlay baru, cukup salin dan sesuaikan kode marker di script.js:

javascript
Copy code
L.marker([latitude, longitude]).addTo(map).bindPopup('Nama Lokasi');
Penggunaan
Aplikasi WebGIS ITERA ini dapat digunakan untuk menampilkan lokasi gedung dan infrastruktur di kampus ITERA. Pengguna dapat:

Melihat peta dan menavigasi melalui berbagai lokasi di kampus.
Mencari lokasi tertentu melalui popup yang muncul saat marker diklik.
Mengaktifkan fitur deteksi lokasi untuk melihat posisi mereka di peta.
Selain itu, pengguna juga bisa mengubah basemap antara OpenStreetMap dan Esri World Imagery dengan menggunakan Layer Control.

Demo
Untuk melihat demo aplikasi, Anda bisa mengunjungi Demo WebGIS ITERA.

Kontribusi
Jika Anda ingin berkontribusi pada proyek ini, silakan ikuti langkah-langkah berikut:

Fork repositori ini ke akun GitHub Anda.
Clone repositori fork ke komputer lokal Anda:
bash
Copy code
git clone https://github.com/username/webgis-iteraproject.git
Buat branch baru:
bash
Copy code
git checkout -b fitur-baru
Lakukan perubahan dan commit perubahan:
bash
Copy code
git add .
git commit -m "Menambahkan fitur baru"
Push perubahan ke repositori fork:
bash
Copy code
git push origin fitur-baru
Buat Pull Request ke repositori utama untuk penggabungan perubahan.
Proyek yang Dapat Dikerjakan
Menambahkan layer peta baru, seperti Stamen atau CartoDB.
Integrasi API untuk menambahkan data dari database.
Pengembangan fitur pencarian lokasi menggunakan geolokasi.
Lisensi
Repositori ini dilisensikan di bawah MIT License. Silakan lihat file LICENSE untuk informasi lebih lanjut.

Referensi
Leaflet.js Documentation: https://leafletjs.com/
Leaflet MiniMap Plugin: https://github.com/Norkart/Leaflet-MiniMap
OpenStreetMap: https://www.openstreetmap.org/
Esri World Imagery: https://www.esri.com/en-us/arcgis/products/arcgis-online
Contact
Nama: M. Gilang Martiansyah M
Email: mgilang.121450056@student.itera.ac.id
Github: github.com/nvrsleep
