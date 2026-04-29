# Agentes Funcionários — 56 subagentes Claude Code para empresas

56 subagentes especializados que funcionam como **funcionários sem salário** para sua empresa. Cada agente é um especialista em uma função específica do dia-a-dia (tráfego, copy, SDR, follow-up, financeiro, RH, etc.) que atua proativamente quando o contexto bate com sua especialidade.

Diferente das skills (instruções pontuais), agentes são **profissionais virtuais** que entrevistam, executam, validam e escalam.

## Como instalar

1. Clone este repo:
   ```bash
   git clone https://github.com/asv-digital/agents-funcionarios.git
   ```

2. Copie os agentes para o seu projeto Claude Code:
   ```bash
   cp -r agents-funcionarios/agents/* /caminho/do/seu/projeto/.claude/agents/
   ```

   Ou, para uso global: `~/.claude/agents/`.

## Como usar

- **Automático**: "preciso lançar uma campanha no Meta Ads para o produto X" → Claude delega para `trafego-meta-analise-campanha`.
- **Manual**: "use o agente `comercial-sdr` para qualificar essa lista de leads".
- **Em pipeline**: `marketing-persona` → `marketing-campanha` → `trafego-meta-copy-criativo` → `lancamento-pagina`.

## Catálogo (56 agentes)

### Tráfego Pago (01-08)
01 Meta — análise de campanha
02 Meta — relatório de performance
03 Meta — copy de criativo
04 Meta — audiência e segmentação
05 Google — análise de campanha
06 Google — relatório
07 Google — copy de anúncio
08 Lançamento — cronograma

### Lançamento (08-15)
08 Cronograma · 09 Copy · 10 E-mails CPL · 11 E-mails carrinho
12 Métricas · 13 Oferta · 14 Página de vendas · 15 Pós-venda

### Conteúdo & Social (16-22)
16 Instagram copy · 17 Instagram calendário · 18 Instagram roteiro · 19 Instagram hashtag
20 Conteúdo pauta SEO · 21 Conteúdo blog · 22 Conteúdo script vídeo

### WhatsApp (23-26)
23 Atendimento · 24 Disparos · 25 Chatbot · 26 CRM

### Comercial (27-29)
27 Proposta · 28 CRM · 29 Follow-up

### Marketing (30-36)
30 Funil · 31 E-mail marketing · 32 Persona · 33 Concorrentes · 34 SEO · 35 Campanha · 36 Influencer

### Negócios (37-43)
37 Diagnóstico · 38 Precificação · 39 Proposta comercial · 40 Processos · 41 KPIs · 42 Forecasting · 43 Pitch

### Design (44-49)
44 Briefing · 45 Brand · 46 Prompts IA · 47 UI/UX · 48 Apresentação · 49 Naming

### Operações (50-56)
50 RH · 51 CS · 52 Documentação · 53 Financeiro · 54 Produto · 55 Automação · 56 Dados

## Avisos

- Outputs são rascunhos profissionais. Revise antes de publicar / enviar / executar.
- Templates e exemplos usam dados fictícios.

## Licença

Uso permitido para clientes ASV Digital / Bravy. Não redistribuir sem autorização.
