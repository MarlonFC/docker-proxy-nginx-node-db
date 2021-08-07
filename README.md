# Nginx com Node.js
Desafio prático do curso FullCycle, no módulo de DevOps, iniciando com docker.

### Descrição do desafio
> Nesse desafio você colocará em prática o que aprendemos em relação a utilização do nginx como proxy reverso. A idéia principal é que quando um usuário acesse o nginx, o mesmo fará uma chamada em nossa aplicação node.js. Essa aplicação por sua vez adicionará um registro em nosso banco de dados mysql, cadastrando um nome na tabela people.

### Requisito
1. Gere o docker-compose de uma forma que basta apenas rodarmos: docker-compose up -d que tudo deverá estar funcionando e disponível na porta: 8080.

__Retorno esperado da aplicação node.js para o nginx:__
```html
<h1>Full Cycle Rocks!</h1>

- Lista de nomes cadastrada no banco de dados.
```

### Execute para obter o resultado :zap:
```
execute o comando no repo local: 

git clone https://github.com/MarlonFC/docker-proxy-nginx-node-db.git

execute o comando para entrar no diretório do projeto: 

cd docker-proxy-nginx-node-db

excute o comando para up do app: 

docker-compose up -d

acesse: http://localhost:8080
```
<br/>