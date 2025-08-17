# 🚀 CIP Tools Enhancement

CIP Tools Enhancement adalah aplikasi internal PT Trakindo Utama untuk mempermudah monitoring, pengolahan, dan pelaporan data Customer Interaction Program (CIP).  
Sistem ini dirancang untuk mengotomatisasi proses yang sebelumnya manual (banyak menggunakan Excel), sehingga lebih cepat, akurat, dan terintegrasi.

---

## 📌 Latar Belakang
Sebelum adanya CIP Tools Enhancement, proses monitoring survey masih menghadapi tantangan:
- **Banyak pekerjaan manual** (dominasi Excel).
- **Waktu pemrosesan lama** untuk menyiapkan data siap survei.
- **Kompleksitas tinggi** dalam validasi dan pelaporan data.
  
Hal ini menimbulkan kebutuhan akan sistem terintegrasi yang mampu menangani alur survei **end-to-end**: dari persiapan *customer list*, monitoring survei, hingga laporan penyelesaian:contentReference[oaicite:0]{index=0}.

---

## 🎯 Tujuan Proyek
- Menyediakan **end-to-end workflow CIP survey** yang cepat dan akurat.  
- Mengurangi pekerjaan manual melalui **otomatisasi input, monitoring, dan pelaporan**.  
- Memberikan **dashboard interaktif** untuk memantau status survei, SLA tiket, dan alert.  

---

## ✨ Fitur Utama

### 1. Dashboard Monitoring
- Menampilkan status tiket terbuka/tertutup.
- SLA monitoring (*Tickets Open >24 hours, Average Resolution Time*).
- Visualisasi status dalam bentuk card interaktif.  

![Dashboard Monitoring](Asset%20Ciptools/Dashboard.jpeg)

---

### 2. Survey Monitoring
- Validasi customer list (cleansing, exclusion, temporary hold).  
- Monitoring status survei: *Complete* vs *Not Complete*.  
- Breakdown data per **area, region, cabang**.  

![Survey Monitoring](Asset%20Ciptools/complete_survey.jpeg)

---

### 3. Alert Management
- **CIP Admin** → assign alert ke **PIC Area**.  
- **PIC Area** → menginput hasil resolusi.  
- Tracking status alert: *Open → Assigned → Resolved → Closed*.  
- **Email notifikasi otomatis** setelah status berubah.  

![Alert Resolution](Asset%20Ciptools/alert.jpeg)

---

### 4. Data Upload & Integrasi
- Upload **Complete Survey**, **BIC**, **Disposition Call**.  
- Mendukung file Excel dengan struktur tabel database.  
- Terintegrasi dengan **Power BI** untuk analisis lanjutan.  

---

### 5. Reporting & Download
- Export data ke Excel (summary maupun detail).  
- Laporan alert resolution & survey monitoring bisa diunduh per periode.  

---

## 🛠️ Teknologi yang Digunakan
- **Backend:** ASP.NET Core  
- **Frontend:** Bootstrap, jQuery, Chart.js  
- **Database:** Microsoft SQL Server  
- **Integrasi:** Power BI untuk analitik lanjutan  
- **Hosting:** Internal Dev Server (Trakindo)  

---

## 📊 Hasil & Dampak
- Proses data survey menjadi **otomatis & efisien**.  
- Waktu pemrosesan turun drastis dibanding metode manual.  
- Monitoring SLA & kepuasan pelanggan lebih **transparan & real-time**.  
- Mempermudah manajemen mengambil keputusan berbasis data.  

---

## 👩‍💻 Peran & Kontribusi


- Mendesain **flow proses & arsitektur sistem**.  
- Mengembangkan modul **Dashboard Monitoring** & **Alert Resolution**.  
- Menyusun query SQL untuk laporan survei & alert.  
- Membuat dokumentasi & panduan penggunaan sistem.  

---

## 📷 Dokumentasi Screenshots
Beberapa tampilan aplikasi:

- Dashboard Monitoring  
  ![Dashboard](Asset%20Ciptools/Dashboard.jpeg)

- Not Yet Complete Survey  
  ![Survey Monitoring](Asset%20Ciptools/not_yet_complete_survey.jpeg)

- Complete Survey Detail  
  ![Survey Detail](Asset%20Ciptools/complete_survey.jpeg)

- Alert Resolution Form  
  ![Alert Resolution](Asset%20Ciptools/alert.jpeg)

---

## 📌 Catatan
Proyek ini merupakan aplikasi internal **PT Trakindo Utama**.  
Hak cipta © 2024 PT Trakindo Utama. All rights reserved.

