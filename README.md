# Pendeteksi-Warna-Helm-pada-Wilayah-Kontruksi
🦺 Pendeteksi Warna Helm pada Wilayah Konstruksi
Sistem ini dirancang untuk mendeteksi keberadaan dan jenis helm keselamatan berdasarkan warnanya di lingkungan proyek konstruksi. Teknologi ini bertujuan membantu memastikan standar keselamatan kerja dengan mengidentifikasi pekerja yang menggunakan helm sesuai perannya, maupun mereka yang tidak mengenakan helm.
Dibangun dengan bantuan YOLOv8 (You Only Look Once versi 8) untuk deteksi objek, serta diintegrasikan ke dalam aplikasi web sederhana menggunakan Flask, sistem ini memungkinkan pengguna mengunggah gambar atau video untuk dianalisis, kemudian menampilkan hasil deteksi berupa anotasi visual langsung pada file tersebut.

🎯 Fitur Utama
✅ Deteksi warna helm secara otomatis:
🔵 Helm Biru – Pekerja teknik atau supervisor
⚪ Helm Putih – Manajer proyek atau insinyur senior
🟡 Helm Kuning – Pekerja umum atau buruh
🟠 Helm Oranye – Keamanan atau pengatur lalu lintas
❌ Tanpa Helm – Deteksi pelanggaran standar keselamatan

✅ Input fleksibel:
1. Bisa menggunakan gambar (.jpg, .png)
2. Bisa menggunakan video (.mp4, .avi, .mov)

✅ Visualisasi output:
1. Hasil deteksi ditampilkan dalam bentuk bounding box berlabel di atas objek yang terdeteksi
2. Output tersedia dalam bentuk gambar atau video hasil anotasi

✅ Deskripsi tambahan:
1. Setiap label helm dilengkapi dengan penjelasan fungsional berdasarkan warna helm
