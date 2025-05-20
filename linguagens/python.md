# 🐍 Python para Back-End

Python é uma linguagem poderosa, simples e muito usada no desenvolvimento de aplicações back-end. Seu ecossistema é rico em frameworks, bibliotecas e ferramentas que facilitam a construção de APIs e sistemas robustos.

---

## 📌 Por que usar Python no Back-End?

- Sintaxe limpa e fácil de aprender
- Grande comunidade e documentação
- Frameworks maduros como Django e FastAPI
- Compatível com bancos de dados SQL e NoSQL
- Suporte a testes, segurança, autenticação, background tasks, etc.

---

## 🚀 Frameworks Populares

| Framework | Descrição |
|----------|-----------|
| [Django](https://www.djangoproject.com/) | Framework completo e baterias inclusas. Ideal para apps robustos. |
| [Flask](https://flask.palletsprojects.com/) | Minimalista e flexível. Ótimo para microserviços e APIs leves. |
| [FastAPI](https://fastapi.tiangolo.com/) | Moderno, rápido e com suporte a tipagem. Excelente para APIs modernas. |

---

## 🧱 Estrutura comum de um projeto

```
meu_projeto/
├── app/
│ ├── init.py
│ ├── models.py
│ ├── routes.py
│ └── services.py
├── tests/
│ └── test_app.py
├── requirements.txt
└── main.py
```

---

## 🧰 Ferramentas e Bibliotecas Úteis

- **ORMs**: [SQLAlchemy](https://www.sqlalchemy.org/), [Tortoise ORM](https://tortoise.github.io/)
- **Autenticação**: [OAuthLib](https://oauthlib.readthedocs.io/), [Authlib](https://docs.authlib.org/)
- **Testes**: [Pytest](https://docs.pytest.org/), [unittest](https://docs.python.org/3/library/unittest.html)
- **Env vars**: [python-decouple](https://github.com/henriquebastos/python-decouple)
- **Documentação de API**: OpenAPI via FastAPI ou Swagger via Django REST Framework

---

## 🎓 Conteúdos Recomendados

### Tutoriais

- [Guia oficial Django (pt-BR)](https://docs.djangoproject.com/pt-br/stable/intro/)
- [FastAPI passo a passo](https://fastapi.tiangolo.com/tutorial/)
- [Flask Mega-Tutorial (en)](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)

### Cursos

- [Python para Web (Alura)](https://www.alura.com.br/)
- [CS50 Web com Python (edX)](https://cs50.harvard.edu/web/2020/)
- [Django REST Framework (Udemy)](https://www.udemy.com/course/django-rest-framework/)

---

## 📚 Livros

- *Two Scoops of Django* – Audrey Roy Greenfeld
- *Fluent Python* – Luciano Ramalho
- *Python Tricks* – Dan Bader

---

## ✅ Checklist para projetos em produção

- [ ] Utilizar `.env` para variáveis sensíveis
- [ ] Usar logging em vez de `print()`
- [ ] Incluir testes automatizados
- [ ] Proteger rotas com autenticação/autorização
- [ ] Fazer deploy seguro (Docker, CI/CD, etc.)

---

> 🧠 Dica: comece pequeno com Flask ou FastAPI para entender o fluxo back-end, depois evolua para Django se precisar de uma estrutura mais robusta.

