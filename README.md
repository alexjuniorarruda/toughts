# Toughts
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/alexjuniorarruda/Accounts/blob/main/LICENSE)

 Esse projeto permite gerenciar pensamentos, nele é possível criar um usuário e com esse usuário nós conseguimos gerenciar pensamentos, onde podemos realizar as operações de CRUD, foi 
 feito utilizando a arquitetura MVC. 
 
 Esse projeto foi feito a partir do Curso de Node.js do Matheus Battisti do Hora de Codar dentro da plataforma da Udemy.

 # Imagens do projeto

 ## Home
 ![Home](https://github.com/alexjuniorarruda/toughts/assets/112874423/baab5e1b-4594-49fb-aec0-ebe6e3a2af87)

 ## Login
 ![Login](https://github.com/alexjuniorarruda/toughts/assets/112874423/3304c58a-fbb9-4120-bef5-5797cd51b845)

 ## Cadastro de Usuário
 ![Registrar usuário](https://github.com/alexjuniorarruda/toughts/assets/112874423/b17a1ceb-cde9-461e-be9c-b0517739022d)

 ## Confirmação do cadastro do usuário ou login
 ![Confirmação Autenticação](https://github.com/alexjuniorarruda/toughts/assets/112874423/0a2600e8-df52-44c4-8ac5-75c328aa9d08)

 ## Dashboard
 ![Dashboard pensamentos](https://github.com/alexjuniorarruda/toughts/assets/112874423/07b1f740-e6d8-428b-91c3-7b613a9c139d)

 ## Criando pensamento
 ![Criando pensamentos](https://github.com/alexjuniorarruda/toughts/assets/112874423/03fe0a9f-f70b-4b1a-b4d7-05f69f376a43)

 ## Confimação pensamento criado
 ![Confirmação criação pensamentos](https://github.com/alexjuniorarruda/toughts/assets/112874423/f690c421-9185-4b75-8f22-325dbeb53505)

 ## Atualizando pensamento
 ![Editando pensamentos](https://github.com/alexjuniorarruda/toughts/assets/112874423/ebbf7df0-4b3a-489a-856c-0d6b84ca7918)

 ## Confirmação pensamento atualizado
 ![Confirmação atualização de pensamentos](https://github.com/alexjuniorarruda/toughts/assets/112874423/442f7804-9c05-4a56-98e5-a1446714ff75)

 ## Excluindo pensamento
 ![Confirmação exclusão de pensamentos](https://github.com/alexjuniorarruda/toughts/assets/112874423/00cdc2b1-bbcf-4522-a4b0-c8e3205d4544)


# Tecnologias utilizadas
## Back-end
- JavaScript
- Node.js

## Front-end
- HTML
- CSS

## Dependências
- bcryptjs
- connect-flash
- cookie-parser 
- cookie-session 
- dotenv 
- express 
- express-flash 
- express-handlebars 
- express-session 
- mysql 
- sequelize 
- session-file-store
- nodemon
- sequelize-cli

## Dependências e Versões Necessárias
- Pré-requisitos: Node.js e NPM

## Como rodar o projeto ✅

- Fazer download do repositório
- Abrir o projeto no terminal
- Instalar as dependencias com o comando
  
```
npm install
```

- criar o arquivo .env na raiz do projeto e colocar as sequintes informações (DB_USER, DB_PASSWORD e DB_HOST fica a critério)
  
```
DB_NAME=toughts
DB_USER=root
DB_PASSWORD=root
DB_HOST=localhost
```

- Criar o banco de dados com o comando
  
```
npx sequelize-cli db:create
```

- Executar o projeto
  
```
npm start
```

# Autor

Alex Junior Arruda

https://www.linkedin.com/in/alex-jr-arruda/
