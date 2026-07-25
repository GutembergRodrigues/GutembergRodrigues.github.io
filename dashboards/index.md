---
layout: clean
title: Dashboards
permalink: /dashboards/
---

<section class="section" id="dashboards">
  <div class="container">

    <header class="page-head">
      <h1 class="section__title">Dashboards</h1>
      <div class="section__underline"></div>

      <p class="page-subtitle"></p>
    </header>

    <div class="projects">

      <!-- Card 1 -->
      <article class="project-card">

        <div class="project-card__media project-card__media--oscar">

          <!-- Fundo ampliado para preencher toda a área -->
          <img
            class="project-card__image-background"
            src="https://unsplash.com/photos/9QadD02QrPw/download?force=true&w=1200"
            alt=""
            aria-hidden="true"
          />

          <!-- Imagem principal completa, sem cortes -->
          <img
            class="project-card__image-main"
            src="https://unsplash.com/photos/9QadD02QrPw/download?force=true&w=1200"
            alt="Dashboard Power BI Oscar 1928 - 2023"
            loading="lazy"
          />

        </div>

        <div class="project-card__body">

          <h3 class="project-card__title">
            Dashboard Power BI Oscar 1928 - 2023
          </h3>

          <p class="project-card__desc">
            Dashboard interativo voltado às premiações do Oscar, com o objetivo
            de apresentar e analisar informações como ano e número da cerimônia,
            Melhor Filme, Melhor Ator e Melhor Atriz, além de atributos dos filmes
            — gênero, duração, avaliações do IMDb e Rotten Tomatoes — e outras
            métricas relevantes, permitindo uma visão comparativa e detalhada
            ao longo dos anos.
          </p>

          <div class="project-card__tags">
            <span class="pill">API</span>
            <span class="pill">HTML</span>
            <span class="pill">CSS</span>
          </div>

          <div class="project-card__links">
            <a
              class="plink"
              href="https://app.powerbi.com/view?r=eyJrIjoiYWIzNjY0ZjktZTllMy00YjVlLWI0ZmQtNmY5M2I2NWJjOTViIiwidCI6IjhlNTIxMGI4LTQ1MzQtNGE1Ny05ODBkLWYxZTdkOGQ0MjVkYiJ9"
              target="_blank"
              rel="noreferrer"
            >
              <i class="fa-solid fa-arrow-up-right-from-square"></i>
              <span>Ver Dashboard</span>
            </a>
          </div>

        </div>
      </article>

    </div>
  </div>
</section>

<style>
  /*
    Mantém exatamente o tamanho original da área da imagem.
    Nenhuma largura ou altura do card é alterada.
  */
  .project-card__media--oscar {
    position: relative;
    overflow: hidden;
    background-color: #000;
  }

  /*
    Imagem usada apenas como fundo.
    Ela preenche toda a área e recebe desfoque.
  */
  .project-card__image-background {
    position: absolute;
    inset: 0;
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: center;
    transform: scale(1.12);
    filter: blur(14px);
    opacity: 0.7;
  }

  /*
    Imagem principal completa.
    O contain impede qualquer corte.
  */
  .project-card__image-main {
    position: relative;
    z-index: 1;
    width: 100%;
    height: 100%;
    object-fit: contain;
    object-position: center;
    display: block;
  }
</style>
