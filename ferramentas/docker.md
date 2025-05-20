# 🐳 Docker

Docker é uma plataforma de containerização que permite empacotar aplicações e suas dependências em containers leves, portáteis e consistentes, facilitando o desenvolvimento, deploy e escalabilidade.

---

## 📌 Por que usar Docker?

- Isolamento do ambiente de execução
- Facilita a portabilidade entre diferentes máquinas e ambientes
- Agiliza o processo de desenvolvimento e deploy
- Compatibilidade com CI/CD
- Permite escalabilidade com orquestradores como Kubernetes

---

## 🧱 Conceitos básicos

- **Imagem:** Snapshot imutável da aplicação e suas dependências
- **Container:** Instância em execução de uma imagem
- **Dockerfile:** Arquivo de configuração para construir imagens Docker
- **Docker Hub:** Registro público para armazenar imagens Docker
- **Volumes:** Para persistência de dados fora do container

---

## 🔧 Comandos essenciais

| Comando                | Descrição                             |
|------------------------|-------------------------------------|
| `docker build`         | Construir uma imagem a partir do Dockerfile |
| `docker run`           | Executar um container               |
| `docker ps`            | Listar containers em execução       |
| `docker stop`          | Parar um container                  |
| `docker pull`          | Baixar uma imagem do Docker Hub     |
| `docker push`          | Enviar uma imagem para o Docker Hub |

---

## 📚 Recursos úteis

- [Documentação oficial Docker](https://docs.docker.com/)
- [Docker Tutorial for Beginners - freeCodeCamp (YouTube)](https://www.youtube.com/watch?v=fqMOX6JJhGo)
- [Docker para desenvolvedores - Alura](https://www.alura.com.br/curso-online-docker)
- [Play with Docker - ambiente interativo online](https://labs.play-with-docker.com/)
- [Livro: Docker Deep Dive - Nigel Poulton](https://www.nigelpoulton.com/books/)

---

> 💡 **Dica:** Sempre utilize `.dockerignore` para evitar copiar arquivos desnecessários para a imagem e reduzir o tamanho final.
