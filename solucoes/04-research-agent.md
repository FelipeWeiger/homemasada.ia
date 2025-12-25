# Research Agent (Agente de Pesquisa com IA)

> "Pesquisa que levaria 2 dias entregue em 20 minutos. Estruturada, com fontes, pronta pra usar."

---

## O Que É

Agente de IA que faz pesquisas profundas e estruturadas automaticamente. Coleta informações de múltiplas fontes, organiza, analisa e entrega um relatório pronto - seja sobre mercado, concorrentes, leads, tendências ou qualquer tema.

Não é uma busca no Google. É um pesquisador incansável que cruza dados, cita fontes e entrega insights acionáveis.

---

## Problema Que Resolve

| Dor | Impacto |
|-----|---------|
| Pesquisa manual consome tempo | Analista gasta dias compilando informações |
| Informação desatualizada | Relatórios de meses atrás não servem |
| Falta de profundidade | Pesquisa superficial leva a decisões ruins |
| Custo de consultoria | Relatórios de mercado custam R$ 10-50k |
| Inconsistência | Cada pessoa pesquisa de um jeito |

---

## Para Quem

**Ideal para:**
- Consultorias (pesquisa pra clientes)
- Vendas B2B (pesquisar empresa antes de reunião)
- M&A / Investidores (due diligence)
- Marketing (análise de concorrentes)
- Produto (pesquisa de mercado)
- Jurídico (pesquisa de jurisprudência)

**Casos de uso comprovados:**
- Briefing de conta antes de call de vendas
- Análise competitiva automatizada
- Monitoramento de mercado/tendências
- Pesquisa de leads com contexto profundo

---

## Como Funciona

```
Define tema/pergunta de pesquisa
            ↓
Agente planeja estratégia de busca
            ↓
Coleta dados de múltiplas fontes
(web, APIs, bases de dados)
            ↓
Processa e estrutura informações
            ↓
Gera relatório com insights + fontes
            ↓
Entrega onde precisar
(email, Slack, Notion, CRM)
```

---

## Stack Técnico

| Componente | Ferramenta |
|------------|------------|
| Web scraping | Firecrawl, Apify, Browserless |
| Pesquisa inteligente | Perplexity API, Tavily, SerpAPI |
| Processamento | Claude, GPT-4 |
| Orquestração | n8n, LangChain |
| Armazenamento | Supabase, Notion |
| Entrega | Email, Slack, Notion, Google Docs |

---

## Preço Referência

| Tipo | Valor |
|------|-------|
| Setup do agente | R$ 5.000 - 15.000 |
| Por pesquisa (sob demanda) | R$ 200 - 1.000 |
| Pacote mensal (X pesquisas) | R$ 2.000 - 5.000/mês |
| Monitoramento contínuo | R$ 1.500 - 4.000/mês |

---

## Tipos de Pesquisa

### 1. Briefing de Conta (Vendas B2B)
**Input:** Nome da empresa
**Output em 5 minutos:**
- Overview da empresa (tamanho, faturamento, setor)
- Tecnologias que usam
- Notícias recentes
- Dores prováveis do setor
- Pontos de entrada pra conversa
- Perfil dos decisores no LinkedIn

### 2. Análise Competitiva
**Input:** Lista de concorrentes
**Output:**
- Posicionamento de cada um
- Preços praticados
- Pontos fortes e fracos
- Movimentos recentes
- Oportunidades de diferenciação

### 3. Pesquisa de Mercado
**Input:** Setor/nicho
**Output:**
- Tamanho do mercado
- Players principais
- Tendências
- Regulamentações
- Oportunidades e ameaças

### 4. Due Diligence Light
**Input:** Empresa alvo
**Output:**
- Histórico da empresa
- Sócios e estrutura
- Processos judiciais
- Presença digital
- Red flags

### 5. Monitoramento de Tendências
**Input:** Tema/keywords
**Output semanal:**
- Novidades relevantes
- Artigos e papers
- Movimentos de mercado
- Oportunidades identificadas

---

## Prova de Mercado

