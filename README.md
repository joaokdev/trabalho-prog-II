# Site Piracanjuba

Página feita para um trabalho de faculdade, seguindo um wireframe dado pelo professor. O tema escolhido foi a Piracanjuba.

## Tecnologias

- HTML
- CSS

## Como executar

Baixe a pasta e abra o arquivo `index.html` no navegador. Não precisa instalar nada, mas é preciso estar conectado à internet para carregar as fontes do Google Fonts (Bricolage Grotesque e Public Sans).

## Sobre o projeto

A página tem cabeçalho (logo e duas informações), menu, corpo (imagem e texto), uma seção de destaques com três cards, uma chamada para ação (título, botão principal, telefone e um cartão com três motivos), uma seção de localização (mapa e endereço organizados com CSS Grid) e o rodapé (links úteis, fale conosco e redes sociais).

Os ícones são SVG colocados direto no HTML. As cores (azul, vermelho, laranja e amarelo) foram tiradas da logo, e a tarja colorida do topo e do rodapé e os arcos da chamada para ação lembram o desenho do sol da marca. Na chamada, o botão amarelo com sombra laranja tem um pequeno efeito ao passar o mouse, feito só com CSS (transition), sem JavaScript.

Responsividade:

- Tablet: fontes menores, texto centralizado, imagem do corpo abaixo do texto, cards dos destaques em uma coluna e cartão da chamada abaixo do texto.
- Localização: duas colunas (mapa e endereço) no desktop e uma coluna, um bloco abaixo do outro, a partir de 768px de largura.
- Celular: logo do cabeçalho menor, sem as informações 1 e 2, e botão da chamada ocupando a largura da tela, com o telefone logo abaixo.

O endereço e o telefone da seção de localização são reais, e o mapa e a foto do prédio são imagens do Google Maps. O e-mail do rodapé é só de exemplo.

Referências: MDN (CSS Grid Layout) e W3Schools (CSS Grid).
