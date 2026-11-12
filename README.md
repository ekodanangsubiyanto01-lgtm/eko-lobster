<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Craftoria | Jasa Desain Canva & Edit Video CapCut untuk Pelajar dan UMKM</title>
<meta name="description" content="Desain Canva dan edit video CapCut dengan harga ramah untuk pelajar dan UMKM. Proses cepat, revisi wajar, pesan lewat WhatsApp.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,500;12..96,800&family=Figtree:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  --ink:#16193a;
  --paper:#f6f5ff;
  --blue:#3a3df5;
  --sun:#ffd23f;
  --coral:#ff6b5e;
  --mint:#2fd1a5;
  --white:#fff;
  --display:"Bricolage Grotesque","Trebuchet MS",system-ui,sans-serif;
  --body:"Figtree",system-ui,-apple-system,"Segoe UI",sans-serif;
}
*{box-sizing:border-box;margin:0}
html{scroll-behavior:smooth}
body{font-family:var(--body);color:var(--ink);background:var(--paper);line-height:1.6;font-size:17px}
a{color:inherit}
:focus-visible{outline:3px solid var(--blue);outline-offset:3px;border-radius:6px}
.wrap{width:min(1120px,92%);margin-inline:auto}
h1,h2,h3{font-family:var(--display);line-height:1.05;letter-spacing:-.02em}

/* nav */
header{padding:20px 0}
.nav{display:flex;align-items:center;justify-content:space-between;gap:16px}
.logo{font-family:var(--display);font-weight:800;font-size:1.5rem;text-decoration:none;display:flex;align-items:center;gap:10px}
.logo i{width:28px;height:28px;background:var(--blue);border-radius:9px 9px 9px 2px;display:inline-block;position:relative}
.logo i::after{content:"";position:absolute;inset:8px;background:var(--sun);border-radius:50%}
.nav a.link{text-decoration:none;font-weight:500;margin-left:22px}
.nav a.link:hover{text-decoration:underline;text-underline-offset:5px}

/* buttons */
.btn{display:inline-flex;align-items:center;justify-content:center;gap:10px;font:600 1rem var(--body);padding:15px 26px;border-radius:999px;border:2px solid var(--ink);background:var(--sun);color:var(--ink);text-decoration:none;cursor:pointer;box-shadow:4px 4px 0 var(--ink);transition:transform .15s,box-shadow .15s}
.btn:hover{transform:translate(2px,2px);box-shadow:2px 2px 0 var(--ink)}
.btn.alt{background:var(--white)}