- Consultorias cobram R$ 10-50k por relatórios de mercado
- Vendedores B2B gastam 6h/semana pesquisando prospects (LinkedIn 2024)
- Empresas com sales intelligence têm 35% mais conversão
- Mercado de AI research tools cresce 40%/ano

---

## ROI Típico

### Exemplo: Time de Vendas B2B (5 vendedores)

**Antes:**
- 1h pesquisando antes de cada reunião
- 20 reuniões/semana = 20h de pesquisa
- Custo: R$ 2.500/semana (tempo dos vendedores)
- Qualidade: Inconsistente

**Depois:**
- Briefing automático em 5 minutos
- Tempo de pesquisa: 2h/semana (só revisar)
- Custo: R$ 1.000/mês (sistema)
- Qualidade: Sempre profundo e estruturado

**Economia:** R$ 8.500/mês
**ROI:** 850%

---

## Exemplos de Output

### Briefing de Conta (resumido)

```
## TechCorp Brasil

**Overview**
- Fintech de pagamentos B2B
- Fundada em 2019, São Paulo
- 150-200 funcionários (LinkedIn)
- Série B de R$ 80M (2023)

**Stack Tecnológico**
- AWS, Node.js, React
- Salesforce CRM
- Slack, Notion

**Notícias Recentes**
- Lançou produto de antecipação de recebíveis (Out/2024)
- Contratando time de AI (3 vagas abertas)

**Dores Prováveis**
- Escala de atendimento ao cliente
- Integração entre sistemas internos
- Onboarding de clientes

**Decisores**
- João Silva - CTO (conectar via AI/automação)
- Maria Santos - COO (conectar via eficiência operacional)

**Sugestão de Abordagem**
Focar em automação de onboarding - dor clara de fintechs em escala.
```

---

## Próximos Passos Para Vender

1. **Criar agente de briefing de vendas** - Use pra sua própria prospecção
2. **Documentar economia de tempo** - "Pesquisa que levava 1h, agora leva 5min"
3. **Oferecer pra times de vendas B2B** - Dor clara, ROI óbvio
4. **Modelo freemium** - "Faço 3 briefings grátis, você vê o valor"

---

## Objeções Comuns

| Objeção | Resposta |
|---------|----------|
| "Já uso Google" | "Google te dá links. Isso te dá relatório pronto, estruturado, com insights." |
| "Não confio na qualidade" | "Todas as informações vêm com fonte. Você pode verificar qualquer dado." |
| "Meu time já faz isso" | "Quanto tempo por semana? Isso libera seu time pra vender, não pesquisar." |
| "Dados podem estar errados" | "IA cruza múltiplas fontes. Erros são mais raros que pesquisa manual apressada." |

---

## Níveis de Complexidade

### Nível 1 - Briefing Rápido (R$ 5-8k)
- Pesquisa de empresas/pessoas
- Template fixo de output
- Entrega por email/Slack
- Sem monitoramento

### Nível 2 - Pesquisa Profunda (R$ 10-15k)
- Múltiplos tipos de pesquisa
- Templates customizados
- Integração com CRM
- Fontes premium (APIs pagas)

### Nível 3 - Intelligence Platform (R$ 20k+)
- Monitoramento contínuo
- Alertas automáticos
- Dashboard de insights
- Histórico e tendências
- API para outros sistemas

---

## Integrações Comuns

| Sistema | Uso |
|---------|-----|
| Pipedrive/HubSpot | Auto-enrichment de leads |
| Slack | Entrega de relatórios |
| Notion | Base de conhecimento |
| Google Docs | Relatórios formatados |
| Email | Briefings antes de reuniões |

---

## Diferencial vs. Ferramentas Prontas

| Aspecto | Ferramentas Prontas | Research Agent Custom |
|---------|--------------------|-----------------------|
| Customização | Template fixo | Seu formato, suas perguntas |
| Fontes | Limitadas | Qualquer fonte pública |
| Integração | APIs genéricas | Conecta com seus sistemas |
| Custo | $$/usuário/mês | Custo fixo, uso ilimitado |
| Output | Padronizado | Exatamente o que você precisa |

---

## Status

[x] Posso entregar hoje
[ ] Preciso validar
[ ] Preciso aprender
