<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Mônica Encante | Marketing Digital</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #fff;
      color: #333;
    }
    header {
      background-color: #f06292;
      padding: 20px 40px;
      color: white;
      position: sticky;
      top: 0;
      z-index: 1000;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      font-size: 1.8em;
    }
    nav a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 60px 40px;
    }
    .hero {
      background: #ffe4ec;
      text-align: center;
    }
    .hero h2 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 1.2em;
    }
    .about, .services, .testimonials, .contact {
      max-width: 1000px;
      margin: auto;
    }
    .services ul {
      list-style: none;
      padding: 0;
    }
    .services li {
      margin-bottom: 15px;
    }
    .testimonial {
      background: #fce4ec;
      padding: 20px;
      border-radius: 10px;
      margin-bottom: 20px;
    }
    .contact form {
      display: flex;
      flex-direction: column;
    }
    .contact input, .contact textarea {
      margin-bottom: 15px;
      padding: 10px;
      font-size: 1em;
    }
    .contact button {
      background-color: #f06292;
      color: white;
      padding: 12px;
      border: none;
      cursor: pointer;
      font-size: 1em;
      border-radius: 5px;
    }
    footer {
      background-color: #333;
      color: white;
      padding: 20px;
      text-align: center;
    }
    footer a {
      color: #f06292;
      margin: 0 10px;
      text-decoration: none;
    }

    @media (max-width: 600px) {
      header {
        flex-direction: column;
        text-align: center;
      }
      nav a {
        margin: 10px 5px;
        display: inline-block;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Mônica Encante</h1>
    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#servicos">Serviços</a>
      <a href="#depoimentos">Depoimentos</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Marketing Digital com Encanto</h2>
    <p>Aprenda a vender mais com estratégias digitais que realmente funcionam.</p>
  </section>

  <section class="about" id="sobre">
    <h2>Sobre Mim</h2>
    <p>Sou <strong>Mônica Lima</strong>, fundadora da <strong>Encante Consultoria</strong> e especialista em marketing digital com mais de 10 anos de experiência. Ensino empreendedores e profissionais a usarem a internet para vender mais, alcançar mais clientes e fortalecer suas marcas.</p>
  </section>

  <section class="services" id="servicos">
    <h2>O que eu ensino</h2>
    <ul>
      <li>✅ Estratégias de vendas para Instagram e WhatsApp</li>
      <li>✅ Posicionamento de marca e criação de autoridade</li>
      <li>✅ Tráfego pago e orgânico de forma prática</li>
      <li>✅ Como criar conteúdo que gera resultados reais</li>
    </ul>
  </section>

  <section class="testimonials" id="depoimentos">
    <h2>Depoimentos</h2>
    <div class="testimonial">
      <p>“Com a mentoria da Mônica, eu finalmente entendi como usar o Instagram para atrair clientes. Vendi mais em 2 semanas do que nos últimos 2 meses.”</p>
      <strong>— Juliana Nunes, artesã</strong>
    </div>
    <div class="testimonial">
      <p>“A didática da Mônica é incrível. Ela simplifica o marketing e mostra o que realmente dá resultado.”</p>
      <strong>— Ricardo Silva, lojista</strong>
    </div>
  </section>

  <section class="contact" id="contato">
    <h2>Fale Comigo</h2>
    <p>Quer agendar uma mentoria ou parceria? Preencha o formulário abaixo:</p>
    <form>
      <input type="text" placeholder="Seu nome" required>
      <input type="email" placeholder="Seu e-mail" required>
      <textarea rows="4" placeholder="Sua mensagem"></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <footer>
    <p>Siga nas redes sociais:</p>
    <a href="https://instagram.com/monicaencante" target="_blank">@monicaencante</a>
    <a href="https://linkedin.com/in/monicaencante" target="_blank">LinkedIn</a>
    <a href="mailto:monica@encante.com.br">E-mail</a>
    <p>&copy; 2025 Mônica Encante. Todos os direitos reservados.</p>
  </footer>

</body>
</html>