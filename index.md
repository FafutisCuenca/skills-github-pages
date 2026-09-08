<!doctype html> <html lang="es"> <head> <meta charset="utf-8"> <meta name="viewport" content="width=device-width, initial-scale=1"> <meta name="theme-color" content="#0b5e55">
<meta name="description" content="Cuencada 2026 — reunión familiar en Mérida, Yucatán. Programa, mapas, fotos, videos, canción y mensajes de la familia.">

<title>CUENCADA 2026 · Mérida 13-18 Septiembre</title> <style>
:root{
--green:#0b5e55;
--green2:#087f6d;
--cream:#fffaf0;
--gold:#e7b84b;
--ink:#17332f;
--muted:#60736f;
--white:#fff;
--shadow:0 12px 35px rgba(19,55,49,.12);
}

*{
box-sizing:border-box;
}

html{
scroll-behavior:smooth;
scroll-padding-top:20px;
}

body{
margin:0;
font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;
color:var(--ink);
background:var(--cream);
line-height:1.5;
}

a{
text-decoration:none;
color:inherit;
}

/* =========================================================
HERO
========================================================= */

.hero{
min-height:92vh;
padding:22px 20px 55px;
display:flex;
flex-direction:column;
justify-content:space-between;

background:
linear-gradient(
135deg,
rgba(7,76,69,.96),
rgba(8,127,109,.88)
),
radial-gradient(
circle at 85% 15%,
#e7b84b55,
transparent 30%
);
}

.nav{
max-width:1100px;
width:100%;
margin:auto;

display:flex;
align-items:center;
justify-content:space-between;

color:white;
}

.logo{
display:flex;
align-items:center;
gap:10px;

font-weight:900;
letter-spacing:.12em;
font-size:20px;
}

.logo img{
width:80px;
height:80px;
object-fit:contain;
display:block;
flex-shrink:0;

background:white;
border:3px solid white;
border-radius:10px;
padding:3px;

box-shadow:0 3px 10px rgba(0,0,0,.25);
}

.nav a{
margin-left:18px;
font-size:14px;
font-weight:700;
}

.hero-content{
max-width:1100px;
width:100%;
margin:0 auto;
color:white;
padding:55px 0 15px;
}

.kicker{
font-weight:800;
letter-spacing:.18em;
color:#ffe39a;
font-size:14px;
}

h1{
font-size:clamp(54px,11vw,118px);
line-height:.9;
margin:14px 0 20px;
letter-spacing:-.06em;
}

.hero h2{
font-size:clamp(20px,3vw,34px);
margin:0 0 18px;
}

.hero p{
font-size:18px;
max-width:700px;
}

/* =========================================================
BOTONES
========================================================= */

.actions{
display:flex;
flex-wrap:wrap;
gap:12px;
margin-top:28px;
}

.btn{
display:inline-flex;
align-items:center;
justify-content:center;

padding:14px 20px;
border-radius:999px;

font-weight:800;
border:2px solid transparent;

cursor:pointer;
transition:.25s ease;
}

.btn:hover{
transform:translateY(-2px);
}

.btn.primary{
background:var(--gold);
color:#183b35;
}

.btn.light{
background:white;
color:var(--green);
}

.btn.ghost{
border-color:#ffffff88;
color:white;
}

.btn.whatsapp{
background:#25D366;
color:#fff;
border:2px solid #25D366;
}

.btn.whatsapp:hover{
background:#1fa855;
border-color:#1fa855;
}

/* =========================================================
CUENTA REGRESIVA
========================================================= */

.countdown{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:10px;

max-width:600px;
margin-top:30px;
}

.countdown div{
background:#ffffff16;
border:1px solid #ffffff30;
border-radius:18px;

padding:12px;
text-align:center;
}

.countdown b{
display:block;
font-size:27px;
}

.countdown span{
font-size:11px;
text-transform:uppercase;
opacity:.8;
}

/* =========================================================
SECCIONES
========================================================= */

section{
max-width:1100px;
margin:auto;
padding:75px 20px;
}

.section-title{
font-size:38px;
line-height:1.05;
margin:0 0 12px;
}

.intro{
color:var(--muted);
max-width:720px;
}

/* =========================================================
TARJETAS
========================================================= */

.grid{
display:grid;
grid-template-columns:repeat(3,1fr);
gap:18px;
margin-top:28px;
}

.card{
background:white;
border-radius:24px;
padding:24px;

box-shadow:var(--shadow);
border:1px solid #e7eee9;

transition:.25s ease;
}

.card:hover{
transform:translateY(-3px);
}

.card .icon{
font-size:34px;
}

.card h3{
margin:10px 0 7px;
font-size:21px;
}

.card p{
margin:0;
color:var(--muted);
}

/* =========================================================
PROGRAMA
========================================================= */

.programa-box{
text-align:center;
margin:30px 0 50px;
}

