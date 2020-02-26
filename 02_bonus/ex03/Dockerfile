#installing fotune a program that dispays psedorandom messsage from a database

FROM debian

RUN apt-get update && apt-get upgrade -y && apt-get install -y cowsay fortune lolcat

ENTRYPOINT /usr/games/fortune | /usr/games/cowsay | /usr/games/lolcat
 
