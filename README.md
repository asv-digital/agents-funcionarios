# 57 Agents Funcionarios — Claude Code para empresas

**57 subagentes especializados** que funcionam como funcionarios sem salario para sua empresa. Cada agente e um especialista em uma funcao especifica do dia-a-dia (trafego, copy, SDR, follow-up, financeiro, RH, etc.) que atua proativamente quando o contexto bate com sua especialidade.

Diferente das skills (instrucoes pontuais), agentes sao **profissionais virtuais** que entrevistam, executam, validam e escalam.

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

3. Reinicie o Claude Code (`/exit` e abra de novo). Confirme com `/agents`.

## Como usar

- **Automatico**: descreva sua necessidade. Ex.: "preciso lancar uma campanha no Meta para o produto X" -> Claude delega para `trafego-meta-analise-campanha`.
- **Manual**: "use o agente `comercial-follow-up` para reativar essa lista de leads frios".
- **Em pipeline**: `marketing-persona` -> `marketing-campanha` -> `trafego-meta-copy-criativo` -> `lancamento-pagina`.

## Catalogo (57 agentes)

### Trafego Pago Meta (01-04)
01 Meta — analise de campanha
02 Meta — relatorio de performance
03 Meta — copy de criativo
04 Meta — audiencia e segmentacao

### Trafego Pago Google (05-07)
05 Google — analise de campanha
06 Google — relatorio
07 Google — copy de anuncio

### Lancamento (08-15)
08 Cronograma · 09 Copy · 10 E-mails CPL · 11 E-mails carrinho
12 Metricas · 13 Oferta · 14 Pagina de vendas · 15 Pos-venda

### Conteudo & Social (16-22)
16 Instagram copy · 17 Instagram calendario · 18 Instagram roteiro · 19 Instagram hashtag
20 Conteudo pauta SEO · 21 Conteudo blog · 22 Conteudo script video

### WhatsApp (23-26)
23 Atendimento · 24 Disparos · 25 Chatbot · 26 CRM

### Comercial (27-29)
27 Proposta · 28 CRM · 29 Follow-up

### Marketing (30-36)
30 Funil · 31 E-mail marketing · 32 Persona · 33 Concorrentes · 34 SEO · 35 Campanha · 36 Influencer

### Negocios (37-43)
37 Diagnostico · 38 Precificacao · 39 Proposta comercial · 40 Processos · 41 KPIs · 42 Forecasting · 43 Pitch

### Design (44-49)
44 Briefing · 45 Brand · 46 Prompts IA · 47 UI/UX · 48 Apresentacao · 49 Naming

### Operacoes (50-56)
50 RH · 51 CS · 52 Documentacao · 53 Financeiro · 54 Produto · 55 Automacao · 56 Dados

### Trafego Pago TikTok (57) — NOVO
57 TikTok Ads — analise, copy, audiencia, relatorio

## Avisos

- Outputs sao rascunhos profissionais. Revise antes de publicar / enviar / executar.
- Templates e exemplos usam dados ficticios.

## Licenca

Uso permitido para clientes ASV Digital / Bravy. Nao redistribuir sem autorizacao.
