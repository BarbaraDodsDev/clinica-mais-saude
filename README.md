# Clínica Mais Saúde 🏥

Sistema web de agendamento médico com autenticação de usuários. Projeto full stack simulado em formato PJ, desenvolvido com foco em usabilidade, integração e escalabilidade.

## 🔧 Tecnologias Utilizadas

- **Front-end:** React, React Router, Tailwind CSS
- **Back-end:** Node.js, Express
- **Banco de Dados:** MongoDB (com Mongoose)
- **Outros:** JWT, Nodemailer, dotenv

## ✨ Funcionalidades

- Cadastro e login de usuários com diferentes perfis (paciente, médico, administrador)
- CRUD de pacientes, médicos e consultas
- Confirmação de consultas por e-mail
- Painel administrativo
- Responsividade mobile-first
- Middleware de autenticação com JWT

## 📸 Demonstrações (opcional)

![Tela de login](./assets/login.png)
![Dashboard](./assets/dashboard.png)

## 🚀 Como Executar

```bash
# Clone o repositório
git clone https://github.com/seuusuario/clinica-mais-saude

# Back-end
cd clinica-mais-saude/backend
npm install
npm run dev

# Front-end
cd ../frontend
npm install
npm start
