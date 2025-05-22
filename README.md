<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="author" content="Agrinho 2025">
  <title>Ciclo do Alimento</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="container">
      <h1>O Ciclo do Alimento</h1>
      <nav>
        <ul>
          <li><a href="#plantio">Plantio</a></li>
          <li><a href="#cultivo">Cultivo</a></li>
          <li><a href="#colheita">Colheita</a></li>
          <li><a href="#transporte">Transporte</a></li>
          <li><a href="#consumo">Consumo</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section id="plantio" class="phase">
    <h2>1. Plantio</h2>
    <p>O ciclo do alimento começa com o plantio, onde as sementes são colocadas no solo para começar a crescer.</p>
  </section>

  <section id="cultivo" class="phase">
    <h2>2. Cultivo</h2>
    <p>O cultivo envolve o cuidado da planta, com irrigação, controle de pragas e nutrição do solo.</p>
  </section>

  <section id="colheita" class="phase">
    <h2>3. Colheita</h2>
    <p>Após crescer, a planta é colhida e os alimentos são preparados para o transporte.</p>
  </section>

  <section id="transporte" class="phase">
    <h2>4. Transporte</h2>
    <p>Os alimentos são transportados para mercados, feiras e indústrias de processamento.</p>
  </section>

  <section id="consumo" class="phase">
    <h2>5. Consumo</h2>
    <p>Finalmente, o alimento chega à nossa mesa, pronto para ser consumido e nutrir o corpo.</p>
  </section>

  <footer>
    <p>&copy; 2025 Ciclo do Alimento - Agrinho</p>
  </footer>
</body>
</html>

/* Estilo Global */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f9;
  color: #333;
  line-height: 1.6;
}

header {
  background-color: #4CAF50;
  color: white;
  padding: 20px 0;
}

header .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 20px;
}

header h1 {
  font-size: 2.5rem;
}

nav ul {
  list-style-type: none;
}

nav ul li {
  display: inline;
  margin: 0 10px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-size: 1.1rem;
  transition: color 0.3s;
}

nav ul li a:hover {
  color: #FFD700;
}

/* Estilo das Fases */
.phase {
  padding: 50px 20px;
  margin: 20px 0;
  background-color: #fff;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.phase h2 {
  font-size: 2rem;
  color: #4CAF50;
  margin-bottom: 10px;
}

.phase p {
  font-size: 1.1rem;
  color: #555;
}

/* Estilo do Footer */
footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 20px;
  margin-top: 40px;
}

footer p {
  font-size: 1rem;
}

/* Responsividade */
@media (max-width: 768px) {
  header .container {
    flex-direction: column;
    align-items: flex-start;
  }

  nav ul {
    display: flex;
    flex-direction: column;
    margin-top: 10px;
  }

  nav ul li {
    margin: 5px 0;
  }
}
