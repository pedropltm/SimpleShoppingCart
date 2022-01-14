Descrição

DockerDotnetAPI é um template preparado para criar APIs .Net Core utilizando Docker.

Iniciando um novo projeto, a partir deste template

  Pré Requisitos

    * VS Code (recomendado) ou outra IDE de sua preferência;
    * Docker For Windows
    * Ter uma conta no Docker HUB

  Passo a passo

    1. Clonar o projeto em seu diretório local desejado;
    2. Abrir a pasta do projeto no VS Code;
    3. No VS Code:
       3.1 Instalar extensões
         3.1.1 C# for Visual Studio Code (ou similar, no caso de outra IDE)
         3.1.2 Docker for Visual Studio Code (ou similar, no caso de outra IDE)
       3.2 Abrir o terminal
       3.3 Navegar até o diretório clonado
       3.4 docker --version
       3.5 docker image build -t seuambiente/dockerdotnetapi .
       3.6 docker container run --name DockerDotnetAPI -p 8080:80 seuambiente/dockerdotnetapi
       3.7 docker image push seuambiente/dockerdotnetapi
    

Fontes de Consulta

Youtube - Les Jackson
Deploy a .NET Core API with Docker (Step-by-Step)
https://www.youtube.com/watch?v=f0lMGPB10bM

Udemy - Leonardo Moura Leitão, Arquiteto de Software
Docker: Ferramenta essencial para Desenvolvedores
http://www.udemy.com

QA Stack - Benjamin Pasero
Should I commit the VSCode folder to source control?
https://qastack.com.br/programming/32964920/should-i-commit-the-vscode-folder-to-source-control

Treinaweb - Marylene Guedes
SQL vs NoSQL, qual usar?
https://www.treinaweb.com.br/blog/sql-vs-nosql-qual-usar

Treinaweb - Ana Paula de Andrade
Os principais SGBDS NoSQL
https://www.treinaweb.com.br/blog/os-principais-sgbds-nosql/

Medium - Renato Groffe
ASP.NET Core + Docker Compose: implementando soluções web multi-containers
https://renatogroffe.medium.com/asp-net-core-docker-compose-implementando-solu%C3%A7%C3%B5es-web-multi-containers-5f46d22a2ca0


Medium - Joe Honour
A guide to setting up a .NET Core project using Docker, with integrated unit and component tests
https://joehonour.medium.com/a-guide-to-setting-up-a-net-core-project-using-docker-with-integrated-unit-and-component-tests-a326ca5a0284


Docker
Create a Dockerfile for and ASP.NET Core application
https://docs.docker.com/samples/dotnetcore/

Docker
Dockerfile reference
https://docs.docker.com/engine/reference/builder/