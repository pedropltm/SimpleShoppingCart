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