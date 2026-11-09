---
title: "Sertifikat Pelatihan Micro Skills: AI Engineer For Milenial"
date: 2024-12-03

event: "Digital Talent Scholarship - Kementerian Komunikasi dan Informatika"
event_url: "https://digitalent.kominfo.go.id"

location: "Badan Pengembangan SDM Kominfo"
address:
  country: "Indonesia"

summary: "Sertifikat resmi dari DTS KOMINFO atas penyelesaian program pelatihan kompetensi kilat dalam skema kecerdasan buatan (Artificial Intelligence Engineer)."

# Waktu pelaksanaan berdasarkan tanggal sertifikat Anda (03 Desember 2024)
event_start: 2024-12-03
event_end: 2024-12-03
all_day: true

authors:
  - me

tags:
  - Certification
  - Artificial Intelligence
  - Kominfo

featured: true

image:
  caption: "Sertifikat Micro Skills AI Engineer Kominfo (Klik gambar untuk Mode Theater Ultra HD)"
  focal_point: "Center"
---

## 📜 Detail Pelatihan Micro Skills

Sertifikat penghargaan ini diberikan secara resmi oleh **Badan Pengembangan SDM Kominfo** melalui program **Digital Talent Scholarship (DTS)** kepada **Angga Prastya** atas keberhasilan menyelesaikan program kelas kompetensi **AI Engineer For Milenial**. Program ini dirancang untuk membekali generasi muda dengan keahlian praktis dan pemahaman taktis dalam industri kecerdasan buatan.

---

### 🧠 Unit Kompetensi & Pemahaman Berbasis AI
* **Fundamental Kecerdasan Buatan**: Memahami dasar-dasar pemodelan kecerdasan buatan, siklus hidup pengembangan sistem berbasis AI, serta pemanfaatannya di dunia industri modern.
* **Alur Kerja Pemrosesan Data**: Mengimplementasikan teknik manipulasi data dasar, ekstraksi fitur, hingga persiapan dataset komputasi sebelum dimasukkan ke dalam model latih.
* **Dasar Perekayasaan Model (AI Engineering)**: Mengenal struktur penulisan instruksi algoritma dan logika komputasi cerdas guna memecahkan masalah prediktif berskala taktis.

> [!SUCCESS] Otoritas Penerbit
> **Kementerian Komunikasi dan Informatika Republik Indonesia** > *Ditetapkan dan disahkan secara digital pada tanggal **03 Desember 2024**.*

<div id="custom-light-box" style="display: none; position: fixed; top: 0; left: 0; width: 100vw; height: 100vh; background: rgba(5, 5, 5, 0.98); z-index: 999999; justify-content: center; align-items: flex-start; padding: 50px 20px; opacity: 0; transition: opacity 0.2s ease-in-out; overflow-y: auto;">
  <span id="close-light-box" style="position: fixed; top: 20px; right: 30px; color: #fff; font-size: 50px; font-weight: bold; cursor: pointer; user-select: none; z-index: 1000000; background: rgba(0,0,0,0.6); width: 60px; height: 60px; display: flex; justify-content: center; align-items: center; border-radius: 50%; line-height: 50px;">&times;</span>
  <img id="light-box-img" src="" alt="Sertifikat Ultra HD" style="display: block; width: 100%; max-width: 1400px; height: auto; border-radius: 6px; box-shadow: 0 0 40px rgba(255,255,255,0.3); margin: 0 auto; cursor: zoom-out; image-rendering: -webkit-optimize-contrast; image-rendering: crisp-edges; image-rendering: pixelated; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; transform: translateZ(0); backface-visibility: hidden;">
</div>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    const mainImg = document.querySelector('.article-header img, .featured-image img, img[class*="featured"]');
    const lightbox = document.getElementById('custom-light-box');
    const lightboxImg = document.getElementById('light-box-img');
    const closeBtn = document.getElementById('close-light-box');

    if (mainImg && lightbox && lightboxImg) {
      mainImg.style.cursor = 'zoom-in';
      mainImg.title = 'Klik untuk melihat ukuran penuh Ultra HD';

      mainImg.addEventListener('click', function(e) {
        e.preventDefault();
        
        // Memanggil file mentah asli di folder aktif tanpa lewat kompresi engine Hugo
        lightboxImg.src = "featured.jpg"; 
        
        lightbox.style.display = 'flex';
        setTimeout(() => { lightbox.style.opacity = '1'; }, 10);
        document.body.style.overflow = 'hidden'; 
      });

      const closeLightbox = function() {
        lightbox.style.opacity = '0';
        setTimeout(() => { 
          lightbox.style.display = 'none'; 
          document.body.style.overflow = ''; 
        }, 200);
      };

      closeBtn.addEventListener('click', closeLightbox);
      lightbox.addEventListener('click', function(e) {
        if (e.target === lightbox || e.target === lightboxImg) { closeLightbox(); }
      });
    }
  });
</script>