.programa-img{
width:100%;
max-width:900px;

border-radius:24px;
box-shadow:var(--shadow);
border:4px solid white;
}

/* =========================================================
TIMELINE
========================================================= */

.day{
display:grid;
grid-template-columns:110px 1fr;
gap:24px;

background:white;
border-radius:24px;

padding:24px;
margin:14px 0;

box-shadow:var(--shadow);
}

.date{
font-weight:900;
color:var(--green);
font-size:20px;
}

.date span{
display:block;
font-size:13px;
color:var(--muted);
text-transform:uppercase;
}

.timeline h3{
margin:0 0 7px;
}

.timeline p{
margin:0;
color:var(--muted);
}

.tags{
display:flex;
flex-wrap:wrap;
gap:8px;
margin-top:12px;
}

.tag{
background:#eef7f3;
color:var(--green);

padding:7px 10px;
border-radius:999px;

font-size:12px;
font-weight:800;
}

/* =========================================================
CANCION
========================================================= */

.song-box{
background:white;
border-radius:28px;
padding:30px;

box-shadow:var(--shadow);
border:1px solid #e7eee9;

text-align:center;
}

.song-box audio{
width:100%;
max-width:650px;
margin-top:15px;
}

/* =========================================================
FOTOS
========================================================= */

.upload{
background:
linear-gradient(
135deg,
#0b5e55,
#087f6d
);

color:white;

border-radius:30px;
padding:38px;

display:grid;
grid-template-columns:1.3fr .7fr;

gap:25px;
align-items:center;

box-shadow:var(--shadow);
}

.upload h2{
font-size:38px;
margin:0 0 10px;
}

.upload p{
opacity:.9;
}

.upload .btn{
background:var(--gold);
color:#17332f;
}

.gallery{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:12px;
margin-top:25px;
}

.photo{
aspect-ratio:1;
border-radius:18px;

background:
linear-gradient(
135deg,
#dfece7,
#f6df9b
);

display:flex;
align-items:center;
justify-content:center;

font-size:30px;
}

/* =========================================================
MAPA
========================================================= */

.mapgrid{
display:grid;
grid-template-columns:repeat(2,1fr);
gap:18px;
margin-top:25px;
}

.mapcard{
background:white;
padding:24px;
border-radius:22px;

box-shadow:var(--shadow);
}

.mapcard a{
display:inline-block;
margin-top:12px;

color:var(--green);
font-weight:900;
}

/* =========================================================
MENSAJES DE LA FAMILIA
========================================================= */

.messages-grid{
display:grid;
grid-template-columns:repeat(3,1fr);

gap:18px;
margin-top:30px;
}

.message-card{
background:white;

border-radius:24px;
padding:28px;

box-shadow:var(--shadow);
border:1px solid #e7eee9;

position:relative;
}

.message-icon{
font-size:32px;
margin-bottom:12px;
}

.message-card p{
color:var(--muted);

font-size:16px;

margin:0 0 18px;
}

.message-card strong{
color:var(--green);
}

.message-date{
display:block;

margin-top:7px;

font-size:12px;
color:#8a9995;
}

.message-action{
display:flex;
justify-content:center;

margin-top:30px;
}

.message-form{
max-width:650px;
margin:35px auto 0;

background:#eef7f3;

border-radius:26px;
padding:30px;

border:1px solid #dcebe5;
}

.message-form h3{
margin-top:0;

color:var(--green);
font-size:26px;
}

.message-form input,
.message-form textarea{
width:100%;

padding:14px 16px;
margin-bottom:14px;

border:1px solid #d5e3de;
border-radius:14px;

font-family:inherit;
font-size:16px;

background:white;
}

.message-form input:focus,
.message-form textarea:focus{
outline:none;

border-color:var(--green);

box-shadow:0 0 0 3px rgba(11,94,85,.10);
}

.message-form textarea{
resize:vertical;
}

.message-help{
font-size:13px;
color:var(--muted);
margin-top:12px;
}

.delete-message{
background:none;
border:0;

color:#a55;
cursor:pointer;

font-size:12px;

margin-top:12px;
}

/* =========================================================
FOOTER
========================================================= */

footer{
background:#153c36;
color:white;

text-align:center;

padding:40px 20px;
}

.small{
font-size:13px;
opacity:.75;
}

/* =========================================================
MODAL
========================================================= */

.modal{
position:fixed;
inset:0;

background:#0008;

display:none;
align-items:center;
justify-content:center;

padding:20px;

z-index:20;
}

.modal.open{
display:flex;
}

.modalbox{
max-width:650px;

background:white;

border-radius:26px;
padding:28px;

max-height:90vh;
overflow:auto;
}

.close{
float:right;

border:0;
background:#eee;

border-radius:50%;

width:36px;
height:36px;

font-size:20px;

cursor:pointer;
}

