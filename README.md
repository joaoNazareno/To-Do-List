## Projeto Lista de Tarefas

Este é um simples aplicativo web de Lista de Tarefas onde os usuários podem adicionar, editar e remover tarefas. A aplicação foi desenvolvida utilizando HTML, CSS, JavaScript (jQuery), PHP e MySQL. O projeto foi gerenciado utilizando o Laragon como ferramenta de gerenciamento de servidor.

## Funcionalidades
º Adicionar novas tarefas
º Marcar tarefas como concluídas
º Editar tarefas
º Excluir tarefas

## Tecnologias Utilizadas
º HTML: Para a estrutura das páginas web
º CSS: Para a estilização das páginas web
º JavaScript (jQuery): Para interatividade e manipulação de requisições AJAX
º PHP: Para a lógica de servidor
º MySQL: Para o banco de dados
º Laragon: Como ambiente de desenvolvimento local

## Instalação e Configuração
1. Clone o repositório:
## git clone https://github.com/joaoNazareno/To-Do-List.git

2. Navegue até o diretório do projeto:
## cd To-Do-List

3. Configure o banco de dados:
º Crie um novo banco de dados MySQL chamado `todo_list`.
º Importe o arquivo `todo_list.sql` fornecido para configurar as tabelas necessárias:
## mysql -u yourusername -p todo_list < todo_list.sql

4. Configure a conexão com o banco de dados:
º Abra o arquivo `db_conn.php` no diretório `app`.
º Atualize as credenciais do banco de dados (host, nome de usuário, senha, nome do banco de dados) conforme sua configuração local.

5. Inicie o servidor:
º Abra o Laragon.
º Inicie os serviços Apache e MySQL.
º Certifique-se de que o projeto está localizado no diretório `www` do Laragon.

6. Acesse a aplicação:
º Abra um navegador web e navegue até `http://localhost/To-Do-List`.


## Estrutura do Projeto

To-Do-List/
│
├── app/
│   ├── add.php
│   ├── check.php
│   ├── db_conn.php
│   ├── edit.php
│   ├── remove.php
│   └── update.php
│
├── css/
│   └── style.css
│
├── img/
│   ├── f.png
│   └── Ellipsis.gif
│
├── js/
│   └── jquery-3.2.1.min.js
│
├── index.php
├── README.md
└── todo_list.sql


## Uso

º Adicionar uma Tarefa:

        Insira a tarefa no campo de entrada e clique em "Incluir".
º Editar uma Tarefa:

        Clique no botão "Editar" ao lado da tarefa, faça as alterações e clique em "Salvar".
º Marcar uma Tarefa como Concluída:

        Clique na caixa de seleção ao lado da tarefa.
º Excluir uma Tarefa:

        Clique no botão "x" ao lado da tarefa.


## Contribuição

Sinta-se à vontade para fazer um fork deste repositório, fazer alterações e enviar pull requests. Qualquer contribuição é bem-vinda!

## Licença
Este projeto é licenciado sob a Licença MIT.




## By João Nazareno
