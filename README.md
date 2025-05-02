# Olá, eu sou [Rafael Campiteli Pereira / campitelirafael]! 👋


Sou um desenvolvedor web full-stack e gosto muito de construir aplicações completas, desde a interface com o usuário até a lógica do servidor e banco de dados. Acredito que cada projeto é uma chance de aprender e superar desafios.

---

## 🚀 Minha Jornada com o "Feedback App"

Recentemente, me dediquei a construir o **[Feedback App]**, um projeto que, apesar de parecer simples no conceito (coletar e gerenciar feedbacks), me proporcionou uma experiência prática valiosa em várias frentes do desenvolvimento full-stack moderno:

* **TypeScript de Ponta a Ponta:** Adotei TypeScript tanto no backend **Node.js/Express** quanto no frontend **React/Vite**. Isso foi ótimo para a segurança e organização do código, embora tenha apresentado desafios interessantes na configuração dos ambientes de build e teste para que tudo "conversasse" bem com os tipos.

* **Backend Robusto:** Criei uma API REST com Express, usando **Mongoose** para modelar e interagir com o **MongoDB**. Implementei um sistema de autenticação completo com **JWT**, incluindo hashing seguro de senhas com **bcryptjs** e um sistema de permissões baseado em papéis (`user` vs `adm`) usando middleware customizado.

* **Frontend Reativo:** No lado do cliente, usei **React** com **Context API** para gerenciar o estado global de autenticação. Criei componentes reutilizáveis (`Button`, `InputField`, etc.) para manter a UI consistente e usei **CSS Modules** para evitar conflitos de estilo. A configuração do **React Router DOM** para proteger rotas e redirecionar usuários logados/deslogados corretamente (especialmente lidando com o botão "voltar" do navegador) foi um aprendizado chave.

* **Testes e Depuração:** 🐛➡️✅ Implementar testes foi uma parte crucial e desafiadora.
    * No **backend**, escrevi testes unitários com **Jest** (usando mocks) e testes de integração com **Supertest** e **MongoDB Memory Server**, o que me deu confiança de que a API estava funcionando como esperado.
    * No **frontend**, comecei com Jest, mas enfrentei dificuldades persistentes na configuração para lidar com imports de módulos (`msw/node`) e transformações (JSX, CSS Modules) no ambiente de teste. Decidi **migrar para o Vitest**, que, por ser integrado ao Vite, resolveu esses problemas de ambiente de forma mais fluida. Usei a **React Testing Library** para focar nos testes como o usuário vê e interage, e configurei o **Mock Service Worker (MSW)** para simular as respostas da API, isolando os testes de frontend. Todo esse processo de depuração de configuração foi intenso, mas extremamente valioso!

---

## 🛠️ Tecnologias que Utilizei Neste Projeto

* **Linguagens:** TypeScript, JavaScript
* **Frontend:** React, Vite, React Router, Context API, CSS Modules, RTL, Vitest, MSW
* **Backend:** Node.js, Express, Mongoose, JWT, Bcryptjs, Jest, Supertest, MongoMemoryServer
* **Banco de Dados:** MongoDB
* **Ferramentas:** Git, GitHub, NPM/Yarn, VS Code

---

## 📌 Projeto em Destaque: Feedback App

Uma aplicação full-stack completa para gerenciamento de feedbacks com autenticação e controle de acesso baseado em papéis. Um ótimo campo de testes para boas práticas de desenvolvimento e resolução de problemas de configuração.

* **Repositório:** `[https://github.com/CampiteliRafael/projetofeedbacks]`

---

## 🌱 O Que Vem Pela Frente?

Estou sempre buscando aprender mais. No momento, estou interessado em explorar testes E2E com Cypress, me aprofundar em Docker, estudar GraphQL, etc.]. Aberto a novas oportunidades e desafios!

---

## 📫 Conecte-se Comigo

* **LinkedIn:** [https://www.linkedin.com/in/rafael-campiteli-pereira-033537240/]
* **Email:** [campitelir8@gmail.com]

---
