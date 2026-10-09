# SIRAMI Dashboard

Dashboard web satu halaman untuk SIRAMI (Sistem Irigasi Presisi berbasis panen air hujan, tenaga surya, dan AI) di Desa Galuk, Kedungtuban, Blora.

Gaya visual mengikuti desain Figma Make "Premium IoT Dashboard UI". Fitur prediksi pertumbuhan cabai berasal dari web SIRAMI Growth.

## Isi
- **Beranda:** cuaca, sensor lapangan, tangki hujan 15 m³, panel surya 500 Wp, aktivitas terbaru
- **Blok:** 4 blok irigasi tetes pada lahan 232 m², dengan saklar aktif/nonaktif
- **Prediksi:** slider umur tanaman, kelembapan tanah, suhu, dan kelembapan udara; hasil berupa fase, tinggi sekarang dan 7 hari lagi, perkiraan panen, kurva pertumbuhan, dan rekomendasi irigasi/fertigasi
- **Analitik:** grafik kelembapan tanah dan energi surya, ringkasan mingguan
- **Atur:** pengaturan sistem, info perangkat, tema gelap

## Catatan
- Semua angka sensor adalah data contoh untuk demonstrasi.
- Prediksi di halaman ini memakai model sederhana berbasis faktor stres. Pada sistem SIRAMI, prediksi dihitung model hibrida CNN-LSTM di cloud.

## Menjalankan
Buka `index.html` di browser. Tidak ada proses build.
