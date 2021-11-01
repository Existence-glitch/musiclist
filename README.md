# Grupo 15

Este es el repositorio del *Grupo 15*, cuyos integrantes son:

* Álvaro Carrasco - 201873018
* Joaquín Tapia - 201873016
* **Tutor**: Joaquín Montes

## Wiki

Puede acceder a la Wiki mediante el siguiente [enlace](https://gitlab.labcomp.cl/wladimir.ormazabal.ex/inf236-2021-2-grupo-15-p-002/-/wikis/home)

## Videos

* [Video presentación cliente](https://youtu.be/xEYDTg0q1Ao)
* [Video presentación avance 1](https://www.youtube.com/watch?v=iyxYf84W7GE)
* Video presentación final (*Pendiente*)

## Aspectos técnicos relevantes

*Por ejemplo, como poder levantar el proyecto, etc...*

El proyecto de ejemplo se baso en la documentación disponible en:

* [MVC Core](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app/start-mvc?view=aspnetcore-5.0&tabs=visual-studio-code)
* [.Net Core + Docker](https://code.visualstudio.com/docs/containers/quickstart-aspnet-core)

Desarrollado con [Docker](https://www.docker.com/) y complementos de [Visual Studio Code](https://code.visualstudio.com/)

**Importante:** Requiere tener [Docker](https://www.docker.com/) instalado. Para levantar el proyecto ejecutar los siguientes pasos:
1. ```docker-compose -f docker-compose.yml build --no-cache```
2. ```docker-compose -f docker-compose.yml up -d```
3. Acceder a http://localhost:5000/

Puede validar la creación de la imagen y contenedor:

1. ```docker images```
2. ```docker ps -a```
