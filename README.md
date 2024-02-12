# Configure DNS server using BIND9 in Docker SWARM

# O que o projeto faz?

É um laboratório de estudos e prática para aqueles que estão aprendendo a trabalhar com soluções DevOps.

# Por que o projeto é útil?

Ele me foi útil para colocar em prática os ensinamentos do Caio Delgado: https://github.com/caiodelgadonew/docker-dca

# Como os usuários podem começar a usar o projeto?

1 - Preparar o ambiente, recomendo o curso do Caio Delgado sobre o Vagrant: https://youtu.be/PX6OmeIbjC4

2 - Clonar este repositório. Se ficar com dúvidas recomendo o vídeo do Christian Lempa: https://www.youtube.com/watch?v=syzwLwE3Xq4&t=524s

3 - Implementar o SWARM, segue um dos links que usei, do Bob Cares: https://bobcares.com/blog/install-docker-swarm-cluster-on-debian-10/

4 - Executar o comando abaixo para implantar o container DNS:

docker stack deploy --compose-file=docker-compose.yml srvdns00 

5 - Executar os testes de conexão usando o comando "nslookup":

nslookup registro.br 172.16.0.203

# Onde os usuários podem obter ajuda com seu projeto?

Caso tenham dúvidas que não estejam documentadas podem me contactar: devops@sso.dev.br

# Quem mantém e contribui com o projeto?

Por enquanto é um projeto solo, surgindo parceria eu adiciono depois.
