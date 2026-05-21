<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">

<style>
.contact-wrapper { font-family: 'Inter', sans-serif; color: #f8fafc; padding: 20px 0; position: relative; }
/* Margin-top dinaikkan ke 100px untuk memberi ruang pada foto yang lebih besar */
.contact-header { text-align: center; margin-top: 100px; margin-bottom: 40px; }
/* Margin-top diubah ke -90px agar foto tetap berada di tengah perbatasan */
.profile-photo-container { display: flex; justify-content: center; align-items: center; margin-top: -90px; margin-bottom: 20px; position: relative; }
/* Ukuran foto diperbesar menjadi 180px */
.profile-photo { width: 300px; height: 300px; border-radius: 50%; border: 6px solid #1e293b; box-shadow: 0 10px 20px rgba(56, 189, 248, 0.4); object-fit: cover; position: relative; z-index: 10; transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out; }
.profile-photo:hover { transform: scale(1.05); box-shadow: 0 15px 30px rgba(56, 189, 248, 0.6); }
.contact-header h1 { font-size: 3rem; font-weight: 800; background: linear-gradient(90deg, #38bdf8, #818cf8); -webkit-background-clip: text; -webkit-text-fill-color: transparent; margin-top: 10px; margin-bottom: 5px; }
.contact-header p { font-size: 1rem; color: #cbd5e1; max-width: 600px; margin: 0 auto 20px auto; }
.contact-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 25px; margin-bottom: 50px; }
.contact-card { background: rgba(30, 41, 59, 0.4); border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 20px; padding: 30px; text-decoration: none !important; transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1); display: flex; align-items: center; gap: 20px; box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05); }
.contact-card:hover { transform: translateY(-10px); background: rgba(30, 41, 59, 0.6); border-color: #38bdf8; box-shadow: 0 20px 25px -5px rgba(56, 189, 248, 0.2); }
.icon-box { width: 60px; height: 60px; background: rgba(56, 189, 248, 0.1); border-radius: 15px; display: flex; align-items: center; justify-content: center; font-size: 24px; color: #38bdf8; }
.info-box h3 { margin: 0; font-size: 1.2rem; color: #f1f5f9; font-weight: 700; border: none; }
.info-box p { margin: 5px 0 0 0; font-size: 0.9rem; color: #94a3b8; }
.status-section { background: linear-gradient(135deg, rgba(56, 189, 248, 0.05) 0%, rgba(129, 140, 248, 0.05) 100%); border-radius: 24px; padding: 40px; border: 1px dashed rgba(56, 189, 248, 0.3); }
.status-list { list-style: none; padding: 0; display: flex; flex-wrap: wrap; gap: 20px; }
.status-item { background: rgba(15, 23, 42, 0.5); padding: 10px 20px; border-radius: 50px; font-size: 0.9rem; border: 1px solid rgba(255, 255, 255, 0.05); color: #e2e8f0; }
.status-item i { color: #10b981; margin-right: 8px; }
.quote-footer { margin-top: 60px; text-align: center; border-top: 1px solid rgba(255, 255, 255, 0.1); padding-top: 40px; }
.quote-text { font-style: italic; color: #94a3b8; font-size: 1.1rem; margin-bottom: 10px; }
</style>

<div class="contact-wrapper">
<div class="contact-header">
<div class="profile-photo-container">
<img src="/media/me.png" alt="Angga Prastya Sianipar" class="profile-photo">
</div>
<h1>Let's Connect.</h1>
<p>Thank you for taking the time to view my portfolio. I am always open to technical discussions, career opportunities, and strategic project collaborations.</p>
</div>

<div class="contact-grid">
<a href="mailto:anggasianipar2@gmail.com" class="contact-card">
<div class="icon-box"><i class="fas fa-envelope"></i></div>
<div class="info-box">
<h3>Email Inquiry</h3>
<p>anggasianipar2@gmail.com</p>
</div>
</a>

<a href="https://wa.me/6281370673195" class="contact-card">
<div class="icon-box"><i class="fab fa-whatsapp"></i></div>
<div class="info-box">
<h3>Direct Message</h3>
<p>+62 813-7067-3195</p>
</div>
</a>

<a href="https://www.linkedin.com/in/angga-sianipar" class="contact-card">
<div class="icon-box"><i class="fab fa-linkedin-in"></i></div>
<div class="info-box">
<h3>Professional Network</h3>
<p>linkedin.com/in/angga-sianipar</p>
</div>
</a>

<a href="https://github.com/AnggaPrastyaSianipar" class="contact-card">
<div class="icon-box"><i class="fab fa-github"></i></div>
<div class="info-box">
<h3>Technical Source</h3>
<p>github.com/AnggaPrastyaSianipar</p>
</div>
</a>
</div>

<div class="status-section">
<h2 style="margin-bottom: 20px; font-size: 1.5rem; border: none; padding: 0; color: #f8fafc;">Current Availability</h2>
<p style="margin-bottom: 25px; color: #cbd5e1;">Based in <strong>Medan, Indonesia</strong>. Available for global collaboration across all time zones.</p>

<div class="status-list">
<div class="status-item"><i class="fas fa-check-circle"></i> Remote Ready</div>
<div class="status-item"><i class="fas fa-check-circle"></i> Hybrid / On-site (Medan)</div>
<div class="status-item"><i class="fas fa-check-circle"></i> Open to Relocation</div>
</div>
</div>

<div class="quote-footer">
<p class="quote-text">"Software is a great combination between artistry and engineering."</p>
<p style="font-weight: 700; color: #38bdf8; margin: 0;">ANGGA PRASTYA SIANIPAR</p>
</div>
</div>