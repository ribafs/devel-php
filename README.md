# Ambiente de desenvolvimento para PHP

Ambiente de desenvolvimento PHP para o desktop, com suporte ao PHP 5.6, 7.4 e 8.1

Aqui teremos imagens docker contendo LAMP e LAMPP, com Apache, MySQL/MariaDb e PHP, como também o LAMPP vem também com o PostgreSQL.

Os container docker, debian-lamp e debian-lampp, cada um traz suporte as 3 versões citadas do PHP. Basta que configure o .env do raiz escolhendo a versão do PHP, que o container será criado com esta versão.

Todos os containers usam o Debian Slim, que é mais enxuto. Cada versão do PHP requer uma versão do Debian:

- PHP 5.6 - Debian Jessir
- PHP 7.4 - Debian stable/11
- PHP 8.1 - Debian unstable/SID

## Projeto Abandonado

Pesquisando como rodar o laravel no docker no grupo PHP Brasil, um colega me falou sobre o devilbox. Testei e ele faz tudo o que pretendiamos com este repositório. Então resolvemos abandonar este projeto em nome do [Devilbox](http://devilbox.org).

## Os containers estarão disponíveis aqui em breve

As imagens publicadas no Docker Hub são, cada uma para apenas uma versão do PHP.

## Imagens disponíveis

- https://hub.docker.com/r/ribafs/lamp-5.6
- https://hub.docker.com/r/ribafs/lamp-7.4
- https://hub.docker.com/r/ribafs/lamp-8.1

Basta que instale o docker em seu desktop e instale a imagem abrindo seu terminal/prompt a executando:

docker pull ribafs/lamp-5.6:latest

## Colaboradores

- Marcos Abreu
- Ribamar FS

## Sugestões

Serão muito bem vindas. Use os issues para isso.

## Licença

MIT
