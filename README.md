# docker-cloud-evolution
Implementação de estrutura de microsserviços com Docker Compose, Nginx e Redis. Foco em portabilidade e independência de infraestrutura.

#  Docker Microservices Stack - Cloud Ready
Este projeto demonstra a implementação de uma arquitetura de microsserviços utilizando **Docker** e **Docker Compose**, seguindo as melhores práticas de isolamento e escalabilidade.

## Arquitetura do Projeto completo
A stack é composta por três camadas principais:
1. **Proxy Reverso (Nginx):** Gerencia o tráfego de entrada e distribui para os serviços.
2. **Application Layer (Node.js):** Microsserviço responsável pela lógica de negócio.
3. **Data Layer (Redis):** Armazenamento de dados em memória para alta performance.

## Tecnologias utilizadas 
* **Docker & Docker Compose**
* **Nginx**
* **Redis**
* **Cloud Principles (AWS Ready)**

## Como Rodar o progama 
Certifique-se de ter o Docker instalado e execute:
```bash
docker-compose up -d
