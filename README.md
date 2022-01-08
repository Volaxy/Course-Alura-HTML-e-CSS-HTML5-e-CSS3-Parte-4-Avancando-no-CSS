# HTML5 e CSS3 parte 4: Avançando no CSS

Curso da Alura sobre HTML e CSS

URL do curso -> [HTML5 e CSS3 parte 4: Avançando no CSS](https://www.alura.com.br/curso-online-html5-css3-avancando-css)
![HTML5 e CSS3 parte 4: Avançando no CSS](https://www.alura.com.br/assets/api/share/curso-html5-css3-avancando-css.png)

## Links Úteis
* [Google Fonts](https://fonts.google.com/) - Site do Google para importação e download de fontes.
* [Google Maps](https://www.google.com/maps) - Site do Google para mapas e importação deles no site.

## Siglas
*

## Atalhos
*

## 01 - Adaptando a Página Inicial
* A ajustar a página principal para utilizar os mesmos padrões da página de produtos.
* Medidas proporcionais com CSS.
* Como funciona a *flutuação* dos elementos e como modificá-la, com a propriedade `float` do CSS.
* Como *limpar* o `float`, com a propriedade `clear` do CSS.

## 02 - Conteúdo Externo
* A utilizar fontes externas nas nossas páginas.
* Como incorporar um mapa à nossa página.
* Como incorporar um vídeo à nossa página.

## 03 - Melhorando o CSS
* A melhorar mais ainda a semântica da página principal, com novas divisões, classes, etc.
* Novas pseudo-classes.
* Como aplicar um *background* gradiente na página.
* Pseudo-elementos.

## 04 - Selecionando Qualquer Coisa
* Seletores avançados CSS
    * Seletor >, para acessar os filhos de determinado elemento. Por exemplo, para acessar todos os p dentro de main:
        ```
        main > p {
        }
        ```
    * Seletor +, para acessar o primeiro irmão de determinado elemento. Por exemplo, para acessar o primeiro p após um img:
        ```
        img + p {
        }
        ```
    * Seletor ~, para acessar todos os irmãos de determinado elemento. Por exemplo, para acessar todos os p após um img:
        ```
        img ~ p {
        }
        ```
    * Seletor not, para acessar os elementos, exceto algum. Por exemplo, para acessar todos os p dentro de main, exceto o p que tem id missao:
        ```
        main p:not(#missao) {
        }
        ```
* Como fazer contas com CSS, com a propriedade calc.

## 05 - Opacidade e Sombra
* Como manipular a opacidade dos elementos, com a propriedade CSS `opacity`.
* Como manipular a opacidade das cores.
* Como adicionar um sombreamento em volta dos elementos, com a propriedade CSS `box-shadow`.
* Como adicionar um sombreamento em textos, com a propriedade CSS `text-shadow`.