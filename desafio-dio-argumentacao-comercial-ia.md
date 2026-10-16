# Desafio Criativo DIO — Quem Não Vende, Ajuda a Vender!

## O Poder da Argumentação: IA aplicada a vendas consultivas de sites e automações

### Sobre o projeto

Este desafio demonstra como a engenharia de prompts pode apoiar a **prospecção e a argumentação comercial** de um profissional que desenvolve **sites, landing pages e automações de processos para empresas**.

Em vez de gerar um discurso de vendas genérico, o objetivo é estruturar um prompt capaz de atuar como um **assistente de vendas consultivas**: compreender o cenário de um possível cliente, levantar hipóteses de problemas, formular perguntas de diagnóstico e construir argumentos claros, relevantes e éticos.

**Objetivo prático:** transformar informações sobre uma empresa em um plano de abordagem comercial que conecte possíveis necessidades a soluções digitais adequadas.

---

## Passo 1 — Definir a intenção

**O que quero que a IA faça?**

Quero que a IA atue como um assistente de vendas consultivas e gere um plano de abordagem comercial personalizado para empresas que possam se beneficiar de **sites, landing pages e automações de atendimento e processos**.

**Para quem?**

Para mim, como profissional que oferece essas soluções a pequenos e médios negócios e precisa conversar com seus responsáveis pela contratação.

**Qual é o resultado esperado?**

Identificar oportunidades de melhoria, preparar perguntas para validar necessidades, apresentar argumentos centrados em benefícios e produzir uma abordagem de prospecção que convide o potencial cliente a uma conversa de diagnóstico.

**Intenção resumida:**

> Quero que a IA gere uma estratégia de abordagem e argumentação comercial para potenciais clientes de sites e automações, com o objetivo de identificar necessidades reais, comunicar o valor das soluções e aumentar a qualidade das conversas de venda.

---

## Passo 2 — Adicionar contexto e restrições

**Contexto:**

- Atuo com desenvolvimento de sites e landing pages, além de automações para negócios.
- Meu público são empresas que podem enfrentar problemas como atendimento manual repetitivo, demora para responder clientes, dificuldade de organizar solicitações, baixa clareza na apresentação de serviços ou processos comerciais pouco eficientes.
- Essas situações são **hipóteses iniciais**, não problemas confirmados de todas as empresas.
- A abordagem deve privilegiar diagnóstico, escuta e propostas compatíveis com a realidade de cada negócio.

**Formato da resposta:**

1. Resumo do cenário e das informações disponíveis.
2. Até 3 oportunidades ou hipóteses de melhoria, indicando o que ainda precisa ser confirmado.
3. Até 5 perguntas de diagnóstico para a conversa comercial.
4. Proposta de valor conectando **problema → solução → benefício potencial**.
5. Uma mensagem curta de prospecção para WhatsApp ou Instagram.
6. Três objeções prováveis e possíveis respostas respeitosas.
7. Um próximo passo simples, como o convite para uma conversa de diagnóstico.

**Estilo:** profissional, humano, objetivo, consultivo e acessível para pessoas que não dominam tecnologia.

**Restrições:**

- Não inventar dados sobre a empresa, faturamento, perdas financeiras, resultados ou retorno sobre investimento.
- Diferenciar informações confirmadas de hipóteses a validar.
- Não usar promessas de resultados garantidos, falsa escassez.
- Evitar termos técnicos sem explicação, textos longos e abordagens genéricas como “tenho a solução perfeita para sua empresa”.
- Não presumir que toda empresa precisa de um site novo ou de automação. Se não houver evidência de necessidade, recomendar uma investigação adicional.
- Quando faltarem informações essenciais, perguntar ou indicar o que precisa ser descoberto antes de recomendar um serviço.

---

## Passo 3 — Unir tudo em um prompt final

### Prompt final — Assistente de Vendas Consultivas para Soluções Digitais

Copie o texto abaixo e preencha os campos entre colchetes para analisar uma nova oportunidade comercial.

