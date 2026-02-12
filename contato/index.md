---
layout: clean
title: Contato
permalink: /contato/
---

<section class="section contact-page">
  <div class="container">
    <header class="page-head">
      <h1 class="section__title">Entre em Contato</h1>
      <div class="section__underline"></div>

      <p class="page-subtitle">
        Vamos conversar sobre seu próximo projeto de dados
      </p>
    </header>

    <div class="contact-grid">
      <!-- COLUNA ESQUERDA -->
      <div class="contact-col">
        <h3 class="contact-title">Informações de Contato</h3>

        <div class="contact-cards">
          <a class="contact-card" href="mailto:gutembergrodrigues07@gmail.com">
            <div class="contact-card__icon">
              <i class="fa-regular fa-envelope"></i>
            </div>
            <div class="contact-card__text">
              <div class="contact-card__label">Email</div>
              <div class="contact-card__value">gutembergrodrigues07@gmail.com</div>
            </div>
          </a>

          <a class="contact-card" href="https://www.linkedin.com/in/gutemberganalista/" target="_blank" rel="noreferrer">
            <div class="contact-card__icon">
              <i class="fa-brands fa-linkedin-in"></i>
            </div>
            <div class="contact-card__text">
              <div class="contact-card__label">LinkedIn</div>
              <div class="contact-card__value">/in/gutemberganalista</div>
            </div>
          </a>

          <a class="contact-card" href="https://github.com/GutembergRodrigues" target="_blank" rel="noreferrer">
            <div class="contact-card__icon">
              <i class="fa-brands fa-github"></i>
            </div>
            <div class="contact-card__text">
              <div class="contact-card__label">GitHub</div>
              <div class="contact-card__value">/GutembergRodrigues</div>
            </div>
          </a>

          <div class="contact-card is-static">
            <div class="contact-card__icon">
              <i class="fa-regular fa-clock"></i>
            </div>
            <div class="contact-card__text">
              <div class="contact-card__label">Disponibilidade</div>
              <div class="contact-card__value">Resposta em até 24 horas</div>
            </div>
          </div>
        </div>
      </div>

      <!-- COLUNA DIREITA -->
      <div class="contact-col">
        <div class="contact-form">
          <h3 class="contact-form__title">Envie uma Mensagem</h3>

          <!-- IMPORTANTE:
               GitHub Pages não envia e-mail sozinho.
               Se quiser envio real, use Formspree/Getform/etc e troque o action. -->
          <form action="#" method="POST">
            <label class="cfield">
              <span>Nome</span>
              <input type="text" name="name" placeholder="Seu nome" />
            </label>

            <label class="cfield">
              <span>Email</span>
              <input type="email" name="email" placeholder="seuemail@exemplo.com" />
            </label>

            <label class="cfield">
              <span>Assunto</span>
              <input type="text" name="subject" placeholder="Assunto" />
            </label>

            <label class="cfield">
              <span>Mensagem</span>
              <textarea name="message" rows="6" placeholder="Conte-me sobre seu projeto..."></textarea>
            </label>

            <button class="btn btn--light contact-send" type="submit">
              <i class="fa-solid fa-paper-plane" style="margin-right:8px;"></i>
              Enviar Mensagem
            </button>
          </form>
        </div>
      </div>
    </div>
  </div>
</section>
