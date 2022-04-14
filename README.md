# Ambiente de desenvolvimento para PHP

Ambiente de desenvolvimento PHP para o desktop, com suporte ao PHP 5.6, 7.4 e 8.1

Aqui teremos imagens docker contendo LAMP e LAMPP, com Apache, MySQL/MariaDb e PHP, como também o LAMPP vem também com o PostgreSQL.

Os container docker, debian-lamp e debian-lampp, cada um traz suporte as 3 versões citadas do PHP. Basta que configure o .env do raiz escolhendo a versão do PHP, que o container será criado com esta versão.

Todos os containers usam o Debian Slim, que é mais enxuto. Cada versão do PHP requer uma versão do Debian:

- PHP 5.6 - Debian Jessir
- PHP 7.4 - Debian stable/11
- PHP 8.1 - Debian unstable/SID

As imagens publicadas no Docker Hub são para apenas uma versão do PHP.

A primeira imagem, para o PHP 5.6 já está no Docker Hub para ser testada.

https://hub.docker.com/repository/docker/ribafs/lamp-5.6

Basta que instale o docker em seu desktop e instale a imagem abrindo seu terminal/prompt a executando:

docker pull ribafs/lamp-5.6:latest

## Colaboradores

- Marcos Abreu
- Ribamar FS

## Sugestões

Serão muito bem vindas. Use os issues para isso.

## Licença

MIT
