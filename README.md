// faz download da imagem para a maquina
docker pull redis

// inicia o redis
docker run --name redis-alcateiadev -d redis

// lista os containeres que estão rodando
docker ps

// exibe os logs
docker logs redis-alcateiadev

// para um containe
docker stop redis-alcateiadev

// inicia um container que está parado
docker start redis-alcateiadev

// apaga o container
docker rm -f redis-alcateiadev

//Apaga a imagem da maquina
docker rmi redis

// Cria uma nova imagem
docker build -t robot-alcateiadev .

// Subir a aplicação liberando a porta
docker run --name robot -p 8080:8080 -d robot-alcateiadev
docker run --name robot -p 7878:8080 -d robot-alcateiadev