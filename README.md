# viagens--landing-page
O App interage com o usuário na cidade Santorini. Descrevendo sua fantástica  cidade da Grécia.
o projeto foi feito em HTML e CSS, possui banner, menu de navegação, três seções (MinhaViagem, NosEncontre e Conselhos), links internos, botão para voltar ao topo, efeito :hover e boas práticas de acessibilidade.

<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Minha Viagem - Santorini</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:Arial, Helvetica, sans-serif;
    line-height:1.6;
    background:#f5f5f5;
    color:#333;
}

nav{
    background:#005b96;
    padding:15px;
    position:sticky;
    top:0;
}

nav ul{
    display:flex;
    justify-content:center;
    list-style:none;
}

nav li{
    margin:0 20px;
}

nav a{
    color:white;
    text-decoration:none;
    font-weight:bold;
    padding:8px 15px;
    border-radius:5px;
    transition:.3s;
}

nav a:hover{
    background:white;
    color:#005b96;
}

.banner{
    height:500px;
    background-image:url("https://images.unsplash.com/photo-1507525428034-b723cf961d3e");
    background-size:cover;
    background-position:center;
    display:flex;
    justify-content:center;
    align-items:center;
}

.banner h1{
    background:rgba(0,0,0,.5);
    color:white;
    padding:20px;
    border-radius:10px;
    font-size:45px;
}

section{
    padding:50px 20px;
    max-width:1000px;
    margin:auto;
}

section h2{
    color:#005b96;
    margin-bottom:15px;
}

section p{
    margin-bottom:15px;
}

img{
    width:100%;
    border-radius:10px;
    margin-top:15px;
}

.voltar{
    display:inline-block;
    margin-top:20px;
    background:#005b96;
    color:white;
    padding:10px 20px;
    text-decoration:none;
    border-radius:5px;
    transition:.3s;
}

.voltar:hover{
    background:#003f6b;
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:20px;
}
</style>

</head>
<body>

<header id="home">

<nav>
<ul>
<li><a href="#home">Início</a></li>
<li><a href="#minhaviagem">Minha Viagem</a></li>
<li><a href="#nosencontre">Nos Encontre</a></li>
<li><a href="#conselhos">Conselhos</a></li>
</ul>
</nav>

</header>

<main>

<div class="banner">
<h1>Descubra Santorini, Grécia</h1>
</div>

<section id="minhaviagem">

<h2>Minha Viagem</h2>

<p>
Santorini é um dos destinos mais bonitos do mundo. Suas casas brancas,
igrejas de cúpulas azuis e o pôr do sol encantam turistas de todos os países.
</p>

<p>
Durante a viagem você poderá conhecer praias vulcânicas, restaurantes
tradicionais e paisagens inesquecíveis.
</p>

<img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb"
alt="Vista da ilha de Santorini">

<a class="voltar" href="#home">Voltar ao topo</a>

</section>

<section id="nosencontre">

<h2>Nos Encontre</h2>

<p>
Nossa agência está pronta para ajudar você a planejar sua viagem dos sonhos.
</p>

<p>
📍 Rua das Viagens, 100 - Centro<br>
📞 (11) 99999-9999<br>
📧 contato@minhaviagem.com
</p>

<img src="https://images.unsplash.com/photo-1526772662000-3f88f10405ff"
alt="Agência de viagens">

<a class="voltar" href="#home">Voltar ao topo</a>

</section>

<section id="conselhos">

<h2>Conselhos</h2>

<ul>
<li>Leve protetor solar.</li>
<li>Use roupas leves.</li>
<li>Tenha sempre água durante os passeios.</li>
<li>Experimente a culinária local.</li>
<li>Leve câmera ou celular para registrar as paisagens.</li>
</ul>

<img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee"
alt="Paisagem turística">

<a class="voltar" href="#home">Voltar ao topo</a>

</section>

</main>

<footer>

<p>© 2026 - Agência Minha Viagem | Projeto de Certificação</p>

</footer>

</body>
</html>
