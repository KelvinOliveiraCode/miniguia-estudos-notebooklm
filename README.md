# miniguia-estudos-notebooklm — Miniguia de Estudos: Engenharia de Prompts com NotebookLM

![Status](https://img.shields.io/badge/Status-Concludido-2EA44F?style=flat-square)
![Google NotebookLM](https://img.shields.io/badge/Google_NotebookLM-Study_Tool-4285F4?style=flat-square&logo=googlegemini&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-10_Experiments-764ABC?style=flat-square)
![Markdown](https://img.shields.io/badge/Markdown-083FA1?style=flat-square&logo=markdown&logoColor=white)
![DIO](https://img.shields.io/badge/DIO-Desafio-9046F5?style=flat-square)

> Caderno temático do projeto: https://notebooklm.google.com/notebook/51ff79c0-4835-4d17-a536-f61670f03d00

**Miniguia de Estudos — Engenharia de Prompts com NotebookLM** é um guia prático documentado com experimentos reais, não teoria copiada: cada um dos 10 prompts testados no NotebookLM tem seu resultado observado e o aprendizado registrado. O tema escolhido foi Engenharia de Prompts para IA Generativa, estudada sobre curadoria de fontes oficiais (OpenAI, Google AI, Microsoft Learn, Anthropic e Prompt Engineering Guide) e organizada em um caderno temático único. A proposta é usar o NotebookLM como ferramenta de aprendizagem ativa — o repositório é o registro completo dessa metodologia: fontes, experimentos, troubleshooting e os prompts reutilizáveis que sobreviveram aos testes.

---

## 🇧🇷 Português

### Sobre

Guia prático documentado com experimentos reais de engenharia de prompts dentro do NotebookLM, desenvolvido como desafio de projeto da DIO sobre aprendizagem ativa com IA. O material é reutilizável: serve tanto como revisão de engenharia de prompts quanto como template metodológico para estudar qualquer tema via NotebookLM.

### Objetivos

- Compreender os fundamentos da Engenharia de Prompts
- Conhecer as principais técnicas usadas com modelos de IA Generativa
- Aprender boas práticas de construção de prompts eficientes
- Identificar erros comuns na elaboração de prompts
- Desenvolver material de revisão baseado em documentação oficial
- Usar o NotebookLM como ferramenta de organização do conhecimento

### Curadoria de fontes

As fontes alimentadas no NotebookLM são todas documentação oficial:

| Fonte | Link |
|---|---|
| OpenAI — Prompt Engineering Guide | https://platform.openai.com/docs/guides/prompt-engineering |
| Google AI — Prompt Design Guide | https://ai.google.dev/gemini-api/docs/prompting-intro |
| Microsoft Learn — Prompt Engineering | https://learn.microsoft.com/azure/ai-foundry/openai/concepts/prompt-engineering |
| Anthropic — Prompt Engineering Overview | https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview |
| Prompt Engineering Guide | https://www.promptingguide.ai/ |

### Os 10 experimentos

Cada prompt foi documentado individualmente com resultado observado e aprendizado:

| # | Prompt | Resultado | Aprendizado |
|---|---|---|---|
| 1 | `Explique Engenharia de Prompts como se eu fosse um iniciante.` | Visão geral clara, porém superficial | Prompts introdutórios funcionam melhor quando pedem exemplos |
| 2 | `Explique Engenharia de Prompts utilizando exemplos em Python.` | Resposta significativamente mais útil | — |
| 3 | `Faça uma tabela comparando Zero-shot, One-shot e Few-shot Prompting.` | Tabela facilitou bastante a compreensão | — |
| 4 | `Explique Chain of Thought passo a passo utilizando exemplos.` | Compreensão melhor da técnica | — |
| 5 | `Resuma todo o conteúdo em apenas uma página.` | Excelente para revisões rápidas | — |
| 6 | `Gere 20 perguntas de revisão com respostas.` | Material útil para autoavaliação | — |
| 7 | `Gere um mapa mental em formato textual.` | Boa organização das ideias | — |
| 8 | `Explique quais erros iniciantes cometem ao escrever prompts.` | Listou problemas frequentes e soluções | — |
| 9 | `Crie um roteiro de estudos de 7 dias utilizando este material.` | Plano consistente e organizado | — |
| 10 | `Utilize apenas as informações presentes nas fontes anexadas.` | Respostas mais confiáveis e alinhadas ao material | — |

### Cicatrizes (Troubleshooting)

Problemas reais encontrados durante os testes, com exemplo e solução:

| Problema | Exemplo | Solução |
|---|---|---|
| Prompt muito genérico | `Explique IA.` → resposta superficial | Adicionar contexto: `Explique Inteligência Artificial Generativa para um desenvolvedor iniciante utilizando exemplos.` |
| Respostas muito longas | — | Limitar o tamanho: `Responda em até 10 linhas.` |
| Informações além das fontes | — | `Utilize apenas as fontes anexadas.` |
| Poucos exemplos | — | `Inclua exemplos práticos.` |

### Técnicas cobertas no guia

Zero-shot, One-shot, Few-shot, Chain of Thought, Role Prompting e Context Prompting — definidas com exemplos no material, junto de glossário (prompt, LLM, token, contexto, hallucination, context window) e prompts reutilizáveis para resumo, revisão, flashcards, mapa mental, perguntas de entrevista e exemplos em Python.

### Organização do caderno

O NotebookLM foi estruturado em 15 seções: Objetivo do Estudo, Resumo Geral, Glossário, Técnicas, Boas Práticas, Erros Comuns, Comparação entre Técnicas, Perguntas de Revisão, Flashcards, Quiz, Mapa Mental, Plano de Estudos, Resumo Executivo, Perguntas de Entrevista e Exemplos em Python.

---

## 🇺🇸 English

### About

A practical guide documented with real prompt engineering experiments inside NotebookLM, built as a DIO project challenge on active learning with AI. The material is reusable: it works both as a prompt engineering review and as a methodological template for studying any topic through NotebookLM.

### Goals

- Understand prompt engineering fundamentals
- Learn the main techniques used with generative AI models
- Learn best practices for building efficient prompts
- Identify common prompt-writing mistakes
- Build review material grounded in official documentation
- Use NotebookLM as a knowledge organization tool

### Source curation

All sources fed into NotebookLM are official documentation: OpenAI's Prompt Engineering Guide, Google AI's Prompt Design Guide, Microsoft Learn's Prompt Engineering, Anthropic's Prompt Engineering Overview, and promptingguide.ai.

### The 10 experiments

Each prompt was documented individually with observed result and takeaway. Highlights: asking for Python examples (prompt 2) made answers significantly more useful; comparative tables (prompt 3) clarified technique differences; grounding ("use only the attached sources", prompt 10) made responses more reliable and aligned with the material. Full detail, prompt by prompt, in the sections below.

| # | Prompt | Observed result |
|---|---|---|
| 1 | Beginner-level explanation request | Clear but shallow overview |
| 2 | Explain with Python examples | Significantly more useful response |
| 3 | Comparison table: Zero/One/Few-shot | Table made comprehension much easier |
| 4 | Chain of Thought, step by step | Better understanding of the technique |
| 5 | One-page summary | Excellent for quick review |
| 6 | 20 review questions with answers | Useful self-assessment material |
| 7 | Textual mind map | Good idea organization |
| 8 | Common beginner mistakes | Listed frequent problems and fixes |
| 9 | 7-day study plan | Consistent, organized plan |
| 10 | "Use only the attached sources" | More reliable, source-aligned answers |

### Scars (Troubleshooting)

Real problems hit during testing, each with example and fix: overly generic prompts (`Explain AI.` → superficial; fix: add context and audience), overly long answers (fix: cap length, "answer in at most 10 lines"), information beyond the sources (fix: "use only the attached sources"), and too few examples (fix: "include practical examples").

### Techniques covered in the guide

Zero-shot, One-shot, Few-shot, Chain of Thought, Role Prompting, and Context Prompting — defined with examples, plus a glossary (prompt, LLM, token, context, hallucination, context window) and reusable prompts for summaries, review, flashcards, mind maps, interview questions, and Python examples.

### Notebook organization

The NotebookLM notebook was structured in 15 sections: Study Goal, General Summary, Glossary, Techniques, Best Practices, Common Mistakes, Technique Comparison, Review Questions, Flashcards, Quiz, Mind Map, Study Plan, Executive Summary, Interview Questions, and Python Examples.

---

## Autor

**Kelvin Oliveira** — [GitHub](https://github.com/KelvinOliveiraCode) · [LinkedIn](https://www.linkedin.com/in/kelvin-oliveira-code/)

## Licença

Projeto educacional, desenvolvido para o desafio da DIO. Sem licença de software formal — os materiais servem como referência de estudo.
