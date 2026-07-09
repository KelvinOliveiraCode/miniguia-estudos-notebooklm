# Miniguia de Estudos - Engenharia de Prompts com NotebookLM

# NotebookLM

O caderno temático utilizado neste projeto pode ser acessado pelo link abaixo:

```
https://notebooklm.google.com/notebook/51ff79c0-4835-4d17-a536-f61670f03d00
```

## Sobre o Projeto

Este repositório foi desenvolvido como parte do desafio de projeto da DIO com o objetivo de explorar o NotebookLM como uma ferramenta de aprendizagem ativa.

O tema escolhido foi **Engenharia de Prompts para Inteligência Artificial Generativa**, por ser uma das competências mais relevantes para profissionais que trabalham com IA atualmente.

Ao longo deste projeto, foram selecionadas fontes oficiais, realizados testes de prompts, analisados os resultados obtidos e consolidado um material de estudo que poderá ser reutilizado futuramente.

---

# Objetivos

Os principais objetivos deste estudo são:

- Compreender os fundamentos da Engenharia de Prompts;
- Conhecer as principais técnicas utilizadas por modelos de IA Generativa;
- Aprender boas práticas para construção de prompts eficientes;
- Identificar erros comuns durante a elaboração de prompts;
- Desenvolver um material de revisão baseado em documentação oficial;
- Utilizar o NotebookLM como ferramenta de organização do conhecimento.

---

# Ferramentas Utilizadas

- NotebookLM
- GitHub
- Markdown
- Inteligência Artificial Generativa

---

# Curadoria de Fontes

As seguintes fontes abertas foram utilizadas para alimentar o NotebookLM:

| Fonte | Link |
|-------|------|
| OpenAI – Prompt Engineering Guide | https://platform.openai.com/docs/guides/prompt-engineering |
| Google AI – Prompt Design Guide | https://ai.google.dev/gemini-api/docs/prompting-intro |
| Microsoft Learn – Prompt Engineering | https://learn.microsoft.com/azure/ai-foundry/openai/concepts/prompt-engineering |
| Anthropic – Prompt Engineering Overview | https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview |
| Prompt Engineering Guide | https://www.promptingguide.ai/ |

---

# Engenharia de Prompts

Durante a construção do caderno temático foram realizados diversos testes para avaliar como pequenas alterações nos prompts impactam a qualidade das respostas produzidas pelo NotebookLM.

## Prompt 1

**Objetivo**

Introduzir o tema.

```text
Explique Engenharia de Prompts como se eu fosse um iniciante.
```

### Resultado

A resposta apresentou uma visão geral clara, porém superficial.

### Aprendizado

Prompts introdutórios funcionam melhor quando solicitam exemplos.

---

## Prompt 2

**Objetivo**

Obter exemplos práticos.

```text
Explique Engenharia de Prompts utilizando exemplos em Python.
```

### Resultado

A resposta tornou-se significativamente mais útil.

---

## Prompt 3

**Objetivo**

Comparar técnicas.

```text
Faça uma tabela comparando Zero-shot, One-shot e Few-shot Prompting.
```

### Resultado

A organização em tabela facilitou bastante a compreensão.

---

## Prompt 4

**Objetivo**

Entender o raciocínio da IA.

```text
Explique Chain of Thought passo a passo utilizando exemplos.
```

### Resultado

Foi possível compreender melhor o funcionamento da técnica.

---

## Prompt 5

**Objetivo**

Produzir um resumo para revisão.

```text
Resuma todo o conteúdo em apenas uma página.
```

### Resultado

Excelente para revisões rápidas.

---

## Prompt 6

**Objetivo**

Fixação do conteúdo.

```text
Gere 20 perguntas de revisão com respostas.
```

### Resultado

Material útil para autoavaliação.

---

## Prompt 7

**Objetivo**

Organizar conceitos.

```text
Gere um mapa mental em formato textual.
```

### Resultado

Boa organização das ideias.

---

## Prompt 8

**Objetivo**

Identificar dificuldades comuns.

```text
Explique quais erros iniciantes cometem ao escrever prompts.
```

### Resultado

Listou problemas frequentes e suas soluções.

---

## Prompt 9

**Objetivo**

Criar um plano de estudos.

```text
Crie um roteiro de estudos de 7 dias utilizando este material.
```

### Resultado

Plano consistente e organizado.

---

## Prompt 10

**Objetivo**

Reduzir respostas fora das fontes.

```text
Utilize apenas as informações presentes nas fontes anexadas.
```

### Resultado

As respostas tornaram-se mais confiáveis e alinhadas ao material estudado.

---

# Cicatrizes (Troubleshooting)

