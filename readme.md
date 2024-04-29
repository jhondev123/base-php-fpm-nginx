Esse é um projeto base para quem está precisando criar uma aplicação com Docker, PHP 8.2-fpm e Nginx.

Criei esse repositório depois de muitas horas batendo cabeça até entender como o nginx funcionaria em conjunto com o php via container

Funcionamento
1° Container do PHP Puro sem nenhuma Lib, se precisar instalar um framework verificar quais Libs e extensões eles precisam para rodar
2° Container do NGINX que irá criar um volume do arquivo de configurações onde está definido que ele irá procurar o container do PHP na porta 9000

Não sei se está perfeito essa implementação, mas foi o mais simples e funcional que eu consegui fazer.

Em breve subo um repositório com esse formato só que subindo uma aplicação laravel