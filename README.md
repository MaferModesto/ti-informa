#Sistema de Gerenciamento e Venda de Cursos Online

## Descrição do Projeto

Este projeto foi desenvolvido como Trabalho de Conclusão de Curso (TCC) do curso técnico de Informática na FIEC. O sistema tem como objetivo o gerenciamento e a comercialização de cursos online, permitindo o cadastro, organização e controle de informações relacionadas aos cursos.

O projeto simula uma aplicação web completa, com separação de responsabilidades entre front-end e back-end, seguindo boas práticas de desenvolvimento.

---

## Minha Contribuição

Neste projeto em grupo, atuei principalmente na camada de backend, sendo responsável por:

**🧩 Modelagem de Dados:**  
Criação de classes Java (Java Beans) para representação das entidades do sistema, com definição de atributos, encapsulamento e métodos getters e setters.

**⚙️ Lógica de Servlets:**  
Implementação do controle de requisições HTTP, responsável pela comunicação entre o front-end e o servidor.

**🗄️ Persistência de Dados:**  
Integração com banco de dados MySQL, realizando operações de inserção, consulta, atualização e exclusão de dados.

**🏗️ Arquitetura do Sistema:**  
Aplicação do padrão DAO (Data Access Object), organizando o acesso ao banco de dados e separando regras de negócio da camada de persistência.

---

## Tecnologias Utilizadas

- Java
- Servlets
- JSP (JavaServer Pages)
- MySQL
- JDBC
- Padrão DAO (Data Access Object)

---

## Arquitetura

O sistema foi estruturado seguindo uma arquitetura em camadas:

- **Camada de Apresentação:** JSP
- **Camada de Controle:** Servlets
- **Camada de Modelo:** Java Beans
- **Camada de Persistência:** DAO + MySQL

---

## Funcionalidades

- Cadastro de cursos
- Listagem de cursos disponíveis
- Edição e remoção de cursos
- Comunicação entre front-end e back-end via Servlets
- Persistência de dados em banco relacional
