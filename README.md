# Drive-Select 📍🗺️

A ideia é simples: um aplicativo web de viagens, semelhante ao Uber, onde usuários podem solicitar corridas e motoristas podem aceitar as solicitações.

## 🛠️ Features
✅ Interface web para solicitação de corridas com visualização da rota, distância e tempo de viagem aproximado
✅ Sistema básico de matching entre passageiros e motoristas
✅ Backend estruturado para gerenciamento de viagens

## 💻 Tecnologias

* Node
* React
* Places Api
* Docker

## Como rodar?

O projeto foi feito usando a api places da google, portanto é necessário que tenha uma chave api gerado no gcp com permissão para usar a api places. [pode ser gerada aqui](https://console.cloud.google.com/apis).

Com a chave, deve ser criado um arquivo .env na raiz da seguinte forma:

``` GOOGLE_API_KEY = [sua chave api] ```

Para iniciar o projeto basta excutar o comando:

``` docker-compose up ```