/* =========================================================
WHATSAPP FLOTANTE
========================================================= */

.whatsapp-float{
position:fixed;

right:20px;
bottom:20px;

width:65px;
height:65px;

border-radius:50%;

background:#25D366;
color:white;

display:flex;
align-items:center;
justify-content:center;

font-size:30px;

box-shadow:0 12px 30px rgba(0,0,0,.25);

z-index:9999;

transition:.25s ease;
}

.whatsapp-float:hover{
transform:scale(1.08);
}

/* =========================================================
RESPONSIVE
========================================================= */

@media(max-width:760px){

.nav a{
display:none;
}

.grid,
.mapgrid,
.messages-grid{
grid-template-columns:1fr;
}

.gallery{
grid-template-columns:repeat(2,1fr);
}

.day{
grid-template-columns:1fr;
gap:8px;
}

.upload{
grid-template-columns:1fr;
padding:28px;
}

.countdown{
grid-template-columns:repeat(2,1fr);
}

section{
padding:55px 16px;
}

.hero{
padding-left:16px;
padding-right:16px;
}

.message-form{
padding:24px;
}

.logo img{
width:65px;
height:65px;
}

}

</style> </head> <body> <!-- ========================================================= INICIO ========================================================= --> <header class="hero" id="inicio"> <nav class="nav">
<div class="logo">

  <img
    src="images/Logo_Cuencada2026.jpg"
    alt="Logo Cuencada 2026"
  >

  CUENCADA 2026

</div>

<div>

  <a href="#programa">Programa</a>
  <a href="#fotos">Fotos</a>
  <a href="#mensajes">Mensajes</a>
  <a href="#mapa">Mapa</a>
  <a href="#familia">Familia</a>

</div>

</nav> <div class="hero-content">
<div class="kicker">
  MÉRIDA · YUCATÁN · 13—18 SEPTIEMBRE 2026
</div>

<h1>CUENCADA</h1>

<h2>
  Una familia. Una historia. Una celebración.
</h2>

<p>
  Bienvenidos al portal oficial de nuestra reunión familiar.
  Aquí encontrarás el programa, actividades, ubicaciones,
  la canción oficial, los mensajes y el álbum vivo de todos
  los momentos que compartamos en Mérida.
</p>

<div class="actions">

  <a class="btn primary" href="#programa">
    📅 Ver programa
  </a>

  <a class="btn light" id="uploadTop" href="#fotos">
    📸 Subir fotos
  </a>

  <a class="btn ghost" href="#mapa">
    🗺️ Ver lugares
  </a>

  <a
    class="btn whatsapp"
    href="https://chat.whatsapp.com/IvI6oayIIoEJ8Wn7EWQxO0?s=cl&p=i&mlu=0"
    target="_blank"
    rel="noopener"
  >
    💬 Grupo WhatsApp
  </a>

  <a class="btn primary" href="#cancion">
    🎵 Escuchar canción
  </a>

  <a
    class="btn ghost"
    href="https://onedrive.live.com/?redeem=aHR0cHM6Ly8xZHJ2Lm1zL2IvYy9iMGM3ZDU5NTVkNGE4NTgxL0lRQ2NwY0UtdWNFblI2djlNNVFIVlBoRkFaOWNUQlVEY0JDYVh0ZlFERFJQcG9n&cid=B0C7D5955D4A8581&id=B0C7D5955D4A8581%21s3ec1a59cc1b94727abfd33940754f845&parId=B0C7D5955D4A8581%21s77e6d760e3954e818d2a0ba22da1c9e7&o=OneUp"
    target="_blank"
    rel="noopener"
  >
    📖 Ver letra oficial
  </a>

</div>

<div
  class="countdown"
  aria-label="Cuenta regresiva"
>

  <div>
    <b id="days">—</b>
    <span>días</span>
  </div>

  <div>
    <b id="hours">—</b>
    <span>horas</span>
  </div>

  <div>
    <b id="mins">—</b>
    <span>minutos</span>
  </div>

  <div>
    <b id="secs">—</b>
    <span>segundos</span>
  </div>

</div>

</div> </header> <!-- ========================================================= TODO EN UN SOLO LUGAR ========================================================= --> <section> <h2 class="section-title"> Todo en un solo lugar </h2> <p class="intro"> La página está pensada primero para celular: durante la Cuencada podrás consultar rápidamente qué sigue, llegar a cada lugar, compartir fotografías y videos y dejar un mensaje para toda la familia. </p> <div class="grid">
<a class="card" href="#programa">
  <div class="icon">📅</div>
  <h3>Programa</h3>
  <p>
    Consulta cada día, horarios y actividades.
  </p>
</a>

<a class="card" href="#fotos">
  <div class="icon">📸</div>
  <h3>Álbum vivo</h3>
  <p>
    Comparte y consulta las fotos de la familia.
  </p>
</a>

