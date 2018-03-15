# Estrutura padrão de projeto para desenvolvimento do front-end
Esse é um modelo padrão para desenvolvimento front-end de qualque projeto onde é seguido boas práticas de estruturação do projeto

## Tópicos

- [Introdução](#introdução)
- [Stack e Instalação](#stack-e-instalação)
  - [Sass](#sass)
  - [Compass](#compass)
  - [Susy](#susy)
  - [Outros Componentes](#outros-componentes)


## Introdução

Para desenvolvimento do front-end de qualquer site é sempre bom manter um padrão de estrutura independente do tipo e do tamanho do projeto em si. Por isso nesse repositório é feito uma pré-estrutura padrão de projeto para ser seguida utilizando a tecnologia do Sass e fazendo a modularização de partes do site tornando assim o projeto mais organizado e facilitando futuras melhorias e manutenções

## Stack e Instalação

Para a utilização correta do padrão de projeto deve ser instalado alguns componentes. É suma importância que o usuário tenha um conhecimento prévio das tecnologias a seguir.

### Sass

Segundo a própria documentação:
> Sass é uma extensão de CSS que adiciona novas possibilidades e elegância à linguagem base.

O seu propósito é corrigir as falhas do CSS. Que é uma linguagem simples de aprender mas pode se tornar complexa de ser mantida. Por este motivo foi idealizado o Sass como uma meta-linguagem para melhorar a sintaxe original do CSS, oferencedo mais funcionalidades.

Sass é uma biblioteca (*gem*) Ruby e para instalá-la é necessário possuir o Ruby instalado.

Para Windows é necessário a instalação do [Ruby Installer](http://rubyinstaller.org/).

Após instalado basta abrir o terminal (linha de comando) e digitar `gem install sass`.

> Para mais informações clique [aqui](http://sass-lang.com/install).

### Compass

O Compass é uma framework CSS que utiliza a linguagem Sass para agregar poder e facilitar a escrita de estilos.

Ele possui uma grande quantidade de mixins previamente implementados que facilitam e diminuem a complexidade com atributos e sua compatibilidade cross-browser, como por exemplo `border-radius` and `text-shadow`. O Compass ainda facilita a utilização de sprites de imagens.

Para instalá-lo você deve possuir o Ruby previamente instalado e executar o seguinte comando no terminal (linha de comando): `gem install compass`.

> Para mais informações clique [aqui](http://compass-style.org/install/).

### Susy

Susy é um grid framework que auxilia na delimitação das colunas de conteúdos, auxiliando a criar layouts responsivos.

Para instalá-lo você deve possuir o Ruby previamente instalado e executar o seguinte comando no terminal (linha de comando): `gem install susy`.

> Para mais informações clique [aqui](http://susydocs.oddbird.net/en/latest/install/).

### Outros Componentes

- **Compass-normalize:** É um plugin do Compass que facilita o uso do `normalize.css`, que é um pequeno CSS cujo objetivo é aumentar a consistência do CSS em diferentes browser, essa consistência é atingida removendo as regras aplicadas por cada browser. Para instalar: `gem install compass-normalize`, mais [aqui](https://github.com/ksmandersen/compass-normalize).
- **Breakpoint:** É uma biblioteca que auxilia a escrita de media queries. Para instalar: `gem install breakpoint`, mais [aqui](https://github.com/at-import/breakpoint/wiki/Installation#installation).
- **optipng:** Otimizador de imagens. Para instalar siga as instruções no [site oficial](http://optipng.sourceforge.net/). Lembrando que no Windows o caminho para o executável deve estar no Path.


## Referências

Este guia de estilos foi baseado nos seguintes conteúdos:
- [Magamobi Sass Styleguide](https://github.com/Magamobi/sass-styleguide)
