
# 🤖 Agente de IA com n8n — Aula 01

![Status](https://img.shields.io/badge/Status-Em%20Andamento-yellow?style=flat)

## 📌 Sobre este projeto

Documentação da primeira aula prática de criação de agentes de IA utilizando o **n8n** como plataforma de orquestração.

> ⚠️ **Nota sobre privacidade:** os prints completos do fluxo não foram incluídos por conterem dados sensíveis de empresa, protegidos pela **LGPD (Lei Geral de Proteção de Dados — Lei nº 13.709/2018)**. Apenas o resultado final de funcionamento foi registrado.

-----

## 🎯 Objetivo da Aula

Criar um agente de IA conectado a dados reais de uma empresa, capaz de responder perguntas dentro de um escopo específico definido na configuração.

-----

## 🧠 Conceitos Aprendidos

### O que é um agente de IA?

Um agente de IA combina um modelo de linguagem (LLM) com ferramentas e fontes de dados, permitindo que ele **aja** no mundo real — não apenas responda.

### Como o n8n funciona nesse contexto?

O n8n atua como o **orquestrador do agente**, definindo:

- De onde o agente busca os dados
- Quais sistemas ele pode acessar
- Como ele deve responder
- Quais assuntos estão dentro do seu escopo

```
[Usuário pergunta]
       ↓
[n8n orquestra]
       ↓
[Agente busca nos dados configurados]
       ↓
[Resposta dentro do escopo definido]
```

### Escopo fechado

O agente **só responde sobre o que foi configurado**. Se foi criado para RH de uma empresa específica, ele responde apenas sobre aquela empresa e aquele contexto.

### Alucinações

Mesmo com escopo configurado, modelos de IA podem **cometer erros ou inventar respostas** — fenômeno chamado de *alucinação*. Isso reforça a importância de validar as respostas e configurar bem as fontes de dados.

-----

## 🛠️ Ferramentas Utilizadas

|Ferramenta                  |Função                                    |
|----------------------------|------------------------------------------|
|**n8n**                     |Orquestração do agente e conexão com dados|
|**LLM (modelo de IA)**      |Raciocínio e geração de respostas         |
|**Base de dados da empresa**|Fonte de informações do agente            |

-----

## ✅ O que foi praticado

- [x] Criação de conta na plataforma n8n
- [x] Configuração do nó de agente de IA
- [x] Conexão com base de dados específica
- [x] Teste de resposta dentro do escopo configurado
- [x] Validação do funcionamento do agente

-----

## 📸 Evidência de funcionamento

> Print do agente funcionando ao final da configuração.

*(imagem a ser adicionada)*

-----

## 📚 Referências

- [Documentação oficial n8n — AI Agents](https://docs.n8n.io/advanced-ai/)
- [O que são agentes de IA — n8n](https://docs.n8n.io/advanced-ai/examples/ai-agent/)
- [LGPD — Lei nº 13.709/2018](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm)

-----

## 👩‍💻 Autora

**Carla Sayonara Freitas**
Estudante de Gestão da Tecnologia da Informação | Foco em Cloud, NOC e Automação

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin)](https://linkedin.com/in/carla-sayonara-freitas-33599b183)
[![GitHub](https://img.shields.io/badge/GitHub-black?style=flat&logo=github)](https://github.com/srtsayonara)