/* hero */
.hero{display:grid;grid-template-columns:1.05fr 1fr;gap:56px;align-items:center;padding:48px 0 88px}
.hero h1{font-size:clamp(2.6rem,6vw,4.6rem);font-weight:800}
.hero h1 span{display:block;color:var(--blue)}
.hero p.lead{font-size:1.2rem;max-width:34ch;margin:24px 0 32px}
.hero .actions{display:flex;flex-wrap:wrap;gap:14px}
.hero small{display:block;margin-top:18px;color:#4a4d72}

/* studio mock */
.studio{background:var(--white);border:2px solid var(--ink);border-radius:20px;box-shadow:8px 8px 0 var(--ink);overflow:hidden}
.bar{display:flex;gap:7px;padding:12px 16px;border-bottom:2px solid var(--ink);background:var(--sun)}
.bar b{width:11px;height:11px;border-radius:50%;border:2px solid var(--ink);background:var(--white)}
.stage{display:grid;grid-template-columns:1fr 112px;gap:16px;padding:18px;background:repeating-linear-gradient(0deg,#fff 0 23px,#eef0ff 23px 24px)}
.poster{aspect-ratio:1;background:var(--blue);border-radius:12px;padding:20px;color:#fff;display:flex;flex-direction:column;justify-content:space-between;position:relative;overflow:hidden}
.poster::before{content:"";position:absolute;right:-30px;top:-30px;width:130px;height:130px;border-radius:50%;background:var(--coral)}
.poster::after{content:"";position:absolute;right:26px;bottom:20px;width:64px;height:64px;background:var(--sun);transform:rotate(14deg);border-radius:12px}
.poster em{font:normal 600 .8rem var(--body);background:#fff;color:var(--ink);padding:3px 10px;border-radius:99px;align-self:flex-start;position:relative;z-index:1}
.poster strong{font:800 1.9rem/1 var(--display);position:relative;z-index:1;max-width:8ch}
.phone{aspect-ratio:9/16;background:var(--ink);border-radius:16px;padding:6px;position:relative}
.phone div{height:100%;border-radius:11px;background:linear-gradient(160deg,var(--mint),var(--blue));display:flex;align-items:flex-end;padding:8px}
.phone span{background:#fff;color:var(--ink);font:600 .68rem var(--body);padding:2px 8px;border-radius:6px}
.timeline{padding:0 18px 18px;position:relative}
.track{height:20px;margin-top:8px;border-radius:6px;background:#eef0ff;position:relative}
.track i{position:absolute;top:0;bottom:0;border-radius:6px;border:2px solid var(--ink)}
.t1 .a{left:0;width:34%;background:var(--coral)}.t1 .b{left:36%;width:26%;background:var(--sun)}.t1 .c{left:64%;width:36%;background:var(--mint)}
.t2 .a{left:10%;width:48%;background:var(--blue)}.t2 .b{left:62%;width:22%;background:var(--coral)}
.t3 .a{left:0;width:78%;background:#c9cbff}
.playhead{position:absolute;top:-2px;bottom:12px;left:18px;width:2px;background:var(--ink);animation:play 3.2s .4s cubic-bezier(.5,0,.3,1) forwards}
.playhead::before{content:"";position:absolute;top:0;left:-5px;border:6px solid transparent;border-top-color:var(--ink)}
@keyframes play{to{left:calc(18px + (100% - 36px) * .62)}}

/* sections */
section{padding:88px 0}
.head{max-width:620px;margin-bottom:44px}
.head h2{font-size:clamp(2rem,4.4vw,3.1rem)}
.head p{margin-top:14px;color:#4a4d72}

/* services */
.services{background:var(--white);border-block:2px solid var(--ink)}
.svc{display:grid;grid-template-columns:1.2fr 1fr;gap:24px}
.panel{border:2px solid var(--ink);border-radius:20px;padding:32px;position:relative;overflow:hidden}
.panel.design{background:var(--sun)}
.panel.video{background:var(--mint)}
.panel h3{font-size:2rem;margin-bottom:10px}
.panel p{max-width:38ch;margin-bottom:18px}
.panel ul{list-style:none;padding:0;display:flex;flex-wrap:wrap;gap:8px}
.panel li{background:var(--white);border:2px solid var(--ink);border-radius:99px;padding:4px 14px;font-weight:500;font-size:.95rem}

/* why */
.why{display:grid;grid-template-columns:repeat(2,1fr);gap:0;border:2px solid var(--ink);border-radius:20px;overflow:hidden;background:var(--white)}
.why div{padding:30px 32px}
.why div:nth-child(odd){border-right:2px solid var(--ink)}
.why div:nth-child(-n+2){border-bottom:2px solid var(--ink)}
.why h3{font-size:1.45rem;margin-bottom:6px}
.why p{color:#4a4d72}
.why .tag{display:inline-block;font-weight:600;font-size:.85rem;padding:2px 12px;border-radius:99px;border:2px solid var(--ink);margin-bottom:12px}

/* order */
.order{background:var(--blue);color:#fff;border-top:2px solid var(--ink)}
.order .grid{display:grid;grid-template-columns:1fr 1fr;gap:56px;align-items:center}
.order h2{font-size:clamp(2rem,4.4vw,3.1rem)}
.order p{margin-top:16px;max-width:36ch;opacity:.92}
form{background:var(--white);color:var(--ink);border:2px solid var(--ink);border-radius:20px;padding:28px;box-shadow:8px 8px 0 var(--ink);display:grid;gap:16px}
label{display:grid;gap:6px;font-weight:600;font-size:.95rem}
select,input,textarea{font:400 1rem var(--body);padding:12px 14px;border:2px solid var(--ink);border-radius:12px;background:var(--paper);color:var(--ink);width:100%}
textarea{min-height:92px;resize:vertical}
form .btn{width:100%}

footer{padding:32px 0;border-top:2px solid var(--ink);background:var(--paper);font-size:.95rem}
footer .wrap{display:flex;flex-wrap:wrap;justify-content:space-between;gap:12px}

.float{position:fixed;right:18px;bottom:18px;z-index:10;box-shadow:4px 4px 0 var(--ink)}

@media (max-width:860px){
  .hero,.svc,.order .grid{grid-template-columns:1fr}
  .hero{gap:40px;padding-bottom:64px}
  .why{grid-template-columns:1fr}
  .why div:nth-child(odd){border-right:0}
  .why div:not(:last-child){border-bottom:2px solid var(--ink)}
  .nav a.link{display:none}
  section{padding:64px 0}
}
@media (prefers-reduced-motion:reduce){
  html{scroll-behavior:auto}
  .playhead{animation:none;left:calc(18px + (100% - 36px) * .62)}
  .btn{transition:none}
}
</style>
</head>
<body>

<header>
  <div class="wrap nav">
    <a class="logo" href="#"><i></i>Craftoria</a>
    <nav>
      <a class="link" href="#layanan">Layanan</a>
      <a class="link" href="#keunggulan">Keunggulan</a>
      <a class="btn alt" style="margin-left:22px;padding:10px 20px" href="#pesan">Pesan</a>
    </nav>
  </div>
</header>

<main>
<div class="wrap hero">
  <div>
    <h1>Desain keren &amp; video kece, <span>harga ramah di kantong.</span></h1>
    <p class="lead">Craftoria bantu pelajar dan UMKM tampil profesional lewat desain Canva dan edit video CapCut, tanpa ribet dan tanpa bikin dompet menjerit.</p>
    <div class="actions">
      <a class="btn" href="https://wa.me/6281532900269?text=Halo%20Craftoria%2C%20saya%20ingin%20pesan%20jasa%20desain%2Fedit%20video" target="_blank" rel="noopener">Pesan via WhatsApp</a>
      <a class="btn alt" href="#layanan">Lihat layanan</a>
    </div>
    <small>Konsultasi gratis. Ceritakan idemu, kami bantu wujudkan.</small>
  </div>

  <div class="studio" aria-hidden="true">
    <div class="bar"><b></b><b></b><b></b></div>
    <div class="stage">
      <div class="poster"><em>Promo Pekan Ini</em><strong>Grand Opening</strong></div>
      <div class="phone"><div><span>Reels 0:15</span></div></div>
    </div>
    <div class="timeline">
      <div class="track t1"><i class="a"></i><i class="b"></i><i class="c"></i></div>
      <div class="track t2"><i class="a"></i><i class="b"></i></div>
      <div class="track t3"><i class="a"></i></div>
      <div class="playhead"></div>
    </div>
  </div>
</div>

<section class="services" id="layanan">
  <div class="wrap">
    <div class="head">
      <h2>Dua layanan, satu tujuan: tampilanmu makin meyakinkan.</h2>
      <p>Dari tugas sekolah sampai konten jualan, semuanya dikerjakan rapi dan sesuai karaktermu.</p>
    </div>
    <div class="svc">
      <div class="panel design">
        <h3>Desain Canva</h3>
        <p>Poster, feed Instagram, logo sederhana, menu, brosur, sampai presentasi tugas. Menarik dilihat dan mudah dibaca.</p>
        <ul><li>Poster</li><li>Feed IG</li><li>Logo</li><li>Menu &amp; brosur</li><li>Presentasi</li></ul>
      </div>
      <div class="panel video">
        <h3>Edit Video CapCut</h3>
        <p>Reels, TikTok, YouTube Shorts, video promosi, sampai video tugas, lengkap dengan teks, musik, dan transisi.</p>
        <ul><li>Reels</li><li>TikTok</li><li>Shorts</li><li>Video promo</li></ul>
      </div>
    </div>
  </div>
</section>

<section id="keunggulan">
  <div class="wrap">
    <div class="head">
      <h2>Kenapa pilih Craftoria?</h2>
      <p>Kami bikin proses pesan desain semudah chat dengan teman.</p>
    </div>
    <div class="why">
      <div><span class="tag" style="background:var(--sun)">Cepat</span><h3>Proses cepat</h3><p>Deadline mepet? Pesananmu dikerjakan sigap tanpa mengorbankan kualitas.</p></div>
      <div><span class="tag" style="background:var(--mint)">Adil</span><h3>Revisi wajar</h3><p>Hasil belum pas? Kami sesuaikan sampai kamu puas, dengan jatah revisi yang adil untuk kedua pihak.</p></div>
      <div><span class="tag" style="background:var(--coral)">Hemat</span><h3>Harga pelajar &amp; UMKM</h3><p>Kualitas profesional dengan tarif bersahabat, cocok untuk tugas, usaha kecil, dan konten harian.</p></div>
      <div><span class="tag" style="background:#c9cbff">Santai</span><h3>Komunikasi jelas</h3><p>Ceritakan kebutuhanmu lewat chat. Tanpa bahasa ribet, tanpa proses berbelit.</p></div>
    </div>
  </div>
</section>

<section class="order" id="pesan">
  <div class="wrap grid">
    <div>
      <h2>Punya ide tapi bingung mulai dari mana?</h2>
      <p>Isi form singkat ini, lalu pesanmu terkirim langsung ke WhatsApp Craftoria.</p>
    </div>
    <form id="orderForm">
      <label>Nama
        <input id="nama" type="text" placeholder="Nama kamu" required>
      </label>
      <label>Layanan
        <select id="layanan-pilih">
          <option>Desain Canva</option>
          <option>Edit Video CapCut</option>
          <option>Desain dan Edit Video</option>
        </select>
      </label>
      <label>Kebutuhan singkat
        <textarea id="catatan" placeholder="Contoh: poster promo kue ulang tahun, ukuran feed IG"></textarea>
      </label>
      <label>Deadline (opsional)
        <input id="deadline" type="text" placeholder="Contoh: Jumat sore">
      </label>
      <button class="btn" type="submit">Kirim pesan via WhatsApp</button>
    </form>
  </div>
</section>
</main>

<footer>
  <div class="wrap">
    <span>&copy; <span id="year">2026</span> Craftoria. Desain &amp; video untuk pelajar dan UMKM.</span>
    <a href="https://wa.me/6281532900269" target="_blank" rel="noopener">WhatsApp 0815-3290-0269</a>
  </div>
</footer>

<a class="btn float" href="https://wa.me/6281532900269?text=Halo%20Craftoria%2C%20saya%20ingin%20tanya%20layanan" target="_blank" rel="noopener">Chat WhatsApp</a>

<script>
document.getElementById('year').textContent = new Date().getFullYear();
document.getElementById('orderForm').addEventListener('submit', function (e) {
  e.preventDefault();
  var nama = document.getElementById('nama').value.trim();
  var layanan = document.getElementById('layanan-pilih').value;
  var catatan = document.getElementById('catatan').value.trim();
  var deadline = document.getElementById('deadline').value.trim();
  var teks = 'Halo Craftoria, saya ' + nama + '. Saya ingin pesan: ' + layanan + '.';
  if (catatan) teks += '\nKebutuhan: ' + catatan;
  if (deadline) teks += '\nDeadline: ' + deadline;
  window.open('https://wa.me/6281532900269?text=' + encodeURIComponent(teks), '_blank', 'noopener');
});
</script>
</body>
</html>
