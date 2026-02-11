---
layout: clean
title: Sobre
permalink: /sobre/
---

<section class="section about-page">
  <div class="container">
    <header class="page-head">
      <h1 class="section__title">Sobre Mim</h1>
      <div class="section__underline"></div>
    </header>

    <div class="about-hero">
      <!-- FOTO -->
      <div class="about-hero__photo">
        <!-- troque o src pela sua foto (pode ser /assets/img/sua-foto.jpg) -->
        <img src="{{ '/assets/img/minha-foto.jpg' | relative_url }}" alt="Sua Foto">
        <div class="about-hero__role">Data Analyst</div>
      </div>

      <!-- TEXTO -->
      <div class="about-hero__text">
        <h2 class="about-hero__title">Olá! Sou o  Gutemberg Rodrigues 😊</h2>

        <p>
          Analista de Dados, com experiência em transformar dados em insights e informações que realmente
          impactam os resultados do negócio.
        </p>

        <p>
          Atuo com análise, visualização e modelagem de dados, desde a coleta com Python e SQL até a
          modelagem em nuvem e entrega de dashboards.
        </p>

        <p>
          Quer conversar sobre freelas, dados ou tech? Fique à vontade para entrar em contato!
        </p>
      </div>
    </div>

    <h3 class="about-section-title">Certificações & Formação</h3>

    <div class="about-certs">
      <article class="about-cert">
        <div class="about-cert__icon"><i class="fa-solid fa-graduation-cap"></i></div>
        <div class="about-cert__name">Engenharia de Produção</div>
        <div class="about-cert__org">Sua Universidade</div>
      </article>

      <article class="about-cert">
        <div class="about-cert__icon"><i class="fa-solid fa-chart-column"></i></div>
        <div class="about-cert__name">Formação Power BI</div>
        <div class="about-cert__org">Sua Escola</div>
      </article>

      <article class="about-cert">
        <div class="about-cert__icon"><i class="fa-brands fa-google"></i></div>
        <div class="about-cert__name">Google Data Analytics</div>
        <div class="about-cert__org">Google</div>
      </article>

      <article class="about-cert">
        <div class="about-cert__icon"><i class="fa-brands fa-python"></i></div>
        <div class="about-cert__name">Formação Data Science</div>
        <div class="about-cert__org">Sua Escola</div>
      </article>
    </div>

    <div class="about-actions">
      <!-- Troque o href pro seu CV (PDF no repo ou link externo) -->
      <a class="btn btn--light" href="#" target="_blank" rel="noreferrer">
        <i class="fa-solid fa-download" style="margin-right:8px;"></i>Download CV
      </a>
    </div>
  </div>
</section>

