# Pendeteksi-Warna-Helm-pada-Wilayah-Kontruksi
Sistem ini dirancang untuk mendeteksi jenis helm keselamatan berdasarkan warnanya (biru, putih, kuning, oranye) serta mengidentifikasi pekerja yang tidak mengenakan helm di area konstruksi. Proyek ini menggunakan YOLOv8 dan diimplementasikan melalui antarmuka berbasis Flask, yang memungkinkan pengguna mengunggah gambar atau video untuk dianalisis secara otomatis.

Fitur Utama
1. Deteksi objek helm berdasarkan warna:
   🔵 Helm Biru – Pekerja teknik,
   ⚪ Helm Putih – Manajer proyek,
   🟡 Helm Kuning – Pekerja umum,
   🟠 Helm Oranye – Petugas keamanan,
   ❌ Tanpa Helm – Indikasi pelanggaran keselamatan.
3. Dukungan untuk input gambar dan vidio
4. Visualisasi hasil dalam bentuk anotasi langsung pada gambar/vidio.

Teknologi yang Digunakan
1. Python 3
2. YOLOv8 (Ultralytics)
3. OpenCV
4. Flask
5. HTML/CSS
