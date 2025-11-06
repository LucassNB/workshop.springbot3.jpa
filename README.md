# 🚀 Workshop Spring Boot 3 + JPA: Gerenciamento de Usuários

Este projeto é um ponto de partida para o desenvolvimento de uma aplicação web robusta utilizando **Spring Boot 3**, **Spring Data JPA** e um banco de dados em memória **H2**. Focado na prática e no aprendizado, este workshop implementa um módulo básico de gerenciamento de usuários (CRUD - Create, Read, Update, Delete) através de uma API RESTful.

Desenvolvido por **Lucas** (Estudante de Engenharia de Software na PUC-Rio), este projeto foi configurado com atenção aos detalhes do ambiente de desenvolvimento, incluindo integração com o VS Code e Git/GitHub.

## ✨ Funcionalidades Implementadas

*   **API RESTful para Gerenciamento de Usuários:** Endpoints dedicados para operações CRUD (Criar, Ler, Atualizar, Deletar) de usuários.
*   **Entidade `User`:** Representação do modelo de dados de usuário, mapeada para o banco de dados com JPA.
*   **Camada de Persistência (Spring Data JPA):** Interface `UserRepository` para interação simplificada com o banco de dados.
*   **Lógica de Negócio (Service Layer):** `UserService` para orquestração das operações e validações.
*   **Banco de Dados H2 em Memória:** Configurado para desenvolvimento, oferecendo um console web para visualização e interação com os dados.
*   **Validação de Dados:** Utilização de anotações para garantir a integridade dos dados (ex: `@Email`, `@NotBlank`).
*   **Configuração de Ambiente Otimizada:** `build.gradle` com dependências essenciais (Lombok, H2, JPA, Web).
*   **Integração com REST Client (VS Code):** Facilita o teste dos endpoints da API diretamente do ambiente de desenvolvimento.

## 🛠️ Tecnologias Utilizadas

*   **Java 21:** Linguagem de programação principal.
*   **Spring Boot 3.5.7:** Framework para construção rápida de aplicações Java.
*   **Gradle:** Ferramenta de automação de build.
*   **Spring Data JPA:** Abstração para simplificar o acesso a dados.
*   **Hibernate 6.x:** Implementação padrão do JPA.
*   **H2 Database:** Banco de dados relacional em memória para desenvolvimento.
*   **Lombok:** Biblioteca para reduzir código boilerplate em classes Java.
*   **Git / GitHub:** Controle de versão e hospedagem de código.
*   **Visual Studio Code:** Ambiente de Desenvolvimento Integrado (IDE).
*   **REST Client Extension (VS Code):** Para testes de API.

## 🚀 Como Começar

Siga os passos abaixo para configurar e executar o projeto em sua máquina local.

### Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas:

*   **Java Development Kit (JDK) 21:** [Adoptium Temurin](https://adoptium.net/) (ou outra distribuição OpenJDK 21)
*   **Git:** [Instruções de Instalação](https://git-scm.com/downloads)
*   **Visual Studio Code:** [Download VS Code](https://code.visualstudio.com/)
    *   **Extensões Recomendadas para VS Code:**
        *   `Extension Pack for Java` (by Microsoft)
        *   `Spring Boot Extension Pack` (by VMWare)
        *   `REST Client` (by Huachao Mao)

### 1. Clonar o Repositório

Abra seu terminal e clone este repositório:

```bash
git clone git@github.com:LucassNB/workshop.springbot3.jpa.git
cd workshop.springbot3.jpa