<a class="card" href="#mapa">
  <div class="icon">🗺️</div>
  <h3>¿Dónde estamos?</h3>
  <p>
    Accesos rápidos a hoteles y lugares del recorrido.
  </p>
</a>

<a class="card" href="#familia">
  <div class="icon">❤️</div>
  <h3>Nuestra familia</h3>
  <p>
    Historias, recuerdos y genealogía familiar.
  </p>
</a>

<a class="card" href="#mensajes">
  <div class="icon">💌</div>
  <h3>Mensajes de la familia</h3>
  <p>
    Comparte un recuerdo, una dedicatoria o unas
    palabras para toda la familia.
  </p>
</a>

<a class="card" href="#extras">
  <div class="icon">⭐</div>
  <h3>Actividades extras</h3>
  <p>
    Ideas para aprovechar el tiempo libre en Mérida.
  </p>
</a>

<a class="card" href="#tips">
  <div class="icon">🎒</div>
  <h3>Tips Cuencada</h3>
  <p>
    Qué llevar y recomendaciones prácticas.
  </p>
</a>

<a
  class="card"
  href="https://chat.whatsapp.com/IvI6oayIIoEJ8Wn7EWQxO0?s=cl&p=i&mlu=0"
  target="_blank"
  rel="noopener"
>

  <div class="icon">💬</div>

  <h3>Grupo WhatsApp</h3>

  <p>
    Avisos, coordinación, fotografías, cambios
    de horario y comunicación familiar.
  </p>

</a>

</div> </section> <!-- ========================================================= CANCION ========================================================= --> <section id="cancion"> <div class="song-box">
<h2 class="section-title">
  🎵 Nuestra canción
</h2>

<p class="intro" style="margin:0 auto">
  Escucha la canción oficial de la reunión familiar.
</p>

<audio controls preload="metadata">

  <source
    src="canciones/Cancion_Oficial.mp3"
    type="audio/mpeg"
  >

  Tu navegador no puede reproducir este audio.

</audio>

<div
  class="actions"
  style="justify-content:center"
>

  <a
    class="btn ghost"
    style="color:var(--green);border-color:var(--green)"
    href="#inicio"
  >
    ↑ Volver arriba
  </a>

</div>

</div> </section> <!-- ========================================================= PROGRAMA ========================================================= --> <section id="programa"> <h2 class="section-title"> 📅 Programa Cuencada 2026 </h2> <p class="intro"> Del domingo 13 al viernes 18 de septiembre. </p> <div class="actions" style="justify-content:center;margin-top:20px" >
<a
  class="btn primary"
  href="https://1drv.ms/i/c/b0c7d5955d4a8581/IQBP_0Olz3lRQ67Vc187M744AXk6A96moN_SdRcg6Lw8y50?e=nGbr9g"
  target="_blank"
  rel="noopener"
>
  🔍 Ver programa completo
</a>

</div> <div class="timeline">
<article class="day">

  <div class="date">
    13
    <span>Domingo</span>
  </div>

  <div>

    <h3>
      🌴 Llegada a Mérida
    </h3>

    <p>
      Check-in en Hotel Chariot / Hotel El Conquistador.
      Nota: Transporte de aeropuerto no incluido.
    </p>

    <div class="tags">

      <span class="tag">
        7:30 PM · Lobby Chariot
      </span>

      <span class="tag">
        🚶 Centro de Mérida
      </span>

      <span class="tag">
        📸 Fotos
      </span>

    </div>

  </div>

</article>

<article class="day">

  <div class="date">
    14
    <span>Lunes</span>
  </div>

  <div>

    <h3>
      💦 Cenote & Izamal
    </h3>

    <p>
      <b>$1,000 p/p</b> · 7:40 AM reunión ·
      8:00 AM salida puntual · 9:00 AM Cenote Santa Bárbara ·
      1:00 PM comida yucateca · 3:00 PM Izamal ·
      6:00 PM hotel.
    </p>

    <div class="tags">

      <span class="tag">
        🚌 Transporte incluido
      </span>

      <span class="tag">
        💦 Cenote
      </span>

      <span class="tag">
        💛 Izamal
      </span>

    </div>

  </div>

</article>

<article class="day">

  <div class="date">
    15
    <span>Martes</span>
  </div>

  <div>

    <h3>
      🇲🇽 Uxmal + CUENCADA FEST
    </h3>

    <p>
      Visita matutina a Uxmal. Por la noche:
      cena, música, baile, taquiza, DJ, mariachi
      y celebración mexicana.
    </p>

    <div class="tags">

      <span class="tag">🌴 Uxmal</span>
      <span class="tag">🌮 Taquiza</span>
      <span class="tag">🎺 Mariachi</span>
      <span class="tag">🎉 Grito</span>

    </div>

  </div>

</article>

