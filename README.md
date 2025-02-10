# CRUD com Login de Usuários/Admin em PHP

Este repositório contém um projeto CRUD completo desenvolvido em PHP com sistema de login para usuários e administradores. A aplicação segue a arquitetura MVC (Model-View-Controller) para melhor organização e manutenção do código. O banco de dados foi estruturado no phpMyAdmin.

## 🚀 Objetivo
Criar uma aplicação funcional de gerenciamento de usuários e dados, implementando:
- PHP: Lógica e estrutura do backend e frontend.
- phpMyAdmin: Gerenciamento do banco de dados MySQL.
- MVC (Model-View-Controller): Organização e separação das responsabilidades.
- Autenticação de usuários: Controle de acesso para usuários e administradores.

## 🔒 Conceitos Abordados
- Implementação do padrão MVC para organização do código.
- Autenticação e controle de sessão para usuários e administradores.
- Operações CRUD utilizando PHP e MySQL.
- Manipulação de formulários e requisições HTTP (GET, POST).

## 📂 Estrutura do Repositório

```plaintext
.
├── Controller/
│   ├── AdministradorController.php
│   ├── ExperienciaProfissionalController.php
│   ├── FormacaoAcadController.php
│   ├── Navegacao.php
│   ├── OutrasFormacoesController.php
│   └── UsuarioController.php
├── Img/
│   └── Enlatados.png
├── Model/
│   ├── Administrador.php
│   ├── ConexaoBD.php
│   ├── ExperienciaProfissional.php
│   ├── FormacaoAcad.php
│   ├── outrasformacoes.php
│   └── Usuario.php
├── View/
├── index.php
└── README.md
