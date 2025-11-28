<div align="center">
<img src="https://placehold.co/1200x300/512BD4/FFFFFF?text=FinDash&font=raleway" alt="Banner do Projeto FinDash">

  <h1 align="center">FinDash: Seu controle financeiro. Rápido, seguro e sem distrações.</h1>

  ![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow) ![Electron](https://img.shields.io/badge/Electron-Desktop-blue) ![React](https://img.shields.io/badge/React-TypeScript-blue) ![License](https://img.shields.io/badge/License-MIT-green)


</div>




<div align="center">
<img src = https://github.com/RafaelErnandes/FinDash/blob/main/projectImages/FinDash_logo.png>
</div>

---
<div align="center">
  
## 📋 Sobre o Projeto
</div>

O **FinDash** é um aplicativo desktop de gestão financeira pessoal desenvolvido para rodar nativamente em Windows e Linux. Diferente de planilhas web complexas, ele oferece uma experiência focada, rápida e segura para controle de gastos.

A principal filosofia do FinDash é **Local-First**: seus dados financeiros são seus. Eles ficam salvos no seu computador e não dependem de internet para serem acessados, garantindo privacidade total e performance instantânea.

> Projeto desenvolvido como parte da disciplina de **Engenharia de Software III** (Startup Simulada).

---

<div align="center">
  
## 📸 Screenshots e Demonstração
  
</div>

### 1. Dashboard Principal
Visualização imediata do saldo consolidado, receitas e despesas do mês.
![Dashboard Principal](https://github.com/RafaelErnandes/FinDash/blob/main/projectImages/image2.png)

### 2. Cadastro de Transações
Interface simplificada para adicionar novas movimentações em poucos cliques.
![Nova Transação](https://github.com/RafaelErnandes/FinDash/blob/main/projectImages/image.png)

### 3. Metas e calculadora de imposto
Acompanhamento de perto realização de metas e sonhps.
![Histórico]![Dashboard Principal](https://github.com/RafaelErnandes/FinDash/blob/main/projectImages/image3.png)

---

## 🚀 Tecnologias (Tech Stack)

Este projeto utiliza uma arquitetura moderna para aplicações desktop de alta performance:

* **Core:** [Electron](https://www.electronjs.org/) (Runtime Desktop)
* **Frontend:** [React.js](https://reactjs.org/) (Interface)
* **Linguagem:** [TypeScript](https://www.typescriptlang.org/) (Tipagem e Segurança)
* **Estilização:** CSS Modules / Tailwind
* **Gráficos:** Recharts
* **Persistência:** Electron Store (JSON Local)

---

## ⚙️ Instalação e Execução

Você pode rodar o projeto localmente para desenvolvimento ou gerar o executável final.

### Pré-requisitos
* Node.js (v16 ou superior)
* NPM ou Yarn

### Passo a passo

1.  **Clone o repositório**
    ```bash
    git clone [https://github.com/RafaelErnandes/FinDash.git](https://github.com/RafaelErnandes/FinDash.git)
    cd FinDash
    ```

2.  **Instale as dependências**
    ```bash
    npm install
    # ou
    yarn install
    ```

3.  **Execute em modo de desenvolvimento**
    Isso abrirá a janela do Electron com Hot Reload ativado.
    ```bash
    npm run electron:dev
    ```

4.  **Gerar Executável (Build)**
    Para criar o instalador `.exe` (Windows) ou binário Linux:
    ```bash
    npm run make
    ```

---

## 📅 Documentação de Engenharia

Este projeto segue metodologias ágeis (Scrum) e práticas de qualidade de software.

### Definition of Done (DoD)
Para uma funcionalidade ser considerada completa, ela deve:
- [x] Ter o código TypeScript compilando sem erros.
- [x] Passar pela verificação de Lint (ESLint).
- [x] Ser testada manualmente no ambiente Electron (Windows/Linux).
- [x] Ter sido revisada via Pull Request.

### Funcionalidades do MVP (Sprint 1 & 2)
- [x] **US01:** Dashboard com cálculo automático de saldo.
- [x] **US02:** Cadastro de receitas e despesas.
- [x] **US03:** Persistência de dados offline (os dados não somem ao fechar).
- [x] **US04:** Edição e exclusão de lançamentos.

---

## 👥 Squad (Equipe)

| Membro | Função | GitHub |
| :--- | :--- | :--- |
| **Arthur Bomfim** | Product Owner (PO) | [@ArthurBomfimDev](https://github.com/ArthurBomfimDev) |
| **Rafael Ernandes** | Scrum Master & Dev | [@RafaelErnandes](https://github.com/RafaelErnandes) |

---

## 📄 Licença

Este projeto é de cunho acadêmico e está sob a licença MIT. Sinta-se livre para contribuir!
