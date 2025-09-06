<!doctype html>
<html lang="uz">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Portfolio — Doston Abdug'apporov</title>
  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --accent:#06b6d4; --muted:#94a3b8;
      --text:#e6eef6; --radius:12px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family:Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background:linear-gradient(180deg,#071127 0%, #07172a 100%);
      color:var(--text);
      line-height:1.5;
      -webkit-font-smoothing:antialiased;
      padding:32px;
    }
    .container{
      max-width:900px;
      margin:0 auto;
    }
    header{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:16px;
      margin-bottom:28px;
    }
    h1{
      margin:0;
      font-size:28px;
      letter-spacing:0.5px;
    }
    nav a{
      color:var(--muted);
      text-decoration:none;
      margin-left:12px;
      font-size:14px;
    }
    .card{
      background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
      border-radius:var(--radius);
      padding:20px;
      box-shadow:0 6px 18px rgba(2,6,23,0.6);
      margin-bottom:18px;
      border:1px solid rgba(255,255,255,0.03);
    }
    .two-col{display:grid;grid-template-columns:1fr 320px;gap:18px}
    @media (max-width:800px){ .two-col{grid-template-columns:1fr} nav{display:none} }
    .badge{display:inline-block;padding:6px 10px;border-radius:999px;background:rgba(6,182,212,0.12);color:var(--accent);font-weight:600;font-size:13px}
    ul.projects{list-style:none;padding:0;margin:0}
    ul.projects li{padding:10px 0;border-bottom:1px dashed rgba(255,255,255,0.03)}
    a.project-link{color:var(--accent);text-decoration:none;font-weight:600}
    .meta{color:var(--muted);font-size:14px}
    footer{margin-top:28px;color:var(--muted);font-size:13px;text-align:center}
    .contact{display:flex;flex-direction:column;gap:6px;font-size:14px}
    .small{font-size:13px;color:var(--muted)}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>Portfolio</h1>
      <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="card" id="about">
      <div class="two-col">
        <div>
          <span class="badge">Doston Abdug'apporov</span>
          <h2 style="margin-top:12px;margin-bottom:6px">Backend developer — Django & DRF</h2>
          <p class="meta">Samarkand · Backend dasturchi · Cybersecurity bo'yicha o'rganmoqda</p>

          <h3 style="margin-top:18px;margin-bottom:8px">About me</h3>
          <p>
            Assalomu alaykum! Men Doston Abdug'apporov — 2001-12-10 tug'ilgan, Tashkent State University of Economics (Samarkand branch)da
            Food and Resources Economics bo'yicha bakalavr (2020–2024). Hozir backend va kiberxavfsizlikni o'rganmoqdaman.
            Asosiy texnologiyalar: <strong>Python, Django, Django REST Framework, Docker, PostgreSQL</strong>.
            JWT va BasicAuthentication bilan ishlaganim bor. Backend stajyorlikka tayyorman.
          </p>

          <p class="small" style="margin-top:10px">
            Agar shu profilni qisqartirilgan ko‘rinishda xohlasangiz, README.md uchun ham tayyor variant yozib beraman.
          </p>
        </div>

        <aside>
          <div class="card" style="padding:14px">
            <strong>Quick info</strong>
            <div style="height:8px"></div>
            <div class="meta">Manzil: Samarkand</div>
            <div class="meta">Email: <a href="mailto:dostonabdugafforov909@gmail.com" style="color:var(--accent)">dostonabdugafforov909@gmail.com</a></div>
            <div class="meta">Phone: <span class="small">+998 90 877 6041</span></div>
            <div style="height:8px"></div>
            <div class="meta">Ta'lim: Tashkent State Univ. of Economics (Samarkand)</div>
            <div class="meta">Cert: Backend programming (2024-05-25)</div>
          </div>
        </aside>
      </div>
    </section>

    <section class="card" id="projects">
      <h3 style="margin-top:0">Projects</h3>
      <p class="small">Quyida loyiha nomlari va GitHub (yoki boshqa) URL manzillari keltirilgan. <br>
      Oʻzingizning GitHub username bilan <code>&lt;your-username&gt;</code> joyini almashtiring.</p>

      <ul class="projects" style="margin-top:12px">
        <li>
          <div>
            <a class="project-link" href="https://github.com/&lt;your-username&gt;/stadium-booking-backend" target="_blank" rel="noopener">stadium-booking-backend</a>
            <div class="meta">Django + DRF — stadion bron qilish tizimi (bronlash logikasi, BasicAuthentication)</div>
          </div>
        </li>

        <li>
          <div>
            <a class="project-link" href="https://github.com/&lt;your-username&gt;/usb-monitoring-script" target="_blank" rel="noopener">usb-monitoring-script</a>
            <div class="meta">Python script — USB serial tekshiruvi va unauthorized qurilmalarni aniqlash</div>
          </div>
        </li>

        <li>
          <div>
            <a class="project-link" href="https://github.com/&lt;your-username&gt;/erp-inventory-system" target="_blank" rel="noopener">erp-inventory-system</a>
            <div class="meta">Inventory (Income / Outcome / Warehouse) modellarini o‘z ichiga olgan ERP backend</div>
          </div>
        </li>

        <li>
          <div>
            <a class="project-link" href="https://github.com/&lt;your-username&gt;/order-pdf-with-qrcodes" target="_blank" rel="noopener">order-pdf-with-qrcodes</a>
            <div class="meta">Orderlarni PDFga aylantirish (xhtml2pdf) va har bir order uchun QR code</div>
          </div>
        </li>

        <li>
          <div>
            <a class="project-link" href="https://github.com/&lt;your-username&gt;/product-images-bulk-upload" target="_blank" rel="noopener">product-images-bulk-upload</a>
            <div class="meta">ProductImage va ProductBanner modellarini bulk_create orqali saqlash</div>
          </div>
        </li>
      </ul>

      <p class="small" style="margin-top:12px">
        Agar sizda aniq repolar mavjud bo‘lsa — shu linklarni menga yuboring, men ularni shu sahifaga to‘liq tavsif va screenshot bilan joylab beraman.
      </p>
    </section>

    <section class="card" id="contact">
      <h3 style="margin-top:0">Contact</h3>
      <div class="contact">
        <div>Email: <a href="mailto:dostonabdugafforov909@gmail.com" style="color:var(--accent)">dostonabdugafforov909@gmail.com</a></div>
        <div>Tel: +998 90 877 6041</div>
        <div class="small">LinkedIn / GitHub: https://github.com/&lt;your-username&gt;</div>
      </div>
    </section>

    <footer>
      © <span id="year"></span> Doston Abdug'apporov — All rights reserved.
    </footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
