# ☀️ Ecossistema Energia

Sistema completo de gestão para empresas do setor de energia solar, com foco em eficiência, integração de dados, usabilidade e escalabilidade. Idealizado e desenvolvido por Gabriela Rodrigues e equipe, esse ecossistema unifica operações administrativas, comerciais e financeiras com segurança e inteligência.

---

## 🚀 Funcionalidades
- Cadastro e gerenciamento de usuários com permissões personalizadas
- Visualização e análise de indicadores financeiros
- Cadastro e controle de usinas
- Painel administrativo moderno e responsivo
- Dashboard financeiro com gráficos em tempo real
- Integração futura com APIs bancárias (ex: Sicoob, Inter)
- Arquitetura preparada para GraphQL e microserviços

---

## 🛠️ Tecnologias Utilizadas
### Backend
- Node.js + Express
- MongoDB (local e Atlas)
- GraphQL (`queries.gql`, `mutations.gql`, `schema.gql`)
- Autenticação com JWT

### Frontend
- React + React Router + Axios
- Bootstrap (SB Admin 2)
- Recharts para visualização de dados
- Controle de permissões dinâmico com `PermissaoRoute`

---

## 🧭 Estrutura do Projeto
```
/ecossistema-energia-backend
  ├── routes/
  ├── models/
  ├── controllers/
  ├── .env
  └── server.js

/ecossistema-energia-frontend
  ├── src/pages/
  ├── src/components/
  ├── src/services/
  └── .env
```

---

## 🔧 Como rodar localmente
### Backend
```bash
cd ecossistema-energia-backend
npm install
npm start
```
Crie um `.env` com:
```env
MONGO_URI=mongodb://127.0.0.1:27017/ecossistemaEnergia
PORT=5000
```

### Frontend
```bash
cd ecossistema-energia-frontend
npm install
npm start
```
Crie um `.env` com:
```env
REACT_APP_API_URL=http://localhost:5000/api
```

---

## 🌐 Deploy
- Backend: [Render](https://render.com/)
- Frontend: em andamento (Vercel ou Netlify)

---

## 📈 Futuras Integrações
- APIs bancárias (Sicoob, Inter)
- Webhooks para automações e notificações
- Painel de indicadores para diretoria e investidores

---

## 👩‍💻 Autoria
Desenvolvido por [Gabriela Rodrigues](https://github.com/ganadunny13) com foco em acessibilidade, sustentabilidade e inovação digital. 💚

---

## 📜 Licença
Projeto privado. Para uso comercial ou adaptação, entre em contato.
