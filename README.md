# EatWell
### Getting started  
Para executar o projeto, será necessário ter instalado
- NodeJs: 12x
- Expo: 3.28.5
- PHP: 7x
### Desenvolvimento
Para iniciar o projeto é necessario somente clonar o repositorio no diretorio escolhido e realizar as configurações necessarias.  
`$ cd "diretorio escolhido"`  
`$ git clone https://github.com/FI12LHO/PHP-React.git`  
### Contrução
- Para construir o projeto em ambos os diretorios "frontend" e "mobile" execute o comando `$ npm install`, para baixar todas as dependências necessarias;
- Construa o banco de dados MYSQL com o nome "guide" (caso opte por outro nome, deve ser alterado no arquivo de conexão dentro da pasta backend/configuration);
- Crie uma tabela com o nome "restaurant" com os campos: id:STRING, name:STRING, owner:STRING, opening:STRING, contact:STRING, address:STRING, cep:STRING, delivery:STRING.
### Features
Este projeto tem como objetivo demonstrar um aplicativo simples de busca, que possibilita o cadastro, edição e exclusão de restaurantes. O sistema faz uso de uma API contruida usando PHP nativo, ReactJs para versão web e Expo(React Native) para versão mobile.
### Configuracão
- Dentro do diretorio "backend/configuration" no arquivo "connection.php" deve ser feito uma verificação nas informações para conexão com o banco de dados.
- Dentro do diretorio "frontend/src/services" no arquivo "api.js" o endereço IP do servidor deve ser alterado, http://10.0.0.102:3333 para o endereço do IP servidor na rede local (http://meu-ip:3333);
- Dentro do diretorio "mobile/src/services" no arquivo "api.js" o endereço IP do servidor deve ser alterado, http://10.0.0.102:3333 para o endereço do IP servidor na rede local (http://meu-ip:3333).
