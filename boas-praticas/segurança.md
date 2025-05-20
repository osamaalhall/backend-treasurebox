# 🔒 Boas Práticas de Segurança no Desenvolvimento

Segurança é fundamental para proteger sistemas, dados e usuários. Adotar boas práticas desde o início do desenvolvimento evita vulnerabilidades e ataques.

---

## 📌 Princípios básicos de segurança

- **Confidencialidade:** Proteger dados contra acessos não autorizados.
- **Integridade:** Garantir que dados não sejam alterados indevidamente.
- **Disponibilidade:** Manter sistemas disponíveis para usuários legítimos.
- **Autenticação e Autorização:** Confirmar identidades e controlar acessos.
- **Princípio do menor privilégio:** Conceder apenas as permissões necessárias.

---

## 🧱 Boas práticas recomendadas

- Use HTTPS para comunicação segura (TLS/SSL)
- Armazene senhas com hashing forte (ex: bcrypt, Argon2)
- Valide e sanitize todas as entradas para evitar injeção de código (SQL, XSS)
- Use tokens seguros para autenticação (JWT, OAuth)
- Implemente políticas de CORS adequadas
- Atualize dependências e frameworks regularmente para corrigir vulnerabilidades
- Faça logs e monitore atividades suspeitas
- Proteja endpoints com rate limiting para evitar ataques DoS
- Utilize ferramentas de análise estática e testes de segurança

---

## 🔧 Segurança em APIs

- Autentique todas as requisições
- Limite o tamanho das requisições e o uso de recursos
- Utilize versionamento para evitar quebrar contratos
- Implemente mecanismos de throttling e caching seguros
- Documente e controle acessos via API Gateway ou proxies

---

## 📚 Recursos úteis

- [OWASP Top 10 - Principais vulnerabilidades web](https://owasp.org/www-project-top-ten/)
- [Guia de segurança para desenvolvedores - Mozilla](https://developer.mozilla.org/pt-BR/docs/Web/Security)
- [JWT Best Practices](https://jwt.io/introduction/)
- [Curso Segurança da Informação - Alura](https://www.alura.com.br/curso-online-seguranca-da-informacao)
- [Ferramentas de análise de vulnerabilidades - OWASP ZAP](https://www.zaproxy.org/)

---

> 💡 **Dica:** Segurança deve ser pensada desde o planejamento, incorporada ao processo de desenvolvimento e mantida continuamente.
