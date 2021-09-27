Sistema de Cadastro Pessoal - Formação Tech 4º edição

- [Sistema de Cadastro Pessoal - Formação Tech 4º edição](#sistema-de-cadastro-pessoal---formação-tech 4º edição)
    - [Autor](#autor)
    - [Objetivo](#objetivo)
    - [Ferramenta](#ferramenta)
    - [Linguagens](#linguagens)

### Autor:

- [José Mauricio Nunes Santos](https://github.com/jmauricions)
- **Idade**: 29 anos
- **Tipo de deficiência:** Cegueira

### Objetivo:

Desenvolver um cadastro pessoal num *site* pequeno e acessível, com campos do formulários, além de validações e expressões regulares.

### Ferramenta:

Visual Studio Code no Windows.

### Linguagens: 

- - HTML
- JavaScript
-CSS
## Descrição do site

### HTML

Começa com um método de documentação para renderizar HTML – `<!DOCTYPE HTML>` e um método de HTML com uma etiqueta `lang` pegando a língua portuguesa do Brasil. Entrando na `head`, que é um método que provdiencia metadados, título (`<title`>), *links* dos ícones, das fontes, do CSS, do JavaScript e o estilo interno (`<style>`), começando com título, um metadado de renderização de caracteres e um metdado de autoria. 

Então no corpo, no qual há um cabeçalho (`<header>`) contendo um título de primeiro grau (`<h1>`) e parágrafos (`<p>`), e um conteúdo principal (`<main>`) contendo um formulário (`<form>`). No formulário, temos grupos (`<fieldset>`), dentro dos quais, temos legendas (`<legend`>) dos grupos, rótulos (`<label`>) e caixas de entradas (`<input>`) com um tipo (`type`), um identificador (`id`) e um nome (`name`) pegados pelos rótulos. Os tipos das caixas de entradas podem ser texto, número, telefone, e-mail, data, seleção de opções, seleção de escolha e senha. Também temos uma área de mensagem para escrever (`textarea`). No final, há dois botões (`input`) para enviar e limpar, contendo métodos em JavaScript para clicar as funções em JavaScript. 

### JavaScript

É um script interno. nele, temos a função Mmsg1, onde exibe um alerta de boas vindas, quando o cliente acessa o formulário. Temos também a função formatar nome, onde impede que o cliente digite números, para que ele digite somente letras.
Tem a função nrg, onde insere um traço no campo RG.
Tem a função formata CPF, função para completar o CPF, com pontos e traço.
 Functiontelcelular: função para completar celular com espaço e traço
functionftelefoneFixo
função para completar telefone fixo com espaço e traço
      function pergunta1
      Checa se quiser enviar no diálogo
      function pergunta2
      Uma função para informar e limpar
      CSS
      Adicionei cores simples, para deixar um bom visual na página.