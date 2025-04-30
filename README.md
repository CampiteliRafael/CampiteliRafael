# Olá! Eu sou [Rafael Campiteli Pereira / campitelirafael] <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-SeuNome-blue?style=flat&logo=linkedin)]([https://www.linkedin.com/in/seu-perfil-linkedin/](https://www.linkedin.com/in/rafael-campiteli-pereira-033537240/)) 
Sou um Desenvolvedor Full-Stack entusiasmado em construir aplicações web completas e funcionais, combinando interfaces de usuário eficazes com lógicas de backend robustas e seguras. Acredito que os desafios técnicos são oportunidades de aprendizado e crescimento, como pude experienciar no desenvolvimento do projeto [Feedback App](#-projeto-em-destaque-feedback-app) detalhado abaixo.

---

## 💡 Habilidades e Experiência Prática (Demonstradas no Feedback App)

Este projeto foi uma jornada prática onde pude aplicar e aprofundar conhecimentos em diversas áreas cruciais do desenvolvimento Full-Stack:

* **Desenvolvimento Full-Stack & TypeScript:** Construí do zero tanto o backend (Node.js/Express) quanto o frontend (React/Vite), utilizando **TypeScript** em ambas as pontas para garantir segurança de tipos, facilitar a refatoração e prevenir erros comuns em tempo de desenvolvimento (como os que depuramos com tipos de JWT e configurações de teste).

* **Backend (Node.js & Express):**
    * Desenvolvi uma **API RESTful** estruturada com padrão similar ao MVC (Models, Routes, Controllers).
    * Implementei **autenticação segura com JWT** (geração no login/registro, validação via middleware) e hashing de senhas com **bcryptjs**.
    * Criei **middleware de autorização (RBAC)** para diferenciar permissões entre usuários (`user`) e administradores (`adm`).
    * Utilizei **Mongoose** para modelagem e interação com banco de dados **MongoDB**, realizando operações CRUD para os feedbacks.
    * Configurei o ambiente com **`dotenv`** e habilitei **CORS**.

* **Frontend (React & Vite):**
    * Estruturei uma **Single Page Application (SPA)** com **React Router DOM**, incluindo rotas públicas, privadas e com restrição de `role`.
    * Gerenciei estado global de autenticação de forma eficaz usando a **Context API**.
    * Desenvolvi **componentes reutilizáveis** (`Button`, `InputField`, `FormErrorMessage`, `Header`, `ProtectedRoute`, `RedirectIfLoggedIn`) para promover consistência e manutenibilidade.
    * Implementei **estilização escopada** com **CSS Modules**.
    * Consumi a API backend de forma assíncrona (usando `Workspace` e `async/await`) e tratei estados de loading e erro na interface.

* **Testes Automatizados & Resolução de Problemas:** 🛠️🐛✅
    * **Backend:** Escrevi **testes unitários** com **Jest** e mocks para validar a lógica de controllers e middleware isoladamente. Criei **testes de integração** com **Jest + Supertest + MongoDB Memory Server** para garantir o funcionamento completo dos endpoints da API e a interação com o banco de dados em memória.
    * **Frontend:** Implementei **testes de componente** com **Vitest + React Testing Library + User Event**, focando no comportamento do usuário. Superei desafios significativos na configuração do ambiente de teste frontend, incluindo:
        * Migração de Jest para **Vitest** para melhor integração com o ecossistema Vite.
        * Configuração de transformadores (ts-jest/babel) e resolução de problemas de sintaxe (JSX).
        * Configuração do **Mock Service Worker (MSW)** para simular a API backend, depurando erros complexos de resolução de módulos ESM (`msw/node`) e garantindo a disponibilidade de APIs Web (`TextEncoder`, `Response` via `whatwg-fetch`) no ambiente de teste (`jsdom`/`happy-dom`).
        * Depuração de testes assíncronos e condicionais com RTL (`waitFor`, `findBy*`).
    * **Depuração Geral:** A depuração de erros de tipo, configuração, lógica assíncrona e ambiente de teste em ambos os stacks reforçou minha capacidade de analisar problemas metodicamente e aplicar soluções eficazes.

---

## 💻 Stack Tecnológica Principal (Usada no Projeto)

**Frontend:** React, Vite, TypeScript, React Router, Context API, CSS Modules, Vitest, React Testing Library, MSW
**Backend:** Node.js, Express, TypeScript, MongoDB, Mongoose, JWT, Bcryptjs, Jest, Supertest, MongoDB Memory Server
**Geral:** Git, GitHub, NPM/Yarn, REST API, dotenv

---

## 📌 Projeto em Destaque: Feedback App

Uma aplicação full-stack completa para gerenciamento de feedbacks com autenticação e controle de acesso baseado em papéis. Este projeto solidificou minhas habilidades em construir e **testar** aplicações web modernas de ponta a ponta.

* **Tecnologias:** Node.js, Express, React, TypeScript, MongoDB, Mongoose, JWT, Bcryptjs, Vitest, RTL, MSW, Jest, Supertest.
* **Repositório:** `[Link para o Repositório do Feedback App no seu GitHub]` *(Adicione outros projetos aqui se tiver)*

---

## 🌱 Aprendizado Contínuo

Estou sempre buscando aprender e melhorar. Atualmente estou focando em [ex: aprofundar em testes E2E com Cypress, explorar Next.js, aprender sobre Docker/Containers, etc.].

---

## 📫 Contato

Vamos conectar!

* **LinkedIn:** [Seu Link do LinkedIn]
* **Portfólio:** [Link para seu site/portfólio]
* **Email:** [seu.email@exemplo.com]

---
