<template>
    <section class="projects" id="projects">
      <h2 class="titleSection">Projetos</h2>
      <div class="project-container">
        <article class="project">
          <div class="description">
            <h3 class="title">Biblioteca</h3>
            <div class="tags">
              <tag>HTML</tag>
              <tag>CSS</tag>
              <tag>Nuxt</tag>
            </div>
            <p class="text">
              Desenvolvido pensando em ser modularizado e simples devido ao tempo do projeto, feito em Nux para
              abranger componentes e Next pela fácil integração com ORM e banco de dados.
            </p>
            <button aria-label="Ver projeto Biblioteca"><a href="https://github.com/postrenan/bibliotecaFront" target="_blank">Ver projeto</a><i  class="fa fa-link"></i></button>
          </div>
          <div class="img">
            <img src="/assets/images/image.png" alt="Imagem do projeto Biblioteca">
          </div>
        </article>
  
        <article class="project">
          <div class="img">
            <img src="/assets/images/fakeSotre.png" alt="Imagem do projeto FakeStore">
          </div>
          <div class="description">
            <h3 class="title">FakeStore</h3>
            <div class="tags">
              <tag>HTML</tag>
              <tag>Bootstrap</tag>
              <tag>Vue.js</tag>
            </div>
            <p class="text">
              Projeto FakeStore feito como um desafio, no projeto utilizei Vue.js 3, TypeScript e Tailwind. O projeto consiste em fazer requisições para a Fake Store API para consumir os produtos, atualizar e deleta-los. Seguem imagens do projeto</p>
            <button aria-label="Ver projeto FakeStore"><a href="https://github.com/postrenan/FakeStore" target="_blank">Ver projeto </a><i  class="fa fa-link"></i></button>
          </div>
        </article>
  
        <article class="project">
          <div class="description">
            <h3 class="title">Urutu</h3>
            <div class="tags">
              <tag>HTML</tag>
              <tag>Bootstrap</tag>
              <tag>Vue.js</tag>
            </div>
            <p class="text">
              Este projeto é para o clã Urutu com o objetivo de ajudar os jogadores com estatísticas e informações do jogo além das novidades decorrentes das atualizações. Além do site ser uma forma de tentar atrair jogadores para o clã.
            </p>
            <button aria-label="Ver projeto Urutu"><a href="https://github.com/postrenan/Urutu" target="_blank">Ver projeto</a><i  class="fa fa-link"></i></button>
          </div>
          <div class="img">
            <img src="/assets/images/Urutu.png" alt="Imagem do projeto Urutu">
          </div>
        </article>
  
        <article class="project">
          <div class="img">
            <img src="/assets/images/GrandTour.png" alt="Imagem do projeto Grandtour Linktree">
          </div>
          <div class="description">
            <h3 class="title">Grandtour Linktree</h3>
            <div class="tags">
              <tag>HTML</tag>
              <tag>Bootstrap</tag>
              <tag>Vue.js</tag>
            </div>
            <p class="text">
              Esse projeto de linktree foi desenvolvido para minha família pois possuem uma agência de viagens e queríamos que os nossos clientes tivessem um contato mais rápido conosco enquanto estivessem vendo nossa página do Instagram, o linktree conta com dois botões de redirecionamento para WhatsApp diferentes
            </p>
            <button aria-label="Ver projeto Grandtour Linktree"><a href="https://github.com/postrenan/GrandtourLinkTree" target="_blank">Ver projeto</a> <i class="fa fa-link"></i></button>
          </div>
        </article>
      </div>
    </section>
  </template>
  
  <style scoped>
  .titleSection {
    display: flex;
    justify-content: center;
    color: var(--primary-text);
    font-size: 50px;
    margin: 100px 0 40px 0;
  }
  
  .projects {
    color: var(--primary-text);
    font-size: 20px;
    margin: 0 75px 200px 75px;
  }
  
  .project-container {
    display: flex;
    flex-direction: column;
    gap: 30px;
  }
  
  .project {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    margin: 20px 0;
    align-items: center;
  }
  
  a{
    text-decoration: none;
    color: inherit;
  }

  i{
    margin-left: 15px;
  }

  .description {
    flex: 1;
    max-width: 50%;
    padding: 10px;
  }
  
  .tags {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 10px;
  }
  
  tag {
    padding: 8px 12px;
    font-size: 14px;
    background-color: var(--second-bg);
    border-radius: 25px;
    transition: background-color 0.3s ease;
  }
  
  tag:hover {
    background-color: var(--third-bg);
  }
  
  .text {
    margin-top: 15px;
    overflow-wrap: break-word;
  }
  
  button {
    padding: 12px 20px;
    font-size: 16px;
    border: none;
    border-bottom: 2px solid var(--third-text);
    background-color: transparent;
    cursor: pointer;
    color: var(--primary-text);
    transition: all 0.3s ease;
    margin-top: 15px;
  }
  
  button:hover {
    color: var(--accent-color);
    border-bottom: 2px solid var(--accent-color);
  }
  
  .img {
    flex: 1;
    display: flex;
    justify-content: center;
  }
  
  img {
    width: 100%;
    max-width: 400px;
    height: auto;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
  }
  
  img:hover {
    transform: scale(1.05);
  }
  
  /* Media Queries for Responsiveness */
  
  @media (max-width: 768px) {
    .titleSection {
      font-size: 40px;
    }
  
    .projects {
      font-size: 18px;
    }
  
    .project {
      flex-direction: column;
      align-items: center;
    }
  
    .description {
      max-width: 100%;
      margin-top: 20px;
    }
  
    .tags {
      justify-content: center;
    }
  
    img {
      max-width: 90%;
    }
  
    button {
      width: 100%;
      padding: 12px;
    }
  }
  
  @media (max-width: 480px) {
    .titleSection {
      font-size: 30px;
    }
  
    .projects {
      font-size: 16px;
      margin: 0 10px;
    }
  
    .project {
      margin: 20px 0;
    }
  
    button {
      padding: 12px;
      font-size: 14px;
    }
  
    img {
      max-width: 100%;
    }
  }
  </style>
  