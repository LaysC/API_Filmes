# API de Filmes 🎬

Este projeto é uma API simples desenvolvida com Express.js que serve uma lista de filmes. Inclui uma interface em HTML para exibir os filmes, com detalhes como imagem, descrição e elenco. O projeto utiliza também um arquivo JSON com os dados dos filmes.

## 🚀 Tecnologias Utilizadas

- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [CORS](https://www.npmjs.com/package/cors) para permitir requisições de outras origens
- HTML e JavaScript para exibição dos dados no navegador

## 📂 Estrutura do Projeto

```json
[
  {
    "id": "1",
    "nome": "Grey's Anatomy",
    "foto": "https://i.pinimg.com/originals/33/39/9d/33399df9faacc5de9e3928f52fabbacf.jpg",
    "descricao": "Durante sua residência, Meredith Grey vive paixões profissionais e pessoais com seus colegas médicos em um hospital de Seattle.",
    "elenco": "Ellen Pompeo, Sandra Oh, Katherine Heigl"
  },
  ...
]

## 📋 Pré-requisitos

- Node.js instalado
- Gerenciador de pacotes npm

 🔧 Instalação e Execução

1. Clone o repositório:

   ```bash
   git clone https://github.com/seuusuario/api-de-filmes.git
   cd api-de-filmes
   
2. Instale as dependências:
npm install express cors

3. Inicie o servidor:
node index.js

4. Acesse o endereço http://localhost:8080 no navegador.

🌐 Rotas da API
GET /filmes: Retorna a lista de filmes em formato JSON.
📄 Exemplo de Uso
A interface HTML no arquivo index.html permite visualizar os filmes com título, imagem, descrição e elenco. A listagem de filmes é gerada com JavaScript, fazendo uma requisição à API.

🛠️ Contribuições
Sinta-se à vontade para contribuir com o projeto, seja melhorando o código, corrigindo bugs ou adicionando novos filmes ao filmes.json.


## Nota: Este projeto foi desenvolvido como parte de uma atividade em sala de aula e tem fins exclusivamente educacionais, visando ao aprendizado prático de construção de APIs com Node.js e Express.
