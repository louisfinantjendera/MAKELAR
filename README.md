<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Makelar Indonesia | Jasa Makelar Terpercaya</title>

<meta name="description" content="Jasa makelar terpercaya membantu jual beli properti, kendaraan, dan bisnis dengan aman dan cepat.">
<meta name="keywords" content="makelar indonesia, makelar properti, jual rumah, jasa makelar terpercaya">
<meta name="author" content="Makelar Indonesia">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
html{scroll-behavior:smooth}
*{margin:0;padding:0;box-sizing:border-box;font-family:sans-serif}
body{background:#0f172a;color:white;line-height:1.6}

/* HEADER */
header{
background:rgba(2,6,23,0.9);
backdrop-filter:blur(10px);
position:sticky;top:0;z-index:999;
padding:15px 40px;
display:flex;justify-content:space-between;align-items:center;
}
header h1{color:#22c55e}
nav a{
color:white;margin-left:20px;text-decoration:none;position:relative;
}
nav a::after{
content:'';width:0;height:2px;background:#22c55e;position:absolute;left:0;bottom:-4px;transition:.3s;
}
nav a:hover::after{width:100%}

/* HERO */
.hero{text-align:center;padding:90px 20px;animation:fadeUp 1s}
.hero h2{font-size:42px}
.hero p{color:#cbd5e1}
.btn{
margin-top:20px;display:inline-block;
background:#22c55e;color:black;
padding:14px 30px;border-radius:10px;
text-decoration:none;font-weight:bold;
transition:.3s;
}
.btn:hover{transform:translateY(-3px);box-shadow:0 10px 25px rgba(34,197,94,0.4)}

/* VIDEO */
.video-wrapper{position:relative;padding-bottom:56.25%;height:0;overflow:hidden;margin:40px}
.video-wrapper iframe{
position:absolute;top:0;left:0;width:100%;height:100%;border-radius:14px;border:none
}

/* SERVICES */
.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:25px;padding:50px;
}
.card{
background:#020617;padding:30px;border-radius:16px;text-align:center;
transition:.4s;
}
.card:hover{transform:translateY(-8px) scale(1.03);background:#1e293b}
.card i{font-size:40px;color:#22c55e;margin-bottom:10px}

/* MAP */
.map{text-align:center;margin:40px}
.map iframe{width:100%;height:350px;border:0;border-radius:12px}

/* CONTACT */
.contact{padding:40px;max-width:700px;margin:auto}
.contact input,.contact textarea{
width:100%;padding:14px;margin:10px 0;border:none;border-radius:10px
}
.contact button{
background:#22c55e;border:none;padding:14px;border-radius:10px;font-weight:bold;cursor:pointer
}

/* INFO */
.info{text-align:center;padding:30px}

/* SOCIAL */
.social-icons{
display:flex;justify-content:center;gap:20px;margin:20px 0;flex-wrap:wrap;
}
.social-icons a{
color:white;font-size:28px;transition:.3s
}
.social-icons a:hover{color:#22c55e;transform:scale(1.2)}

/* FLOAT BUTTON */
.whatsapp-float,.call-float{
position:fixed;right:20px;color:white;padding:15px;border-radius:50%;
font-size:24px;z-index:100;
}
.whatsapp-float{bottom:20px;background:#25D366}
.call-float{bottom:85px;background:#22c55e}

/* FOOTER */
footer{text-align:center;padding:20px;background:#020617;color:#94a3b8;margin-top:40px}

/* ANIMATION */
@keyframes fadeUp{
from{opacity:0;transform:translateY(40px)}
to{opacity:1;transform:translateY(0)}
}

/* RESPONSIVE MOBILE */
@media(max-width:768px){

header{flex-direction:column}
nav{margin-top:10px}
nav a{margin:8px;display:inline-block}

.hero h2{font-size:28px}

.services{grid-template-columns:1fr;padding:25px}

.video-wrapper{margin:20px}

.map iframe{height:250px}

}
</style>
</head>
<body>

<header>
<h1>Makelar Indonesia</h1>
<nav>
<a href="#">Beranda</a>
<a href="#layanan">Layanan</a>
<a href="#kontak">Kontak</a>
</nav>
</header>

<section class="hero">
<h2>Jasa Makelar Terpercaya</h2>
<p>Membantu jual beli properti, kendaraan & bisnis dengan aman.</p>
<a href="https://wa.me/6288222605888" class="btn">Hubungi Sekarang</a>
</section>

<div class="video-wrapper">
<iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ"></iframe>
</div>

<section id="layanan" class="services">
<div class="card"><i class="fa-solid fa-house"></i><h3>Jual Beli Rumah</h3></div>
<div class="card"><i class="fa-solid fa-car"></i><h3>Jual Beli Kendaraan</h3></div>
<div class="card"><i class="fa-solid fa-briefcase"></i><h3>Jual Beli Bisnis</h3></div>
<div class="card"><i class="fa-solid fa-handshake"></i><h3>Konsultasi</h3></div>
</section>

<section class="map">
<h2>Lokasi Kantor</h2>
<iframe src="https://maps.google.com/maps?q=Jalan%20Karya%20Gang%20Idi%201%20No%206&output=embed"></iframe>
<br><br>
<a href="https://www.google.com/maps/search/?api=1&query=Jalan+Karya+Gang+Idi+1+No+6" target="_blank" class="btn">Buka Google Maps</a>
<p>📍 Jalan Karya Gang Idi 1 No. 6</p>
</section>

<section id="kontak" class="contact">
<h2>Hubungi Kami</h2>
<form action="mailto:makelar.indonesia@gmail.com" method="post" enctype="text/plain">
<input type="text" name="nama" placeholder="Nama Anda" required>
<input type="email" name="email" placeholder="Email Anda" required>
<textarea name="pesan" rows="5" placeholder="Pesan..." required></textarea>
<button type="submit">Kirim Pesan</button>
</form>
</section>

<div class="info">
<p>📞 +62 882-2260-5888</p>
<p>📧 makelar.indonesia@gmail.com</p>
</div>

<div class="social-icons">
<a href="https://www.youtube.com/@makelarindonesia" target="_blank"><i class="fab fa-youtube"></i></a>
<a href="https://web.facebook.com/makelar" target="_blank"><i class="fab fa-facebook"></i></a>
<a href="https://www.instagram.com/makelar.indonesia" target="_blank"><i class="fab fa-instagram"></i></a>
<a href="https://www.tiktok.com/@makelarindonesia" target="_blank"><i class="fab fa-tiktok"></i></a>
</div>

<footer>
© 2026 Makelar Indonesia
</footer>

<a href="tel:+6288222605888" class="call-float"><i class="fa fa-phone"></i></a>
<a href="https://wa.me/6288222605888" class="whatsapp-float"><i class="fab fa-whatsapp"></i></a>