```text
Atue como um especialista em vendas consultivas B2B, com experiência em
serviços digitais para pequenas e médias empresas.

Sou um profissional que oferece desenvolvimento de sites, landing pages
e automações de atendimento e processos. Quero preparar uma abordagem
comercial personalizada, útil e respeitosa, com foco em compreender as
necessidades reais do potencial cliente.

Analise as informações a seguir:

- Empresa ou segmento: [PREENCHER]
- O que a empresa oferece: [PREENCHER]
- Como atrai e atende clientes atualmente: [PREENCHER OU "NÃO SEI"]
- Presença digital atual: [PREENCHER OU "NÃO SEI"]
- Problemas observados ou relatados: [PREENCHER OU "NÃO SEI"]
- Soluções que posso oferecer: [PREENCHER]
- Canal de primeiro contato: [WHATSAPP, INSTAGRAM, E-MAIL OU OUTRO]

Com base exclusivamente nessas informações:

1. Resuma o cenário e separe o que é informação confirmada do que é
   hipótese.
2. Identifique até 3 oportunidades de melhoria relevantes e diga o
   que precisaria ser validado com o responsável pela empresa.
3. Sugira até 5 perguntas abertas para diagnosticar necessidades,
   gargalos e prioridades antes de oferecer qualquer serviço.
4. Construa uma argumentação comercial organizada em:
   problema identificado ou hipotético → solução digital adequada →
   benefício potencial para o negócio.
5. Escreva uma mensagem inicial de prospecção, com no máximo 100
   palavras, adaptada ao canal escolhido. A mensagem deve ser natural,
   personalizada e terminar com uma pergunta simples, sem pressionar.
6. Liste 3 objeções plausíveis (por exemplo, custo, falta de tempo ou
   dúvida sobre a necessidade) e apresente respostas consultivas,
   que reconheçam a preocupação e proponham um próximo passo útil.
7. Recomende uma chamada para ação adequada, preferencialmente um
   convite para uma conversa breve de diagnóstico.
8. Caso as informações sejam insuficientes para sustentar uma oferta,
   deixe isso claro e recomende quais dados coletar primeiro.

Use linguagem profissional, humana, objetiva e sem jargões técnicos.
Não invente métricas, dados, problemas, depoimentos ou resultados.
Não prometa aumento garantido de vendas, economia ou retorno financeiro.
Evite mensagens comerciais genéricas.
Se um site ou uma automação não fizer sentido para esse negócio,
explique por quê e não force a recomendação.

Organize a resposta com títulos claros e tópicos curtos para que eu
possa utilizá-la antes e durante uma conversa comercial real.
```

---

## Exemplo de aplicação (cenário fictício)

Para testar o prompt, seria possível preencher os campos assim:

| Campo | Exemplo de preenchimento |
| --- | --- |
| Empresa ou segmento | Clínica de estética de bairro |
| O que oferece | Procedimentos estéticos e agendamentos |
| Como atrai e atende clientes | Instagram e WhatsApp; não sei como organiza as solicitações |
| Presença digital | Perfil no Instagram; site não verificado |
| Problemas observados ou relatados | Nenhum problema confirmado |
| Soluções possíveis | Página de apresentação de serviços, página de agendamento e automações de atendimento |
| Canal de contato | Instagram |

**O que esperar de uma boa resposta?**

A IA deve tratar a possível demora nas respostas e a organização dos agendamentos como **pontos a investigar**, não como defeitos comprovados da clínica. Em vez de oferecer imediatamente um site ou uma automação, ela deve sugerir perguntas para entender o processo atual e, apenas depois, desenvolver uma proposta de valor.

**Exemplo de argumento condicionado ao diagnóstico:**

> Se a clínica confirmar que recebe muitas perguntas repetidas sobre serviços e horários, uma página com informações claras ou uma automação simples poderá reduzir parte desse trabalho manual, desde que seja compatível com a rotina de atendimento.

Esse tipo de argumentação vende a possibilidade de resolver um problema real, sem fazer promessas sem fundamento.

---

## Aprendizados esperados

Ao concluir este desafio, o prompt deve demonstrar a aplicação de:

- **Intenção clara:** definir o papel da IA, o público e o objetivo da tarefa.
- **Contexto:** informar os serviços oferecidos e a realidade conhecida do potencial cliente.
- **Restrições:** controlar tom, formato e limites éticos dos argumentos.
- **Instruções específicas:** solicitar entregas concretas e organizadas.
- **Reutilização:** permitir personalização do mesmo prompt para diferentes empresas.

### Entrega

Arquivo em formato `.md`, preparado para publicação em um repositório público do GitHub como parte dos desafios de engenharia de prompts da DIO.

> **Observação:** este projeto apresenta a construção do prompt e um cenário ilustrativo. Os resultados comerciais dependerão da qualidade dos dados fornecidos, da validação das hipóteses e da aplicação prática em cada negociação.
