# ⚡ FastAPI

[FastAPI](https://fastapi.tiangolo.com/) é um framework moderno, rápido (high-performance) para construir APIs com Python 3.7+ baseado em padrões modernos como type hints do Python, com foco em desempenho e produtividade.

---

## 📌 Por que usar FastAPI?

- Muito rápido (baseado em Starlette e Pydantic)
- Validação automática de dados com base em tipos Python
- Geração automática de documentação interativa (Swagger UI e ReDoc)
- Suporte nativo a async/await para alta performance
- Fácil integração com OAuth2, JWT, CORS e outras tecnologias
- Ótima experiência de desenvolvimento e testes

---

## 🧱 Estrutura comum de projeto FastAPI

```
meu_projeto/
├── main.py
├── app/
│ ├── api/
│ │ ├── endpoints/
│ │ └── dependencies.py
│ ├── core/
│ ├── models/
│ ├── schemas/
│ └── services/
├── requirements.txt
└── Dockerfile
```

---

## ✅ Exemplo básico

```python
from fastapi import FastAPI

app = FastAPI()

@app.get("/")
async def root():
    return {"message": "API funcionando com FastAPI!"}
```

---

## 📚 Recursos úteis

- [Documentação oficial FastAPI](https://fastapi.tiangolo.com/)
- [FastAPI Tutorial (YouTube) - CodeWithHarry](https://www.youtube.com/watch?v=7t2alSnE2-I)
- [Awesome FastAPI (repositório GitHub)](https://github.com/mjhea0/awesome-fastapi)
- [FastAPI + Docker - Tutorial Completo](https://testdriven.io/blog/fastapi-docker-traefik/)

---

> 💡 **Dica:** Use o suporte embutido ao OpenAPI para testar suas APIs diretamente pelo navegador.
