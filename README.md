# simple-finance
Your personal financial manager

Um gerenciador financeiro pessoal desenvolvido para tornar o controle das finanças mais simples, visual e agradável.

Ele te ajuda a responder a pergunta: Para onde está indo o meu dinheiro?
E te auxilia a organizar sua vida financeira de um jeito simples e fácil!

# MVP
A primeira versão do Simple Finance contempla:
- Cadastro e autenticação de usuários
- Receitas
- Despesas
- Saldo
- Fechamento mensal
- Dashboard financeiro
- Maiores gastos
- Usuários com dados independentes
  
### Frontend
- React
- Vite
- TypeScript
- Axios

### Backend
- Node.js
- Express
- TypeScript
- MVC

### Banco de dados
- PostgreSQL
- Prisma ORM

### Autenticação e segurança
- JWT
- OAuth / Google Login
- Hash de senhas
- Controle de acesso

### Qualidade
- Testes automatizados
- Testes de API
- Testes funcionais
- Validação de regras de negócio

  ## ⚙️ Como executar

### Pré-requisitos

- Node.js
- npm
- PostgreSQL
- Git

### Clone o projeto

```bash
git clone <repository-url>
cd simple-finance

### Backend
cd backend
npm install

Configure o arquivo .env:
DATABASE_URL=
JWT_SECRET=
GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

Execute as migrations:
npx prisma migrate dev

Inicie o servidor:
npm run dev

### Frontend
cd frontend
npm install
npm run dev
