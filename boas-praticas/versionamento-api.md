# 📦 Versionamento de API

O versionamento de API é fundamental para garantir compatibilidade e evolução dos serviços sem interromper os consumidores existentes.

---

## 📌 Por que versionar sua API?

- Permite adicionar novas funcionalidades sem quebrar clientes antigos
- Facilita correções e melhorias sem impactos negativos
- Suporta coexistência de múltiplas versões da API
- Facilita comunicação clara com consumidores sobre mudanças

---

## 🧱 Estratégias comuns de versionamento

| Estratégia           | Descrição                                        | Exemplo                         |
|----------------------|-------------------------------------------------|--------------------------------|
| **URL Versioning**   | A versão é parte da URL da API                    | `/api/v1/users`                |
| **Header Versioning** | A versão é informada no cabeçalho da requisição  | `Accept: application/vnd.api.v1+json` |
| **Query Parameter**   | Versão informada como parâmetro na URL           | `/api/users?version=1`         |

---

## 🔧 Boas práticas para versionamento

- Use versionamento explícito para evitar ambiguidades
- Documente todas as versões ativas da API
- Mantenha versões antigas apenas pelo tempo necessário
- Evite mudanças breaking sem incremento da versão major
- Use semântica de versionamento (MAJOR.MINOR.PATCH) para comunicação clara
- Notifique consumidores sobre descontinuação de versões

---

## 📚 Recursos úteis

- [API Versioning - Microsoft Docs](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design#versioning)
- [REST API Versioning - Baeldung](https://www.baeldung.com/rest-versioning)
- [Best Practices for Versioning REST APIs - Nordic APIs](https://nordicapis.com/versioning-a-rest-api/)
- [Semver.org - Semantic Versioning](https://semver.org/)

---

> 💡 **Dica:** Planeje o versionamento desde o início do desenvolvimento da API para evitar retrabalho e problemas futuros.
