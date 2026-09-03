# Cypress_eXpress

Bem-vindo ao Projeto Mark L!

Este projeto tem como objetivo testar o gerenciador de tarefas **Mark L**, explorando os conceitos fundamentais do framework Cypress. Ao longo do desenvolvimento, são aplicadas boas práticas de automação e, ao final, são gerados relatórios de testes de regressão com evidências em imagens e vídeos.

---

## 🚀 Tecnologias Utilizadas
- [Cypress](https://www.cypress.io/) - Framework de testes E2E.
- [Node.js](https://nodejs.org) - Ambiente de execução JavaScript.

---

## 📋 Pré-requisitos
Antes de começar, certifique-se de ter instalado em sua máquina:
- [Visual Studio Code](https://code.visualstudio.com/download)
- [Node.js](https://nodejs.org) (versão LTS recomendada)

- Gerenciador de pacotes:
  -  `npm` (já inclusos no Node.js)
  -  [Yarn](https://yarnpkg.com/)

---

## ⚙️ Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com
   ```

2. Acesse a pasta do projeto:
   ```bash
   cd nome-do-repositorio
   ```

3. Instale as dependências do projeto:
   ```bash
   npm install
   ```

---

## 🧪 Como Executar os Testes

* **Abrir a interface gráfica do Cypress** (modo interativo):
  ```bash
  npx cypress open
  ```

* **Executar os testes em modo headless** (terminal / linha de comando):
  ```bash
  npx cypress run
  ```

* **Executar os testes em um navegador específico** (ex: Chrome):
  ```bash
  npx cypress run --browser chrome
  ```

---

## 📁 Estrutura do Projeto
- `cypress/e2e/` - Contém os arquivos de teste (`.cy.js` ou `.cy.ts`).
- `cypress/support/` - Comandos customizados e configurações globais.
- `cypress/fixtures/` - Massa de dados mockados para os testes.

##  📄 Licença

Este projeto é destinado a fins de estudo, prática profissional e demonstração de conhecimentos em automação de testes.
