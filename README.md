
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>🌸 Minha Loja Feminina</title>

<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #fff0f6;
}

header {
  background: #ff4fa0;
  color: white;
  padding: 20px;
  text-align: center;
}

.produtos {
  display: flex;
  justify-content: center;
  gap: 20px;
  padding: 20px;
  flex-wrap: wrap;
}

.card {
  background: white;
  padding: 15px;
  border-radius: 15px;
  width: 220px;
  text-align: center;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.card h3 {
  margin-bottom: 10px;
}

.preco {
  font-weight: bold;
  color: #ff4fa0;
  margin-bottom: 10px;
}

button {
  background: #ff4fa0;
  color: white;
  border: none;
  padding: 10px;
  border-radius: 10px;
  cursor: pointer;
  width: 100%;
  font-weight: bold;
}

button:hover {
  background: #e0438c;
}

footer {
  text-align: center;
  padding: 15px;
  font-size: 14px;
  color: #555;
}
</style>
</head>

<body>

<header>
<h1>🌸 Minha Loja Feminina</h1>
<p>As melhores tendências para o seu estilo</p>
</header>

<div class="produtos">

<div class="card">
<h3>Vestido Floral</h3>
<p class="preco">R$ 129,90</p>
<button onclick="comprar('Vestido Floral - R$129,90')">Comprar</button>
</div>

<div class="card">
<h3>Vestido Midi Elegante</h3>
<p class="preco">R$ 159,90</p>
<button onclick="comprar('Vestido Midi Elegante - R$159,90')">Comprar</button>
</div>

<div class="card">
<h3>Conjunto Casual Chic</h3>
<p class="preco">R$ 199,90</p>
<button onclick="comprar('Conjunto Casual Chic - R$199,90')">Comprar</button>
</div>

<div class="card">
<h3>Blusa Seda Branca</h3>
<p class="preco">R$ 89,90</p>
<button onclick="comprar('Blusa Seda Branca - R$89,90')">Comprar</button>
</div>

</div>

<footer>
© 2026 Minha Loja Feminina 💖
</footer>

<script>
function comprar(produto){
  let numero = "5511999999999"; // 👈 COLOQUE SEU WHATSAPP AQUI
  let mensagem = "Olá, quero comprar: " + produto;
  let url = "https://wa.me/" + numero + "?text=" + encodeURIComponent(mensagem);
  window.open(url, "_blank");
}
</script>

</body>
</html>
