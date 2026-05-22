<h1 align="center">
  <img alt="Move.it" src="https://raw.githubusercontent.com/michelspirlandeli/Next-Level-Week-4/main/moveit-next/public/logo-full.svg" width="200px" />
</h1>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/michelspirlandeli/Next-Level-Week-4?color=%2304D361">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/michelspirlandeli/Next-Level-Week-4">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/michelspirlandeli/Next-Level-Week-4">
  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
  <a href="https://moveit-next-orcin-five.vercel.app/">
    <img alt="Deploy" src="https://img.shields.io/badge/deploy-vercel-black?logo=vercel">
  </a>
</p>

<p align="center">
  <a href="#-sobre">Sobre</a>&nbsp;&nbsp;•&nbsp;
  <a href="#-funcionalidades">Funcionalidades</a>&nbsp;&nbsp;•&nbsp;
  <a href="#-demonstração">Demonstração</a>&nbsp;&nbsp;•&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;•&nbsp;
  <a href="#-como-executar">Como executar</a>&nbsp;&nbsp;•&nbsp;
  <a href="#-licença">Licença</a>
</p>

---

## 💡 Sobre

**Move.it** é uma aplicação de produtividade baseada na técnica **Pomodoro** combinada com exercícios físicos leves. A ideia é simples: a cada ciclo de foco concluído (25 minutos), o app te propõe um desafio de movimento — um exercício rápido para os olhos, corpo ou mente — e recompensa você com XP, incentivando a progressão de nível.

O projeto foi desenvolvido durante a **Next Level Week #4** da [Rocketseat](https://rocketseat.com.br/), utilizando o stack moderno do ecossistema React: **Next.js**, **TypeScript** e **Context API** para gerenciamento de estado global.

---

## ✅ Funcionalidades

- ⏱️ **Timer Pomodoro** — ciclos de 25 minutos com controle de início, pausa e reset
- 🏋️ **Desafios de movimento** — exercícios aleatórios ao completar cada ciclo
- 🎯 **Sistema de XP e níveis** — progressão gamificada para manter a motivação
- 🔔 **Notificações no navegador** — alerta sonoro e visual ao fim de cada ciclo
- 📊 **Histórico de ciclos** — contagem de desafios completados por sessão
- 🌗 **Interface responsiva** — layout adaptado para diferentes tamanhos de tela

---

## 🎨 Demonstração

> **🔗 [Acesse o deploy ao vivo →](https://moveit-next-orcin-five.vercel.app/)**

<p align="center">
  <img src="./moveit-next/public/home.png" alt="Tela inicial do Move.it" width="700px" />
</p>

<p align="center">
  <img src="./moveit-next/public/desafio.png" alt="Tela de desafio" width="700px" />
</p>

<p align="center">
  <img src="./moveit-next/public/nivel.png" alt="Tela de novo nível" width="700px" />
</p>

---

## 🛠 Tecnologias

| Tecnologia | Versão | Descrição |
|---|---|---|
| [Next.js](https://nextjs.org/) | 10.x | Framework React com SSR e rotas automáticas |
| [React](https://reactjs.org/) | 17.x | Biblioteca para construção de UI |
| [TypeScript](https://www.typescriptlang.org/) | 4.x | Superset tipado do JavaScript |
| [Styled Components](https://styled-components.com/) | 5.x | CSS-in-JS para estilização por componente |

**Conceitos aplicados:** Context API · Custom Hooks · Server-Side Rendering · Notificações Web API

---

## 🚀 Como executar

### Pré-requisitos

Antes de começar, você precisa ter instalado:
- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en/) (v14 ou superior)
- [Yarn](https://yarnpkg.com/) ou npm

### Rodando localmente

```bash
# Clone o repositório
$ git clone https://github.com/michelspirlandeli/Next-Level-Week-4.git

# Entre na pasta do projeto
$ cd Next-Level-Week-4/moveit-next

# Instale as dependências
$ yarn install
# ou: npm install

# Inicie o servidor de desenvolvimento
$ yarn dev
# ou: npm run dev
```

Acesse **[http://localhost:3000](http://localhost:3000)** no seu navegador.

### Build de produção

```bash
$ yarn build
$ yarn start
```

---

## 📁 Estrutura do projeto

```
moveit-next/
├── src/
│   ├── components/        # Componentes reutilizáveis (Timer, Profile, Sidebar...)
│   ├── contexts/          # Context API (ChallengesContext, CountdownContext)
│   ├── pages/             # Rotas do Next.js (_app, index)
│   └── styles/            # Estilos globais
├── public/
│   ├── icons/             # Ícones dos desafios
│   └── *.png              # Imagens do projeto
└── package.json
```

---

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.

---
