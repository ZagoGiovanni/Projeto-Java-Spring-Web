<h1 align="center">Lista de Tarefas - Aplicação Web</h1>
<p align="center">Interface web para o sistema de gerenciamento de tarefas (To-Do List), desenvolvida com Angular.</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-21-blue?style=for-the-badge&logo=java" alt="Java 21">
  <img src="https://img.shields.io/badge/Spring_Boot-3-success?style=for-the-badge&logo=spring" alt="Spring Boot 3">
  <img src="https://img.shields.io/badge/Maven-4-red?style=for-the-badge&logo=apache-maven" alt="Maven">
  <img src="https://img.shields.io/badge/PostgreSQL-16-blue?style=for-the-badge&logo=postgresql" alt="PostgreSQL">
</p>

<details>
  <summary><strong>📝 Sobre o Projeto</strong></summary>
  <br>
  Esta é a interface de usuário (Frontend) da aplicação "Lista de Tarefas". Ela consome a API REST para fornecer uma experiência interativa, permitindo que o usuário gerencie suas tarefas de forma visual e intuitiva.

  O projeto foi desenvolvido seguindo o tutorial "Projeto Aplicação Full Stack" do professor Ricardo Tec.
</details>

## 🏛️ Arquitetura da Solução

Este projeto corresponde à API (Backend) da aplicação "Lista de Tarefas". A solução completa é modularizada em três repositórios independentes para garantir a separação de responsabilidades.

* **Frontend (Esta Aplicação):** Interface web desenvolvida com Angular que consome os dados da API.
* **Backend (API REST):** API RESTful desenvolvida com Spring Boot que serve como o núcleo da aplicação.
    * ➡️ **Link para o repositório:** `https://github.com/ZagoGiovanni/Projeto-Java-Spring-API`
* **Desktop:** Aplicação de desktop (Desktop).
    * ➡️ **Link para o repositório:** `https://github.com/ZagoGiovanni/Projeto-Java-Spring-Desktop`

## 💻 Tecnologias Utilizadas

* **Linguagem:** Java 21
* **Framework:** Spring Boot 3
* **Banco de Dados:**
    * H2 (Ambiente de Desenvolvimento)
    * PostgreSQL (Ambiente de Produção)
* **Gerenciamento de Dependências:** Maven
* **Mapeamento Objeto-Relacional:** Spring Data JPA / Hibernate

## 🚀 Como Executar o Projeto

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina:
* [Node.js e npm](https://nodejs.org/en/) - Versão LTS.
* [Angular CLI](https://angular.dev/cli) - Versão 20 ou superior.
* [Git](https://git-scm.com/downloads).

### Rodando a Aplicação

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/lista-tarefas-api.git](https://github.com/seu-usuario/lista-tarefas-api.git)
    ```

2.  **Navegue até a pasta do projeto:**
    ```bash
    cd lista-tarefas-api
    ```

3.  **Configure o banco de dados** no arquivo `src/main/resources/application.properties`.

4.  **Execute a aplicação:**
    ```bash
    mvn spring-boot:run
    ```

5.  A API estará disponível em `http://localhost:8080`.

## Autor

**Giovanni dos Santos Zago**

- LinkedIn: `https://www.linkedin.com/in/giovanni-zago-058891290/`
- GitHub: `https://github.com/ZagoGiovanni`
