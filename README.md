<h1 align="center"> 🐳 curso-docker 🐳 </h1>

## Descrição

Repositório destinado a armazenar os projetos realizados durante o curso de Docker oferecido pela Cod3r.

***

## Sobre

Neste repositório é apresentado dois projetos realizados durante o curso de Docker, eles apresentam o intuito de fixar o aprendizado sobre o conteúdo de Docker Compose.

***

## Projetos, serviços e imagens

A seguir é apresentado uma breve explicação de cada projeto e os serviços e suas respectivas imagens do docker compose:

* node-mongo-compose: este projeto é destinado a implementar um sistema de cadastro simples:
    * backend - node (8.1)
    * frontend: nginx (1.13)
    * banco de dados: mongoDB (3.4)
* email-worker-compose: este projeto tem como simular um ambiente para envio de e-mails:
    * db - postgres (9.6)
    * frontend - nginx (1.13)
    * app - python (3.6)
    * queue - redis (3.2)
    * worker - build do python (3.6)

***

## Execução

Para executar o projeto "node-mongo-compose":
* Abra o terminal.
* Localize-se na pasta do projeto.
* Digite o seguinte comando:
```
docker-compose up -d

```

Para executar o projeto "email-worker-compose":
* Abra o terminal.
* Localize-se na pasta do projeto.
* Digite o seguinte comando:
```
docker-compose up -d --scale worker=3

```

***

## Curso

<a href="https://www.udemy.com/share/101WFA3@d0oq7WPo2MmaT3GcCWFLhS9yEPTo3YwOuB_H806_puk2KY5lS1hdt1gadP4DNXitIA==/">LINK DO CURSO</a>

***

## Status

:white_check_mark: **FINALIZADO** :white_check_mark:

***

## Autor

Feito por Bruno Jun Amanai Yamada.

[![Linkedin Badge](https://img.shields.io/badge/-BrunoJun-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/brunojun//)](https://www.linkedin.com/in/brunojun/) [![Gmail Badge](https://img.shields.io/badge/-brunojun7@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:brunojun7@gmail.com)](mailto:brunojun7@gmail.com)
