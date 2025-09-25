<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Curriculum Vitae — Achmad Nuhan T</title>
  <style>
    :root{
      --bg:#f7f8fb;
      --card:#ffffff;
      --muted:#6b7280;
      --accent:#0f6fff;
      --glass: rgba(15,111,255,0.06);
      --radius:12px;
      --maxw:980px;
      --gap:18px;
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
      color:#0f172a;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      background: linear-gradient(180deg,var(--bg),#eef2ff 60%);
      display: block; 
      padding:28px;
    }

    .container{
      width:100%;
      max-width:var(--maxw);
      background:var(--card);
      border-radius:16px;
      box-shadow:0 10px 30px rgba(12,20,40,0.08);
      display:grid;
      grid-template-columns:320px 1fr;
      gap:var(--gap);
      overflow:hidden;
    }

    .sidebar{
      background:linear-gradient(180deg, rgba(255,255,255,0.8), rgba(255,255,255,0.6));
      padding:26px;
      display:flex;
      flex-direction:column;
      gap:18px;
    }
    .photo{
      width:100%;
      display:flex;
      justify-content:center;
    }
    .photo img{
      width:160px;
      height:160px;
      object-fit:cover;
      border-radius:50%;
      border:6px solid var(--glass);
      box-shadow:0 8px 20px rgba(15,111,255,0.08);
    }
    h1 {
      font-size: 22px;
      margin: 0;
      text-transform: uppercase;
      background: #111;
      color: #fff;
      padding: 6px 12px;
      border-radius: 8px;
      display: inline-block;
    }
    .title{font-weight:600;color:var(--accent);font-size:14px;margin-top:6px}

    .contact, .skills, .lang{
      background:transparent;
      padding:8px 0;
      font-size:14px;
    }
    .contact-item{display:flex;gap:10px;align-items:center;margin-bottom:10px;color:var(--muted)}
    .contact-item svg{width:18px;height:18px;opacity:0.9}

    .section-title {
      font-size: 13px;
      color: #fff;
      background: #111;
      text-transform: uppercase;
      letter-spacing: 0.08em;
      margin-bottom: 8px;
      padding: 4px 10px;
      border-radius: 6px;
      display: inline-block;
    }

    .skill-list{display:flex;flex-wrap:wrap;gap:8px}
    .skill{background:var(--glass);padding:6px 10px;border-radius:999px;font-size:13px}

    /* MAIN */
    .main{padding:26px}
    .summary{margin-bottom:16px;color:#111827}
    .block{margin-bottom:18px}

    .role{display:flex;justify-content:space-between;align-items:flex-start}
    .role h3{margin:0;font-size:15px}
    .role .meta{font-size:13px;color:var(--muted)}

    .list{margin-top:8px;padding-left:18px}
    .list li{margin-bottom:8px}

    .edu-grid{display:grid;grid-template-columns:1fr 1fr;gap:12px}

    footer{font-size:12px;color:var(--muted);padding:12px 26px;border-top:1px solid #f1f5f9}

    /* responsive */
    @media (max-width:900px){
      .container{grid-template-columns:1fr;}
      .photo img{width:120px;height:120px}
    }

    /* print */
    @media print{
      body{background:white}
      .container{box-shadow:none}
      a[href]:after{content:""}
    }
  </style>
</head>
<body>
  <div class="container" role="document">
    <aside class="sidebar" aria-label="Sidebar">
      <div class="photo">
        <img src="nuhan 3.jpg" alt="Foto profil">
      </div>
      <div>
        <h1>Achmad Nuhan T</h1>
        <div class="title">Saya Mahasiswa Universitas Jember</div>
      </div>

      <div class="birth">
        <div class="section-title">TEMPAT,TANGGAL LAHIR</div>
        <div class="contact-item">
          <span>Jember, 15 November 2005</span>
        </div>
      </div>

      <!-- Kontak -->
      <div class="contact">
        <div class="section-title">KONTAK</div>
        <div class="contact-item">
          <span>📱</span>
          <span>+62 851 0308 0404</span>
        </div>
        <div class="contact-item">
          <span>✉️</span>
          <span>a_nhntr</span>
        </div>
        <div class="contact-item">
          <span>📍</span>
          <span>Jember, Indonesia</span>
        </div>
      </div>

      <div class="skills">
        <div class="section-title">HOBBY</div>
        <div class="skill-list">
          <div class="skill">Futsal</div>
          <div class="skill">Pencak Silat</div>
          <div class="skill">Teknologi</div>
          <div class="skill">Sound Sytem</div>
          <div class="skill">Mancing</div>
        </div>
      </div>

      <div class="lang">
        <div class="section-title">BAHASA</div>
        <div class="skill-list">
          <div class="skill">Bahasa Indonesia</div>
          <div class="skill">Jawa</div>
          <div class="skill">Madura</div>
        </div>
      </div>

    </aside>

    <main class="main" aria-label="Konten utama">
      <section class="summary block">
        <div class="section-title">RINGKASAN</div>
        <p class="summary"> Saya seorang mahasiswa Uneversitas jember yang sedang menempuh pendidikan S1 di bidang Informatika, Fakultas Ilmu Komputer. Kenapa saya memilih jurusan tersebut karena saya sangat tertarik dengan dunia pemrograman dan teknologi sekarang ini.
      mungkin itu saja sekit profil saya Terima kasih.</p>
      </section>

      <section class="experience block">
        <div class="section-title">PENGALAMAN </div>

        <article class="role">
          <div>
            <h3>Berorganisasi</h3>
            <div class="meta">OSIS SMAN ARJASA JEMBER</div>
            <ul class="list">
              <li>Mengembangkan diri dalam berkomunikasi,dan juga memperbanyak pengalaman.</li>
            </ul>
          </div>
          <div style="text-align:right;color:var(--muted);font-size:13px"></div>
        </article>

        <article class="role" style="margin-top:14px">
          <div>
            <h3>UKM AL AZHAR</h3>
            <div class="meta">Pengurus ukm di Fakultas ilmu komputer.</div>
            <ul class="list">
              <li>Dengan mengikuti kegitan tersebut saya banyak pengalaman dan relasi tentang ukm, maupun perkulihan terhadap angkatan saya maupin kakak tingkat saya.</li>
            </ul>
          </div>
          <div style="text-align:right;color:var(--muted);font-size:13px"></div>
        </article>
      </section>

      <section class="education block">
        <div class="section-title">Pendidikan</div>
        <div class="edu-grid">
          <div>
            <strong>SD ANTIROGO 1</strong>
            <div class="meta">2012 - 2018</div>
          </div>
          <div>
            <strong>SMP NEGERI 3 JEMBER</strong>
            <div class="meta">2018 — 2021</div>
          </div>
          <div>
            <strong>SMA NEGERI ARJASA JEMBER</strong>
            <div class="meta">2021 — 2024</div> 
        </div>
      </section>

      <section class="extras block">
        <div class="section-title">Sertifikat & Kegiatan</div>
        <ul class="list">
          <li>OSIS SMAN — 2022-2023</li>
        </ul>
      </section>
    </main>

    <footer>
      <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
        <div>&copy; <span id="year"></span> Achmad Nuhan T</div>
        <div style="font-size:13px;color:var(--muted)">CV saya buat dengan identitas saya.</div>
      </div>
    </footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
