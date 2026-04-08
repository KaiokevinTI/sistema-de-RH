# 🌍 Sistema de Cadastro de Funcionários

Um sistema web simples e responsivo para gerenciamento de recursos humanos. Este projeto foi desenvolvido com foco na aplicação de princípios de **HTML Semântico** e **CSS Moderno** (Grid e Flexbox), rodando sobre um servidor local PHP.

## 🚀 Funcionalidades

O sistema é composto por três telas principais interligadas:

* **Página de Login (`index.php`):** Interface de acesso segura e limpa, com campos validados visualmente.
* **Listagem de Funcionários (`page3.php`):** Tabela de dados (Data Table) estruturada de forma semântica, contendo barra de busca, etiquetas de status e botões de ação (editar/excluir).
* **Cadastro de Funcionário (`page2.php`):** Formulário complexo utilizando CSS Grid em duas colunas, preparado para coleta detalhada de dados do usuário.

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica rigorosa (`<main>`, `<nav>`, `<header>`, `<fieldset>`, etc.) focada em acessibilidade (a11y).
* **CSS3:** Estilização pura (Vanilla CSS) utilizando variáveis (`:root`), Flexbox para alinhamentos e CSS Grid para o layout de formulários.
* **PHP:** Utilizado para o roteamento e execução no servidor local.
* **FontAwesome (v6):** Biblioteca de ícones (via CDN).

## ⚙️ Como executar o projeto localmente

Para rodar este projeto na sua máquina, você precisará de um ambiente de servidor local como o **XAMPP**, **WAMP** ou **MAMP**.

1. Faça o download ou clone este repositório.
2. Copie a pasta do projeto para dentro do diretório público do seu servidor web:
   * No XAMPP: `C:\xampp\htdocs\seu_projeto`
3. Inicie o serviço do **Apache** no painel de controle do XAMPP.
4. Abra o seu navegador e acesse a URL:
   ```text
   http://localhost/seu_projeto/
