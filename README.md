# ingrid-nails-studio
Site profissional da Ingrid Nails 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ingrid Nails Studio</title>
<meta name="description" content="Ingrid Nails Studio - Beleza e delicadeza em cada detalhe. Agende seu horário em Canoas RS.">

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', sans-serif;
}

html { scroll-behavior: smooth; }

body {
  background: #fffafb;
  color: #49383c;
}

header {
  background: #fff;
  padding: 18px 6%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-bottom: 1px solid #f3dce3;
  position: sticky;
  top: 0;
  z-index: 10;
}

.logo {
  color: #b9788c;
  font-size: 20px;
  font-weight: bold;
  letter-spacing: 2px;
}

.logo span {
  display: block;
  color: #bd9a55;
  font-size: 10px;
  letter-spacing: 4px;
  text-align: center;
}

nav a {
  text-decoration: none;
  color: #75535d;
  font-size: 13px;
  margin-left: 12px;
}

.hero {
  padding: 85px 8%;
  text-align: center;
  background: linear-gradient(135deg,#fff0f4,#fff9fa,#f8e8ec);
}

.hero small {
  color: #bd9a55;
  letter-spacing: 4px;
}

.hero h1 {
  font-family: Georgia, serif;
  color: #ad7184;
  font-size: 42px;
  margin: 18px 0;
}

.hero p {
  color: #795f66;
  line-height: 1.8;
  max-width: 450px;
  margin: auto;
}

.btn {
  display: inline-block;
  background: #bd8295;
  color: white;
  padding: 15px 27px;
  border-radius: 30px;
  text-decoration: none;
  margin-top: 25px;
  border: none;
  cursor: pointer;
  font-size: 14px;
}

section {
  padding: 65px 7%;
  text-align: center;
}

.section-title {
  color: #b9788c;
  font-family: Georgia, serif;
  font-size: 30px;
  margin-bottom: 12px;
}

.subtitle {
  color: #927b81;
  font-size: 14px;
  margin-bottom: 35px;
}

.services {
  display: grid;
  grid-template-columns: repeat(auto-fit,minmax(140px,1fr));
  gap: 15px;
}

.service {
  background: white;
  border: 1px solid #f0dce2;
  border-radius: 15px;
  padding: 24px 12px;
  box-shadow: 0 5px 15px #b9788c10;
}

.service .symbol {
  font-size: 28px;
  margin-bottom: 12px;
}

.service h3 {
  color: #a86d81;
  font-size: 15px;
  margin-bottom: 9px;
}

.service p {
  font-size: 12px;
  color: #967f85;
}

.gallery {
  background: #fff1f4;
}

.gallery-grid {
  display: grid;
  grid-template-columns: repeat(2,1fr);
  gap: 12px;
}

.gallery-grid img {
  width: 100%;
  height: 190px;
  object-fit: cover;
  border-radius: 13px;
}

.booking {
  background: white;
}

.booking-box {
  max-width: 500px;
  margin: auto;
  padding: 25px;
  border: 1px solid #f0dce2;
  border-radius: 20px;
  text-align: left;
  box-shadow: 0 5px 25px #b9788c10;
}

label {
  display: block;
  margin: 15px 0 7px;
  color: #986879;
  font-size: 13px;
}

input, select {
  width: 100%;
  padding: 13px;
  border: 1px solid #ead4dc;
  border-radius: 9px;
  background: #fffafb;
  color: #49383c;
  outline: none;
}

input:focus, select:focus {
  border-color: #bd8295;
}

.booking-box button {
  width: 100%;
}

.note {
  font-size: 12px;
  color: #967f85;
  margin-top: 15px;
  line-height: 1.6;
}

.about {
  background: #fff2f5;
}

.about p {
  max-width: 500px;
  margin: auto;
  line-height: 1.8;
  color: #806a70;
}

footer {
  background: #b9788c;
  color: white;
  text-align: center;
  padding: 30px 15px;
  font-size: 13px;
  line-height: 2;
}

@media(max-width: 480px) {
  nav a { font-size: 11px; margin-left: 7px; }
  .hero h1 { font-size: 34px; }
}
</style>
</head>

<body>

<header>
  <div class="logo">
    INGRID
    <span>NAILS STUDIO</span>
  </div>
  <nav>
    <a href="#servicos">Serviços</a>
    <a href="#galeria">Fotos</a>
    <a href="#agendar">Agendar</a>
  </nav>
</header>

<div class="hero">
  <small>BELEZA EM CADA DETALHE</small>
  <h1>Ingrid Nails Studio</h1>
  <p>
    Suas unhas merecem um cuidado especial.
    Realce sua beleza com delicadeza, elegância
    e muito carinho.
  </p>
  <a href="#agendar" class="btn">Agendar meu horário</a>
</div>

<section id="servicos">
  <h2 class="section-title">Nossos serviços</h2>
  <p class="subtitle">Encontre o cuidado perfeito para suas unhas.</p>

  <div class="services">

    <div class="service">
      <div class="symbol">💅</div>
      <h3>Unhas em gel</h3>
      <p>Beleza e acabamento delicado.</p>
    </div>

    <div class="service">
      <div class="symbol">✨</div>
      <h3>Alongamento em gel</h3>
      <p>Alongamento com elegância.</p>
    </div>

    <div class="service">
      <div class="symbol">🌸</div>
      <h3>Banho de gel</h3>
      <p>Mais cuidado para suas unhas.</p>
    </div>

    <div class="service">
      <div class="symbol">💎</div>
      <h3>Fibra de vidro</h3>
      <p>Alongamento com fibra.</p>
    </div>

    <div class="service">
      <div class="symbol">🤍</div>
      <h3>Manutenção</h3>
      <p>Cuidado para manter suas unhas.</p>
    </div>

    <div class="service">
      <div class="symbol">🎀</div>
      <h3>Esmaltação em gel</h3>
      <p>Acabamento bonito e delicado.</p>
    </div>

    <div class="service">
      <div class="symbol">🌷</div>
      <h3>Decoração</h3>
      <p>Detalhes especiais para suas unhas.</p>
    </div>

  </div>

  <p class="subtitle" style="margin-top:25px">
    Valores sob consulta pelo WhatsApp.
  </p>
</section>

<section class="gallery" id="galeria">
  <h2 class="section-title">Galeria de inspirações</h2>
  <p class="subtitle">Algumas inspirações para seu próximo visual.</p>

  <div class="gallery-grid">
    
    <img src="dde45942-6ec5-4de2-aef2-931cf41cf632.jpeg" alt="Inspiração de unhas">
    <img src="https://images.unsplash.com/photo-1632345031435-8727f6897d53?w=600" alt="Inspiração de nail art">
    <img src="https://images.unsplash.com/photo-1610992015732-2449b76344bc?w=600" alt="Inspiração de unhas decoradas">
    <img src="dde45942-6ec5-4de2-aef2-931cf41cf632.jpeg" alt="Inspiração de unhas">
  </div>
  <p class="note">Fotos ilustrativas. Em breve, trabalhos reais da Ingrid.</p>
</section>

<section class="booking" id="agendar">
  <h2 class="section-title">Agende seu horário</h2>
  <p class="subtitle">Será um prazer receber você!</p>

  <div class="booking-box">

    <form id="bookingForm">

      <label>Seu nome</label>
      <input type="text" id="nome" placeholder="Digite seu nome" required>

      <label>Seu WhatsApp</label>
      <input type="tel" id="telefone" placeholder="Seu número" required>

      <label>Serviço desejado</label>
      <select id="servico" required>
        <option value="">Escolha um serviço</option>
        <option>Unhas em gel</option>
        <option>Alongamento em gel</option>
        <option>Banho de gel</option>
        <option>Fibra de vidro</option>
        <option>Manutenção</option>
        <option>Esmaltação em gel</option>
        <option>Decoração</option>
      </select>

      <label>Data desejada</label>
      <input type="date" id="data" required>

      <label>Horário desejado</label>
      <select id="horario" required>
        <option value="">Escolha um horário</option>
        <option>08:00</option>
        <option>09:00</option>
        <option>10:00</option>
        <option>11:00</option>
        <option>12:00</option>
        <option>13:00</option>
        <option>14:00</option>
        <option>15:00</option>
        <option>16:00</option>
      </select>

      <label>Observações (opcional)</label>
      <input type="text" id="observacao" placeholder="Alguma informação adicional">

      <button type="submit" class="btn">
        Solicitar pelo WhatsApp
      </button>

      <p class="note">
        Seu horário será confirmado pela Ingrid
        após o contato pelo WhatsApp.
      </p>

    </form>
  </div>
</section>

<section class="about">
  <h2 class="section-title">Onde estamos</h2>
  <p>
    Atendimento realizado exclusivamente no
    Ingrid Nails Studio, em Canoas – Rio Grande do Sul.
    <br><br>
    Todos os dias, das 08h às 17h.
  </p>
</section>

<footer>
  <strong>INGRID NAILS STUDIO</strong>
  <br>
  Beleza e delicadeza em cada detalhe.
  <br>
  Canoas – RS | Todos os dias, 08h às 17h
  <br>
  © 2026 Ingrid Nails Studio
</footer>

<script>
const hoje = new Date();
const dataLocal = new Date(
  hoje.getTime() - hoje.getTimezoneOffset() * 60000
).toISOString().split("T")[0];

document.getElementById("data").min = dataLocal;

document.getElementById("bookingForm").addEventListener("submit", function(e) {
  e.preventDefault();

  const nome = document.getElementById("nome").value.trim();
  const telefone = document.getElementById("telefone").value.trim();
  const servico = document.getElementById("servico").value;
  const data = document.getElementById("data").value;
  const horario = document.getElementById("horario").value;
  const observacao = document.getElementById("observacao").value.trim();

  if (!nome || !telefone || !servico || !data || !horario) {
    alert("Preencha todos os campos obrigatórios.");
    return;
  }

  const dataEscolhida = new Date(data + "T12:00:00");
  const dataFormatada = dataEscolhida.toLocaleDateString("pt-BR");

  const mensagem =
`Olá, Ingrid! 💗 Gostaria de solicitar um agendamento.

Nome: ${nome}
Meu WhatsApp: ${telefone}
Serviço: ${servico}
Data desejada: ${dataFormatada}
Horário desejado: ${horario}
Observações: ${observacao || "Nenhuma"}

Aguardo a confirmação. Obrigada!`;

  const numero = "5551996450572";

  const url = "https://wa.me/" + numero + "?text=" + encodeURIComponent(mensagem);

  window.open(url, "_blank");
});
</script>

</body>
</html>
