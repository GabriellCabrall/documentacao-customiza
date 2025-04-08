# Documento de Arquitetura de Sofware

## 1. Introdução

### 1.1. Finalidade

Este documento oferece uma visão geral arquitetural abrangente do sistema, utilizando diferentes perspectivas arquiteturais. O objetivo é capturar e comunicar as decisões arquiteturais significativas tomadas em relação ao sistema.

### 1.2. Escopo

Este documento serve como guia para a construção arquitetural do software, abordando os principais pontos desenvolvidos na arquitetura do projeto. A partir deste resumo, é possível se orientar sobre outros documentos detalhados da arquitetura do projeto, proporcionando uma visão clara e completa de cada tema.

## 2. Representação Arquitetural

### Tecnologias

#### Frontend

- **Javascript**: JavaScript é uma linguagem de programação de alto nível e dinâmica, amplamente utilizada no desenvolvimento web. Desenvolvida inicialmente pela Netscape, tornou-se uma das principais tecnologias da web, ao lado de HTML e CSS. JavaScript permite a criação de páginas web interativas, manipulando o DOM (Document Object Model) e permitindo a integração de APIs externas. É uma linguagem interpretada que segue o padrão ECMAScript, sendo flexível e poderosa, com tipagem dinâmica e suporte a programação orientada a objetos, funcional e imperativa. Sua popularidade e versatilidade a tornam essencial para o desenvolvimento moderno de aplicações web.

- **React**: O React é um conjunto de bibliotecas open source voltados para a criação de UIs interativas de forma mais fácil. Toda a lógica do React é escrita em JavaScript, facilitando a passagem de dados ao longo da aplicação. Essa tecnologia foi escolhida por conta da quantidade de conteúdo disponível na internet, facilitando o treinamento e aprendizado da equipe. Outro fator importante é a comunidade, que está sempre ativa para ajudar em possíveis dúvidas.

- **Next.js**: O Next.js é uma estrutura da web de desenvolvimento front-end React de código aberto criada por Vercel que permite funcionalidades como renderização do lado do servidor e geração de sites estáticos para aplicativos da web baseados em React. É uma estrutura pronta para produção que permite que os desenvolvedores criem rapidamente sites estáticos e dinâmicos e é amplamente usada por muitas grandes empresas.

#### Backend

- **Python**: Python é uma linguagem de programação de alto nível, interpretada de script, imperativa, orientada a objetos, funcional, de tipagem dinâmica e forte.

- **Django**: Django é um framework para desenvolvimento rápido para web, escrito em Python, que utiliza o padrão model-template-view. Também foi utilizado o banco de dados gerado pelo o Django que utiliza o SQL.

## 3. Metas e Restrições da Arquitetura

### 3.1. - Restrições

- O _software_ deve ser desenvolvido com as tecnologias definidas;
- O _software_ deve rodar nos navegadores: Web Firefox, Google Chrome, Edge e Opera;
- O ambiente de desenvolvimento do _software_ deve funcionar tanto em Windows quanto em Linux;
- Para utilizar o _software_ é necessário estar conectado à internet;

### 3.2. - Metas

- **Portabilidade** - Deve ser possível utilizar a plataforma em qualquer navegador web;
- **Usabilidade** - O _software_ deve possuir alta aprendibilidade e inteligibilidade, para que atenda aos requisitos elicitados;
- **Manutenibilidade** - O código e as documentações realizadas pelo desenvolvedor devem atingir um alto nível de qualidade, seguindo os padrões de projeto e bibliografia, onde a manutenção seja fácil de ser realizada.

## 4. Visão Lógica

A visão lógica descreve como o sistema é estruturado, em termos de unidade e implementação. Mostra como está a organização conceitual do sistema em termos de camadas, pacotes, classes e interfaces. O relacionamento entre os elementos mostra as dependências, as realizações de interface, os relacionamentos parte-todo e assim por diante.

### 4.1 Diagrama de Classes

_Em construção_

## 5. Visão de Deploy

Descreve como a aplicação é disponibilizada para uso, seja em ambiente de desenvolvimento, para testes ou em produção. O deploy será feito utilizando AWS para o backend e Vercel para o frontend.

## 6. Visão de implementação

### 6.1. Visão Geral

Descreve como os artefatos de desenvolvimento estão organizados no sistema de arquivos, incluindo arquivos e diretórios relevantes, bem como itens de configuração. Isso abrange tanto os artefatos de desenvolvimento, como código-fonte e scripts, quanto os artefatos de implantação, como pacotes e executáveis necessários para colocar o software em produção. Essa visão é opcional dentro da abordagem das Visões 4+1, que se referem às diferentes perspectivas arquiteturais de um sistema. A inclusão dessa visão pode ajudar a facilitar a navegação e a manutenção do projeto, proporcionando uma melhor compreensão da estrutura dos arquivos e diretórios.

### 6.2. Diagrama de Classes

O Diagrama de Classes é uma representação da estrutura e relações das classes que servem de modelo para os objetos. Consiste em um conjunto de objetos com as mesmas características. Dessa forma, consegue-se identificar os objetos e agrupá-los, de forma a encontrar suas respectivas classes.

## 7. Tamanho e Desempenho

### 7.1 Visão Geral

Descrição do desempenho e das características do _software_ que impactam na arquitetura de software

### 7.2 Requisitos Mínimos

- É necessário possuir conexão com a internet;
- Navegador com suporte a HTML5, CSS e JavaScript
- Para desenvolvimento possuir sistema operacional Windows ou Linux

---

| Data       | Versão | Descrição                                       | Autor(es)                                           |
| ---------- | ------ | ----------------------------------------------- | --------------------------------------------------- |
| 07/04/2025 | 1.0    | Iniciando a criação da modelagem de arquitetura | [Gabrie Cabral](https://github.com/GabriellCabrall) |
