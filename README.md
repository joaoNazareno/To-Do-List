

---

<br>

[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=DC143C&size=35&center=true&vCenter=true&width=1000&lines=TO-DO+LIST+PROJECT;Gerencie+suas+tarefas+facilmente!)](https://git.io/typing-svg)

## Como Rodar o Projeto

### Pré-requisitos

- ![PHP](https://img.shields.io/badge/-PHP-0D1117?style=for-the-badge&logo=php&labelColor=0D1117)&nbsp; 8.0+
- ![MySQL](https://img.shields.io/badge/-MySQL-0D1117?style=for-the-badge&logo=mysql&labelColor=0D1117)&nbsp;
- ![Laragon](https://img.shields.io/badge/-Laragon-0D1117?style=for-the-badge&logo=laragon&labelColor=0D1117)&nbsp;

### Configuração

1. **Clone o Repositório:**
   ```bash
   git clone https://github.com/joaoNazareno/To-Do-List.git
   cd To-Do-List
   ```

2. **Configure o Banco de Dados:**
   - Crie um banco de dados MySQL chamado `todo_list`.
   - Importe o arquivo `todo_list.sql`:
   ```bash
   mysql -u seu_usuario -p todo_list < todo_list.sql
   ```

3. **Atualize as Credenciais no Arquivo `db_conn.php`:**
   - No diretório `app/`, abra `db_conn.php` e configure as credenciais do banco de dados conforme necessário.

4. **Inicie o Servidor Laragon:**
   - Abra o Laragon e inicie os serviços Apache e MySQL.
   - Certifique-se de que o projeto esteja no diretório `www` do Laragon.

5. **Acesse a Aplicação:**
   - Navegue até `http://localhost/To-Do-List`.

## Funcionalidades

- **Adicionar** novas tarefas.
- **Marcar** tarefas como concluídas.
- **Editar** tarefas existentes.
- **Excluir** tarefas.

## Estrutura do Projeto

```plaintext
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
```

---

**By João Nazareno 🦅**

--- 

