---
title: "Perancangan Aplikasi Pemesanan Obat dan Digitalisasi Resep Dokter Berbasis Android pada Apotek Angga Punya"
date: "2025-11-01T00:00:00Z"
publishDate: "2026-08-01T00:00:00Z"
summary: "Full-stack mobile application development featuring Android (React Native), Node.js API, MySQL database, digital prescription uploads, and e-commerce checkout features."
tags:
  - Full-Stack Development
  - Mobile Application
  - React Native
  - Node.js & Express
  - Database Architecture
image:
  preview_only: true
links:
  - icon: github
    icon_pack: fab
    name: View Code
    url: https://github.com/AnggaPrastyaSianipar/ApotekMobile
---

<style>
  /* Text Optimization for Clarity */
  body {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-rendering: optimizeLegibility;
  }

  /* Image Container */
  .img-container { 
    position: relative; 
    overflow: hidden;
  }
  
  /* Zoom Icon - Uniform with diagonal arrows */
  .zoom-icon {
    position: absolute; bottom: 15px; right: 15px;
    background: rgba(0, 0, 0, 0.7); backdrop-filter: blur(6px);
    border: 1px solid rgba(255, 255, 255, 0.3);
    border-radius: 8px; padding: 8px; color: white;
    display: flex; align-items: center; justify-content: center;
    cursor: pointer;
    transition: all 0.3s ease; z-index: 10;
  }
  .zoom-icon svg { width: 20px; height: 20px; }
  .zoom-icon:hover { background: rgba(99, 102, 241, 0.8); transform: scale(1.1); }

  /* MODAL CSS */
  #modal { 
    display: none; position: fixed; z-index: 999999; top: 0; left: 0; 
    width: 100vw; height: 100vh; background: rgba(10, 10, 25, 0.98); 
    backdrop-filter: blur(15px); justify-content: center; align-items: center;
  }
  
  #modal.show { display: flex; }

  /* Modal Image - Auto Responsive */
  .modal-content { 
    width: 90vw !important; 
    height: auto !important;
    max-height: 90vh !important;
    object-fit: contain !important;
    border-radius: 20px !important;
    box-shadow: 0 0 80px rgba(99, 102, 241, 0.4);
    image-rendering: -webkit-optimize-contrast;
    animation: zoomIn 0.4s ease;
  }

  @keyframes zoomIn {
    from { transform: scale(0.95); opacity: 0; }
    to { transform: scale(1); opacity: 1; }
  }

  .close-x { 
    position: absolute; top: 20px; right: 40px; color: #fff; 
    font-size: 50px; font-weight: 800; cursor: pointer; 
    transition: 0.2s ease; z-index: 1000000;
  }
  .close-x:hover { color: #ff007f; transform: scale(1.1); }
</style>

<div id="modal" onclick="closeModal()">
  <span class="close-x">&times;</span>
  <img id="modalContent" class="modal-content" onclick="event.stopPropagation()">
</div>

<div class="img-container" style="max-width: 80%; margin: 0 auto 40px auto; border-radius: 20px; box-shadow: 0 15px 35px rgba(0,0,0,0.3);">
  <img src="banner.png" style="width: 100%; display: block; border-radius: 20px;">
  <div class="zoom-icon" onclick="openModal('banner.png')">
    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg>
  </div>
</div>

## About the Project
<p style="font-size: 1.1rem; line-height: 1.8; color: #b3b3b3; text-align: justify;">
  <strong>Apotek Angga Punya</strong> is an Android-based mobile application specifically designed to modernize medicine ordering and prescription digitization. This system serves as a solution to streamline pharmacy operations, particularly concerning the seamless submission of doctor's prescriptions and real-time product accessibility</strong> claims.
  <br><br>
  Prior to this system, ordering and prescription processes were managed manually, leading to fragmented communication and inefficiencies. Through this platform, users can securely register, browse categorized medicine inventories, upload digital prescriptions via Multer, consult with pharmacists interactively, and execute structured checkouts with flexible payment methods. Powered by React Native, Node.js with Express, and MySQL databases (db_apotek), this application acts as an end-to-end digital commerce infrastructure—ensuring accurate data integration, streamlined user management, and enhanced operational efficiency.
</p>

### System Documentation
<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 20px; margin-top: 25px;">
  <div class="img-container" style="background: white; border-radius: 20px; padding: 20px;"><img src="https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek1.png" style="width: 100%; border-radius: 12px;"><div class="zoom-icon" onclick="openModal('https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek1.png')"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg></div></div>
  <div class="img-container" style="background: white; border-radius: 20px; padding: 20px;"><img src="https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek2.png" style="width: 100%; border-radius: 12px;"><div class="zoom-icon" onclick="openModal('https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek2.png')"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg></div></div>
  <div class="img-container" style="background: white; border-radius: 20px; padding: 20px;"><img src="https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek3.png" style="width: 100%; border-radius: 12px;"><div class="zoom-icon" onclick="openModal('https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek3.png')"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg></div></div>
  <div class="img-container" style="background: white; border-radius: 20px; padding: 20px;"><img src="https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek4.png" style="width: 100%; border-radius: 12px;"><div class="zoom-icon" onclick="openModal('https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek4.png')"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg></div></div>
  <div class="img-container" style="background: white; border-radius: 20px; padding: 20px;"><img src="https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek5.png" style="width: 100%; border-radius: 12px;"><div class="zoom-icon" onclick="openModal('https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek5.png')"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg></div></div>
  <div class="img-container" style="background: white; border-radius: 20px; padding: 20px;"><img src="https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek6.png" style="width: 100%; border-radius: 12px;"><div class="zoom-icon" onclick="openModal('https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek6.png')"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg></div></div>
  <div class="img-container" style="background: white; border-radius: 20px; padding: 20px;"><img src="https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek7.png" style="width: 100%; border-radius: 12px;"><div class="zoom-icon" onclick="openModal('https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek7.png')"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg></div></div>
    <div class="img-container" style="background: white; border-radius: 20px; padding: 20px;"><img src="https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek8.png" style="width: 100%; border-radius: 12px;"><div class="zoom-icon" onclick="openModal('https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek8.png')"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg></div></div>
    <div class="img-container" style="background: white; border-radius: 20px; padding: 20px;"><img src="https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek9.png" style="width: 100%; border-radius: 12px;"><div class="zoom-icon" onclick="openModal('https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek9.png')"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg></div></div>
    <div class="img-container" style="background: white; border-radius: 20px; padding: 20px;"><img src="https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek10.png" style="width: 100%; border-radius: 12px;"><div class="zoom-icon" onclick="openModal('https://anggaprastyasianipar.github.io/portofolio-angga/gallery/Apotek10.png')"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg></div></div>
 </div>

<script>
  function openModal(src) {
    const modal = document.getElementById('modal');
    document.getElementById('modalContent').src = src;
    modal.classList.add('show');
    document.body.style.overflow = 'hidden';
  }
  function closeModal() {
    document.getElementById('modal').classList.remove('show');
    document.body.style.overflow = 'auto';
  }
</script>