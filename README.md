# Sistema de Acesso ao IFSP

## Descrição do Projeto

Este projeto consiste em uma página web simples de acesso ao sistema do Instituto Federal de São Paulo (IFSP). O sistema oferece dois tipos de autenticação:

- Administrador
- Usuário

Além disso, o sistema realiza uma validação do campo de usuário, impedindo que o formulário seja enviado caso o campo esteja vazio.

O projeto foi desenvolvido para a disciplina de **Gestão de Projetos de Software**, com foco no planejamento de releases e controle de funcionalidades.

---

## Funcionalidades

### Implementadas

- Tela de login.
- Acesso como Administrador.
- Acesso como Usuário.
- Validação do campo de usuário.
- Mensagem de erro quando o campo estiver vazio.

### Regras de Negócio

- O campo **Usuário** é obrigatório.
- O sistema não permite o acesso caso o campo esteja vazio.
- O usuário deve selecionar um perfil de acesso antes de entrar no sistema.

---

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript

---

## Estrutura do Projeto

```text
projeto-ifsp/
│
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── README.md
```

