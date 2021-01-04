## Udemy: Docker para iniciante: Seu primeiro contato

Em 20 anos de carreira na área de tecnologia, desenvolvendo software, usei diversas ferramentas para criar softwares. Sabe o que eu reparei? Conhecimentos e configurações sobre ambiente de produção, ambientes de desenvolvimentos, eram tudo muito complicado. Montar um ambiente de desenvolvimento parecido com o ambiente de produção então, quase impossível. Sabe mais uma coisa que eu reparei? Os líderes técnicos, líder de times, os sênior, tinham essas habilidades e eles eram as pessoas que mais ganhavam aumento ou subiam de cargo.

Mas aprender isso não foi fácil, pois encontrar cursos ou algum mentor que me auxiliasse era muito difícil. Dessa maneira, decidi fazer este curso exclusivo, para que você caro aluno, não passe pelo mesmo problema que tive.

Este curso tem o objetivo de introduzir o aluno ao mundo do Docker, de uma forma bem simples. Vamos entender pra que serve, como instala em Linux e Windows, os comandos básicos. Vamos explorar o Docker e Docker Compose. 

Com esses conhecimentos você vai poder construir um ambiente de desenvolvimento de uma forma muito simples e não vai ficar pra trás de ninguém na carreira.

Saiba que, fazendo este curso, você entra para a exclusiva e limitada Comunidade Alcatéia Dev, que tem como foco conhecimentos, cursos, conteúdos, organização do GitHub, grupo de discussão sobre a área de tecnologia e micro serviços.

E daí? Curtiu?

** Conceitos do curso:

1. Docker

2. Docker Compose;

3. Contêiner;



   
## Alcateia Dev

<img src="Transparente.png">

Link com todos os cursos e cupons: [http://www.alcateiadev.com.br/](http://www.alcateiadev.com.br/) <br>
Slack: https://alcateiadev.slack.com/


## Comandos



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
