# Validador de Formulário

Este projeto é um validador de formulário desenvolvido em JavaScript, HTML e CSS. Ele valida vários campos de um formulário, incluindo CPF, e fornece feedback ao usuário sobre a validade dos dados inseridos.

## Sobre o Projeto

O validador de formulário foi criado para demonstrar a integração de diferentes tecnologias da web (HTML, CSS, JavaScript) e a utilização de módulos JavaScript para organizar a lógica de validação.

## Funcionalidades

- **Validação de CPF:** Verifica se um CPF é válido ou inválido, considerando os dígitos verificadores.
- **Validação de Outros Campos:** Valida outros campos do formulário (ex: nome, senha) conforme necessário.
- **Feedback ao Usuário:** Informa se os dados inseridos são válidos ou inválidos após a validação.

## Estrutura do Projeto

O projeto é composto pelos seguintes arquivos:

- `index.html`: Contém a estrutura do formulário.
- `style.css`: Contém os estilos do formulário.
- `index.js`: Contém a lógica de validação geral do formulário e a integração com o arquivo `validateCpf.js`.
- `validateCpf.js`: Contém a lógica específica de validação de CPF utilizando classes em JavaScript.