<article class="day">

  <div class="date">
    16
    <span>Miércoles</span>
  </div>

  <div>

    <h3>
      🌊 Chuburná · Isla Columpios · Progreso
    </h3>

    <p>
      Salida a Chuburná e Isla Columpios.
      Después, Progreso y recorrido por el malecón.
      <b>
        7:00 PM atardecer · 8:00 PM regreso al hotel.
      </b>
    </p>

    <div class="tags">

      <span class="tag">🏝️ Chuburná</span>
      <span class="tag">🛟 Isla Columpios</span>
      <span class="tag">🌅 Puesta del sol</span>

    </div>

  </div>

</article>

<article class="day">

  <div class="date">
    17
    <span>Jueves</span>
  </div>

  <div>

    <h3>
      🛍️ Día libre
    </h3>

    <p>
      Compras, Centro Histórico de Mérida,
      restaurantes y actividades extras.
    </p>

    <div class="tags">

      <span class="tag">🛍️ Compras</span>
      <span class="tag">📍 Centro</span>
      <span class="tag">⭐ Extras</span>

    </div>

  </div>

</article>

<article class="day">

  <div class="date">
    18
    <span>Viernes</span>
  </div>

  <div>

    <h3>
      ❤️ Despedida
    </h3>

    <p>
      Tiempo libre para quienes permanezcan
      más tiempo en Mérida.
    </p>

  </div>

</article>

</div> <div class="actions" style="justify-content:center;margin-top:30px" >
<a class="btn ghost"
   style="color:var(--green);border-color:var(--green)"
   href="#inicio">

  ↑ Volver al inicio

</a>

</div> </section> <!-- ========================================================= FOTOS ========================================================= --> <section id="fotos"> <div class="upload">
<div>

  <div class="kicker">
    ÁLBUM VIVO
  </div>

  <h2>
    📸 ¡Sube tus fotos y videos!
  </h2>

  <p>
    Comparte los momentos de la Cuencada con toda
    la familia. El botón de abajo se enlaza al
    repositorio compartido en OneDrive configurado
    para recibir y ver fotos y videos.
  </p>

  <div class="actions">

    <a
      class="btn"
      id="uploadBtn"
      href="https://1drv.ms/f/c/b0c7d5955d4a8581/IgAC5vDMrmIvTJwWwOjkJJM7AT3DxtBo9OFj8FSXJI_GQY0?e=ASBPLY"
      target="_blank"
      rel="noopener noreferrer"
    >
      📤 SUBIR FOTOS Y VIDEOS
    </a>

    <a
      class="btn ghost"
      id="galleryBtn"
      href="https://1drv.ms/f/c/b0c7d5955d4a8581/IgAC5vDMrmIvTJwWwOjkJJM7AT3DxtBo9OFj8FSXJI_GQY0?e=ASBPLY"
      target="_blank"
      rel="noopener noreferrer"
    >
      👀 VER ÁLBUM
    </a>

  </div>

</div>

<div>

  <div
    class="card"
    style="color:var(--ink)"
  >

    <b>💡 Consejo</b>

    <p style="margin-top:7px">

      Nuestro repositorio tiene carpetas por día
      para que ahí subas tus fotos y videos:
      13, 14, 15, 16, 17 y 18 de septiembre.

    </p>

  </div>

</div>

</div> <div class="actions" style="justify-content:center;margin-top:30px" >
<a
  class="btn ghost"
  style="color:var(--green);border-color:var(--green)"
  href="#inicio"
>
  ↑ Volver al inicio
</a>

</div> </section> <!-- ========================================================= MENSAJES DE LA FAMILIA ========================================================= --> <section id="mensajes"> <h2 class="section-title"> 💌 Mensajes de la familia </h2> <p class="intro">
Este espacio es para compartir palabras,
recuerdos, dedicatorias y buenos deseos
para todos los integrantes de nuestra familia.

</p> <!-- MENSAJES --> <div class="messages-grid" id="messagesContainer" >
<!-- Los mensajes se cargan automáticamente -->

</div> <!-- BOTON --> <div class="message-action" >
<a
  class="btn primary"
  href="#dejar-mensaje"
>
  ✍️ Dejar un mensaje
</a>

</div> <!-- FORMULARIO --> <div id="dejar-mensaje" class="message-form" >
<h3>
  ✍️ Comparte unas palabras
</h3>

<p class="message-help">

  Escribe tu nombre y un mensaje para
  toda la familia.

</p>

<input
  type="text"
  id="nombreMensaje"
  maxlength="60"
  placeholder="Tu nombre"
  autocomplete="name"
>

<textarea
  id="textoMensaje"
  rows="5"
  maxlength="500"
  placeholder="Escribe aquí tu mensaje para la familia..."
></textarea>

<button
  class="btn primary"
  type="button"
  onclick="agregarMensaje()"
>
  💌 Publicar mensaje
</button>

