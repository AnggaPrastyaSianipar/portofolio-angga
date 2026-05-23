---
title: "Sertifikasi Kompetensi BNSP: Ilmuwan Data Muda (Associate Data Scientist)"
date: 2026-01-14

event: "Badan Nasional Sertifikasi Profesi (BNSP) - LSP Digital Technology"
event_url: "https://bnsp.go.id"

location: "Lembaga Sertifikasi Profesi (LSP) Teknologi Digital"
address:
  country: "Indonesia"

summary: "Sertifikat Kompetensi Nasional (Serkom) resmi dari BNSP yang menyatakan KOMPETEN dalam bidang Sains Data (Data Science)."

# Waktu pelaksanaan mengikuti tanggal terbit sertifikat Anda (14 Januari 2026)
event_start: 2026-01-14
event_end: 2026-01-14
all_day: true

authors:
  - me

tags:
  - Certification
  - Data Science
  - BNSP

featured: true

image:
  caption: "Sertifikat Kompetensi BNSP Data Science (Klik gambar untuk Mode Theater HD)"
  focal_point: "Center"
---

## Deskripsi Sertifikasi Kompetensi

Sertifikat dengan nomor **No. 63111 2511 5 0167280 2026** serta **No. Reg. TIK 1565 51969 2026** ini diterbitkan oleh **Badan Nasional Sertifikasi Profesi (BNSP)** melalui **LSP Teknologi Digital**. Kredensial ini merupakan pengakuan formal skala nasional yang menyatakan bahwa saya **KOMPETEN** pada bidang **Sains Data (Data Science)** dengan kualifikasi sebagai **Ilmuwan Data Muda (Associate Data Scientist)**.

---

### Kompetensi Inti yang Divalidasi
* **Prapemrosesan Data (Data Preprocessing)**: Melakukan pembersihan data, penanganan *missing values*, transformasi variabel, dan rekayasa fitur siap pakai untuk pemodelan algoritma.
* **Analisis & Eksplorasi Data (EDA)**: Menemukan pola tersembunyi, korelasi antar variabel, serta merancang visualisasi data kuantitatif yang informatif.
* **Pemodelan Prediktif (Machine Learning)**: Membangun, menguji, dan mengevaluasi performa model komputasi kecerdasan buatan baik untuk klasifikasi maupun klasterisasi data.

> [!SUCCESS] Masa Berlaku Kredensial
> Sertifikat ini ditetapkan di Yogyakarta pada **14 Januari 2026** dan berlaku selama **3 (tiga) tahun** (hingga 14 Januari 2029) di bawah otoritas Ir. Gunawan Ramli, M.Kom. selaku Direktur LSP Teknologi Digital.

<div id="custom-light-box" style="display: none; position: fixed; top: 0; left: 0; width: 100vw; height: 100vh; background: rgba(5, 5, 5, 0.98); z-index: 9999999 !important; justify-content: center; align-items: flex-start; padding: 50px 20px; opacity: 0; transition: opacity 0.2s ease-in-out; overflow-y: auto;">
  <span id="close-light-box" style="position: fixed; top: 20px; right: 30px; color: #fff; font-size: 50px; font-weight: bold; cursor: pointer; user-select: none; z-index: 10000000 !important; background: rgba(0,0,0,0.6); width: 60px; height: 60px; display: flex; justify-content: center; align-items: center; border-radius: 50%; line-height: 50px;">&times;</span>
  
  <img id="light-box-img" src="" alt="Sertifikat Ultra HD" style="display: block; width: 100%; max-width: 1400px; height: auto; border-radius: 6px; box-shadow: 0 0 40px rgba(255,255,255,0.3); margin: 0 auto; cursor: zoom-out; image-rendering: -webkit-optimize-contrast; image-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; transform: translateZ(0); backface-visibility: hidden;">
</div>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    // Memperluas query selector agar mencakup seluruh kemungkinan class penampung gambar di tema Anda
    const mainImg = document.querySelector('.article-header img, .featured-image img, img[class*="featured"], .wg-featured img');
    const lightbox = document.getElementById('custom-light-box');
    const lightboxImg = document.getElementById('light-box-img');
    const closeBtn = document.getElementById('close-light-box');

    if (mainImg && lightbox && lightboxImg) {
      mainImg.style.cursor = 'zoom-in';
      mainImg.title = 'Klik untuk melihat ukuran penuh Ultra HD';

      mainImg.addEventListener('click', function(e) {
        e.preventDefault();
        
        // Memanggil file mentah asli di folder aktif Anda (featured.jpg)
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