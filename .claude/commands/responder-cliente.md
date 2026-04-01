---
name: responder-cliente
description: >
  Gera resposta pronta pra copiar e colar no GHL/WhatsApp com base na situação
  descrita pelo usuário. Calibra o tom para comunidade latina, estilo direto e
  humano. Use quando o usuário descrever uma dúvida ou situação de cliente e
  pedir uma resposta.
---

# /responder-cliente — Resposta pronta para WhatsApp/GHL

## Dependências

- **Tom e estilo:** `_contexto/preferencias.md`
- **Contexto do negócio:** `_contexto/empresa.md`

---

## Workflow

### Passo 1 — Entender a situação

Se o usuário não forneceu contexto suficiente, perguntar:

1. "Qual é a dúvida ou situação do cliente?"
2. "O cliente é brasileiro, hispânico ou fala inglês?" *(define o idioma da resposta)*
3. "A resposta é pra informar, pedir documento, explicar um resultado, ou outro?"

Se o usuário já descreveu a situação claramente, extrair o que der e prosseguir.

### Passo 2 — Gerar a resposta

**Regras obrigatórias:**
- Tom humano, como se fosse o próprio Jorge escrevendo
- Curto e direto — estilo WhatsApp, não email
- Sem saudações genéricas ("Prezado cliente", "Espero que esteja bem")
- Sem assinatura formal
- Sem bullet points desnecessários
- Sem enrolação — ir direto ao ponto
- Didático quando necessário: explicar como para leigo, sem termos técnicos soltos
- **Nunca sugerir ligação telefônica** — toda comunicação é por escrito via WhatsApp/GHL
- Se for má notícia (balance due, erro de filing, problema com IRS): ser direto mas tranquilizador. Não alarmar desnecessariamente, não minimizar o problema
- Se for explicação técnica (refund, crédito, SE tax): usar analogia simples se necessário

**Idioma:**
- Cliente brasileiro → português do Brasil
- Cliente hispânico → espanhol
- Cliente anglófono → inglês
- Se não souber → perguntar antes

### Passo 3 — Apresentar a resposta

Apresentar o texto pronto para copiar e colar, sem instruções adicionais antes ou depois do texto.

Se a situação for delicada (erro do contador anterior, balance due inesperado, problema com IRS), oferecer 2 versões:
- **Versão direta** — vai logo ao ponto
- **Versão mais suave** — abre antes de dar a notícia

Deixar o Jorge escolher.

---

## Casos comuns na White Castle Solutions

### "Por que meu refund caiu / sumiu?"
- Verificar se teve aumento de renda, perda de crédito (filho cresceu, saiu de casa), mudança de status
- Explicar de forma simples: "Seu refund é a diferença entre o que você pagou e o que você devia. Se você ganhou mais, deve mais."

### "Por que agora tenho que pagar?"
- Verificar self-employment income, falta de withholding, perda de créditos
- Explicar: "Quando você trabalha por conta própria, ninguém desconta o imposto automaticamente. Aí ele vem na declaração."

### Erro de filing do contador anterior
- Ser honesto e direto
- Não atacar o contador anterior, mas deixar claro o que precisa ser corrigido
- Nunca minimizar o risco de não corrigir
- **Nunca sugerir ligação** — tudo por escrito

### Balance due / parcelamento IRS
- Explicar o que é, quanto é, e o que acontece se não pagar
- Dar a opção de parcelamento se aplicável
- Manter tom calmo — não alarmar

### Carta do IRS
- Pedir uma foto da carta antes de qualquer coisa
- Nunca responder sem ver o documento

---

## Regras

- Nunca inventar informação técnica que não tem certeza
- Se não tiver certeza sobre uma regra do IRS, dizer "vou confirmar e te aviso" em vez de chutar
- Nunca sugerir que o cliente ligue — toda comunicação é por escrito
- Não fazer promessas de resultado ("você vai receber X")
- Respostas em português devem soar naturais, não traduzidas
