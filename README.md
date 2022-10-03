<p>Este projeto foi desenvolvido por <a href="https://github.com/Istvanoliva">Istvan Oliva</a> enquanto estudava Desenvolvimento Back-end na <a href="https://www.betrybe.com/">Trybe</a> :rocket:</p>

# O que deverá ser desenvolvido

Você irá "conteinerizar" as aplicações de frontend, backend e testes, criar uma conexão entre elas e orquestrar seu funcionamento.

Crie imagens das aplicações e os configure com o docker-compose.

## Requisitos do projeto
  - [Comandos docker](#comandos-docker)
      - [1. Crie um novo container de modo interativo sem roda-lo nomeando-o como `01container` e utilizando a imagem `alpine` usando a versão `3.12`](#1-crie-um-novo-container-de-modo-interativo-sem-roda-lo-nomeando-o-como-01container-e-utilizando-a-imagem-alpine-usando-a-versão-312)
      - [2. Inicie o container `01container`](#2-inicie-o-container-01container)
      - [3. Liste os containers filtrando pelo nome `01container`](#3-liste-os-containers-filtrando-pelo-nome-01container)
      - [4. Execute o comando `cat /etc/os-release` no container `01container` sem se acoplar a ele](#4-execute-o-comando-cat-etcos-release-no-container-01container-sem-se-acoplar-a-ele)
      - [5. Remova o container `01container` que está em andamento.](#5-remova-o-container-01container-que-está-em-andamento)
      - [6. Faça o download da imagem `nginx` com a versão `1.21.3-alpine` sem criar ou rodar um container.](#6-faça-o-download-da-imagem-nginx-com-a-versão-1213-alpine-sem-criar-ou-rodar-um-container)
      - [7. Rode um novo container com a imagem  `nginx` com a versão `1.21.3-alpine` em segundo plano nomeando-o como `02images` e mapeando sua porta padrão de acesso para porta `3000` do sistema hospedeiro.](#7-rode-um-novo-container-com-a-imagem--nginx-com-a-versão-1213-alpine-em-segundo-plano-nomeando-o-como-02images-e-mapeando-sua-porta-padrão-de-acesso-para-porta-3000-do-sistema-hospedeiro)
      - [8. Pare o container `02images` que está em andamento.](#8-pare-o-container-02images-que-está-em-andamento)
  - [Dockerfile](#dockerfile)
      - [9. Gere uma build a partir do Dockerfile do `back-end` do `todo-app` nomeando a imagem para `todobackend`.](#9-gere-uma-build-a-partir-do-dockerfile-do-back-end-do-todo-app-nomeando-a-imagem-para-todobackend)
      - [10. Gere uma build a partir do Dockerfile do `front-end` do `todo-app` nomeando a imagem para `todofrontend`.](#10-gere-uma-build-a-partir-do-dockerfile-do-front-end-do-todo-app-nomeando-a-imagem-para-todofrontend)
      - [11.Gere uma build a partir do Dockerfile dos `testes` do `todo-app` nomeando a imagem para `todotests`.](#11gere-uma-build-a-partir-do-dockerfile-dos-testes-do-todo-app-nomeando-a-imagem-para-todotests)
  - [Bônus](#bônus)
    - [Docker-compose](#docker-compose)
      - [12. Suba uma orquestração em segundo plano com o docker-compose de forma que `backend`, `frontend` e `tests` consigam se comunicar.](#12-suba-uma-orquestração-em-segundo-plano-com-o-docker-compose-de-forma-que-backend-frontend-e-tests-consigam-se-comunicar)

---

# Habilidades
Neste projeto, você será capaz de:
  * Usar comandos dockers no CLI - Interface de linha de comando;
  * Criar um contêiner Docker para uma aplicação de front-end;
  * Criar um contêiner Docker para uma aplicação de back-end;
  * Criar um contêiner Docker para uma aplicação de testes;
  * Orquestrar os três contêineres utilizando o Docker compose.
  
