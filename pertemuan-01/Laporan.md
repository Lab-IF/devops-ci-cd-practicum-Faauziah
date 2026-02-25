# 📋 Laporan Praktikum Pertemuan 01
## DevOps Culture & Principles

---

## 👤 Identitas Mahasiswa

| Item | Keterangan |
|------|------------|
| **Nama** | Fauziah |
| **NIM** | 105841104223 |
| **Kelas** | 5B |
| **Tanggal** | 2026-02-25 |

---

## 📚 Pemahaman DevOps

### Apa itu DevOps?

DevOps adalah sebuah pendekatan atau budaya kerja dalam pengembangan perangkat lunak yang bertujuan untuk menyatukan tim Development (pengembang) dan Operations (operasional) agar dapat bekerja secara kolaboratif dan terintegrasi. Sebelum adanya DevOps, kedua tim ini sering bekerja secara terpisah. Tim developer lebih berfokus pada pembuatan dan pengembangan aplikasi, sementara tim operasional bertanggung jawab dalam menjalankan, memelihara, dan menjaga stabilitas sistem di lingkungan produksi. Pemisahan peran ini kerap menimbulkan berbagai permasalahan, seperti miskomunikasi antar tim, proses rilis yang lambat, serta kesulitan saat aplikasi dipindahkan dari tahap pengembangan ke tahap produksi. DevOps hadir sebagai solusi untuk menjembatani permasalahan tersebut dengan menekankan kolaborasi, otomatisasi, serta integrasi dan pengiriman berkelanjutan. Dengan adanya DevOps, seluruh proses mulai dari perencanaan, pengembangan, pengujian, hingga deployment dapat dilakukan secara lebih terkoordinasi. DevOps menjadi sangat penting dalam industri perangkat lunak saat ini karena tuntutan akan kecepatan, stabilitas, dan kualitas aplikasi yang semakin tinggi. Perusahaan dituntut untuk dapat merilis fitur baru secara cepat tanpa mengorbankan keandalan sistem. Melalui penerapan praktik DevOps seperti Continuous Integration (CI) dan Continuous Deployment (CD), proses build, testing, dan deployment dapat diotomatisasi. Otomatisasi ini membantu mengurangi kesalahan manual, mempercepat waktu rilis, serta meningkatkan konsistensi dan keandalan aplikasi. Selain itu, DevOps juga mendorong adanya monitoring dan feedback secara berkelanjutan sehingga masalah dapat terdeteksi lebih dini dan diperbaiki dengan lebih cepat, yang pada akhirnya meningkatkan kualitas layanan kepada pengguna.

### Mengapa DevOps Penting?

Banyak perusahaan besar yang sukses menerapkan DevOps. Contohnya Netflix yang menggunakan otomatisasi dan cloud untuk memastikan layanan streaming tetap stabil meskipun melayani jutaan pengguna secara bersamaan. Amazon juga menerapkan DevOps untuk melakukan deployment ribuan kali per hari tanpa mengganggu layanan pelanggan. Selain itu, Google memanfaatkan DevOps untuk menjaga keandalan sistem skala besar dengan tingkat ketersediaan yang sangat tinggi. Keberhasilan perusahaan-perusahaan tersebut menunjukkan bahwa DevOps bukan hanya tren, tetapi kebutuhan dalam pengembangan software modern.

### Contoh Perusahaan yang Menerapkan DevOps

netfix dan Amazon

---

## 🎯 Pemahaman Prinsip CALMS

C – Culture : Culture menekankan kolaborasi dan komunikasi antara tim Development dan Operations. Dalam DevOps, kedua tim bekerja sebagai satu kesatuan dan memiliki tanggung jawab bersama terhadap keberhasilan aplikasi. Budaya ini mendorong keterbukaan, saling percaya, dan penyelesaian masalah tanpa saling menyalahkan. Contoh penerapan: developer dan tim operasional bersama-sama melakukan perencanaan, deployment, serta menangani masalah di production secara kolaboratif.
A – Automation : Automation bertujuan mengurangi proses manual yang berulang agar pekerjaan lebih cepat, konsisten, dan minim kesalahan. Otomatisasi menjadi kunci utama dalam mempercepat proses pengembangan dan rilis aplikasi. Contoh penerapan: penggunaan pipeline CI/CD untuk menjalankan proses build, testing, dan deployment aplikasi secara otomatis setiap kali terjadi perubahan kode.
L – Lean: Lean berfokus pada efisiensi dengan menghilangkan proses yang tidak memberikan nilai tambah dalam pengembangan perangkat lunak. Prinsip ini membantu tim bekerja lebih cepat dan efektif. Contoh penerapan: menyederhanakan alur rilis aplikasi dengan mengurangi tahapan persetujuan yang tidak perlu.
M – Measurement : Measurement berarti melakukan pengukuran terhadap performa sistem dan proses kerja untuk mengetahui efektivitas penerapan DevOps. Data digunakan sebagai dasar pengambilan keputusan. Contoh penerapan: memantau waktu deployment, jumlah kegagalan rilis, dan performa aplikasi melalui sistem monitoring.
S – Sharing : Sharing menekankan pentingnya berbagi informasi, pengetahuan, dan pengalaman antar tim agar semua pihak dapat belajar dan berkembang bersama. Contoh penerapan: mendokumentasikan solusi masalah dan membagikannya kepada seluruh tim sebagai bahan pembelajaran.


