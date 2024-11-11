# AdvogadosCompanhia
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Companhia Advogados</title>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
  <link href="https://fonts.googleapis.com/css2?family=Petit+Formal+Script&amp;display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
 
</head>

<body>

  <!-- Div com imagem de fundo, cobrindo header até os cards -->
  <div class="content-background">
    <!-- Header Section Start -->
    <header class="d-flex justify-content-between align-items-center">
      <div class="header-left">
        <h1>Companhia Advogados</h1>
      </div>

      <div class="header-right">
        <div class="btn-group-container text-center mt-4">
          <div class="btn-group btn-group-toggle" data-toggle="buttons">
            <label class="btn btn-secondary active">
              <input type="radio" name="options" id="option1" autocomplete="off" checked=""> Página Inicial
            </label>
            <label class="btn btn-secondary">
              <input type="radio" name="options" id="option2" autocomplete="off"> Conheça Advogados
            </label>
            <label class="btn btn-secondary">
              <input type="radio" name="options" id="option3" autocomplete="off"> Contato
            </label>
            <label class="btn btn-secondary">
              <input type="radio" name="options" id="option4" autocomplete="off"> Contate-nos
            </label>
            <label class="btn btn-secondary">
              <input type="radio" name="options" id="option5" autocomplete="off"> Sobre Nós
            </label>
          </div>
        </div>
      </div>
    </header>
    <!-- Header Section End -->

    <!-- About Us Section Start -->
    <section id="about-us">
      <div class="container">
        <div class="row">
          <div class="col-md-12"></div>
        </div>

        <!-- Cards Section below btn-group -->
        <div class="lista-cards mt-4 d-flex justify-content-between">
          <div class="card" style="width: 18rem;">
            <img class="card-img-top" src="Flux.1 AI-2024-10-31 (2).png" alt="Imagem de capa do card">
            <div class="card-body">
              <p class="card-text">"Com uma carreira marcada por notáveis conquistas, Renata Almeida é reconhecida por sua
                habilidade em lidar com questões complexas no direito empresarial. Sua expertise em negociações e litígios
                a destaca como uma advogada de confiança, sempre pronta para oferecer soluções inovadoras. Com um compromisso
                inabalável com a ética e a justiça, ela é uma referência na área, sendo frequentemente elogiada por seus
                clientes e colegas." - Renata Almeida</p>
              <button class="button-85" role="button">Saiba Mais</button>
            </div>
          </div>

          <div class="card" style="width: 18rem;">
            <img class="card-img-top" src="Flux.1 AI-2024-10-31 (1).png" alt="Imagem de capa do card">
            <div class="card-body">
              <p class="card-text">"Com uma visão estratégica e um compromisso inabalável com a justiça, Rafael Fernandes é
                mais do que um advogado; ele é um defensor incansável dos direitos de seus clientes. Sua experiência e ética
                profissional o tornam um aliado valioso em cada desafio legal, transformando complexidades em soluções
                eficazes." - Rafael Fernandes</p>
              <button class="button-85" role="button">Saiba Mais</button>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- About Us Section End -->

    <!-- Área de Atuação Section Start -->
    <section id="area-de-atuacao" class="py-5">
      <div class="container">
        <h2 class="text-center mb-4">Áreas de Atuação</h2>
        <div class="row">
          <div class="col-md-4">
            <div class="card">
              <img class="card-img-top" src="area-atuacao-imagem1.jpg" alt="Imagem Área de Atuação 1">
              <div class="card-body">
                <h5 class="card-title">Direito Empresarial</h5>
                <p class="card-text">Consultoria em todas as questões jurídicas empresariais, como contratos, fusões e aquisições, e muito mais.</p>
                <button class="button-85" role="button">Saiba Mais</button>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card">
              <img class="card-img-top" src="area-atuacao-imagem2.jpg" alt="Imagem Área de Atuação 2">
              <div class="card-body">
                <h5 class="card-title">Direito Civil</h5>
                <p class="card-text">Atuamos com questões relacionadas a contratos, danos materiais, família, sucessões e mais no direito civil.</p>
                <button class="button-85" role="button">Saiba Mais</button>
              </div>
            </div>
          </div>
          <div class="col-md-4">
            <div class="card">
              <img class="card-img-top" src="area-atuacao-imagem3.jpg" alt="Imagem Área de Atuação 3">
              <div class="card-body">
                <h5 class="card-title">Direito Trabalhista</h5>
                <p class="card-text">Consultoria e assessoria em questões trabalhistas para empregados e empregadores, incluindo disputas e negociações.</p>
                <button class="button-85" role="button">Saiba Mais</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Área de Atuação Section End -->

  </div>
  <!-- End of Div with Background Image -->

  <footer>
    <div class="footer-image">
      <div class="glass-effect-footer">
        <p>© 2024 Meu Site. Todos os direitos reservados.</p>
        <p>
          <a href="#" style="color: white;">Sobre</a> |
          <a href="#" style="color: white;">Contato</a>
        </p>
        <p>Av. Álvares Cabral nº 1777, 4º e 18º andares, Santo Agostinho, Patos De Minas/MG<br>
          E-mail: dhayerfort@gmail.com</p>
      </div>
    </div>
  </footer>

</body>
</html>
