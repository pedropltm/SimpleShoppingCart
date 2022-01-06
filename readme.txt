Descrição

DockerDotnetAPI é um template preparado para criar APIs .Net Core utilizando Docker.

Iniciando um novo projeto, a partir deste template

  Pré Requisitos

    * VS Code ou Visual Studio;
    * Docker For Windows
    * Ter uma conta no Docker HUB

  Passo a passo

    1. Clonar o projeto em seu diretório local desejado;
    2. Abrir a pasta do projeto no VS Code ou Visual Studio;
    3. No VS Code:
       3.1 Abrir o terminal;
       3.2 Navegar até o diretório clonado;
       3.3 docker --version;
       3.4 docker build -t seuambiente/dockerdotnetapi .
       3.5 docker run -p 8080:80 seuambiente/dockerdotnetapi
       3.6 docker push seuambiente/dockerdotnetapi
    

Fontes de Consulta

Youtube - Les Jackson
Deploy a .NET Core API with Docker (Step-by-Step)
https://www.youtube.com/watch?v=f0lMGPB10bM