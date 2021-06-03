# Jupyter: um caderno computacional

Este repositório foi feito para o workshop sobre Jupyter na 1ª Semana de Workshops do ICMC - USP em 03/05/2021.

## Apresentação

É possível conferir a apresentação do Workshop aqui.

## Jupyter Notebooks

Para a melhor visualização dos cadernos pode-se utilizar do [nbviewer](https://nbviewer.jupyter.org/) que pode renderizar os cadernos hospedado no repositório do GitHub. Os cadernos podem ser visualizados nos seguintes links:

[1 - Introdução](https://nbviewer.jupyter.org/github/brenoslivio/WorkshopJupyterICMC/blob/main/1-Introducao.ipynb)

[2 - Imagens](https://nbviewer.jupyter.org/github/brenoslivio/WorkshopJupyterICMC/blob/main/2-Imagens.ipynb)

[3 - Widgets](https://nbviewer.jupyter.org/github/brenoslivio/WorkshopJupyterICMC/blob/main/3-Widgets.ipynb)

## Abrindo os Notebooks pelo Google Colab

Ao abrir os links anteriores dos cadernos no nbviewer, você verá o seguinte ícone:

![colab](https://colab.research.google.com/assets/colab-badge.svg)

Basta clicar nele para abrir o caderno no Colab.

## Arquivo para o Docker Compose

Com o Docker Compose instalado, utilize do arquivo `yml` localizado [aqui](https://github.com/brenoslivio/WorkshopJupyterICMC/blob/main/Docker/docker-compose.yml) para utilizar do seguinte comando:

```bash
	docker-compose up
```

O arquivo `yml` tem o seguinte conteúdo:

```
version:                "3"
services:
  datascience-notebook:
      image:            jupyter/datascience-notebook
      volumes:
        - /SEU/DIRETORIO/AQUI:/home/jovyan/work
      environment:
        GRANT_SUDO: "yes"
        #JUPYTER_ENABLE_LAB: "yes"
      user: root
      ports:
        - 8888:8888
      container_name:   datascience-notebook-container
```

Troque `/SEU/DIRETORIO/AQUI` para o caminho onde vai abrir seus cadernos Jupyter.

Se quiser utilizar o JupyterLab ao invés do Jupyter clássico, basta retirar o `#` para utilizar o comando `JUPYTER_ENABLE_LAB: "yes"`.