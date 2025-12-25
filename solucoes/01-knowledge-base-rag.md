# Base de Conhecimento com IA (RAG)

> "Funcionários gastam 24% do dia buscando informação. E se um chat respondesse tudo em segundos?"

---

## O Que É

Sistema de chat interno que centraliza todo o conhecimento da empresa (documentos, processos, histórico) e permite que qualquer funcionário encontre informações instantaneamente, fazendo perguntas em linguagem natural.

Usa RAG (Retrieval-Augmented Generation): a IA busca nos documentos relevantes e responde com contexto real da empresa, não com alucinações.

---

## Problema Que Resolve

| Dor | Impacto |
|-----|---------|
| Conhecimento espalhado | Docs no Drive, Notion, email, cabeça das pessoas |
| Perguntas repetitivas ao time | "Onde fica o modelo de contrato?" 50x/mês |
| Onboarding lento | Novo funcionário leva semanas pra se achar |
| Dependência de pessoas-chave | "Só o João sabe como funciona isso" |
| Perda de conhecimento | Funcionário sai, conhecimento vai junto |

---

## Para Quem

**Ideal para:**
- Empresas com 20+ funcionários
- Operações com muitos processos documentados
- Times de suporte/CS (acesso rápido a info)
- Empresas com alta rotatividade
- Indústrias reguladas (compliance, SOPs)

**Não funciona bem para:**
- Empresas muito pequenas (< 10 pessoas)
- Negócios sem documentação existente

---

## Como Funciona

```
Conecta fontes de dados
(Notion, Drive, Confluence, PDFs, etc.)
            ↓
Processa e cria embeddings
(transforma texto em vetores semânticos)
            ↓
Armazena em banco vetorial
(Pinecone, Supabase, Qdrant)
            ↓
Funcionário pergunta no chat
"Como faço pra solicitar férias?"
            ↓
Sistema busca documentos relevantes
            ↓
IA responde com base nos docs
+ cita a fonte original
```

---

## Stack Técnico

| Componente | Ferramenta |
|------------|------------|
| Fontes de dados | Notion API, Google Drive API, Confluence, PDFs |
| Embeddings | OpenAI, Cohere, Voyage AI |
| Banco vetorial | Supabase pgvector, Pinecone, Qdrant |
| LLM | Claude, GPT-4 |
| Interface | Slack bot, Teams bot, web app |
| Orquestração | n8n, LangChain |

---

## Preço Referência

| Tipo | Valor |
|------|-------|
| Implementação | R$ 10.000 - 30.000 |
| Recorrente | R$ 1.000 - 3.000/mês |

**Variáveis de preço:**
- Volume de documentos
- Número de fontes de dados
- Complexidade das integrações
- Número de usuários

---

## Prova de Mercado

- **Ask Manny (Liam Ottley):** Vendido por $19.600/ano
  - Sistema RAG para indústria manufatureira
  - Integrado com Azure + Microsoft Teams
  - Resolve problema de 24-33% do tempo buscando informação

- **JPMorgan LLM Suite:** 250.000 funcionários usando sistema interno de conhecimento
- Gartner: 80% das empresas terão alguma forma de knowledge management com IA até 2026

---

## ROI Típico

| Métrica | Antes | Depois |
|---------|-------|--------|
| Tempo buscando info | 2h/dia | 15min/dia |
| Tempo de onboarding | 4 semanas | 1 semana |
| Perguntas repetitivas ao time | 50/semana | 5/semana |
| Dependência de pessoas-chave | Alta | Baixa |

**Cálculo rápido:**
- 50 funcionários x 1.5h economizada/dia x R$ 50/hora = R$ 3.750/dia
- ROI em < 2 meses

---

## Próximos Passos Para Vender

1. **Criar demo com dados genéricos** - Policies de RH, FAQs de produto
2. **Identificar empresas com dor clara** - Crescendo rápido, muita rotatividade
3. **Oferecer piloto** - "Conectamos 3 fontes de dados, você testa por 2 semanas"
4. **Quantificar o problema** - "Quanto tempo seu time gasta respondendo as mesmas perguntas?"

---

## Objeções Comuns

| Objeção | Resposta |
|---------|----------|
| "Já temos Confluence/Notion" | "Ter docs não é o problema. Encontrar é. Quantas vezes alguém perguntou algo que já estava documentado?" |
| "E se a IA responder errado?" | "Sistema cita a fonte. Funcionário pode verificar. Além disso, treinamos com seus dados reais." |
| "Nossos dados são sensíveis" | "Tudo roda em ambiente seguro. Podemos usar Azure/AWS privado. Nada vai pra OpenAI." |
| "É caro" | "Quanto custa 50 funcionários perdendo 1h/dia buscando info? Faz a conta." |

---

## Níveis de Complexidade

### Nível 1 - MVP (R$ 10-15k)
- 1-2 fontes de dados
- Chat via Slack ou web simples
- Respostas básicas com citação

### Nível 2 - Completo (R$ 15-25k)
- Múltiplas fontes de dados
- Atualização automática de docs
- Histórico de conversas
- Analytics de uso

### Nível 3 - Enterprise (R$ 25k+)
- Permissões por cargo/departamento
- Integração com sistemas internos
- SLA de uptime
- Suporte dedicado

---

## Casos de Uso Específicos

### Suporte ao Cliente Interno
- Agente CS pergunta: "Qual a política de reembolso pra produto danificado?"
- Sistema responde com base no manual de políticas

### Onboarding
- Novo funcionário: "Como configuro meu email corporativo?"
- Sistema guia passo a passo com base na documentação de TI

### Vendas
- Vendedor: "Quais cases temos no setor financeiro?"
- Sistema retorna cases, resultados, contatos

### Compliance
- Auditor: "Qual nosso processo de aprovação de fornecedores?"
- Sistema mostra SOP com links para formulários

---

## Status

[x] Posso entregar hoje
[ ] Preciso validar
[ ] Preciso aprender
