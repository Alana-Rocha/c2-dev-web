# 📦 Como Inicializar o Projeto

Siga os passos abaixo para rodar o projeto localmente:

## 1. Instale as dependências

No terminal, dentro da pasta raiz do projeto, execute:

```bash
yarn

## 2. Crie o arquivo `.env`

Na raiz do projeto, crie um arquivo `.env` e adicione a seguinte variável de ambiente:

```env
DATABASE_URL="file:./dev.db"

## 3. Gere o Prisma Client
Com o ambiente configurado, execute o seguinte comando para gerar o client do Prisma:
npx prisma generate

## 4. Inicie o servidor
yarn dev