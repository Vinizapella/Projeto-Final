# Trabalho Final - Sistema de Cadastro de Orientações WEG (WegOne)

Este repositório contém o código-fonte do WegOne, um sistema de console para cadastro e consulta de orientações e regras de conduta da empresa WEG, desenvolvido como trabalho final da unidade curricular de Lógica de Programação.

> **Unidade Curricular:** Lógica de Programação
> **Tecnologia:** Java
> **Foco:** Arrays, Lógica de Controle, CRUD em console

---

## 🏭 Contextualização

A WEG, como uma multinacional de equipamentos industriais, necessita de um sistema eficiente para que seus colaboradores acessem instruções de uso, segurança e procedimentos operacionais. O WegOne foi criado para ser essa solução, um sistema multilíngue (Português, Inglês e Alemão) que organiza e facilita o acesso a essas informações vitais, integrando também conhecimentos da matéria de Inglês para uma experiência de usuário otimizada.

---

## 🎯 Objetivo do Projeto

Desenvolver um sistema em Java que permita o cadastro, consulta, edição e exclusão de orientações operacionais da WEG. O sistema deve ser interativo, multilíngue e utilizar arrays como estrutura de dados principal, simulando uma solução prática para as necessidades da empresa.

---

## ✨ Funcionalidades Principais

* **Cadastro de Orientações:** Permite adicionar novas regras e manuais ao sistema.
* **Pesquisa Avançada:** Busca de orientações por título ou por código.
* **Edição Completa (PLUS):** Altera qualquer informação de uma orientação já cadastrada.
* **Exclusão Segura:** Remove orientações do sistema e reorganiza os dados.
* **Suporte a 3 Idiomas:** Toda a interação e o conteúdo podem ser exibidos em Português, Inglês ou Alemão.
* **Menu de Navegação Intuitivo:** Interface de console clara para acesso a todas as funcionalidades.

---

## 📋 Requisitos do Sistema

### 1. Cadastro de Orientações
Para cada orientação, o sistema armazena:
- **Título da Orientação**
- **Tipo:** (Manual de Operação, Procedimento de Segurança, Manutenção, Testes, Conduta)
- **Conteúdo em Português**
- **Conteúdo em Inglês**
- **Conteúdo em Alemão**

### 2. Pesquisa e Exibição
- A busca pode ser feita por **título** ou **código**.
- O conteúdo encontrado é exibido no idioma previamente selecionado pelo usuário.

### 3. Edição de Orientações (PLUS)
- Permite a alteração do título, tipo ou do conteúdo em qualquer um dos três idiomas.

### 4. Exclusão de Orientações
- Remove a orientação selecionada e ajusta o array de dados para manter a consistência.

### 5. Categorias de Orientações
O sistema organiza as orientações nos seguintes tipos:
- **Manual de Operação:** Uso correto dos equipamentos (motores, geradores, etc.).
- **Procedimento de Segurança:** Normas e práticas seguras.
- **Manutenção e Reparos:** Guias para manutenção preventiva e corretiva.
- **Testes e Diagnóstico:** Procedimentos para testes e identificação de falhas.
- **Manual de Conduta e Operações Setoriais:** Boas práticas e processos específicos de cada setor.

---

## 🗃️ Estrutura de Dados

-   O armazenamento de todos os dados (títulos, tipos, conteúdos em PT/EN/DE) é feito exclusivamente através de **Arrays Unidimensionais** em Java.
-   O sistema é inicializado com 10 orientações pré-cadastradas, com capacidade para novos cadastros.

---

## 🛠️ Tecnologias e Implementação

* **Linguagem:** **Java**
* **Estruturas de Controle:** O fluxo do programa é gerenciado por laços de repetição (`while`, `for`) e estruturas condicionais (`if/else`, `switch case`).
* **Boas Práticas:** O código foi desenvolvido seguindo princípios de **Clean Code**, com variáveis e métodos nomeados de forma clara, comentários pertinentes e boa organização para facilitar a leitura e manutenção.

---

## 🚀 Como Executar o Projeto

1.  Clone este repositório para sua máquina local.
2.  Abra o projeto em sua IDE Java de preferência (Eclipse, IntelliJ, VS Code).
3.  Localize o arquivo principal que contém o método `main`.
4.  Compile e execute o arquivo para iniciar o sistema no console.

---

<p align="center">
  &copy; 2025 - Lógica de Programação
</p>
