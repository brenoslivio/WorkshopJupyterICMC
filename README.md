# Jupyter: um caderno computacional

Este repositório foi feito para o workshop sobre Jupyter na 1ª Semana de Workshops do ICMC - USP em 03/05/2021.

## O que pretendo passar

- História e introdução dando diversos exemplos de como pode ser usado;
- As diversas formas de se usar o sistema Jupyter;
- Instalação;
- Aplicações com o Jupyter envolvendo plottar gráficos, desenvolver widgets e até fazer documentos somente em texto, incluindo com LaTeX. Existem várias extensões para o Jupyter que penso em falar e mostrar como utilizá-las;
- Uso de linguagens além de Python no Jupyter, como R e C++.

## O que é o Jupyter?

Jupyter é uma ferramenta interativa de código aberto e conhecida como um caderno de anotações computacional, que os pesquisadores podem usar para combinar códigos de software, saídas computacionais, textos explicativos e recursos multimídia em um único documento [1]. 

## Project Jupyter

O Projeto Jupyter é um projeto sem fins lucrativos e de código aberto, nascido do projeto IPython em 2014, à medida que evoluiu para apoiar a ciência dos dados interativos e a computação científica em todas as linguagens de programação [2].

JUlia + PYThon + R = Jupyter!!

## História dos cadernos computacionais

Em 1987, foi desenvolvido uma espécie de caderno computacional pensando no software Mathematica. 
Quando você observa como esses cadernos foram estruturados, você percebe que eles dependiam de uma hierarquia de células que permitia o esboço e a seção de documentos, que você agora também encontra nos cadernos Jupyter.

## IPython

No final de 2001, cerca de vinte anos depois que Guido van Rossum começou a desenvolver o Python no Instituto Nacional de Pesquisa em Matemática e Ciência da Computação na Holanda, Fernando Pérez começou a desenvolver o IPython.
IPython tem agora apenas dois papéis a cumprir: ser o backend Python para o Jupyter Notebook, que também é conhecido como o kernel, e um shell Python interativo [3].

## Importância desses cadernos computacionais

Esses cadernos podem auxiliar em diversos tipos de casos:

- Ensino de programação;
- Produção de relatórios científicos;
- Desenvolvimento de aplicações de estatística e ciência de dados.

## Crescimento do uso desses cadernos

Há cerca de 3 anos, havia 1.230.000 cadernos Jupyter publicados no GitHub. Em outubro de 2020, este número havia crescido 8 vezes, e conta com 9.720.000 cadernos [4].

## R Markdown

Outra “alternativa” ao Jupyter pode ser o RMarkdown.  Ele funciona de forma análoga ao Jupyter pensando em células de texto e código.
As diferenças notáveis é que o arquivo do RMarkdown é possível editar como texto, enquanto o Jupyter gera um código em JSON (JavaScript Object Notation), como se o caderno já fosse pensado como uma “aplicação web”.
Além disso, para reproduzir widgets como o Jupyter, recomenda-se o uso do pacote Shiny.

## Markdown no Jupyter

O Markdown é uma linguagem de marcação (markup language) para formatar textos, tal como HTML, XML e LaTeX, que podem ser também consideradas linguagens de marcação.

Para células de texto no Jupyter, a formatação é em Markdown.

## Diversas formas de se usar o Jupyter

Online, por um servidor que armazena o sistema Jupyter:

    Google Colab, Binder.

Instalando no computador:
- Instalar diretamente pelo pip ou conda;
- Instalar extensão de Python no Visual Studio Code;
- Docker.

## Usando o Docker

Usar o Jupyter com o Docker é provavelmente o melhor caminho.
Instruções de como instalar o Docker Compose em qualquer Sistema Operacional:

https://docs.docker.com/compose/install/
