<img src="./assets/img/icon.svg" alt="Melhor com Saúde" width="96">

# Vue Challenge Coodesh

<p> Desafio Coodesh para a vaga de Front End.

## Introdução 

Este é um desafio para testar seus conhecimentos em JavaScript, Vue.js e Nuxt.js ou Quasar (opcional);
Neste desafio existem várias formas de desenvolver com qualidade e reutilizar este tipo de projeto.
O objetivo é avaliar a sua forma de estruturação e autonomia em decisões para construir algo escalável.

## Desafio

Os sites do cliente Translation, Inc impactam milhões de pessoas mensalmente em diversos países e disponíveis em pelo menos 23 idiomas. Uma das principais características da Translation, Inc é o posicionamento orgânico no Google (SEO). Por isso, os projetos devem ser muito bem pensados ​​todos os projetos pensando em SEO, fluidez, reuso (componentes reutilizados em vários projetos) e velocidade de exibição do Google PageSpeed ​​( https ://developers/pagespeed/insights / ). O seu objetivo é criar um projeto que dê atenção aos requisitos acima.

## Recursos

- Verificar a documentação: https ://developerwordpress.org-api/

- Consumir uma REST API Wordpress do Mejor Con Salud: https://api.beta.mejorconsalud.com/wp-json/mc/v1/

- O seu ambiente local rodando na porta 9045 (localhost:9045)
- Webpack
- Vue.js
- NuxtJs ou Quasar - [Diferencial]
- Vue-Tailwind CSS: https://vue-tailwind.com (poderá definir outro se achar mais conveniente).

## Passo a Passo

Ao abrir a Home deve conter um buscador de artigos para facilitar aos usuários encontrarem conteúdos personalizados sobre saúde e nutrição. Deverá ser possível filtrar os artigos por: "Mais Relevantes" no topo.
Para isso, devemos usar o endpoint de busca:


- https://api.beta.mejorconsalud.com/wp-json/mc/v2/posts?search={{texto digitado sem entrada}}

- https://api.beta.mejorconsalud.com/wp-json/mc/v2/posts?search={{texto digitado sem entrada}}&page=1&orderby=relevance


Exemplo https://api.beta.mejorconsalud.com/wp-json/mc/v2/posts?search=calabazas 
Exemplo https://api.beta.mejorconsalud.com/wp-json/mc/v2/posts?search =calabazas&page=1&orderby=relevância

## Instalação

Após clonar o repositório, em um terminal no diretório do projeto, execute:

``` bash
npm install
```

## Compila e recarrega a quente para desenvolvimento

``` bash
$ npm run dev
```
Abir a porta (http://localhost:9045)

## Compila e minifica para produção

``` bash
$ npm run build
$ npm run start
```
