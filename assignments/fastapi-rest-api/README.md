# 📘 Atividade: Construindo uma API REST com FastAPI

## 🎯 Objetivo

Construa uma API REST para gerenciar tarefas usando FastAPI. Pratique criação de rotas, validação de dados, operações CRUD e respostas com códigos HTTP apropriados.

## 📝 Tarefas

### 🛠️ Criar e executar a aplicação

#### Descrição

Configure uma aplicação FastAPI e crie uma rota simples para confirmar que a API está funcionando.

#### Requisitos
O programa concluído deve:

- Criar uma instância da aplicação FastAPI em `main.py`.
- Disponibilizar uma rota `GET /health` que retorne o JSON `{"status": "ok"}`.
- Permitir iniciar a aplicação com `uvicorn main:app --reload`.
- Disponibilizar a documentação interativa do FastAPI em `/docs`.

### 🛠️ Criar e consultar tarefas

#### Descrição

Implemente operações para criar tarefas e consultar uma tarefa específica ou a lista completa. Nesta etapa, os dados podem ficar armazenados em memória e não precisam persistir após reiniciar a aplicação.

#### Requisitos
O programa concluído deve:

- Definir um modelo de dados com Pydantic para validar o nome da tarefa e, opcionalmente, sua descrição.
- Disponibilizar `GET /tasks` para retornar todas as tarefas, inicialmente como uma lista vazia.
- Disponibilizar `POST /tasks` para criar uma tarefa e retornar o código HTTP `201`.
- Atribuir um identificador único a cada tarefa criada.
- Disponibilizar `GET /tasks/{task_id}` para consultar uma tarefa pelo identificador.
- Retornar o código HTTP `404` quando o identificador solicitado não existir.

### 🛠️ Atualizar e remover tarefas

#### Descrição

Complete a API implementando as operações para atualizar e remover tarefas existentes, mantendo respostas consistentes quando uma tarefa não for encontrada.

#### Requisitos
O programa concluído deve:

- Disponibilizar `PUT /tasks/{task_id}` para atualizar os dados de uma tarefa existente e retornar o código HTTP `200`.
- Disponibilizar `DELETE /tasks/{task_id}` para remover uma tarefa existente e retornar o código HTTP `204` sem conteúdo.
- Retornar o código HTTP `404` ao tentar atualizar ou remover uma tarefa inexistente.
- Permitir testar todas as rotas pela documentação interativa em `/docs`.
