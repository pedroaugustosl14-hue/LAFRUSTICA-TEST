[teste12.html](https://github.com/user-attachments/files/24547738/teste12.html)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<title>LAFRUSTICA • Sucos Naturais Premium</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
:root{
  --orange:#ff8a00;
  --orange-dark:#ff6a00;
  --green:#2ecc71;
  --green-dark:#27ae60;
  --bg:#fff8f0;
  --dark:#1e1e1e;
  --gray:#6d6d6d;
  --white:#ffffff;
}

/* RESET */
*{margin:0;padding:0;box-sizing:border-box}

/* BASE */
body{
  font-family:'Segoe UI',Arial,sans-serif;
  background:linear-gradient(180deg,#fff1df,#f1fff6);
  color:var(--dark);
}

/* ANIMAÇÕES */
@keyframes fadeUp{
  from{opacity:0;transform:translateY(40px)}
  to{opacity:1;transform:translateY(0)}
}
@keyframes float{
  0%,100%{transform:translateY(0)}
  50%{transform:translateY(-12px)}
}

/* HEADER */
header{
  position:sticky;
  top:0;
  z-index:10;
  background:rgba(255,255,255,.95);
  backdrop-filter:blur(10px);
  padding:20px 40px;
  display:flex;
  justify-content:space-between;
  align-items:center;
  border-bottom:1px solid #eee;
}
.logo{
  font-size:32px;
  font-weight:900;
  letter-spacing:3px;
  background:linear-gradient(135deg,var(--orange),var(--green));
  -webkit-background-clip:text;
  color:transparent;
}
nav a{
  margin-left:28px;
  text-decoration:none;
  color:var(--gray);
  font-weight:600;
}

/* HERO */
.hero{
  max-width:1200px;
  margin:90px auto;
  padding:0 20px;
  display:grid;
  grid-template-columns:1.1fr .9fr;
  gap:60px;
  align-items:center;
  animation:fadeUp 1s ease;
}
.hero h1{
  font-size:56px;
  line-height:1.1;
  margin-bottom:20px;
}
.hero p{
  font-size:19px;
  color:var(--gray);
  margin-bottom:35px;
}
.btn{
  padding:18px 42px;
  border-radius:22px;
  text-decoration:none;
  font-weight:700;
  font-size:18px;
  color:white;
  background:linear-gradient(135deg,var(--orange),var(--green));
  box-shadow:0 20px 40px rgba(0,0,0,.2);
}
.hero img{
  width:100%;
  border-radius:45px;
  animation:float 5s ease-in-out infinite;
  box-shadow:0 45px 90px rgba(0,0,0,.22);
}

/* SEÇÃO */
.section{
  max-width:1200px;
  margin:130px auto;
  padding:0 20px;
  animation:fadeUp 1s ease;
}
.section h2{
  font-size:42px;
  text-align:center;
}
.section p{
  text-align:center;
  color:var(--gray);
  margin:20px 0 70px;
}

/* PRODUTOS */
.products{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
  gap:40px;
}
.product{
  background:white;
  border-radius:38px;
  padding:26px;
  text-align:center;
  box-shadow:0 35px 80px rgba(0,0,0,.15);
  transition:.3s;
}
.product:hover{transform:translateY(-10px)}
.product img{
  width:100%;
  height:200px;
  object-fit:cover;
  border-radius:28px;
}
.product h3{
  margin:18px 0 6px;
  font-size:21px;
}
.product span{
  font-size:22px;
  font-weight:800;
  color:var(--orange);
}
.product button{
  margin-top:18px;
  width:100%;
  padding:16px;
  border:none;
  border-radius:18px;
  font-size:16px;
  background:linear-gradient(135deg,var(--orange),var(--green));
  color:white;
  font-weight:700;
  cursor:pointer;
}

/* PIX */
.pix{
  background:white;
  max-width:520px;
  margin:140px auto;
  padding:48px;
  border-radius:45px;
  text-align:center;
  box-shadow:0 35px 85px rgba(0,0,0,.18);
}
.pix img{
  margin-top:28px;
  width:220px;
}

/* WHATSAPP */
.whatsapp{
  position:fixed;
  bottom:25px;
  right:25px;
  width:64px;
  height:64px;
  background:#25d366;
  color:white;
  font-size:32px;
  display:flex;
  align-items:center;
  justify-content:center;
  border-radius:50%;
  text-decoration:none;
  box-shadow:0 25px 45px rgba(0,0,0,.3);
  z-index:100;
}

/* FOOTER */
footer{
  background:#111;
  color:#aaa;
  padding:40px;
  text-align:center;
  font-size:14px;
}

/* MOBILE */
@media(max-width:900px){
  .hero{grid-template-columns:1fr;text-align:center}
  header{flex-direction:column;gap:15px}
}
</style>
</head>

<body>

<header>
  <div class="logo">LAFRUSTICA</div>
  <nav>
    <a href="#">Início</a>
    <a href="#laranja">Laranja</a>
    <a href="#limao">Limonada</a>
    <a href="#pix">PIX</a>
  </nav>
</header>

<section class="hero">
  <div>
    <h1>Sucos Naturais<br>Premium</h1>
    <p>Laranja 🍊 e Limonada 🍋 com qualidade profissional.</p>
    <a href="https://wa.me/554299072951" class="btn">Comprar pelo WhatsApp</a>
  </div>
  <img src="c:\Users\Home\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\LocalState\sessions\E84CEEF147590163CA603792365B306581F8250C\transfers\2026-02\WhatsApp Image 2026-01-10 at 15.01.13.jpeg">
</section>

<!-- LARANJA -->
<section class="section" id="laranja">
<h2>Suco de Laranja</h2>
<p>Garrafinhas para todos os momentos</p>
<div class="products">
  <div class="product"><img src="c:\Users\Home\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\LocalState\sessions\E84CEEF147590163CA603792365B306581F8250C\transfers\2026-02\WhatsApp Image 2026-01-10 at 13.40.01.jpeg"><h3>100 ml</h3><span>R$ 3,50</span><button onclick="pedido('Suco de Laranja 100ml')">Comprar</button></div>
  <div class="product"><img src="c:\Users\Home\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\LocalState\sessions\E84CEEF147590163CA603792365B306581F8250C\transfers\2026-02\WhatsApp Image 2026-01-10 at 14.20.42.jpeg"><h3>250 ml</h3><span>R$ 6,00</span><button onclick="pedido('Suco de Laranja 250ml')">Comprar</button></div>
  <div class="product"><img src="c:\Users\Home\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\LocalState\sessions\E84CEEF147590163CA603792365B306581F8250C\transfers\2026-02\WhatsApp Image 2026-01-10 at 14.22.01.jpeg"><h3>500 ml</h3><span>R$ 10,00</span><button onclick="pedido('Suco de Laranja 500ml')">Comprar</button></div>
  <div class="product"><img src="c:\Users\Home\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\LocalState\sessions\E84CEEF147590163CA603792365B306581F8250C\transfers\2026-02\WhatsApp Image 2026-01-10 at 13.36.37.jpeg"><h3>1 Litro</h3><span>R$ 18,00</span><button onclick="pedido('Suco de Laranja 1L')">Comprar</button></div>
</div>
</section>

<!-- LIMONADA -->
<section class="section" id="limao">
<h2>Limonada Natural</h2>
<p>Refrescante e equilibrada</p>
<div class="products">
  <div class="product"><img src="c:\Users\Home\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\LocalState\sessions\E84CEEF147590163CA603792365B306581F8250C\transfers\2026-02\WhatsApp Image 2026-01-10 at 14.28.28.jpeg"><h3>100 ml</h3><span>R$ 3,00</span><button onclick="pedido('Limonada 100ml')">Comprar</button></div>
  <div class="product"><img src="c:\Users\Home\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\LocalState\sessions\E84CEEF147590163CA603792365B306581F8250C\transfers\2026-02\WhatsApp Image 2026-01-10 at 15.14.48.jpeg"><h3>250 ml</h3><span>R$ 5,50</span><button onclick="pedido('Limonada 250ml')">Comprar</button></div>
  <div class="product"><img src="c:\Users\Home\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\LocalState\sessions\E84CEEF147590163CA603792365B306581F8250C\transfers\2026-02\WhatsApp Image 2026-01-10 at 15.17.09.jpeg"><h3>500 ml</h3><span>R$ 9,00</span><button onclick="pedido('Limonada 500ml')">Comprar</button></div>
  <div class="product"><img src="c:\Users\Home\AppData\Local\Packages\5319275A.WhatsAppDesktop_cv1g1gvanyjgm\LocalState\sessions\E84CEEF147590163CA603792365B306581F8250C\transfers\2026-02\WhatsApp Image 2026-01-10 at 15.24.54.jpeg"><h3>1 Litro</h3><span>R$ 16,00</span><button onclick="pedido('Limonada 1L')">Comprar</button></div>
</div>
</section>

<section class="pix" id="pix">
<h2>Pagamento PIX</h2>
<p>Rápido • Seguro • Instantâneo</p>
<strong>Chave PIX:</strong>
<p>pedroaugustosl14@gmail.com</p>
</section>

<footer>
© 2026 LAFRUSTICA • 🍊 Laranja • 🍋 Limão • WhatsApp • PIX
</footer>

<a class="whatsapp" href="https://wa.me/554299072951">💬</a>

<script>
function pedido(produto){
  const msg = "🍹 Pedido LAFRUSTICA 🍹%0AProduto: "+produto;
  window.open("https://wa.me/554299072951?text="+msg);
}
</script>

</body>
</html>
