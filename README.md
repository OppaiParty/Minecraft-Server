#How to use

##For GitHub

~~~bash
$ git clone https://github.com/OppaiParty/Minecraft-Server.git ~/Desktop/Minecraft-Server && cd ~/Desktop/Minecraft-Server
$ docker build it minecraft && docker run -p 25565:25565 minecraft
~~~
or
~~~bash
$ git clone https://github.com/OppaiParty/Minecraft-Server.git ~/Desktop/Minecraft-Server && ~/Desktop/Minecraft-Server/start.sh
~~~
**Wait 10minutes**

##For DockerHub

[DockerHub](https://hub.docker.com/r/jpnlavender/spigot-minecraft-server/)

~~~bash
$ docker run -p 25565:25565 --name mine-server jpnlavender/spigot-minecraft-server
~~~

#How to Use CraftBukkit Plugin

~~~
.
├── Dockerfile
├── README.md
├── docker-compose.yml
└── plugins <----- Put a jar file here
    ├── hoge.jar
    └── fuga.jar
~~~
