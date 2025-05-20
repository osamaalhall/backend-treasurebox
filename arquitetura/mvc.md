# 🏗️ Arquitetura MVC (Model-View-Controller)

O padrão **MVC** é uma arquitetura amplamente usada no desenvolvimento de software para organizar aplicações em três componentes principais: Model, View e Controller. Isso ajuda a separar responsabilidades, facilitar manutenção e permitir escalabilidade.

---

## 📌 Componentes do MVC

| Componente | Função                                                      |
|------------|-------------------------------------------------------------|
| **Model**  | Representa os dados e a lógica de negócio da aplicação.     |
| **View**   | Responsável pela interface e apresentação dos dados.        |
| **Controller** | Recebe as entradas do usuário, processa e interage com Model e View. |

---

## 🧱 Como funciona o fluxo MVC

1. O usuário interage com a **View** (ex: clica em um botão).
2. A **View** envia a ação para o **Controller**.
3. O **Controller** processa a ação, atualiza o **Model** se necessário.
4. O **Model** notifica a **View** sobre as mudanças nos dados.
5. A **View** atualiza a interface para refletir o novo estado.

---

## 🔧 Benefícios do MVC

- Separação clara de responsabilidades
- Facilita testes e manutenção
- Permite equipes trabalharem em paralelo (front-end e back-end)
- Reutilização e modularidade de componentes

---

## 📚 Recursos úteis

- [Padrão MVC - Wikipédia](https://pt.wikipedia.org/wiki/Modelo-visão-controlador)
- [Tutorial MVC - MDN](https://developer.mozilla.org/pt-BR/docs/Glossary/MVC)
- [Entendendo MVC - Alura](https://www.alura.com.br/artigos/arquitetura-mvc-na-pratica)
- [Curso MVC - YouTube (Programação Dinâmica)](https://www.youtube.com/watch?v=1i4y_1LKNLY)

---

> 💡 **Dica:** Muitos frameworks seguem MVC ou variações dele, como Ruby on Rails, ASP.NET MVC, Laravel, e Spring MVC.
