/* Resetando Margens e Paddings */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Arial', sans-serif;
  background-color: #f4f7f6; /* Fundo claro para contraste */
  color: #333;
  line-height: 1.6;
}

header {
  background: linear-gradient(135deg, #388E3C, #66BB6A); /* Tons de verde */
  color: white;
  padding: 20px 0;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 1000;
}

header .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 20px;
}

header .logo {
  height: 50px;
  width: auto;
}

header h1 {
  font-size: 2.5rem;
  color: white;
}

nav ul {
  list-style: none;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-size: 1.2rem;
  font-weight: bold;
  transition: color 0.3s;
}

nav ul li a:hover {
  color: #FFD700; /* Cor de destaque ao passar o mouse */
}

section {
  padding: 100px 20px; /* Ajustando o padding para se adequar ao header fixo */
  margin-top: 100px;
}

.phase {
  background-color: #fff;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  padding: 30px;
  margin-bottom: 40px;
  animation: fadeIn 1s ease-in-out;
  background: linear-gradient(135deg, #A5D6A7, #C8E6C9); /* Verde claro com suave transição */
}

.phase-title {
  font-size: 2.5rem;
  color: #388E3C; /* Verde escuro */
  margin-bottom: 20px;
}

.phase p {
  font-size: 1.2rem;
  color: #555;
  margin-bottom: 20px;
}

.phase-image {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 20px;
  animation: fadeIn 1.5s ease-in-out;
}

.phase-image img {
  max-width: 100%;
  height: auto;
  border-radius: 8px;
  object-fit: cover; /* Garante que a imagem ocupe o espaço sem distorcer */
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

footer {
  background-color: #388E3C;
  color: white;
  text-align: center;
  padding: 20px;
}

footer p {
  font-size: 1rem;
}

/* Animação de Fade-In */
@keyframes fadeIn {
  0% { opacity: 0; transform: translateY(50px); }
  100% { opacity: 1; transform: translateY(0); }
}

@media (max-width: 768px) {
  header .container {
    flex-direction: column;
    text-align: center;
  }

  header h1 {
    font-size: 2rem;
  }

  nav ul {
    display: flex;
    flex-direction: column;
    margin-top: 10px;
  }

  nav ul li {
    margin: 10px 0;
  }

  section {
    padding: 50px 10px;
  }

  .phase-title {
    font-size: 2rem;
  }

  .phase p {
    font-size: 1rem;
  }
}
