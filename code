<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MY WEBSITE</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: url('nuhan 2.jpg') no-repeat center center fixed;
      background-size: cover;
    }
    header {
      background: rgba(0,0,0,0.5);
      color: white;
      text-align: center;
      padding: 60px 20px 40px 20px;
      min-height: 60vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }
    header img {
      width: 120px;
      border-radius: 50%;
      margin-bottom: 20px;
      box-shadow: 0 0 15px #222;
      animation: imgPop 1s;
    }
    nav {
      background: #0056b3;
      padding: 15px 0;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 10;
    }
    nav a {
      color: white;
      margin: 0 20px;
      text-decoration: none;
      font-size: 1.2em;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffd700;
    }
    #main-content {
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 40vh;
      margin-top: 30px;
    }
    section {
      background: rgba(255,255,255,0.95);
      padding: 30px 20px;
      margin: 20px 0;
      border-radius: 12px;
      box-shadow: 0 0 20px rgba(0,0,0,0.08);
      width: 80%;
      max-width: 700px;
      text-align: center;
      display: none;
      opacity: 0;
      transition: opacity 0.5s;
    }
    section.active {
      display: block;
      opacity: 1;
      animation: fadeIn 0.7s;
    }
    section h2 {
      margin-top: 0;
      font-size: 2em;
      color: #0056b3;
    }
    .galeri-img {
      width: 180px;
      margin: 10px;
      border-radius: 10px;
      cursor: pointer;
      transition: transform 0.3s, box-shadow 0.3s;
      box-shadow: 0 0 10px #bbb;
    }
    .galeri-img:hover {
      transform: scale(1.08);
      box-shadow: 0 0 20px #0056b3;
    }
    .app-icons img {
      width: 40px;
      margin: 0 8px;
      vertical-align: middle;
      transition: transform 0.3s;
    }
    .app-icons img:hover {
      transform: scale(1.2) rotate(-10deg);
    }
    button {
      padding: 8px 18px;
      border-radius: 6px;
      border: 1px solid #0056b3;
      background: #fff;
      color: #0056b3;
      font-weight: bold;
      cursor: pointer;
      margin-top: 18px;
      transition: background 0.3s, color 0.3s;
    }
    button:hover {
      background: #0056b3;
      color: #fff;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 15px;
      width: 100%;
      font-size: 1em;
      letter-spacing: 1px;
      position: static;
      margin-top: 40px;
    }
    /* Modal styling */
    .modal {
      display: none;
      position: fixed;
      z-index: 999;
      left: 0; top: 0;
      width: 100%; height: 100%;
      overflow: auto;
      background: rgba(0,0,0,0.7);
    }
    .modal-content {
      margin: 10% auto;
      display: block;
      max-width: 80%;
      border-radius: 10px;
      box-shadow: 0 0 20px #000;
    }
    .close {
      position: absolute;
      top: 30px;
      right: 50px;
      color: #fff;
      font-size: 40px;
      font-weight: bold;
      cursor: pointer;
      z-index: 1000;
    }
    /* Animasi */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px);}
      to { opacity: 1; transform: translateY(0);}
    }
    @keyframes imgPop {
      0% { transform: scale(0.8);}
      60% { transform: scale(1.1);}
      100% { transform: scale(1);}
    }
    /* Responsive */
    @media (max-width: 600px) {
      section { width: 98%; padding: 15px 5px;}
      nav a { font-size: 1em; margin: 0 10px;}
      header { padding: 30px 5px 20px 5px;}
    }
  </style>
