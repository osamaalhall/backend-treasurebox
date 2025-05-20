# ⚙️ Microserviços

Microserviços são uma abordagem arquitetural para desenvolver sistemas como um conjunto de serviços pequenos, independentes e focados em funcionalidades específicas, que se comunicam por APIs.

---

## 📌 Por que usar microserviços?

- Escalabilidade independente de cada serviço
- Implantação contínua e atualizações isoladas
- Melhor isolamento de falhas (um serviço não derruba o sistema todo)
- Times organizados por domínio de negócio
- Flexibilidade para usar diferentes tecnologias em cada serviço

---

## 🧱 Características principais

- Serviços pequenos e focados em uma única responsabilidade
- Comunicação via APIs REST, RPC ou mensageria (ex: Kafka, RabbitMQ)
- Banco de dados desacoplados (cada serviço pode ter seu próprio banco)
- Deploy independente e isolado
- Monitoramento e logging distribuídos

---

## 🔧 Desafios comuns

- Complexidade na gestão e orquestração dos serviços
- Comunicação entre serviços (latência e tolerância a falhas)
- Consistência eventual dos dados
- Testes e depuração distribuídos
- Segurança e autenticação distribuídas

---

## 📚 Recursos úteis

- [Microservices.io - Martin Fowler](https://microservices.io/)
- [Documentação oficial do Spring Cloud](https://spring.io/projects/spring-cloud)
- [Microservices Architecture - AWS](https://aws.amazon.com/microservices/)
- [Curso Microservices - Udemy](https://www.udemy.com/course/microservices-with-spring-boot/)
- [Microservices Patterns - Chris Richardson (livro)](https://microservices.io/patterns/index.html)

---

> 💡 **Dica:** Utilize ferramentas como Docker, Kubernetes e API Gateway para gerenciar seus microserviços de forma eficiente.
