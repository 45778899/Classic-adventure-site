# <!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Classic Adventure - Aluguer de Carros Clássicos</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
      color: #333;
    }
    header {
      background-color: #003d2d;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header img {
      height: 60px;
    }
    nav {
      background-color: #026e4f;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      padding: 15px;
      display: inline-block;
    }
    nav a:hover {
      background-color: #014f38;
    }
    .hero {
      background-image: url('banner-ds20.jpg');
      background-size: cover;
      background-position: center;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.7);
    }
    .hero h1 {
      font-size: 3rem;
    }
    .content {
      padding: 40px;
      max-width: 900px;
      margin: 0 auto;
    }
    .services, .contact {
      margin-top: 40px;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      margin-top: 20px;
    }
    .gallery img {
      width: 100%;
      max-width: 280px;
      height: auto;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }
    footer {
      background-color: #003d2d;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 60px;
      font-size: 0.9rem;
    }
    footer a {
      color: #b0f0e5;
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo_classic_adventure_small.png" alt="Logo Classic Adventure" />
    <h2>Classic Adventure</h2>
    <p>Aluguer de carros clássicos para eventos</p>
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#servicos">Serviços</a>
    <a href="#galeria">Galeria</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section class="hero">
    <h1>Viva o charme de outros tempos</h1>
  </section>

  <div class="content">
    <section id="sobre">
      <h2>Sobre Nós</h2>
      <p>A Classic Adventure proporciona experiências únicas ao volante de verdadeiras lendas automóveis. Alugamos carros clássicos para ocasiões especiais, eventos, casamentos, produções fotográficas e muito mais.</p>
    </section>

    <section class="services" id="servicos">
      <h2>Serviços</h2>
      <ul>
        <li>Aluguer de Citroën DS 20 de 1970</li>
        <li>Aluguer com ou sem condutor</li>
        <li>Eventos corporativos e privados</li>
        <li>Casamentos, aniversários e ocasiões especiais</li>
        <li>Produções de cinema, TV e fotografia</li>
      </ul>
    </section>

    <section id="galeria">
      <h2>Galeria</h2>
      <p>Veja algumas fotos do nosso Citroën DS 20 preto em ação durante eventos e casamentos:</p>
      <div class="gallery">
        <img src="ds20-casamento1.jpg" alt="Citroën DS 20 em casamento" />
        <img src="ds20-evento1.jpg" alt="Citroën DS 20 em evento" />
        <img src="ds20-casamento2.jpg" alt="Casamento com DS 20" />
        <img src="ds20-evento2.jpg" alt="Evento com DS 20 preto" />
      </div>
    </section>

    <section class="contact" id="contacto">
      <h2>Contacto</h2>
      <p><strong>Simão Santos</strong></p>
      <p>Tel: <a href="tel:+351915481181">915 481 181</a></p>
      <p>Email: <a href="mailto:classic.advtr@gmail.com">classic.advtr@gmail.com</a></p>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 Classic Adventure. Todos os direitos reservados.</p>
    <p>Código licenciado sob a <a href="https://www.apache.org/licenses/LICENSE-2.0" target="_blank">Licença Apache 2.0</a>.</p>
  </footer>
</body>
</html>
Classic-adventure-site
