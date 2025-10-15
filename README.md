<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Laís Silva — Portfólio</title>
  <meta name="description" content="Portfólio de Laís Silva — Estudante de Sistemas de Informação com foco em dados" />
  <link rel="stylesheet" href="assets/css/styles.css" />
</head>
<body>
  <header class="site-header">
    <div class="container">
      <h1>Laís Silva</h1>
      <p class="subtitle">Estudante de Sistemas de Informação • Foco em Dados</p>
      <nav class="nav">
        <a href="#sobre">Sobre</a>
        <a href="#projetos">Projetos</a>
        <a href="#habilidades">Habilidades</a>
        <a href="#contato">Contato</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section id="sobre" class="card">
      <h2>Sobre</h2>
      <p>Olá! Sou Laís Silva — estudante de Sistemas de Informação, com experiência em atividades administrativas que me deram visão estrutural dos processos. Atualmente sou bolsista de extensão no projeto <em>Diário de Ideias</em>, onde aplico meus conhecimentos acadêmicos à prática.</p>
      <p>Tenho grande interesse e dedicação à área de Dados e venho estudando Python, SQL, visualização de dados e demais tópicos relacionados.</p>
      <a class="btn" href="#projetos">Ver meus projetos</a>
    </section>

    <section id="projetos" class="card">
      <h2>Projetos</h2>
      <div class="grid">
        <!-- Projeto: Praticando_C -->
        <article class="proj">
          <img src="assets/imgs/praticando_c.png" alt="Thumb do Praticando_C" />
          <h3>Praticando_C</h3>
          <p>Projetos e desafios em linguagem C para fixação de lógica e manipulação de dados.</p>
          <p class="meta">GitHub: <a href="https://github.com/laisso/Praticando_C" target="_blank">Praticando_C</a></p>
        </article>

        <!-- Projeto: Iniciando_Python -->
        <article class="proj">
          <img src="assets/imgs/iniciando_python.png" alt="Thumb do Iniciando_Python" />
          <h3>Iniciando_Python</h3>
          <p>Notebooks com exemplos práticos de uso de Python para análise de dados e estudos iniciais.</p>
          <p class="meta">GitHub: <a href="https://github.com/laisso/Iniciando_Python" target="_blank">Iniciando_Python</a></p>
        </article>

        <!-- Projeto: BancoDeDados_CopaDoMundo -->
        <article class="proj">
          <img src="assets/imgs/banco_copa.png" alt="Thumb do BancoDeDados_CopaDoMundo" />
          <h3>BancoDeDados_CopaDoMundo</h3>
          <p>Modelagem de banco de dados com PL/pgSQL para simular dados de copas do mundo.</p>
          <p class="meta">GitHub: <a href="https://github.com/laisso/BancoDeDados_CopaDoMundo" target="_blank">BancoDeDados_CopaDoMundo</a></p>
        </article>

        <!-- Você pode incluir mais projetos similares -->
      </div>
    </section>

    <section id="habilidades" class="card">
      <h2>Habilidades</h2>
      <ul class="skills">
        <li>C</li>
        <li>Python</li>
        <li>SQL / PostgreSQL</li>
        <li>HTML & CSS</li>
        <li>JavaScript</li>
        <li>Modelagem de dados</li>
      </ul>
    </section>

    <section id="contato" class="card">
      <h2>Contato</h2>
      <p>Email: <a href="mailto:seu-email@exemplo.com">seu-email@exemplo.com</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/seu-usuario" target="_blank">seu-usuario</a></p>
      <p>GitHub: <a href="https://github.com/laisso" target="_blank">github.com/laisso</a></p>
      <a class="btn-outline" href="assets/CV_Lais_Silva.pdf" target="_blank">Baixar CV (PDF)</a>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="ano"></span> Laís Silva — Transformando ideias em dados</p>
    </div>
  </footer>

  <script>
    document.getElementById('ano').textContent = new Date().getFullYear();
  </script>
</body>
</html>


