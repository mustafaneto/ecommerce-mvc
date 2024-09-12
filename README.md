# Ecommerce MVC

Este é um projeto de exemplo utilizando Node.js com o padrão de arquitetura MVC, que está configurado para ser executado em um container Docker.

## Requisitos

Certifique-se de ter os seguintes itens instalados em sua máquina antes de executar o projeto:

- [Docker](https://www.docker.com/get-started)

## Instruções para executar o projeto com Docker

Siga os passos abaixo para construir e executar o projeto utilizando Docker.

### 1. Clonar o repositório

```
git clone https://github.com/mustafaneto/ecommerce-mvc.git
cd ecommerce-mvc
```

### 2. Construir a imagem Docker

```
docker build -t mustafaneto/ecommerce-mvc .
```

### 3. Executar o container

```
docker run -p 3000:3000 mustafaneto/ecommerce-mvc:latest
```

### 4. Acessar o aplicativo

```
http://localhost:3000
```

### 5. Parar o container

Se precisar parar o container, pressione CTRL + C no terminal onde o container está sendo executado.







