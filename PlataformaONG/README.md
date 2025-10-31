# 🤝 Plataforma de Gestão e Captação de ONGs (Mãos Solidárias)

## 1. Visão Geral

Este projeto consiste no desenvolvimento de uma **Plataforma Web Profissional** destinada a Organizações Não Governamentais (ONGs), visando ampliar sua presença digital, transparência e capacidade de mobilização.

A plataforma atua como um ponto central para:
* **Captação de Voluntários e Doadores:** Facilitando o cadastro de pessoas dispostas a contribuir de forma mútua.
* **Divulgação de Projetos:** Dando visibilidade a ações que impactam positivamente pessoas em situações de risco e vulnerabilidade.

Este desenvolvimento é socialmente relevante, pois além de se tratar de uma atividade acadêmica, ira ser utilizada como ponto de partida para projetos de Salvador-BA que não possuem uma presença digital adequada.

---
## 2. Estrutura do Projeto

A arquitetura do projeto segue a divisão padrão do Front-End (HTML, CSS, JS) para garantir organização e escalabilidade.

---

## 3. Requisitos de HTML5 Cumpridos

Nesta etapa inicial, todo o desenvolvimento foi focado em estabelecer a estrutura semântica e a validação de formulários, de acordo como foi exigido na orientação.

### 3.1. Estrutura Semântica
* **Tags Estruturais:** Utilização completa de `<header>`, `<main>`, `<footer>` e `<nav>` nas três páginas (index.html, projetos.html, cadastro.html) para hierarquia e acessibilidade.
* **Conteúdo:** Uso de `<section>` e `<article>` para organizar o conteúdo de forma lógica (ex: cada projeto social é um `<article>`).
* **Mídia:** Aplicação de `<figure>` e `<figcaption>` para garantir a semântica de imagens e suas legendas.

### 3.2. Formulários Complexos e Agrupamento
* **Agrupamento Lógico:** O formulário de cadastro (cadastro.html) utiliza as tags **<fieldset>** e **<legend>** para separar os campos de "Dados Pessoais" e "Endereço", garantindo organização e melhor suporte a leitores de tela.
* **Validação Nativa (HTML5):**
    * Uso do atributo **`required`** em todos os campos obrigatórios.
    * Utilização de tipos específicos de input: **`type="email"`**, **`type="date"`**, e **`type="tel"`** para validação automática do formato.
    * Implementação do atributo **`pattern`** nos campos de **CPF** e **Telefone** para forçar o formato brasileiro e cumprir a simulação de máscara exigida na atividade.

---

## 4. Como Executar e Visualizar o Projeto

Por ser um projeto puramente Front-End (HTML estático) nesta primeira entrega, a visualização no navegador é extremamente simples e não requer a instalação de servidores locais (como o Node.js).

### Instruções:

1.Faça o download ou clone este repositório do GitHub para sua máquina local.
2.Abra a pasta principal do projeto "Projeto ONG".
3.Clique duas vezes em qualquer um dos arquivos HTML  sendo "index.html", "projetos.html", ou "cadastro.html".

O arquivo será aberto automaticamente no seu navegador padrão (Chrome, Edge, Firefox, etc.).