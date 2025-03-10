# 📌 Microserviços com Docker e Adminer

Este projeto configura três microserviços, cada um conectado ao seu próprio banco de dados, usando Docker e Docker Compose. O sistema também inclui **Adminer**, uma ferramenta web para gerenciamento de bancos de dados.

## 1️⃣ Pré-requisitos
Certifique-se de ter o **Docker** e o **Docker Compose** instalados.

- Instalar Docker: https://docs.docker.com/get-docker/
- Instalar Docker Compose: https://docs.docker.com/compose/install/

## 2️⃣ Executando o projeto
Para iniciar todos os serviços, execute:
```sh
docker-compose up -d --build
```
Isso criará as imagens e iniciará todos os containers no modo em segundo plano (`-d`).

## 3️⃣ Acessando os serviços
- Microserviço 1 → http://localhost:8001
- Microserviço 2 → http://localhost:8002
- Microserviço 3 → http://localhost:8003
- Adminer (Interface do Banco de Dados) → http://localhost:8080

## 4️⃣ Credenciais dos Bancos de Dados
Use estas credenciais para acessar o **Adminer**:

PostgreSQL (db1 & db3)
- Sistema: PostgreSQL
- Servidor: db1 ou db3
- Usuário: user1 / user3
- Senha: password1 / password3
- Banco de Dados: db1 / db3

MySQL (db2)
- Sistema: MySQL
- Servidor: db2
- Usuário: user2
- Senha: password2
- Banco de Dados: db2

