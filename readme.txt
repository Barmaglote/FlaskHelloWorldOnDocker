 Simple Hello-World application with Docker. 

 Run: 

 docker run --rm --name web -p 8080:8080 -e TZ="Europe/Moscow" -v  C:\REPOSITORY\dockers\docker-hello-world\resources:/usr/src/app/resources web-hello

 Change "C:\REPOSITORY\dockers\docker-hello-world\resources" to Volume with resources folder