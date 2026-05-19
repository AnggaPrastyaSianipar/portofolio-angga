---
title: Engagements
summary: Pengalaman volunteer, kontribusi komunitas, dan jejaring sosial.
type: landing

sections:
  # ────────────────────────────────────────────────────────────────────────────
  # SECTION 1: SOSIAL MEDIA (2 KOLOM FLAT)
  # ────────────────────────────────────────────────────────────────────────────
  - block: markdown
    id: social-media
    content:
      title: "🌐 Media Sosial & Jejaring"
      subtitle: "Mari terhubung dan berkolaborasi secara profesional melalui platform di bawah ini"
      text: |
        <style>
          /* Trik utama untuk menjebol batas max-width bawaan tema */
          .twocolumn-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 40px;
            margin-top: 35px;
            
            /* Memaksa kontainer menggunakan lebar layar penuh */
            width: 85vw; 
            max-width: 1400px;
            position: relative;
            left: 50%;
            right: 50%;
            margin-left: -42.5vw;
            margin-right: -42.5vw;
          }
          
          @media (max-width: 992px) {
            .twocolumn-grid { 
              grid-template-columns: 1fr; 
              width: 100%;
              left: 0;
              right: 0;
              margin-left: 0;
              margin-right: 0;
            }
          }
          
          .custom-card {
            background: rgba(30, 27, 75, 0.4) !important;
            border: 1px solid rgba(99, 102, 241, 0.2) !important;
            backdrop-filter: blur(8px);
            padding: 50px 40px !important;
            border-radius: 24px !important;
            text-align: center;
            height: 100%;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.4);
            transition: all 0.4s cubic-bezier(0.165, 0.84, 0.44, 1) !important;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
          }
          
          .custom-card-link { text-decoration: none !important; color: inherit !important; width: 100%; }
          .custom-card-link:hover .custom-card {
            transform: translateY(-10px) !important;
            border-color: #ff007f !important;
            box-shadow: 0 15px 30px rgba(255, 0, 127, 0.25) !important;
          }

          .card-icon-wrap { background: rgba(255, 255, 255, 0.08); padding: 22px; border-radius: 50%; margin-bottom: 25px; transition: transform 0.3s ease; }
          .custom-card-link:hover .card-icon-wrap { transform: scale(1.15) rotate(5deg); }
        </style>

        <div class="twocolumn-grid">
          
          <a href="https://github.com/AnggaPrastyaSianipar" target="_blank" class="custom-card-link">
            <div class="custom-card">
              <div class="card-icon-wrap">
                <img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" width="65" height="65" style="display: block; filter: invert(1);">
              </div>
              <h3 style="margin-bottom: 15px; font-size: 1.8rem; font-weight: 800; color: #fff;">GitHub</h3>
              <p style="font-size: 1.1rem; opacity: 0.85; line-height: 1.6;">Repositori backend, skrip prediksi Python, dan proyek data science.</p>
            </div>
          </a>

          <a href="https://linkedin.com/in/angga-prastya-sianipar" target="_blank" class="custom-card-link">
            <div class="custom-card">
              <div class="card-icon-wrap" style="background: rgba(0, 119, 181, 0.15);">
                <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="65" height="65" style="display: block;">
              </div>
              <h3 style="margin-bottom: 15px; font-size: 1.8rem; font-weight: 800; color: #fff;">LinkedIn</h3>
              <p style="font-size: 1.1rem; opacity: 0.85; line-height: 1.6;">Jaringan profesional, Software Engineering, dan karir resmi.</p>
            </div>
          </a>

        </div>
    design:
      columns: 1

  # ────────────────────────────────────────────────────────────────────────────
  # SECTION 2: VOLUNTEER (FOTO OTOMATIS PENUH & PRESISI)
  # ────────────────────────────────────────────────────────────────────────────
  - block: markdown
    id: volunteers
    content:
      title: "🤝 Pengalaman Volunteer"
      subtitle: "Kontribusi nyata dan keterlibatan saya dalam pengembangan teknologi masyarakat"
      text: |
        <style>
          .volunteer-card {
            background: rgba(30, 27, 75, 0.4) !important;
            border: 1px solid rgba(99, 102, 241, 0.2) !important;
            border-radius: 24px !important;
            overflow: hidden;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.4);
            transition: all 0.4s ease !important;
            height: 100%;
            display: flex;
            flex-direction: column;
          }
          
          .volunteer-card .image-frame {
            width: 100%;
            height: 440px; 
            overflow: hidden;
            position: relative;
            background: rgba(20, 15, 50, 0.4); 
            display: flex;
            align-items: center;
            justify-content: center;
            /* Memberikan ruang di sekitar foto agar bayangan (shadow) tidak terpotong tepi card */
            padding: 25px; 
            box-sizing: border-box;
          }
          
          .volunteer-card .image-frame img {
            max-width: 100%;
            max-height: 100%;
            object-fit: contain; 
            display: block;
            transition: transform 0.4s ease, box-shadow 0.4s ease;
            
            /* KUNCI UTAMA: Menambahkan kelengkungan sudut dan bayangan bersinar putih pada foto */
            border-radius: 20px !important;
            border: 1px solid rgba(255, 255, 255, 0.1);
            box-shadow: 0 12px 35px rgba(255, 255, 255, 0.25), 0 4px 10px rgba(0, 0, 0, 0.5);
          }
          
          /* Modifikasi efek kode tag Open Source contributor agar serasi */
          .volunteer-card .image-frame code {
            color: #6366f1; 
            font-size: 6rem; 
            font-family: monospace; 
            font-weight: bold; 
            text-shadow: 0 0 25px rgba(99,102,241,0.6);
            transition: transform 0.4s ease;
          }
          
          .volunteer-card:hover { transform: translateY(-10px); border-color: #6366f1; }
          .volunteer-card:hover img { 
            transform: scale(1.03); 
            box-shadow: 0 15px 40px rgba(255, 255, 255, 0.35), 0 5px 15px rgba(0, 0, 0, 0.6);
          }
          .volunteer-card:hover code { transform: scale(1.1); }

          .volunteer-text { padding: 45px !important; text-align: left; flex-grow: 1; }
          .volunteer-text h3 { font-size: 1.7rem; font-weight: 800; color: #fff; margin-bottom: 15px; }
          .volunteer-text p { font-size: 1.1rem; opacity: 0.85; line-height: 1.6; }
        </style>

        <div class="twocolumn-grid">
          
          <div class="volunteer-card">
            <div class="image-frame">
              <img src="/media/foto-volunteer-angga.png" onerror="this.src='https://images.unsplash.com/photo-1517694712202-14dd9538aa97?w=800';">
            </div>
            <div class="volunteer-text">
              <h3>Volunteer Data Management</h3>
              <p>Melakukan rekayasa data, optimalisasi query, dan membantu digitalisasi arsip administrasi desa menggunakan basis data relasional MySQL.</p>
            </div>
          </div>

          <div class="volunteer-card">
            <div class="image-frame" style="background: linear-gradient(135deg, #1e1b4b 0%, #311b92 100%);">
              <code style="display: block;">&lt;/&gt;</code>
            </div>
            <div class="volunteer-text">
              <h3>Open Source Contributor</h3>
              <p>Aktif membangun logika backend, melakukan integrasi REST API, serta berkontribusi optimasi performa dalam tim internal komunitas teknologi.</p>
            </div>
          </div>

        </div>
---