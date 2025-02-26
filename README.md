# ✅ API RESTful para Gerenciamento de Tarefas

Este projeto é uma API RESTful desenvolvida com Flask para gerenciar tarefas. A API permite operações CRUD completas e inclui testes automatizados utilizando PyTest.

## 🚀 Tecnologias Utilizadas
- Python
- Flask
- Flask-RESTful
- SQLite (ou PostgreSQL para produção)
- PyTest para testes automatizados

## 📌 Funcionalidades
A API fornece um CRUD completo para o gerenciamento de tarefas:
- **Criar Tarefa**: Adicionar uma nova tarefa.
- **Listar Tarefas**: Obter todas as tarefas cadastradas.
- **Obter Detalhes de uma Tarefa**: Visualizar informações detalhadas de uma tarefa específica.
- **Atualizar Tarefa**: Modificar dados de uma tarefa existente.
- **Excluir Tarefa**: Remover uma tarefa.

## 📦 Instalação e Configuração
### 1. Clone o repositório:
```bash
$ git clone https://github.com/seu-usuario/nome-do-repositorio.git
$ cd nome-do-repositorio
```

### 2. Crie um ambiente virtual e ative-o:
```bash
$ python -m venv venv
$ source venv/bin/activate  # Para Linux/Mac
$ venv\Scripts\activate  # Para Windows
```

### 3. Instale as dependências:
```bash
$ pip install -r requirements.txt
```

### 4. Execute a aplicação:
```bash
$ flask run
```
A API estará disponível em `http://127.0.0.1:5000/`

## 📖 Endpoints Principais
### Tarefas
- `GET /tasks/` → Lista todas as tarefas.
- `POST /tasks/` → Cria uma nova tarefa.
- `GET /tasks/{id}/` → Obtém detalhes de uma tarefa específica.
- `PUT /tasks/{id}/` → Atualiza uma tarefa.
- `DELETE /tasks/{id}/` → Exclui uma tarefa.

## 🛠️ Testes Automatizados
Para rodar os testes automatizados com PyTest, utilize o comando:
```bash
$ pytest
```


Desenvolvido por [William Amaral Franco](https://github.com/willfranco) 🚀