Durante os testes alguns problemas foram identificados.

## Problema

Prompt muito genérico.

### Exemplo

```text
Explique IA.
```

### Resultado

Resposta superficial.

### Solução

Adicionar contexto.

```text
Explique Inteligência Artificial Generativa para um desenvolvedor iniciante utilizando exemplos.
```

---

## Problema

Respostas muito longas.

### Solução

Limitar o tamanho.

```text
Responda em até 10 linhas.
```

---

## Problema

Informações além das fontes.

### Solução

```text
Utilize apenas as fontes anexadas.
```

---

## Problema

Poucos exemplos.

### Solução

```text
Inclua exemplos práticos.
```

---

# Miniguia de Estudo

## O que é Engenharia de Prompts?

Engenharia de Prompts consiste na elaboração de instruções claras e estruturadas para que modelos de Inteligência Artificial produzam respostas mais precisas, úteis e contextualizadas.

---

## Principais Técnicas

### Zero-shot Prompting

Nenhum exemplo é fornecido ao modelo.

Exemplo:

```text
Traduza este texto para inglês.
```

---

### One-shot Prompting

Um exemplo é apresentado antes da solicitação.

---

### Few-shot Prompting

São fornecidos vários exemplos para orientar o modelo.

---

### Chain of Thought

Incentiva o modelo a explicar seu raciocínio antes da resposta final.

---

### Role Prompting

Define um papel para o modelo.

Exemplo:

```text
Você é um professor de Ciência da Computação.
```

---

### Context Prompting

Adiciona informações extras para contextualizar a tarefa.

---

# Glossário

| Conceito | Definição |
|----------|-----------|
| Prompt | Instrução enviada ao modelo de IA. |
| LLM | Large Language Model. |
| Token | Unidade de texto processada pelo modelo. |
| Contexto | Informações adicionais fornecidas ao modelo. |
| Hallucination | Resposta criada sem suporte nas fontes utilizadas. |
| Zero-shot | Técnica sem exemplos. |
| One-shot | Técnica utilizando um exemplo. |
| Few-shot | Técnica utilizando vários exemplos. |
| Chain of Thought | Explicação passo a passo do raciocínio. |
| Role Prompting | Técnica que atribui um papel ao modelo. |
| Context Window | Quantidade máxima de informações consideradas pelo modelo durante a resposta. |

---

# Prompts Reutilizáveis

## Resumo

```text
Resuma este documento destacando apenas os conceitos mais importantes.
```

## Explicação para iniciantes

```text
Explique este conteúdo como se eu estivesse estudando o assunto pela primeira vez.
```

## Revisão

```text
Crie 20 perguntas com respostas utilizando apenas as fontes anexadas.
```

## Mapa Mental

```text
Organize este conteúdo em formato de mapa mental textual.
```

## Flashcards

```text
Transforme este conteúdo em flashcards.
```

## Perguntas para entrevistas

```text
Crie perguntas de entrevista técnica com respostas comentadas.
```

## Exemplos em programação

```text
Mostre exemplos utilizando Python.
```

## Revisão rápida

```text
Resuma todo o conteúdo em apenas uma página.
```

## Aprofundamento

```text
Explique cada conceito utilizando exemplos e analogias.
```

## Respostas fundamentadas

```text
Responda exclusivamente utilizando as informações presentes nas fontes anexadas.
```

---

# Organização do NotebookLM

O NotebookLM foi estruturado da seguinte forma:

```text
NotebookLM
│
├── 01 - Objetivo do Estudo
├── 02 - Resumo Geral
├── 03 - Glossário
├── 04 - Técnicas de Prompt Engineering
├── 05 - Boas Práticas
├── 06 - Erros Comuns
├── 07 - Comparação entre Técnicas
├── 08 - Perguntas de Revisão
├── 09 - Flashcards
├── 10 - Quiz
├── 11 - Mapa Mental
├── 12 - Plano de Estudos
├── 13 - Resumo Executivo
├── 14 - Perguntas de Entrevista
└── 15 - Exemplos em Python
```

---

---

# Conclusão

A utilização do NotebookLM demonstrou como a Inteligência Artificial pode atuar como uma ferramenta de apoio à aprendizagem quando combinada com documentação oficial e uma boa Engenharia de Prompts.

A organização das fontes, a experimentação com diferentes estratégias de prompting e a consolidação do conhecimento em um único caderno permitiram construir um material de estudo reutilizável, confiável e de fácil consulta.

---



---

Projeto desenvolvido como parte do desafio de projeto da **Digital Innovation One (DIO)**, utilizando o NotebookLM para estudo dirigido sobre Engenharia de Prompts em Inteligência Artificial Generativa.
