<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Carlos Alisson | Portfólio</title>

  <!-- Fonte moderna -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <!-- Ícones -->
  <script src="https://unpkg.com/lucide@latest"></script>

  <style>
    :root {
      --bg: #0b0b0c;
      --card: #111113;
      --text: #f5f5f7;
      --sub: #9a9aa0;
      --accent: #2997ff;
      --border: #1f1f22;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }

    body {
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    .container {
      max-width: 900px;
      margin: 80px auto;
      padding: 20px;
    }

    header {
      margin-bottom: 80px;
    }

    header h1 {
      font-size: 2.5rem;
      font-weight: 700;
      letter-spacing: -1px;
    }

    header p {
      color: var(--sub);
      margin-top: 10px;
    }

    section {
      margin-bottom: 60px;
    }

    h2 {
      font-size: 0.85rem;
      letter-spacing: 2px;
      text-transform: uppercase;
      color: var(--sub);
      margin-bottom: 20px;
    }

    .card {
      background: var(--card);
      padding: 25px;
      border-radius: 14px;
      border: 1px solid var(--border);
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-4px);
      border-color: #2c2c30;
    }

    p {
      font-size: 0.95rem;
    }

    .perfil p {
      margin-bottom: 8px;
    }

    /* Skills */
    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .skill {
      display: flex;
      align-items: center;
      gap: 8px;
      padding: 10px 14px;
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 10px;
      font-size: 0.85rem;
      transition: 0.2s;
    }

    .skill:hover {
      background: var(--accent);
      color: white;
    }

    .skill i {
      width: 16px;
      height: 16px;
    }

    a {
      color: var(--accent);
      text-decoration: none;
    }

    a:hover {
      opacity: 0.8;
    }

    footer {
      margin-top: 60px;
      text-align: center;
      font-size: 0.75rem;
      color: var(--sub);
    }

  </style>
</head>

<body>

  <div class="container">

    <header>
      <h1>Carlos Alisson</h1>
      <p>Desenvolvedor em formação • Web & Programação</p>
    </header>

    <!-- Informações -->
    <section>
      <h2>Informações</h2>
      <div class="card perfil">
        <p><strong>Nome:</strong> Carlos Alisson</p>
        <p><strong>Curso:</strong> Informática</p>
        <p><strong>Campus:</strong> IFRN Pau dos Ferros</p>
      </div>
    </section>

    <!-- Sobre -->
    <section>
      <h2>Sobre</h2>
      <div class="card">
        <p>
          Estudante de Informática apaixonado por tecnologia e desenvolvimento web.
          Estou construindo minhas habilidades com foco em criar interfaces modernas,
          rápidas e funcionais.
        </p>
      </div>
    </section>

    <!-- Habilidades -->
    <section>
      <h2>Habilidades</h2>
      <div class="skills">

        <div class="skill">
          <i data-lucide="code"></i> HTML
        </div>

        <div class="skill">
          <i data-lucide="palette"></i> CSS
        </div>

        <div class="skill">
          <i data-lucide="cpu"></i> JavaScript
        </div>

        <div class="skill">
          <i data-lucide="terminal"></i> Python
        </div>

      </div>
    </section>

    <!-- Projetos -->
    <section>
      <h2>Projetos</h2>
      <div class="card">
        <p>
          📚 <a href="https://github.com/Carlos-615/minha-livraria-online" target="_blank">
            Livraria Online
          </a>
        </p>

        <p style="margin-top:10px; color:var(--sub); font-size:0.85rem;">
          Projeto de e-commerce simples desenvolvido para prática de front-end.
        </p>
      </div>
    </section>

    <!-- Contato -->
    <section>
      <h2>Contato</h2>
      <div class="card">
        <p><strong>GitHub:</strong> <a href="https://github.com/Carlos-615" target="_blank">Carlos-615</a></p>
        <p><strong>Email:</strong> torrescarlospedro@gmail.com</p>
        <p><strong>Acadêmico:</strong> carlos.torres@escolar.ifrn.edu.br</p>
      </div>
    </section>

    <footer>
      © 2026 • Portfólio pessoal
    </footer>

  </div>

  <script>
    lucide.createIcons();
  </script>

</body>
</html>
