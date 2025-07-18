# Debuguei Barber 💈

Sistema completo para agendamento de horários em barbearias, desenvolvido com foco em performance, escalabilidade e experiência do usuário.
 <!-- Substitua ou remova se não houver imagem -->

---

## 🚀 Tecnologias

Este projeto foi desenvolvido com as seguintes tecnologias:

- **Next.js + React + TypeScript**
- **Tailwind CSS**
- **Prisma ORM**
- **PostgreSQL (NeonDB ou Docker)**
- **NextAuth.js** (Autenticação com Google)
- **Zod, React Hook Form**
- **Husky, ESLint, ts-node, dotenv**

---

## 🔧 Funcionalidades

- Login com Google (NextAuth)
- CRUD de serviços
- Cadastro de barbearias
- Seleção de horários disponíveis
- Painel administrativo
- Banco de dados PostgreSQL via Prisma
- Deploy com Vercel

---

## 🛠️ Como rodar localmente

```bash
# Clone o projeto
git clone https://github.com/alexsantos-djesus/Debuguei-Barber.git
cd Debuguei-Barber

# Instale as dependências
npm install

# Configure as variáveis de ambiente
cp .env.example .env

# Execute as migrações (após configurar o banco)
npx prisma migrate dev

# Inicie o servidor
npm run dev
