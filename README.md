<!DOCTYPE html><html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ODAN | Pazarlama ve Medya</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #ffffff;
      border-bottom: 1px solid #ddd;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 30px;
      margin: 15px 0;
    }
    nav a {
      text-decoration: none;
      color: #0073e6;
      font-weight: bold;
    }
    .lang-switch {
      position: absolute;
      top: 20px;
      right: 20px;
    }
    main {
      max-width: 1000px;
      margin: 30px auto;
      padding: 20px;
      background-color: #fff;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #f1f1f1;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <div class="lang-switch">
    <button onclick="setLang('tr')">TR</button>
    <button onclick="setLang('en')">EN</button>
  </div>  <header>
    <h1 id="title">ODAN Medya</h1>
    <p id="slogan">Pazarlama Dünyasının Nabzı</p>
    <nav>
      <a href="#trend">Trend Ürünler</a>
      <a href="#firsat">Fırsatlar</a>
      <a href="#hakkimizda">Hakkımızda</a>
    </nav>
  </header>  <main>
    <section id="trend">
      <h2 id="trend-title">Trend Ürünler</h2>
      <p id="trend-text">Trendyol, Alibaba ve Amazon'da en çok satan ürünlerin analizini ve pazarlama stratejilerini paylaşıyoruz.</p>
    </section>
    <section id="firsat">
      <h2 id="firsat-title">Satış Fırsatları</h2>
      <p id="firsat-text">Dropshipping ve e-ticaret yapanlara özel fırsatlar, ipuçları ve tedarikçi tavsiyeleri.</p>
    </section>
    <section id="hakkimizda">
      <h2 id="about-title">Hakkımızda</h2>
      <p id="about-text">ODAN, girişimcilere pazarlama odaklı içerikler sunan dijital medya platformudur.</p>
    </section>
  </main>  <footer>
    <p>&copy; 2025 ODAN Media | Tüm hakları saklıdır.</p>
  </footer>  <script>
    const translations = {
      tr: {
        title: "ODAN Medya",
        slogan: "Pazarlama Dünyasının Nabzı",
        trend_title: "Trend Ürünler",
        trend_text: "Trendyol, Alibaba ve Amazon'da en çok satan ürünlerin analizini ve pazarlama stratejilerini paylaşıyoruz.",
        firsat_title: "Satış Fırsatları",
        firsat_text: "Dropshipping ve e-ticaret yapanlara özel fırsatlar, ipuçları ve tedarikçi tavsiyeleri.",
        about_title: "Hakkımızda",
        about_text: "ODAN, girişimcilere pazarlama odaklı içerikler sunan dijital medya platformudur."
      },
      en: {
        title: "ODAN Media",
        slogan: "Pulse of the Marketing World",
        trend_title: "Trending Products",
        trend_text: "We share analysis and marketing strategies of top-selling products on Trendyol, Alibaba, and Amazon.",
        firsat_title: "Sales Opportunities",
        firsat_text: "Tips, deals and supplier suggestions for dropshipping and e-commerce businesses.",
        about_title: "About Us",
        about_text: "ODAN is a digital media platform providing marketing-focused content for entrepreneurs."
      }
    };

    function setLang(lang) {
      document.getElementById("title").innerText = translations[lang].title;
      document.getElementById("slogan").innerText = translations[lang].slogan;
      document.getElementById("trend-title").innerText = translations[lang].trend_title;
      document.getElementById("trend-text").innerText = translations[lang].trend_text;
      document.getElementById("firsat-title").innerText = translations[lang].firsat_title;
      document.getElementById("firsat-text").innerText = translations[lang].firsat_text;
      document.getElementById("about-title").innerText = translations[lang].about_title;
      document.getElementById("about-text").innerText = translations[lang].about_text;
    }
  </script></body>
</html># ODAN