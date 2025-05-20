# 🧹 Clean Architecture

Clean Architecture é um conjunto de princípios para organizar o código de forma que ele seja independente de frameworks, UI, banco de dados e agentes externos. O objetivo é criar sistemas flexíveis, testáveis e fáceis de manter.

---

## 📌 Princípios básicos

- **Independência de Frameworks:** O sistema não depende de bibliotecas específicas, facilitando mudanças.
- **Testabilidade:** A lógica de negócio é isolada, permitindo testes unitários simples.
- **UI Independente:** A interface do usuário pode ser alterada sem impactar a lógica do sistema.
- **Banco de Dados Independente:** Mudanças na tecnologia de armazenamento não afetam o domínio.
- **Separação de Responsabilidades:** Código dividido em camadas com responsabilidades claras.

---

## 🧱 Camadas da Clean Architecture

```
+-----------------------+
| UI / Interface | ← camada externa (ex: Web, Mobile)
+-----------------------+
| Application Layer | ← casos de uso, orquestração
+-----------------------+
| Domain Layer | ← regras de negócio e entidades
+-----------------------+
| Infrastructure | ← acesso a banco, frameworks, APIs externas
+-----------------------+
```

---

## 🔄 Fluxo de dependência

- As dependências sempre apontam para dentro (camadas internas).
- As camadas externas podem conhecer as internas, mas nunca o contrário.
- O domínio (regras de negócio) é o núcleo, totalmente isolado.

---

## 📚 Recursos úteis

- [Clean Architecture - Robert C. Martin (Uncle Bob)](https://8thlight.com/blog/uncle-bob/2012/08/13/the-clean-architecture.html)
- [Artigo explicativo - Alura](https://www.alura.com.br/artigos/clean-architecture-o-que-e-como-implementar)
- [Vídeo Clean Architecture - Rodrigo Branas (YouTube)](https://www.youtube.com/watch?v=Qv_hX6mK0RU)
- [Livro: Clean Architecture (Robert C. Martin)](https://www.amazon.com.br/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164)

---

> 💡 **Dica:** Aplique Clean Architecture para aumentar a longevidade e qualidade do seu código, principalmente em sistemas complexos e de longo prazo.


