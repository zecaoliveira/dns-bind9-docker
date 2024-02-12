# EN

# Configure DNS server using BIND9 in Docker SWARM

- What does the project do?

It is a study and practice laboratory for those who are learning to work with DevOps solutions.

- Why is the project useful?

It was useful for me to put Caio Delgado's teachings into practice: https://github.com/caiodelgadonew/docker-dca

- How can users start using the project?

1 - Prepare the environment, I recommend Caio Delgado's course on Vagrant: https://youtu.be/PX6OmeIbjC4

2 - Clone this repository. If you have any doubts, I recommend Christian Lempa's video: https://www.youtube.com/watch?v=syzwLwE3Xq4&t=524s

3 - Implement SWARM, here is one of the links I used, from Bob Cares: https://bobcares.com/blog/install-docker-swarm-cluster-on-debian-10/

4 - Run the command below to deploy the DNS container:

Source: https://blog.4linux.com.br/docker-swarm-criando-cluster-utilizando-docker-stack-deploy/

docker stack deploy --compose-file=docker-compose.yml srvdns00

5 - Run connection tests using the "nslookup" command:

nslookup Registro.br 172.16.0.203

- Where can users get help with their project?

If you have questions that are not documented, you can contact me: devops@sso.dev.br

- Who maintains and contributes to the project?

For now it's a solo project, with a partnership coming up I'll add it later.

############################################################################################################

# PT-BR

# Configurar servidor DNS usando BIND9 no Docker SWARM

- O que o projeto faz?

É um laboratório de estudos e prática para aqueles que estão aprendendo a trabalhar com soluções DevOps.

- Por que o projeto é útil?

Ele me foi útil para colocar em prática os ensinamentos do Caio Delgado: https://github.com/caiodelgadonew/docker-dca

- Como os usuários podem começar a usar o projeto?

1 - Preparar o ambiente, recomendo o curso do Caio Delgado sobre o Vagrant: https://youtu.be/PX6OmeIbjC4

2 - Clonar este repositório. Se ficar com dúvidas recomendo o vídeo do Christian Lempa: https://www.youtube.com/watch?v=syzwLwE3Xq4&t=524s

3 - Implementar o SWARM, segue um dos links que usei, do Bob Cares: https://bobcares.com/blog/install-docker-swarm-cluster-on-debian-10/

4 - Executar o comando abaixo para implantar o container DNS:

Fonte: https://blog.4linux.com.br/docker-swarm-criando-cluster-utilizando-docker-stack-deploy/

docker stack deploy --compose-file=docker-compose.yml srvdns00 

5 - Executar os testes de conexão usando o comando "nslookup":

nslookup registro.br 172.16.0.203

- Onde os usuários podem obter ajuda com seu projeto?

Caso tenham dúvidas que não estejam documentadas podem me contactar: devops@sso.dev.br

- Quem mantém e contribui com o projeto?

Por enquanto é um projeto solo, surgindo parceria eu adiciono depois.
