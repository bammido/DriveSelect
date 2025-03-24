# 📍🗺️ Drive-Select

<div align="center">

<img src="./.gitassets/driveSelect-logo.png">

<div data-badges>
    <img src="https://img.shields.io/badge/axios-671ddf?&style=for-the-badge&logo=axios&logoColor=white">
    <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white">
    <img src="https://img.shields.io/badge/Express%20js-000000?style=for-the-badge&logo=express&logoColor=white">
    <img src="https://img.shields.io/badge/Node%20js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white">
    <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white">
</div>
</div>

A ideia é simples: um aplicativo web de viagens, semelhante ao Uber, onde usuários podem solicitar corridas.

## ⚙️ Como rodar?

### Pré-requisitos:

* Ter o docker e o docker-compose instalado e configurado
* Chave api do places da google

### Passos:


1. criar o .env

O projeto foi feito usando a api places da google, portanto é necessário que tenha uma chave api gerado no gcp com permissão para usar a api places. [pode ser gerada aqui](https://console.cloud.google.com/apis).

Com a chave, deve ser criado um arquivo .env na raiz da seguinte forma:

``` GOOGLE_API_KEY = [sua chave api] ```

2. buildar e rodar com o docker compose

Para iniciar o projeto basta excutar o comando:

``` docker-compose up ```

Após o processo ele deve estar disponível em [localhost:80](http://localhost:80)

## 🛠️ Features

✅ Interface web para solicitação de corridas com visualização da rota, distância e tempo de viagem aproximado

✅ Sistema básico de matching entre passageiros e motoristas

✅ Backend estruturado para gerenciamento de viagens

## 💻 Tecnologias

* Node
* React
* Places Api
* Docker

![](./.gitassets/mapa.png)

![](./.gitassets/historico.png)

## Links Úteis

* [docker](https://www.docker.com/)
* [apis gcp](https://cloud.google.com/apis)
