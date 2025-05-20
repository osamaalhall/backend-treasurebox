# 🌱 Spring Boot

[Spring Boot](https://spring.io/projects/spring-boot) é um framework baseado no ecossistema Spring que simplifica a criação de aplicações Java modernas, especialmente APIs REST e microsserviços, com configuração mínima e muita produtividade.

---

## 📌 Por que usar Spring Boot?

- Configuração automática e rápida inicialização
- Baseado em padrões e boas práticas do Java Enterprise
- Suporte nativo a segurança, bancos de dados, mensageria e mais
- Comunidade gigante e muito material de aprendizado
- Fácil integração com containers (Docker, Kubernetes)

---

## 🧱 Estrutura comum de um projeto Spring Boot

meu-projeto/
├── src/
│ └── main/
│ ├── java/
│ │ └── com/
│ │ └── exemplo/
│ │ ├── controller/
│ │ ├── service/
│ │ ├── repository/
│ │ └── Application.java
│ └── resources/
│ ├── application.properties
│ └── static/
├── pom.xml


---

## ✅ Exemplo básico de Controller REST

```java
@RestController
@RequestMapping("/api")
public class HelloController {

    @GetMapping("/hello")
    public String hello() {
        return "Olá, Spring Boot!";
    }
}
```
---

## 📚 Recursos úteis

- [Documentação oficial Spring Boot](https://spring.io/projects/spring-boot)
- [Guia Spring Boot - Baeldung](https://www.baeldung.com/spring-boot)
- [Spring Boot Tutorials - Java Brains (YouTube)](https://www.youtube.com/playlist?list=PLqq-6Pq4lTTanfgsbnFzfWUhhAz3tIezU)
- [Curso Spring Boot - Alura](https://www.alura.com.br/curso-online-spring-boot)

---

> 💡 **Dica:** Use o [Spring Initializr](https://start.spring.io/) para criar projetos Spring Boot configurados automaticamente.
