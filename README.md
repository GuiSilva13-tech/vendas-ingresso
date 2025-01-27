Sistema de vendas de ingressos

## Requerimentos

- Node.js 20+
- Docker



### Docker

Dependendo do seu sistema operacional, você tem 2 opções para instalar o Docker:

- [Docker Desktop] - Interface gráfica para gerenciar e usar o Docker.
- [Docker Engine] - Apenas a engine do Docker, sem interface gráfica, chamado de Docker Nativo.

Se você tem 8GB ou menos de memória RAM, recomendamos o uso do Docker Engine, pois a interface gráfica do Docker Desktop + a execução dos containers pode consumir praticamente a memória da máquina, caso contrário usar o Docker Desktop é mais prático.

## Rodar a aplicação

Rode a aplicação:

```bash
npm install
```

```
npx nodemon
```

Use o arquivo `api.http` para testar a API. Você pode usar a extensão REST Client no VSCode para fazer isso.


## Requisitos do sistema

Leia o arquivo [requisitos-sistema.md](./requisitos-sistema.md) para entender o escopo do sistema.

## Sugestão de livros

* [Clean Code](https://www.amazon.com.br/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
* [Clean Architecture](https://www.amazon.com.br/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164)
* [Patterns of Enterprise Application Architecture](https://www.amazon.com.br/Patterns-Enterprise-Application-Architecture-Martin/dp/0321127420)
