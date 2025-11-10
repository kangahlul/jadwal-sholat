# 🕌 Jadwal Sholat Digital - Premium Edition

Aplikasi web jadwal sholat digital dengan fitur lengkap untuk membantu ibadah sehari-hari umat Muslim. Dibangun dengan teknologi web modern dan desain yang responsif.

## ✨ Fitur Utama

- ⏰ **Jadwal Sholat 5 Waktu** - Subuh, Dzuhur, Ashar, Maghrib, Isya dengan countdown real-time
- 🔊 **Adzan Otomatis** - 5 pilihan suara adzan (Mekkah, Madinah, Mesir, Indonesia, Simple)
- 📖 **Al-Quran Digital** - Baca Al-Quran lengkap dengan terjemahan bahasa Indonesia
- 📅 **Kalender Hijriah & Masehi** - Dengan event-event Islam penting
- 🌤️ **Informasi Cuaca** - Data cuaca terkini berdasarkan lokasi
- 🧭 **Kompas Kiblat** - Penunjuk arah kiblat otomatis
- 🎨 **Mode Terang/Gelap** - Tema yang dapat disesuaikan
- 📱 **Responsive Design** - Optimal di desktop, tablet, dan mobile
- 🔔 **Notifikasi** - Pengingat waktu sholat dengan berbagai opsi
- ⚙️ **Pengaturan Lengkap** - Kustomisasi metode perhitungan dan preferensi

## 🚀 Demo

[Live Demo](https://username.github.io/jadwal-sholat-digital) *(Ganti dengan link GitHub Pages Anda)*

## 📱 Screenshot

![Screenshot Aplikasi](screenshot.png) *(Tambahkan screenshot jika ada)*

## 🛠️ Teknologi yang Digunakan

### Frontend
- **HTML5** - Struktur aplikasi
- **CSS3** - Styling dengan Flexbox/Grid, animasi, dan glassmorphism
- **JavaScript (ES6+)** - Logika aplikasi dan interaksi
- **Font Awesome 6.4.0** - Icon library
- **Google Fonts** - Amiri (Arabic) & Inter fonts

### API External
- **[Aladhan API](https://aladhan.com/prayer-times-api)** - Jadwal sholat dan data Hijriah
  - `https://api.aladhan.com/v1/timingsByCity` - Waktu sholat berdasarkan kota
- **[Al-Quran Cloud API](https://alquran.cloud/api)** - Data Al-Quran
  - `https://api.alquran.cloud/v1/surah` - Daftar surah
  - `https://api.alquran.cloud/v1/surah/{number}/ar.alafasy` - Teks Arab
  - `https://api.alquran.cloud/v1/surah/{number}/id.indonesian` - Terjemahan Indonesia
- **[Nominatim API](https://nominatim.org/)** - Geocoding dan reverse geocoding
  - `https://nominatim.openstreetmap.org/` - Deteksi lokasi dan informasi geografis

### Audio
- **Web Audio API** - Untuk suara adzan dan notifikasi
- **HTML5 Audio** - Pemutaran file audio lokal (adzan1.mp3 - adzan5.mp3)

### Storage
- **LocalStorage** - Menyimpan pengaturan user dan preferensi

## 📦 Instalasi & Penggunaan

### 1. Clone Repository
```bash
git clone https://github.com/username/jadwal-sholat-digital.git
cd jadwal-sholat-digital
```

### 2. Jalankan Aplikasi
Buka file `index.html` di browser modern (Chrome, Firefox, Safari, Edge)

### 3. File Audio (Opsional)
Untuk fitur adzan, tambahkan file audio berikut di root folder:
- `adzan1.mp3` - Adzan Mekkah
- `adzan2.mp3` - Adzan Madinah  
- `adzan3.mp3` - Adzan Mesir
- `adzan4.mp3` - Adzan Indonesia
- `adzan5.mp3` - Nada sederhana

*Jika file tidak tersedia, aplikasi akan menggunakan Web Audio API sebagai fallback*

## ⚙️ Konfigurasi

### Metode Perhitungan Sholat
- **Kementerian Agama RI** (Default)
- Muslim World League
- Egyptian General Authority
- Umm Al-Qura
- Dubai

### Pengaturan Tersedia
- Metode perhitungan waktu sholat
- Mazhab untuk waktu Ashar
- Jenis suara adzan
- Notifikasi dan pengingat
- Tema tampilan
- Ukuran teks

## 🌐 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

## 📝 Fitur Mendatang

- [ ] PWA (Progressive Web App)
- [ ] Offline mode
- [ ] Tasbih digital
- [ ] Doa-doa harian
- [ ] Jadwal kajian
- [ ] Export/import pengaturan

## 🤝 Kontribusi

1. Fork repository ini
2. Buat branch fitur (`git checkout -b fitur-baru`)
3. Commit perubahan (`git commit -m 'Menambah fitur baru'`)
4. Push ke branch (`git push origin fitur-baru`)
5. Buat Pull Request

## 📄 Lisensi

Proyek ini menggunakan lisensi MIT. Lihat file [LICENSE](LICENSE) untuk detail.

## 🙏 Acknowledgments

- [Aladhan.com](https://aladhan.com/) untuk API jadwal sholat
- [AlQuran.cloud](https://alquran.cloud/) untuk API Al-Quran
- [OpenStreetMap](https://openstreetmap.org/) untuk layanan geocoding
- [Font Awesome](https://fontawesome.com/) untuk icon library
- [Google Fonts](https://fonts.google.com/) untuk web fonts

## 📞 Kontak

- **Developer**: [Nama Anda]
- **Email**: email@anda.com
- **GitHub**: [@username](https://github.com/username)

---

**Jadwal Sholat Digital** - Membantu umat Muslim dalam menjalankan ibadah dengan teknologi modern 🕌