<p class="message-help">
  Máximo 500 caracteres.
</p>

</div> <div class="actions" style="justify-content:center;margin-top:30px" >
<a
  class="btn ghost"
  style="color:var(--green);border-color:var(--green)"
  href="#inicio"
>
  ↑ Volver arriba
</a>

</div> </section> <!-- ========================================================= MAPA ========================================================= --> <section id="mapa"> <h2 class="section-title"> 🗺️ Lugares principales </h2> <div class="mapgrid">
<div class="mapcard">

  <h3>
    🏨 Hotel Chariot Mérida
  </h3>

  <p>
    Uno de los hoteles base de la Cuencada.
  </p>

  <a
    target="_blank"
    rel="noopener"
    href="https://www.hotelchariotmerida.com/"
  >
    Abrir sitio del hotel →
  </a>

</div>

<div class="mapcard">

  <h3>
    🏨 Hotel El Conquistador
  </h3>

  <p>
    Segundo hotel considerado para la familia.
  </p>

  <a
    target="_blank"
    rel="noopener"
    href="https://www.elconquistador.com.mx/"
  >
    Abrir sitio del hotel →
  </a>

</div>

<div class="mapcard">

  <h3>
    💦 Cenote Santa Bárbara
  </h3>

  <p>
    Actividad del lunes 14.
  </p>

  <a
    target="_blank"
    rel="noopener"
    href="https://www.google.com/maps/search/?api=1&query=Cenotes+Santa+Barbara+Homun+Yucatan"
  >
    Abrir en Google Maps →
  </a>

</div>

<div class="mapcard">

  <h3>
    💛 Izamal
  </h3>

  <p>
    Pueblo Mágico amarillo.
  </p>

  <a
    target="_blank"
    rel="noopener"
    href="https://www.google.com/maps/search/?api=1&query=Izamal+Yucatan"
  >
    Abrir en Google Maps →
  </a>

</div>

<div class="mapcard">

  <h3>
    🌴 Uxmal
  </h3>

  <p>
    Visita del martes 15.
  </p>

  <a
    target="_blank"
    rel="noopener"
    href="https://www.google.com/maps/search/?api=1&query=Uxmal+Yucatan"
  >
    Abrir en Google Maps →
  </a>

</div>

<div class="mapcard">

  <h3>
    🌊 Progreso
  </h3>

  <p>
    Malecón y atardecer del miércoles 16.
  </p>

  <a
    target="_blank"
    rel="noopener"
    href="https://www.google.com/maps/search/?api=1&query=Progreso+Yucatan"
  >
    Abrir en Google Maps →
  </a>

</div>

</div> <div class="actions" style="justify-content:center" >
<a
  class="btn ghost"
  style="color:var(--green);border-color:var(--green)"
  href="#inicio"
>
  ↑ Volver arriba
</a>

</div> </section> <!-- ========================================================= FAMILIA ========================================================= --> <section id="familia"> <h2 class="section-title"> ❤️ Nuestra familia </h2> <p class="intro">
La Cuencada también es una oportunidad
para conservar nuestra historia.
Esta sección puede crecer con fotografías
antiguas, árbol genealógico, historias
familiares y recuerdos.

</p> <div class="grid">
<div class="card">

  <div class="icon">🌳</div>

  <h3>
    Árbol familiar
  </h3>

  <p>
    Espacio para integrar generaciones
    y parentescos.
  </p>

</div>

<div class="card">

  <div class="icon">📜</div>

  <h3>
    Nuestra historia
  </h3>

  <p>
    Relatos y documentos que ayuden
    a preservar nuestra memoria.
  </p>

</div>

<div class="card">

  <div class="icon">🖼️</div>

  <h3>
    Fotos antiguas
  </h3>

  <p>
    Un álbum especial para las imágenes
    de nuestros padres y abuelos.
  </p>

</div>

</div> <div class="actions" style="justify-content:center" >
<a
  class="btn ghost"
  style="color:var(--green);border-color:var(--green)"
  href="#inicio"
>
  ↑ Volver arriba
</a>

</div> </section> <!-- ========================================================= EXTRAS ========================================================= --> <section id="extras"> <h2 class="section-title"> ⭐ Actividades extras </h2> <div class="grid">
<div class="card">

  <h3>
    🏛️ Centro Histórico
  </h3>

  <p>
    Plaza Grande, Catedral,
    Paseo de Montejo y calles del centro.
  </p>

</div>

<div class="card">

  <h3>
    🍴 Gastronomía
  </h3>

  <p>
    Descubre cochinita, sopa de lima,
    papadzules y otras especialidades yucatecas.
  </p>

</div>

<div class="card">

  <h3>
    🛍️ Compras
  </h3>

  <p>
    Artesanías, textiles,
    recuerdos y productos locales.
  </p>

</div>

