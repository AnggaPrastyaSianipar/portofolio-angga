---
title: Engagements
summary: Volunteer experiences, community contributions, and professional networking.
type: landing

sections:
  - block: markdown
    id: social-media
    content:
      title: " Social Media & Networking"
      subtitle: "Let's connect and collaborate professionally through the platforms below"
      text: |
        <style>
          .twocolumn-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 40px;
            margin-top: 35px;
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
            border-radius: 24px !important;
            text-align: center;
            height: 100%;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.4);
            transition: all 0.4s cubic-bezier(0.165, 0.84, 0.44, 1) !important;
            display: flex;
            flex-direction: column;
            overflow: hidden;
          }
          .custom-card:hover {
            transform: translateY(-10px) !important;
            border-color: #6366f1 !important;
            box-shadow: 0 15px 30px rgba(99, 102, 241, 0.25) !important;
          }
          
          .card-text-link {
            text-decoration: none !important;
            color: inherit !important;
            display: block;
            height: 100%;
          }
          .card-text-link:hover h3 {
            color: #ff007f !important;
          }

          .card-banner {
            width: 100%;
            height: 260px;
            overflow: hidden;
            position: relative;
          }
          .card-banner img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            object-position: top;
            display: block;
            transition: transform 0.4s ease;
          }
          .custom-card:hover .card-banner img { transform: scale(1.05); }

          .card-body { padding: 30px 35px 35px; text-align: left; flex-grow: 1; }
          .card-body h3 { font-size: 1.6rem; font-weight: 800; color: #fff; margin-bottom: 10px; transition: color 0.3s ease; }
          .card-body p { font-size: 1.05rem; opacity: 0.8; line-height: 1.6; margin: 0; }
          .skill-tags { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 16px; }
          .skill-tag {
            background: rgba(99, 102, 241, 0.2);
            border: 1px solid rgba(99, 102, 241, 0.4);
            color: #a5b4fc;
            font-size: 0.78rem;
            font-weight: 600;
            padding: 5px 12px;
            border-radius: 20px;
            letter-spacing: 0.03em;
          }
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
            background: #0d0b2b;
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
            position: relative;
          }
          .image-frame a {
            width: 100%;
            height: 100%;
            display: block;
            position: relative;
            cursor: pointer;
          }
          .volunteer-card .image-frame img {
            width: 100%;
            height: 100%;
            object-fit: contain;
            object-position: center;
            display: block;
            transition: transform 0.4s ease;
          }
          .volunteer-card:hover { transform: translateY(-10px); border-color: #6366f1; }
          .volunteer-card:hover img { transform: scale(1.03); }
          .volunteer-text { padding: 45px !important; text-align: left; flex-grow: 1; }
          .volunteer-text h3 { font-size: 1.7rem; font-weight: 800; color: #fff; margin-bottom: 15px; }
          .volunteer-text p { font-size: 1.1rem; opacity: 0.85; line-height: 1.6; }
          
          .zoom-icon {
            position: absolute;
            bottom: 15px;
            right: 15px;
            background: rgba(0, 0, 0, 0.6);
            backdrop-filter: blur(4px);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 8px;
            padding: 8px;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            opacity: 0.7;
            transition: all 0.3s ease;
            z-index: 10;
            pointer-events: none;
          }
          .image-frame a:hover .zoom-icon,
          .card-banner a:hover .zoom-icon {
            opacity: 1;
            transform: scale(1.1);
            background: rgba(99, 102, 241, 0.8);
            border-color: #a5b4fc;
          }

          #imageModal {
            display: none;
            position: fixed;
            z-index: 99999;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(10, 10, 25, 0.95);
            backdrop-filter: blur(8px);
            align-items: center;
            justify-content: center;
          }
          #imageModal.show {
            display: flex;
          }
          .modal-content {
            max-width: 90vw;
            max-height: 85vh;
            border-radius: 12px;
            box-shadow: 0 15px 50px rgba(0,0,0,0.6);
            object-fit: contain;
            animation: zoomIn 0.3s cubic-bezier(0.165, 0.84, 0.44, 1);
          }
          @keyframes zoomIn {
            from { transform: scale(0.9); opacity: 0; }
            to { transform: scale(1); opacity: 1; }
          }
          .close-modal {
            position: absolute;
            top: 25px;
            right: 40px;
            color: #ffffff;
            font-size: 45px;
            font-weight: bold;
            cursor: pointer;
            transition: 0.2s ease;
            z-index: 100000;
          }
          .close-modal:hover {
            color: #ff007f;
            transform: scale(1.1);
          }
        </style>

        <div class="twocolumn-grid">
          <div class="custom-card">
            <div class="card-banner">
              <a href="https://anggaprastyasianipar.github.io/portofolio-angga/media/github.png" onclick="openModal(event, this.href)" style="display:block; width:100%; height:100%;">
                <img src="https://anggaprastyasianipar.github.io/portofolio-angga/media/github.png">
                <div class="zoom-icon">
                  <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg>
                </div>
              </a>
            </div>
            <a href="https://github.com/AnggaPrastyaSianipar" target="_blank" class="card-text-link">
              <div class="card-body">
                <h3>GitHub</h3>
                <p>A dedicated Back-End Engineer and Informatics Engineering graduate with hands-on experience in designing, developing, and maintaining scalable web applications and database systems. Skilled in building robust back-end architectures, RESTful APIs, and dynamic web platforms using PHP, JavaScript, and Python, with additional expertise in HTML, CSS, MySQL, SQLite, and MongoDB. Experienced in database design, query optimization, software testing, debugging, and system integration to ensure high-performance and reliable applications. Passionate about clean code, problem-solving, and continuous learning in modern web technologies. Explore 16 public repositories showcasing real-world projects, including web development systems, data processing applications, and database-driven solutions.</p>
                <div class="skill-tags">
                  <span class="skill-tag"> Back-End Engineering</span>
                  <span class="skill-tag"> Web Application Development</span>
                  <span class="skill-tag"> Database Architecture & Optimization</span>
                  <span class="skill-tag"> Software Testing & Automation</span>
                </div>
              </div>
            </a>
          </div>

          <div class="custom-card">
            <div class="card-banner">
              <a href="https://anggaprastyasianipar.github.io/portofolio-angga/media/linkedin.png" onclick="openModal(event, this.href)" style="display:block; width:100%; height:100%;">
                <img src="https://anggaprastyasianipar.github.io/portofolio-angga/media/linkedin.png">
                <div class="zoom-icon">
                  <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg>
                </div>
              </a>
            </div>
            <a href="https://linkedin.com/in/angga-prastya-sianipar" target="_blank" class="card-text-link">
              <div class="card-body">
                <h3>LinkedIn</h3>
                <p>An Informatics Engineering graduate from Universitas Methodist Indonesia with hands-on experience in web development, back-end engineering, and database management. Skilled in developing scalable and efficient web applications using PHP, JavaScript, Python, HTML, CSS, MySQL, SQLite, and MongoDB. Experienced in building RESTful APIs, managing databases, performing software testing, debugging, and optimizing application performance. Previously gained industry experience at PT Presentologics, contributing to real-world software development projects and collaborative engineering environments. Passionate about clean code, system architecture, and continuous learning in modern technologies. This LinkedIn profile showcases professional experience, technical skills, certifications, and project portfolios, including 16 public repositories featuring real-world applications and software development projects. Open to networking, collaborations, internships, and career opportunities in web development and software engineering.</p>
                <div class="skill-tags">
                  <span class="skill-tag"> Back-End Engineering</span>
                  <span class="skill-tag"> Web Application Development</span>
                  <span class="skill-tag"> Database Architecture & Optimization</span>
                  <span class="skill-tag"> Software Testing & Automation</span>
                </div>
              </div>
            </a>
          </div>
        </div>

        <br><br>

        <h2 style="text-align:center; font-size:2rem; font-weight:800; color:#fff; margin-bottom: 10px;"> Teaching Assistant | Faculty of Computer Science</h2>
        <p style="text-align:center; opacity:0.75; margin-bottom:40px;">Supporting academic processes, laboratory guidance, and student development</p>

        <div class="twocolumn-grid">
          <div class="volunteer-card">
            <div class="image-frame">
              <a href="https://anggaprastyasianipar.github.io/portofolio-angga/media/asisten1.jpeg" onclick="openModal(event, this.href)">
                <img src="https://anggaprastyasianipar.github.io/portofolio-angga/media/asisten1.jpeg">
                <div class="zoom-icon">
                  <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg>
                </div>
              </a>
            </div>
            <div class="volunteer-text">
              <h3>Computer Laboratory Assistant | Faculty of Computer Science (2024–2025)</h3>
              <p>Served for two consecutive semesters at Universitas Methodist Indonesia, assisting lead lecturers in designing and delivering practicum materials. Responsible for guiding laboratory sessions, evaluating assignments, and mentoring students in technical troubleshooting. Played an active role in ensuring comprehensive student understanding across three core subjects: <strong>Web Programming & Design</strong> (mastery of HTML5, CSS3, JavaScript, DOM manipulation, and database integration), <strong>Database Systems</strong> (ERD design, normalization, and MySQL queries), and <strong>Operating Systems</strong> (memory management, file systems, and CLI execution).</p>
            </div>
          </div>
          
          <div class="volunteer-card">
            <div class="image-frame">
              <a href="https://anggaprastyasianipar.github.io/portofolio-angga/media/asisten2.jpeg" onclick="openModal(event, this.href)">
                <img src="https://anggaprastyasianipar.github.io/portofolio-angga/media/asisten2.jpeg">
                <div class="zoom-icon">
                  <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg>
                </div>
              </a>
            </div>
            <div class="volunteer-text">
              <h3>Teaching Assistant — Practicum Mentoring & Academic Evaluation</h3>
              <p>Dedicated to fostering an interactive and student-centric laboratory learning environment. Provided personalized technical support (<em>hands-on mentoring</em>) to guide students in solving case studies and performing independent code <em>troubleshooting</em>. Entrusted to manage practicum class operations, develop objective evaluation instruments, and coordinate closely with presiding lecturers to ensure harmonization between theoretical concepts and technical field implementation.</p>
            </div>
          </div>
        </div>

        <br><br>

        <h2 style="text-align:center; font-size:2rem; font-weight:800; color:#fff; margin-bottom: 10px;"> Field Work Practice (PKL) | BPJS Ketenagakerjaan</h2>
        <p style="text-align:center; opacity:0.75; margin-bottom:40px;">Applying information technology competencies to support social security agency operations in Medan (2025)</p>

        <div class="twocolumn-grid">
          <div class="volunteer-card">
            <div class="image-frame">
              <a href="https://anggaprastyasianipar.github.io/portofolio-angga/media/pkl1.jpeg" onclick="openModal(event, this.href)">
                <img src="https://anggaprastyasianipar.github.io/portofolio-angga/media/pkl1.jpeg">
                <div class="zoom-icon">
                  <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg>
                </div>
              </a>
            </div>
            <div class="volunteer-text">
              <h3>PKL — Web Developer, IT Support & Administration | BPJS Ketenagakerjaan Medan Kota</h3>
              <p>Executed field work practice from July to September 2025 focusing on software engineering to optimize operational efficiency for the Death Security (JKM) program. <strong>Application Design & Development:</strong> Engineered a web-based JKM Visit Scheduling System to automate field inspection scheduling and accelerate claim processing. <strong>Database Management:</strong> Developed an integrated database structure (MySQL) to centralize operational visit logs and ensure data consistency. <strong>Systems Analysis & IT Support:</strong> Identified technical bottlenecks in manual workflows and formulated digitalization recommendations. <strong>Administrative Support:</strong> Assisted with daily administrative tasks, including document processing and membership archive digitalization to ensure seamless branch operations.</p>
            </div>
          </div>
        </div>

        <br><br>

        <h2 style="text-align:center; font-size:2rem; font-weight:800; color:#fff; margin-bottom: 10px;"> Volunteer Experience</h2>
        <p style="text-align:center; opacity:0.75; margin-bottom:40px;">Tangible contributions and my involvement in technological community development</p>

        <div class="twocolumn-grid">
          <div class="volunteer-card">
            <div class="image-frame">
              <a href="https://anggaprastyasianipar.github.io/portofolio-angga/media/volunter1.jpeg" onclick="openModal(event, this.href)">
                <img src="https://anggaprastyasianipar.github.io/portofolio-angga/media/volunter1.jpeg">
                <div class="zoom-icon">
                  <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg>
                </div>
              </a>
            </div>
            <div class="volunteer-text">
              <h3>Volunteer — Technical Support Coordinator | ICIC 2022</h3>
              <p>Entrusted as a Technical Support Coordinator at the International Conference on Informatics and Computing (ICIC) 2022, Universitas Methodist Indonesia, Medan (October 24–25, 2022). Oversaw end-to-end technical operations across multi-session plenary events, including audio-visual system management, equipment readiness, and real-time troubleshooting. Demonstrated reliability, professional discipline, and the ability to perform under pressure in an international-scale academic conference attended by researchers and institutional representatives from across Indonesia and abroad.</p>
            </div>
          </div>
          
          <div class="volunteer-card">
            <div class="image-frame">
              <a href="https://anggaprastyasianipar.github.io/portofolio-angga/media/volunter2.jpeg" onclick="openModal(event, this.href)">
                <img src="https://anggaprastyasianipar.github.io/portofolio-angga/media/volunter2.jpeg">
                <div class="zoom-icon">
                  <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg>
                </div>
              </a>
            </div>
            <div class="volunteer-text">
              <h3>Volunteer — Event Technology Support | Rakornas APTIKOM 2024</h3>
              <p>Appointed as Event Technology Support Volunteer at the Rakornas APTIKOM (National Coordination Meeting of the Indonesian Informatics and Computing Association), held on October 24–26, 2024. Responsible for delivering seamless digital presentation support throughout the event, executing precise real-time content delivery in close coordination with keynote speakers and session moderators. Ensured zero disruption across all plenary sessions, exhibiting strong initiative, technical attentiveness, and a high sense of responsibility — competencies that contributed directly to the event's professional execution and overall success.</p>
            </div>
          </div>

          <div class="volunteer-card">
            <div class="image-frame">
              <a href="https://anggaprastyasianipar.github.io/portofolio-angga/media/volunter3.jpeg" onclick="openModal(event, this.href)">
                <img src="https://anggaprastyasianipar.github.io/portofolio-angga/media/volunter3.jpeg">
                <div class="zoom-icon">
                  <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg>
                </div>
              </a>
            </div>
            <div class="volunteer-text">
              <h3>Volunteer — Tour Guide & Liaison Officer | Rakornas APTIKOM 2024</h3>
              <p>Acted as a Tour Guide and Liaison Officer for delegates and honorary guests from various higher education institutions across Indonesia during the Rakornas APTIKOM event (October 24–26, 2024). Fully responsible for ensuring smooth participant mobility, coordinating tour agendas, and providing local information alongside excellent service. Prioritized interpersonal communication, rapid problem-solving, and outstanding hospitality to deliver a memorable experience and positive representation for the host institution.</p>
            </div>
          </div>

          <div class="volunteer-card">
            <div class="image-frame">
              <a href="https://anggaprastyasianipar.github.io/portofolio-angga/media/volunter4.jpeg" onclick="openModal(event, this.href)">
                <img src="https://anggaprastyasianipar.github.io/portofolio-angga/media/volunter4.jpeg">
                <div class="zoom-icon">
                  <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg>
                </div>
              </a>
            </div>
            <div class="volunteer-text">
              <h3>Volunteer — Team Coordination & Community Management | Rakornas APTIKOM 2024</h3>
              <p>Actively participated in the core volunteer team under the direct guidance and supervision of a faculty mentor to ensure the success of the Rakornas APTIKOM 2024 national agenda (October 24–26, 2024). Responsible for building team solidarity, facilitating adaptive communication among committee members, and ensuring field task execution aligned with interdisciplinary directives. This collaborative experience strengthened competencies in organizational management, team-based leadership, and professional execution in supporting large-scale events.</p>
            </div>
          </div>
        </div>

        <br><br>

        <h2 style="text-align:center; font-size:2rem; font-weight:800; color:#fff; margin-bottom: 10px;"> Committee | Faculty of Computer Science Retreat</h2>
        <p style="text-align:center; opacity:0.75; margin-bottom:40px;">Dedication and active collaboration in driving successful faculty gathering activities</p>

        <div class="twocolumn-grid">
          <div class="volunteer-card">
            <div class="image-frame">
              <a href="https://anggaprastyasianipar.github.io/portofolio-angga/media/retreat1.jpeg" onclick="openModal(event, this.href)">
                <img src="https://anggaprastyasianipar.github.io/portofolio-angga/media/retreat1.jpeg">
                <div class="zoom-icon">
                  <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg>
                </div>
              </a>
            </div>
            <div class="volunteer-text">
              <h3>Committee — Security Division | Faculty of Computer Science Retreat 2024</h3>
              <p>Fully responsible for designing, coordinating, and executing risk management and security strategies across all operational areas during the Faculty of Computer Science Retreat 2024. Led preventive surveillance to ensure the safety of hundreds of participants and the seamless flow of event mobility from start to finish. Demonstrated high discipline, precise response in emergency situations, and solid cross-divisional coordination, directly contributing to the creation of a safe, conducive, and successful event environment.</p>
            </div>
          </div>

          <div class="volunteer-card">
            <div class="image-frame">
              <a href="https://anggaprastyasianipar.github.io/portofolio-angga/media/retreat2.jpeg" onclick="openModal(event, this.href)">
                <img src="https://anggaprastyasianipar.github.io/portofolio-angga/media/retreat2.jpeg">
                <div class="zoom-icon">
                  <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="15 3 21 3 21 9"></polyline><polyline points="9 21 3 21 3 15"></polyline><line x1="21" y1="3" x2="14" y2="10"></line><line x1="3" y1="21" x2="10" y2="14"></line></svg>
                </div>
              </a>
            </div>
            <div class="volunteer-text">
              <h3>Committee — Security Division | Faculty of Computer Science Retreat 2024</h3>
              <p>Fully responsible for designing, coordinating, and executing risk management and security strategies across all operational areas during the Faculty of Computer Science Retreat 2024. Led preventive surveillance to ensure the safety of hundreds of participants and the seamless flow of event mobility from start to finish. Demonstrated high discipline, precise response in emergency situations, and solid cross-divisional coordination, directly contributing to the creation of a safe, conducive, and successful event environment.</p>
            </div>
          </div>
        </div>

        <div id="imageModal" onclick="closeModal()">
          <span class="close-modal" onclick="closeModal()">&times;</span>
          <img class="modal-content" id="modalImg" onclick="event.stopPropagation()">
        </div>

        <script>
          function openModal(e, imgSrc) {
            e.preventDefault(); 
            document.getElementById('imageModal').classList.add('show'); 
            document.getElementById('modalImg').src = imgSrc; 
          }
          function closeModal() {
            document.getElementById('imageModal').classList.remove('show'); 
          }
        </script>

    design:
      columns: 1
---