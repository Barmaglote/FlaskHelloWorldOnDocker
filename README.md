# FlaskHelloWorldOnDocker

Hello World for Flask with Docker

Run: 

 docker run --rm --name web -p 8080:8080 -e TZ="Europe/Moscow" -v  <PathToFolderWithApplicaion>\resources:/usr/src/app/resources web-hello