</div> <div class="actions" style="justify-content:center" >
<a
  class="btn ghost"
  style="color:var(--green);border-color:var(--green)"
  href="#inicio"
>
  ↑ Volver arriba
</a>

</div> </section> <!-- ========================================================= TIPS ========================================================= --> <section id="tips"> <h2 class="section-title"> 🎒 Tips Cuencada </h2> <div class="grid">
<div class="card">

  <h3>
    ☀️ Para el calor
  </h3>

  <p>
    Protector solar,
    sombrero/gorra y agua.
  </p>

</div>

<div class="card">

  <h3>
    💦 Para cenotes y playa
  </h3>

  <p>
    Traje de baño
    y una toalla pequeña.
  </p>

</div>

<div class="card">

  <h3>
    👟 Para caminar
  </h3>

  <p>
    Calzado cómodo para Mérida,
    Izamal y las visitas arqueológicas.
  </p>

</div>

</div> <div class="actions" style="justify-content:center" >
<a
  class="btn ghost"
  style="color:var(--green);border-color:var(--green)"
  href="#inicio"
>
  ↑ Volver arriba
</a>

</div> </section> <!-- ========================================================= DESPEDIDA ========================================================= --> <section> <div class="card" style="text-align:center;padding:38px" >
<h2 class="section-title">

  <img
    src="images/Bandera_México.png"
    alt="Bandera de México"
    style="width:30px;height:auto"
  >

  ¡Nos vemos en Mérida!

</h2>

<p
  class="intro"
  style="margin:0 auto"
>

  Que esta Cuencada 2026 se convierta
  en otro capítulo de nuestra historia familiar.

</p>

<div
  class="actions"
  style="justify-content:center"
>

  <a
    class="btn primary"
    href="#inicio"
  >
    ↑ Volver arriba
  </a>

</div>

</div> </section> <!-- ========================================================= FOOTER ========================================================= --> <footer> <strong> CUENCADA 2026 · MÉRIDA, YUCATÁN </strong> <p class="small"> Portal familiar · 13—18 septiembre 2026 </p> <p class="small"> © 2026 Jorge Cuenca Fafutis · Todos los derechos reservados · Página elaborada exclusivamente para la Cuencada 2026 </p> </footer> <!-- ========================================================= MODAL ========================================================= --> <div class="modal" id="modal" > <div class="modalbox">
<button
  class="close"
  onclick="closeModal()"
>
  ×
</button>

<h2>
  📸 Comparte tus recuerdos
</h2>

<p>
  Antes de publicar la página,
  sustituye los enlaces de carga y álbum
  por tus enlaces reales de OneDrive.
</p>

<p>

  <b>1.</b>
  Crea una carpeta
  “CUENCADA 2026 / FOTOS Y VIDEOS”.

  <br><br>

  <b>2.</b>
  Genera una solicitud para cargar archivos
  si tu cuenta de Microsoft lo permite.

  <br><br>

  <b>3.</b>
  Copia el enlace y pégalo
  en la configuración del sitio.

</p>

</div> </div> <!-- ========================================================= JAVASCRIPT ========================================================= --> <script>
/* =========================================================
CONFIGURACIÓN ONEDRIVE
========================================================= */

const ONEDRIVE_UPLOAD_URL =
"https://1drv.ms/f/c/b0c7d5955d4a8581/IgAC5vDMrmIvTJwWwOjkJJM7AT3DxtBo9OFj8FSXJI_GQY0?e=ASBPLY";

const ONEDRIVE_GALLERY_URL =
"https://1drv.ms/f/c/b0c7d5955d4a8581/IgAC5vDMrmIvTJwWwOjkJJM7AT3DxtBo9OFj8FSXJI_GQY0?e=ASBPLY";

function setLink(id,url){

const el=document.getElementById(id);

if(!el)return;

if(
url &&
!url.startsWith("PEGA_AQUI")
){

el.href=url;
el.target="_blank";
el.rel="noopener";

}else{

el.href="#";

el.onclick=(e)=>{

  e.preventDefault();

  document
  .getElementById("modal")
  .classList.add("open");

};

}

}

setLink(
"uploadBtn",
ONEDRIVE_UPLOAD_URL
);

setLink(
"galleryBtn",
ONEDRIVE_GALLERY_URL
);

/* =========================================================
MODAL
========================================================= */

function closeModal(){

document
.getElementById("modal")
.classList.remove("open");

}

document
.getElementById("modal")
.addEventListener(
"click",
e=>{

if(
  e.target.id==="modal"
){

  closeModal();

}

}
);

/* =========================================================
CUENTA REGRESIVA
========================================================= */

const target =
new Date(
"2026-09-13T00:00:00-06:00"
).getTime();

