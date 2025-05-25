# ✅ To-Do List Profissional com Autenticação, CRUD e SQL

Aplicação web para gerenciamento de tarefas com autenticação segura, interface moderna e banco de dados relacional.

## 🚀 Tecnologias Utilizadas
- **Frontend**: React + Tailwind CSS
- **Backend**: Node.js + Express
- **Banco de Dados**: PostgreSQL
- **ORM**: Prisma
- **Autenticação**: JWT + Bcrypt
- **Deploy**: Vercel (Frontend) + Railway (Backend e Banco)

## 🔐 Funcionalidades
- Cadastro e login de usuários
- CRUD completo de tarefas (Criar, Ler, Atualizar, Excluir)
- Interface moderna e responsiva
- Filtros de tarefas
- Logout e proteção de rotas

## 📦 Instalação Local

### Backend
```bash
cd server
npm install
npx prisma migrate dev --name init
npm start
```

### Frontend
```bash
cd client
npm install
npm run dev
```

## 🖼️ Tela de Exemplo
![Dashboard](./assets/dashboard.png)

## 📄 Licença
MIT License
