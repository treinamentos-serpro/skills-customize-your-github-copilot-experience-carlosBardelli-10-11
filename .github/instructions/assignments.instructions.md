---
description: "Instruções para usar sempre que criar ou editar arquivos markdown de assignment, garantindo consistência e clareza para os alunos."
applyTo: "assignments/**/*.md"
---

# Diretrizes para Arquivos Markdown de Tarefas

Todos os arquivos Markdown de tarefas devem seguir o template do projeto:

## Estrutura obrigatória

- Use [`templates/assignment-template.md`](../../templates/assignment-template.md) como base para cada tarefa.
- Salve o conteúdo da tarefa em `README.md` dentro da pasta correspondente em `assignments/`.
- Mantenha todas as seções e os títulos do template, nesta ordem:
   - `# 📘 Atividade: [Título da Atividade]`
   - `## 🎯 Objetivo`
   - `## 📝 Tarefas`
   - Para cada tarefa, `### 🛠️ [Título da Tarefa]`, seguido de `#### Descrição` e `#### Requisitos`.

## Orientações de conteúdo

- Preserve o texto dos títulos e os emojis exatamente como aparecem no template. Não traduza nem renomeie os cabeçalhos.

- No título da atividade e nos títulos das tarefas, use nomes curtos, claros e descritivos.
- Em `Objetivo`, resuma em uma ou duas frases o que o aluno aprenderá ou construirá.
- Em `Descrição`, explique claramente a ação que o aluno deve realizar.
- Em `Requisitos`, liste em marcadores os resultados esperados, com critérios específicos e verificáveis.
- Inclua exemplos de entrada e saída em blocos de código quando ajudarem a esclarecer o resultado esperado.
- Escreva o conteúdo em português claro e adequado ao nível dos alunos, salvo quando a atividade exigir outro idioma.

Não remova seções obrigatórias nem adicione seções que não existam no template, a menos que isso seja solicitado explicitamente.