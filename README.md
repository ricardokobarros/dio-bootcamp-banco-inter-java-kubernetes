<h2>Bootcamp Banco Inter Digital Innovation One: Rodando sua aplicação Java no Kubernetes. Do deploy ao debug sem medo! </h2>

Baseado no projeto [java-kubernetes](https://github.com/sandrogiacom/java-kubernetes.git)
Este projeto adiciona scripts para automatizar a criação de containers e implantar a aplicação usando kubernetes.

Para rodar a aplicação no docker:
```bash
chmod +x create create-docker-images
./create-docker-images
```
Para rodar a aplicação e implantar usando kubernetes:
```bash
chmod +x create deploy-kubernetes
./deploy-kubernetes
```

São necessários os seguintes pré-requisitos para a execução:

* Docker
* Java 15
* Maven 3.6
* Minikube
* Kubectl

Caso precise de ajuda para instalar as ferramentas [clique aqui](https://github.com/sandrogiacom/k8s)