---

## 🔧 Setup Development Environment

### Versi Software

| Software | Versi |
|----------|-------|
| Git | git version 2.52.0 |
| Docker | Docker version 29.0.1 |

### Konfigurasi Git

```
Fauziah
105841104223@student.unismuh.ac.id
```

### VS Code Extensions

1. Docker
2. gitlans
3. YAML
4. Remote- Containers

### GitHub Account

- Username: Faauziah

---

## 📸 Screenshots

| No | Screenshot | Keterangan |
|----|------------|------------|
| 1 | ![Git Version](screenshots/01-git-version.png) | Output git --version |
| 2 | ![Git Config](screenshots/02-git-config.png) | Output git config --list |
| 3 | ![Docker Version](screenshots/03-docker-version.png) | Output docker --version |
| 4 | ![Docker Hello World](screenshots/04-docker-hello-world.png) | Output docker run hello-world |
| 5 | ![VS Code](screenshots/05-vscode-extensions.png) | VS Code dengan extensions |

---

## 💭 Refleksi Pribadi

### Harapan dari Praktikum Ini

Harapan saya dari praktikum DevOps ini adalah dapat memahami alur kerja pengembangan perangkat lunak secara menyeluruh, tidak hanya dari sisi pemrograman, tetapi juga dari sisi deployment dan operasional sistem. Selama ini saya lebih fokus pada penulisan kode, namun melalui praktikum DevOps saya berharap dapat mengetahui bagaimana sebuah aplikasi dijalankan di server, dikelola, dan dipelihara secara berkelanjutan. Dengan adanya praktikum ini, saya ingin belajar bekerja secara sistematis dan terstruktur, seperti yang diterapkan di dunia industri.  

### Skill yang Ingin Dikuasai

Skill yang ingin saya kuasai di akhir semester adalah kemampuan untuk menguasai dan memahami proses pembuatan serta perawatan sebuah aplikasi secara menyeluruh. Saya ingin tidak hanya mampu membuat aplikasi dari sisi penulisan kode, tetapi juga memahami bagaimana aplikasi tersebut dijalankan, diperbarui, dan dipelihara agar tetap stabil dan dapat digunakan dalam jangka panjang. Melalui praktikum DevOps, saya berharap dapat memahami alur pengembangan aplikasi mulai dari tahap perencanaan, pengembangan, pengujian, hingga deployment dan maintenance. Dengan penguasaan skill ini, saya ingin memiliki bekal yang cukup untuk menghadapi permasalahan yang muncul saat aplikasi sudah digunakan oleh pengguna, serta mampu melakukan perbaikan dan peningkatan sistem secara berkelanjutan.

### Tantangan yang Dihadapi

ketika terjadi kesalahan pada repository atau konfigurasi project. Dalam beberapa kasus, kesalahan tersebut tidak langsung disertai dengan penjelasan atau petunjuk yang jelas, sehingga praktikan harus mencari dan memahami sendiri sumber permasalahan yang terjadi. Hal ini menuntut kemampuan analisis dan kemandirian dalam melakukan troubleshooting, mulai dari mengecek struktur repository, perintah yang digunakan, hingga referensi dari dokumentasi atau sumber lain.

---

## ✅ Checklist

- [x] Git terinstall dan terkonfigurasi dengan benar
- [x] Docker dapat menjalankan container hello-world
- [x] VS Code terinstall dengan semua extensions yang diminta
- [x] Laporan ditulis dengan bahasa yang baik dan benar
- [x] Semua screenshot jelas dan terbaca

---

*Laporan ini dibuat pada Rabu, 25 Februari 2026*
