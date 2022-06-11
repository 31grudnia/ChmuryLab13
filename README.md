# ChmuryLab13
Docker-Swarm 

**// Inicjalizacja węzła**

docker swarm init 

**// Uruchomienie klastra**

docker stack deploy --compose-file docker_stack.yml swarm 



**Wnioski:** Dzięki swojej budowie Docker Swarm potrafi eliminować pojedyncze punkty awarii. 
Skalowanie usługi pozwala na uruchomienie dowolnej liczby ‘tasków’. 
