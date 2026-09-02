---
title: "Website Pendaftaran Siswa SMA"
date: "2026-05-01T00:00:00Z"
weight: 8
summary: "An interactive web-based school registration and information system powered by PHP to streamline student admissions and institutional management."
tags:
  - Web Development
  - PHP
  - MySQL
  - School Information System
image:
  preview_only: true
links:
  - icon: github
    icon_pack: fab
    name: Source Code
    url: https://github.com/AnggaPrastyaSianipar/Asri-School
---

<style>
  /* Text Optimization */
  body {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-rendering: optimizeLegibility;
  }

  /* Image Container - Removed onclick so clicking outside the icon doesn't trigger the modal */
  .img-container { 
    transition: all 0.4s cubic-bezier(0.165, 0.84, 0.44, 1); 
    position: relative; 
    overflow: hidden;
  }
  .img-container:hover { 
    box-shadow: 0 15px 30px rgba(99, 102, 241, 0.25) !important; 
  }
  
  /* Zoom Icon - The only trigger for the modal */
  .zoom-icon {
    position: absolute; bottom: 15px; right: 15px;
    background: rgba(0, 0, 0, 0.7); backdrop-filter: blur(6px);
    border: 1px solid rgba(255, 255, 255, 0.3);
    border-radius: 8px; padding: 10px; cursor: pointer;
    display: flex; align-items: center; justify-content: center;
    transition: all 0.3s ease; z-index: 10;
  }
  .zoom-icon:hover { background: rgba(99, 102, 241, 0.8); transform: scale(1.1); }

  /* MODAL CSS */
  #modal { 
    display: none; position: fixed; z-index: 999999; top: 0; left: 0; 
    width: 100vw; height: 100vh; background: rgba(10, 10, 25, 0.98); 
    backdrop-filter: blur(15px); justify-content: center; align-items: center;
  }
  #modal.show { display: flex; }

  .modal-content { 
    width: 90vw !important; height: 85vh !important; 
    object-fit: contain !important; border-radius: 20px !important; 
    box-shadow: 0 0 80px rgba(99, 102, 241, 0.4);
    image-rendering: -webkit-optimize-contrast;
    animation: zoomIn 0.4s ease;
  }
  @keyframes zoomIn { from { transform: scale(0.95); opacity: 0; } to { transform: scale(1); opacity: 1; } }

  .close-x { 
    position: absolute; top: 20px; right: 40px; color: #fff; 
    font-size: 50px; font-weight: 800; cursor: pointer; z-index: 1000000;
  }
</style>

<div id="modal" onclick="closeModal()">
  <span class="close-x">&times;</span>
  <img id="modalContent" class="modal-content" onclick="event.stopPropagation()">
</div>

<div class="img-container" style="width: 100%; margin-bottom: 40px; border-radius: 20px;">
  <img src="banner.png" style="width: 100%; display: block; border-radius: 20px;">
  <div class="zoom-icon" onclick="openModal('featured.png')">
    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M15 3h6v6M9 21H3v-6M21 3l-7 7M3 21l7-7"/></svg>
  </div>
</div>

Asri School is a web-based school information and student registration platform designed to efficiently manage student admissions and institutional workflows.

### Roles & Responsibilities:
* **Back-End Development:** Built a robust and secure server-side application architecture using PHP.
* **Database Management:** Structured and managed relational database operations using MySQL to securely handle student records.
* **Front-End Integration:** Implemented an intuitive and responsive user interface for applicants and administrative staff.

## About the Project
<p style="font-size: 1.1rem; line-height: 1.8; color: #b3b3b3; text-align: justify;">
  <strong>Asri School</strong> was developed in response to the inefficiencies often found in traditional school administration processes, such as manual paperwork, long queues, and data management errors. Serving as an integrated school management system platform, Asri School focuses on providing fast, transparent, and practical online student registration services. 
  <br><br>
  This platform is designed to make it easier for prospective students to apply from anywhere and to assist school administrators in organizing student data efficiently through a fully integrated PHP backend system.
</p>

### System Documentation
<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 20px; margin-top: 25px;">
  <div class="img-container" style="background: white; border-radius: 20px; padding: 20px;">
    <img src="https://anggaprastyasianipar.github.io/portofolio-angga/gallery/AsriSchool1.jpg" style="width: 100%; border-radius: 12px;">
    <div class="zoom-icon" onclick="openModal('https://anggaprastyasianipar.github.io/portofolio-angga/gallery/AsriSchool1.jpg')"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M15 3h6v6M9 21H3v-6M21 3l-7 7M3 21l7-7"/></svg></div>
  </div>
  <div class="img-container" style="background: white; border-radius: 20px; padding: 20px;">
    <img src="https://anggaprastyasianipar.github.io/portofolio-angga/gallery/AsriSchool2.jpg" style="width: 100%; border-radius: 12px;">
    <div class="zoom-icon" onclick="openModal('https://anggaprastyasianipar.github.io/portofolio-angga/gallery/AsriSchool2.jpg')"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M15 3h6v6M9 21H3v-6M21 3l-7 7M3 21l7-7"/></svg></div>
  </div>
  
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