</head>
<body>
  <header id="cover">
    <h1 onclick="showMenu()" style="cursor:pointer;">Selamat Datang di Website Saya</h1>
    <h3 style="color:#ffd700; margin-top:30px;">Kepo ya? hehehehe...</h3>
  </header>

  <nav>
    <a href="#" onclick="showSection('about')">Tentang</a>
    <a href="#" onclick="showSection('galeri')">Galeri</a>
    <a href="#" onclick="showSection('kontak')">Kontak</a>
    <a href="#" onclick="showSection('cv')">CV</a>
  </nav>

  <div id="main-content">
    <section id="about">
      <h2>Tentang Saya</h2>
      <p>
        Hai... Kenalin saya Achmad Nuhan Taufiqur Rohim biasa dipanggil Nuhan, saya berasal dari Jember. Saya seorang mahasiswa Universitas Jember yang sedang menempuh pendidikan S1 di bidang Informatika, Fakultas Ilmu Komputer. Saya sangat tertarik dengan dunia pemrograman dan teknologi sekarang ini. Terima kasih!
      </p>
      <button onclick="goBack()">Kembali</button>
    </section>

    <section id="galeri">
      <h2>My Galeri</h2>
      <img src="nuhan 3.jpg" alt="Foto 1" class="galeri-img">
      <img src="nuhan 4.jpg" alt="Foto 2" class="galeri-img">
      <img src="nuhan.jpg" alt="Foto 3" class="galeri-img">
      <br>
      <button onclick="goBack()">Kembali</button>
    </section>

    <section id="kontak">
      <h2>Kontak</h2>
      <div class="app-icons" style="margin-bottom:18px;">
        <a href="https://instagram.com/a_nhntr" target="_blank" title="Instagram">
          <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" alt="Instagram">
        </a>
        <a href="https://wa.me/6285103080404" target="_blank" title="WhatsApp">
          <img src="https://cdn-icons-png.flaticon.com/512/733/733585.png" alt="WhatsApp">
        </a>
      </div>
      <p>
        ig: <a href="https://instagram.com/a_nhntr" target="_blank">a_nhntr</a><br>
        wa: <a href="https://wa.me/6285103080404" target="_blank">0851-0308-0404</a>
      </p>
      <button onclick="goBack()">Kembali</button>
    </section>

    <section id="cv">
      <h2>Curriculum Vitae</h2>
      <div style="text-align:left; margin:20px auto; max-width:600px;">
        <h3>Nama</h3>
        <p>
          Achmad Nuhan Taufiqur Rohim<br>
          Tanggal Lahir: 15 November 2005<br>
          Umur: 20 tahun
        </p>
        <h3>Ringkasan</h3>
        <p>
          Saya seorang mahasiswa Universitas Jember yang sedang menempuh pendidikan S1 Informatika,
          Fakultas Ilmu Komputer. Saya tertarik pada dunia pemrograman dan teknologi.
        </p>
        <h3>Pengalaman</h3>
        <ul>
          <li><b>OSIS SMAN Arjasa Jember</b> – Mengembangkan diri dalam komunikasi dan pengalaman organisasi.</li>
          <li><b>UKM Al Azhar</b> – Pengurus UKM Fakultas Ilmu Komputer, memperoleh pengalaman serta relasi antar mahasiswa.</li>
        </ul>
        <h3>Pendidikan</h3>
        <ul>
          <li>SD Antirogo 1 (2012 – 2018)</li>
          <li>SMP Negeri 3 Jember (2018 – 2021)</li>
          <li>SMA Negeri Arjasa Jember (2021 – 2024)</li>
          <li>S1 Informatika – Universitas Jember (2024 – sekarang)</li>
        </ul>
        <h3>Kontak</h3>
        <p>📞 0851-0308-0404<br>
           📧 a_nhntr<br>
           📍 Jember, Indonesia
        </p>
      </div>
      <button onclick="goBack()">Kembali</button>
      <button onclick="backToAwal()">Kembali ke Awal</button>
    </section>
  </div>

  <div id="imgModal" class="modal">
    <span class="close" id="closeModal">&times;</span>
    <img class="modal-content" id="modalImg">
  </div>

  <footer>
    <p>&copy;2025 My Website</p>
  </footer>

  <script>
    let historyStack = [];

    function showSection(sectionId) {
      let currentSection = getCurrentSection();
      if (currentSection) historyStack.push(currentSection);

      document.getElementById('cover').style.display = 'none';
      document.querySelectorAll('#main-content section').forEach(sec => {
        sec.classList.remove('active');
      });

      const section = document.getElementById(sectionId);
      section.classList.add('active');
      document.getElementById('main-content').style.display = 'flex';
    }

    function hideSections() {
      document.querySelectorAll('#main-content section').forEach(sec => {
        sec.classList.remove('active');
      });
    }

    function showMenu() {
      historyStack = [];
      document.getElementById('cover').style.display = 'none';
      document.getElementById('main-content').style.display = 'flex';
      hideSections();
    }

    function goBack() {
      hideSections();
      if (historyStack.length === 0) {
        document.getElementById('main-content').style.display = 'none';
        document.getElementById('cover').style.display = 'flex';
      } else {
        const prevSection = historyStack.pop();
        document.getElementById(prevSection).classList.add('active');
        document.getElementById('main-content').style.display = 'flex';
      }
    }

    function getCurrentSection() {
      let active = null;
      document.querySelectorAll('#main-content section').forEach(sec => {
        if (sec.classList.contains('active')) active = sec.id;
      });
      return active;
    }

    var modal = document.getElementById("imgModal");
    var modalImg = document.getElementById("modalImg");
    var closeBtn = document.getElementById("closeModal");

    document.querySelectorAll(".galeri-img").forEach(function(img) {
      img.onclick = function() {
        modal.style.display = "block";
        modalImg.src = this.src;
        modalImg.alt = this.alt;
      }
    });

    closeBtn.onclick = function() {
      modal.style.display = "none";
    }

    window.onclick = function(event) {
      if (event.target == modal) {
        modal.style.display = "none";
      }
    }

    function backToAwal() {
      document.getElementById('main-content').style.display = 'none';
      document.getElementById('cover').style.display = 'flex';
      hideSections();
      historyStack = [];
    }
  </script>
</body>
</html>
