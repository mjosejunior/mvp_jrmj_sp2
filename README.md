![MVP PUC-Rio - José Rodrigues Matos Junior](./img/banner_repo.png)
#
&nbsp;
&nbsp;

***MVP PUC-Rio-JRMJ SP2 - Sistema Integrado***

🚀 Bem-vindo ao repositório integrado do Sistema de controle de atividades de serviço de campo! Este projeto é o marco de conclusão da *Sprint 2 do Curso de Desenvolvimento Full Stack na PUC-Rio*.

# Sobre o MVP
Desenvolvemos esta aplicação para auxiliar o "Publicador de Boas Novas" a registrar suas atividades diárias de trabalho. Utilizando a  [OpenStreetMap (OSM) Nominatim API](https://nominatim.org/release-docs/develop/api/Overview/) é possível obter nomes de lugares e detalhes com base nas coordenadas do local. 

## Tecnologias Utilizadas
- ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white)
- ![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=Flask&logoColor=white)
- ![OpenAPI](https://img.shields.io/badge/-OpenAPI-6BA539?style=flat-square&logo=OpenAPI-Initiative&logoColor=white)
- ![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=SQLite&logoColor=white)
- ![SQLAlchemy](https://img.shields.io/badge/-SQLAlchemy-8C2D19?style=flat-square&logo=SQLAlchemy&logoColor=white)
- ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white)
- ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=black)
- ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=Docker&logoColor=white)
- ![Nginx](https://img.shields.io/badge/-Nginx-269539?style=flat-square&logo=Nginx&logoColor=white)

📺 [Vídeo de Visão Geral do Projeto](https://youtu.be/mD65-vTK5FE)

## O sistema está organizado em submódulos:

* [Backend](https://github.com/mjosejunior/mvp_jrmj_sp2_back.git)
* [Frontend](https://github.com/mjosejunior/mvp_jrmj_sp2_front.git)

## Como Executar o Sistema Integrado

## Com Docker - ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=Docker&logoColor=white)

1. Certifique-se de ter o Docker e o Docker Compose instalados.

2. Clone este repositório, que inclui os submódulos:
```bash
git clone --recursive https://github.com/mjosejunior/mvp_jrmj_sp2.git
```
3. No diretório principal, onde o `docker-compose.yml` está localizado, execute:
```bash
docker-compose up --build
```

## Acesse:

*Frontend*: `http://localhost`

*Backend*: `http://localhost:5001`

*Para executar individualmente, sem Docker, consulte as instruções nos repositórios de 
[Backend](https://github.com/mjosejunior/mvp_jrmj_sp2_back.git) e [Frontend](https://github.com/mjosejunior/mvp_jrmj_sp2_front.git)

## Suporte

Em caso de dúvidas ou dificuldades, por favor, entre em contato conosco.




