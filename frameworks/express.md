# 🚂 Express.js

[Express.js](https://expressjs.com/) é o framework web mais popular para Node.js, conhecido pela sua simplicidade, flexibilidade e performance. Ideal para criar APIs REST, servidores e aplicações web rápidas.

---

## 📌 Por que usar Express?

- Minimalista e altamente customizável
- Fácil integração com middlewares
- Ampla comunidade e suporte
- Compatível com todo o ecossistema Node.js
- Ideal para microserviços e aplicações pequenas a médias

---

## 🧱 Estrutura comum de um projeto Express

meu-projeto/
├── node_modules/
├── src/
│ ├── controllers/
│ ├── routes/
│ ├── models/
│ └── app.js
├── .env
├── package.json
└── server.js


---

## 🔧 Principais recursos

- Roteamento simples e intuitivo
- Middleware para manipular requisições e respostas
- Suporte para templates (Pug, EJS, Handlebars)
- Suporte para REST APIs e WebSockets

---

## ✅ Exemplo básico

```js
const express = require('express');
const app = express();

app.use(express.json());

app.get('/', (req, res) => {
  res.send('API funcionando!');
});

app.listen(3000, () => {
  console.log('Servidor rodando na porta 3000');
});
```
---

## 📚 Recursos úteis

- [Documentação oficial Express](https://expressjs.com/)
- [Express.js Guide - MDN](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs)
- [Curso Node + Express (YouTube)](https://www.youtube.com/watch?v=Oe421EPjeBE)

---

> 💡 **Dica:** Combine Express com bancos de dados como MongoDB (via Mongoose) ou PostgreSQL (via Sequelize/Knex) para construir aplicações completas.
