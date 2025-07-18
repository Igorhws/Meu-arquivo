<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Esporte Fale</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #f4f4f4;
      color: #333;
    }

    header {
      background: #0077b6;
      color: #fff;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      margin: 0;
    }

    nav a {
      color: #fff;
      margin-left: 20px;
      text-decoration: none;
      font-weight: bold;
    }

    .banner {
      background: url('https://source.unsplash.com/1200x400/?sports') center/cover no-repeat;
      height: 400px;
      display: flex;
      justify-content: center;
      align-items: center;
      color: #fff;
      text-shadow: 2px 2px 4px #000;
    }

    .banner h2 {
      font-size: 48px;
      background: rgba(0,0,0,0.5);
      padding: 20px;
      border-radius: 10px;
    }

    .content {
      max-width: 1200px;
      margin: 40px auto;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      padding: 0 20px;
    }

    .card {
      background: #fff;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .card-content {
      padding: 20px;
    }

    .card-content h3 {
      margin: 0 0 10px;
      font-size: 20px;
      color: #0077b6;
    }

    .card-content p {
      margin: 0;
    }

    footer {
      background: #0077b6;
      color: #fff;
      text-align: center;
      padding: 20px;
    }

    footer a {
      color: #fff;
      margin: 0 10px;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Esporte Fale</h1>
    <nav>
      <a href="#">Início</a>
      <a href="#">Notícias</a>
      <a href="#">Partidas</a>
      <a href="#">Contato</a>
    </nav>
  </header>

  <section class="banner">
    <h2>As últimas notícias do mundo esportivo!</h2>
  </section>

  <section class="content">
    <div class="card">
      <img src="https://source.unsplash.com/400x200/?soccer" alt="Futebol">
      <div class="card-content">
        <h3>Campeonato Brasileiro</h3>
        <p>Times disputam rodada emocionante neste final de semana.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://source.unsplash.com/400x200/?basketball" alt="Basquete">
      <div class="card-content">
        <h3>NBA Playoffs</h3>
        <p>Veja quem avança para a grande final da NBA 2025.</p>
      </div>
    </div>

    <div class="card">
      <img src="https://source.unsplash.com/400x200/?olympics" alt="Olimpíadas">
      <div class="card-content">
        <h3>Olimpíadas 2025</h3>
        <p>Delegação brasileira conquista mais medalhas em Tóquio.</p>
      </div>
    </div>
  </section>

  <footer>
    <p>© 2025 Esporte Fale | Siga-nos: 
      <a href="#">Facebook</a> |
      <a href="#">Instagram</a> |
      <a href="#">Twitter</a>
    </p>
  </footer>
</body>
</html>
