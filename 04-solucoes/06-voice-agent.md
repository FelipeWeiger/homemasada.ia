# Voice Agent (Agente de Voz IA)

> "Ligações 24/7 que qualificam, agendam e convertem - sem contratar SDR."

---

## O Que É

Agente de IA que faz e recebe ligações telefônicas de forma autônoma. Conversa naturalmente, entende contexto, qualifica leads, agenda reuniões, faz follow-ups - tudo por voz.

Não é aquela URA robótica. É uma conversa real, com voz natural, que os clientes não percebem que é IA.

---

## Problema Que Resolve

| Dor | Impacto |
|-----|---------|
| Custo de SDR/atendentes | R$ 5-10k/mês por funcionário |
| Horário limitado | Ligações só em horário comercial |
| Inconsistência | Cada atendente faz diferente |
| Escalabilidade | Não consegue ligar pra 1000 pessoas/dia |
| No-shows | Cliente agenda e não aparece |

---

## Para Quem

**Ideal para:**
- Clínicas/Consultórios (agendamento, confirmação, lembretes)
- Imobiliárias (qualificação inicial, agendamento de visitas)
- Escolas/Cursos (captação, follow-up de interessados)
- Financeiras (cobrança, renegociação)
- Qualquer empresa com alto volume de ligações

**Casos de uso comprovados:**
- Outbound: Prospecção, follow-up de leads
- Inbound: Atendimento 24/7, triagem, agendamento
- Confirmação: Lembrete de consultas, redução de no-show

---

## Como Funciona

```
Lead entra no sistema (CRM, formulário, lista)
            ↓
Voice Agent liga automaticamente
            ↓
Conversa natural (qualifica, responde dúvidas)
            ↓
   ┌────────┼────────┐
   ↓        ↓        ↓
Agenda    Marca     Transfere
reunião   follow-up  pra humano
   ↓        ↓        ↓
Atualiza CRM + notifica time
```

---

## Stack Técnico

| Componente | Ferramenta |
|------------|------------|
| Plataforma de voz | VAPI, Bland.ai, Retell.ai |
| Voz sintética | ElevenLabs, PlayHT |
| Telefonia | Twilio, Vonage |
| LLM | Claude, GPT-4 |
| Orquestração | n8n |
| CRM | Pipedrive, HubSpot |

---

## Preço Referência

| Tipo | Valor |
|------|-------|
| Implementação | R$ 8.000 - 20.000 |
| Recorrente | R$ 500 - 2.000/mês |
| Por minuto (alternativo) | R$ 0,50 - 2,00/min |

---

## Prova de Mercado

- **AI Voice Fundraising (Liam Ottley):** Vendido por $24.000
  - $2.400/mês por 10 meses + ~$1.000/mês de uso
  - Agente outbound para ONGs fazer captação de doações
  - Conversas personalizadas por doador

- Mercado de voice AI: $2.4B (2024) → $47.5B (2034) - CAGR 34.8%
- 68% dos clientes preferem voice AI a IVR tradicional (Gartner)
- 41% preferem IA a humanos para tarefas simples

---

## ROI Típico

### Exemplo: Clínica com Confirmação de Consultas

**Antes:**
- Recepcionista liga pra 50 pacientes/dia
- Taxa de no-show: 25%
- Custo: R$ 3.000/mês (tempo da funcionária)
- Perda por no-show: R$ 15.000/mês

**Depois:**
- Voice Agent liga automaticamente
- Taxa de no-show: 8% (lembrete + confirmação)
- Custo: R$ 1.500/mês
- Economia total: R$ 16.500/mês

---

## Próximos Passos Para Vender

1. **Estudar VAPI ou Bland.ai** - Criar primeiro agente funcional
2. **Criar demo de nicho** - Ex: agendamento de consultas
3. **Gravar exemplo de ligação** - Mostrar qualidade da conversa
4. **Prospectar clínicas** - Dor clara, volume alto, ROI óbvio

---

## O Que Preciso Aprender

- [ ] Setup de VAPI ou Bland.ai
- [ ] Integração com Twilio
- [ ] Prompt engineering para voz (diferente de texto)
- [ ] Handling de interrupções e silêncios
- [ ] Integração com calendário para agendamento

---

## Objeções Comuns

| Objeção | Resposta |
|---------|----------|
| "Clientes não gostam de robô" | "A voz é indistinguível de humano. Posso te ligar agora pra você testar." |
| "Preciso de atendimento humanizado" | "O agente faz a triagem. Casos complexos vão pro humano. Você ganha tempo." |
| "E se der problema?" | "Monitoramento em tempo real. Qualquer anomalia, sou notificado." |

---

## Níveis de Complexidade

### Nível 1 - Confirmação (R$ 8-12k)
- Liga pra confirmar agendamentos
- Script simples: confirma, reagenda ou cancela
- Atualiza sistema automaticamente

### Nível 2 - Qualificação (R$ 12-18k)
- Qualifica leads inbound
- Perguntas de descoberta
- Agenda reunião se qualificado

### Nível 3 - Outbound Completo (R$ 18-25k)
- Prospecção ativa
- Múltiplos fluxos de conversa
- Integração completa com CRM
- Follow-up automatizado

---

## Status

[ ] Posso entregar hoje
[x] Preciso validar
[ ] Preciso aprender