function countdown(){

let d =
target-Date.now();

if(d<0)d=0;

const days =
Math.floor(
d/86400000
);

d%=86400000;

const hours =
Math.floor(
d/3600000
);

d%=3600000;

const mins =
Math.floor(
d/60000
);

const secs =
Math.floor(
(d%60000)/1000
);

document
.getElementById("days")
.textContent=days;

document
.getElementById("hours")
.textContent=hours;

document
.getElementById("mins")
.textContent=mins;

document
.getElementById("secs")
.textContent=secs;

}

countdown();

setInterval(
countdown,
1000
);

/* =========================================================
MENSAJES DE LA FAMILIA
========================================================= */

const STORAGE_KEY =
"cuencada2026_mensajes";

function obtenerMensajes(){

try{

return JSON.parse(
  localStorage.getItem(
    STORAGE_KEY
  )
) || [];

}catch(error){

return [];

}

}

/* =========================================================
ESCAPAR HTML
Evita que alguien introduzca código
dentro del mensaje.
========================================================= */

function escaparHTML(texto){

const div =
document.createElement("div");

div.textContent=texto;

return div.innerHTML;

}

/* =========================================================
MOSTRAR MENSAJES
========================================================= */

function mostrarMensajes(){

const container =
document.getElementById(
"messagesContainer"
);

const mensajes =
obtenerMensajes();

container.innerHTML="";

if(mensajes.length===0){

container.innerHTML=`

  <article class="message-card">

    <div class="message-icon">
      💌
    </div>

    <p>
      Sé el primero en dejar un mensaje
      para la familia.
    </p>

    <strong>
      ¡Escribe unas palabras!
    </strong>

  </article>

`;

return;

}

mensajes
.slice()
.reverse()
.forEach(
(mensaje,index)=>{

  const card =
    document.createElement(
      "article"
    );

  card.className=
    "message-card";

  const fecha =
    new Date(
      mensaje.fecha
    );

  const fechaTexto =
    fecha.toLocaleDateString(
      "es-MX",
      {
        day:"numeric",
        month:"long",
        year:"numeric"
      }
    );

  const horaTexto =
    fecha.toLocaleTimeString(
      "es-MX",
      {
        hour:"2-digit",
        minute:"2-digit"
      }
    );

  card.innerHTML=`

    <div class="message-icon">
      ${mensaje.icono || "❤️"}
    </div>

    <p>
      “${escaparHTML(mensaje.texto)}”
    </p>

    <strong>
      — ${escaparHTML(mensaje.nombre)}
    </strong>

    <span class="message-date">
      ${fechaTexto} · ${horaTexto}
    </span>

    <button
      class="delete-message"
      onclick="eliminarMensaje(${mensajes.length - 1 - index})"
    >
      🗑️ Eliminar
    </button>

  `;

  container.appendChild(
    card
  );

}

);

}

/* =========================================================
AGREGAR MENSAJE
========================================================= */

function agregarMensaje(){

const nombreInput =
document.getElementById(
"nombreMensaje"
);

const textoInput =
document.getElementById(
"textoMensaje"
);

const nombre =
nombreInput.value.trim();

const texto =
textoInput.value.trim();

if(!nombre){

alert(
  "Por favor escribe tu nombre."
);

nombreInput.focus();

return;

}

if(!texto){

alert(
  "Por favor escribe un mensaje."
);

textoInput.focus();

return;

}

if(texto.length>500){

alert(
  "El mensaje no puede superar los 500 caracteres."
);

return;

}

const mensajes =
obtenerMensajes();

const iconos=[
"❤️",
"🥰",
"🌴",
"💌",
"😊",
"🎉",
"🇲🇽"
];

const icono =
iconos[
Math.floor(
Math.random()*iconos.length
)
];

mensajes.push({

nombre:nombre,

texto:texto,

icono:icono,

fecha:new Date().toISOString()

});

localStorage.setItem(
STORAGE_KEY,
JSON.stringify(mensajes)
);

nombreInput.value="";
textoInput.value="";

mostrarMensajes();

document
.getElementById(
"mensajes"
)
.scrollIntoView({
behavior:"smooth"
});

}

/* =========================================================
ELIMINAR MENSAJE
========================================================= */

function eliminarMensaje(indice){

const mensajes =
obtenerMensajes();

if(
!confirm(
"¿Quieres eliminar este mensaje?"
)
){

return;

}

mensajes.splice(
indice,
1
);

localStorage.setItem(
STORAGE_KEY,
JSON.stringify(mensajes)
);

mostrarMensajes();

}

/* =========================================================
INICIALIZAR MENSAJES
========================================================= */

mostrarMensajes();

</script> <!-- ========================================================= WHATSAPP FLOTANTE ========================================================= -->
<a
href="https://chat.whatsapp.com/IvI6oayIIoEJ8Wn7EWQxO0?s=cl&p=i&mlu=0"
class="whatsapp-float"
target="_blank"
rel="noopener"
title="Grupo WhatsApp Cuencada"

💬
</a>

</body> </html>
