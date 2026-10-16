# Quem Não Vende, Ajuda a Vender!

### O poder da argumentação com IA aplicada a vendas consultivas

Projeto desenvolvido para o **Desafio Criativo da DIO**, com foco em **engenharia de prompts** e no uso da inteligência artificial como apoio à prospecção e à argumentação comercial.

A proposta é aplicar IA a um cenário profissional real: a venda consultiva de **sites, landing pages e automações de atendimento e processos para empresas**.

> **Ideia central:** antes de oferecer uma solução digital, é preciso compreender o problema que ela pode resolver.

## Sobre o projeto

Muitas empresas podem ter oportunidades de melhoria em sua presença digital, na organização do atendimento ou em processos repetitivos. Isso não significa que toda empresa precise de um site novo ou de uma automação.

Este projeto apresenta um **prompt reutilizável** que orienta a IA a atuar como um **assistente de vendas consultivas B2B**. A partir de informações fornecidas sobre um potencial cliente, ela ajuda a organizar hipóteses, formular perguntas, construir argumentos e preparar uma primeira abordagem comercial.

O objetivo não é automatizar decisões comerciais nem gerar mensagens agressivas de venda: é **melhorar a qualidade do diagnóstico e da comunicação de valor**.

## Objetivos

- Identificar possíveis oportunidades de melhoria em empresas de diferentes segmentos.
- Separar **informações confirmadas** de **hipóteses que precisam ser validadas**.
- Elaborar perguntas para entender gargalos e prioridades de um potencial cliente.
- Traduzir recursos técnicos de sites e automações em **benefícios de negócio compreensíveis**.
- Criar mensagens de prospecção personalizadas e respostas respeitosas a objeções.
- Sugerir próximos passos sem pressão, promessas irreais ou manipulação.

## Construção do desafio

O desenvolvimento do prompt segue três etapas:

| Etapa | O que foi definido |
| --- | --- |
| **1. Intenção** | O papel da IA, o público-alvo e o resultado comercial esperado. |
| **2. Contexto e restrições** | Serviços oferecidos, formato da resposta, linguagem e limites éticos. |
| **3. Prompt final** | Um comando único, estruturado e reutilizável para diferentes empresas. |

A descrição completa de cada etapa está no arquivo do desafio.

## O que o prompt entrega

Ao informar o contexto de uma empresa, a IA é orientada a produzir:

1. **Análise inicial:** resumo do cenário com fatos e hipóteses separados.
2. **Oportunidades:** até três possíveis melhorias e o que falta validar.
3. **Diagnóstico:** até cinco perguntas abertas para uma conversa comercial.
4. **Argumentação:** relação entre problema, solução digital e benefício potencial.
5. **Prospecção:** mensagem inicial de até 100 palavras para o canal escolhido.
6. **Objeções:** três preocupações prováveis e respostas consultivas.
7. **Próximo passo:** convite contextualizado para uma conversa de diagnóstico.

Se os dados forem insuficientes, a IA deve indicar **quais informações coletar antes de recomendar uma solução**.

## Como utilizar

1. Abra o arquivo [`desafio-dio-argumentacao-comercial-ia.md`](./desafio-dio-argumentacao-comercial-ia.md).
2. Localize a seção **“Passo 3 — Una tudo em um prompt final”**.
3. Copie o prompt e substitua os campos entre colchetes pelas informações disponíveis sobre a empresa.
4. Cole o comando em um assistente de IA generativa.
5. Revise as sugestões, **valide as hipóteses** com o potencial cliente e adapte a abordagem ao contexto real.

### Exemplo de aplicação

**Cenário fictício:** uma clínica de estética divulga seus serviços pelo Instagram e recebe contatos pelo WhatsApp. Ainda não sabemos se enfrenta dificuldades de agendamento, demora nas respostas ou falta de informações para clientes.

O prompt deve ajudar a elaborar perguntas como:

- Como vocês organizam os contatos que chegam pelo Instagram e pelo WhatsApp?
- Quais dúvidas os clientes mais repetem antes de agendar?
- Existe alguma etapa do atendimento que consome mais tempo da equipe?

Somente após conhecer as respostas faria sentido avaliar alternativas como uma página de serviços, um fluxo de agendamento ou uma automação simples.

**Importante:** o exemplo é ilustrativo e não representa um diagnóstico realizado em uma empresa real.

## Conceitos aplicados

- Engenharia de prompts
- Inteligência artificial generativa
- Vendas consultivas B2B
- Prospecção comercial
- Argumentação baseada em valor
- Diagnóstico de necessidades

**Formato do projeto:** documentação em Markdown (`.md`). Não há aplicação, integração ou automação de software implementada neste repositório; a entrega é o prompt estruturado e sua metodologia de utilização.

## Estrutura do repositório

```text
.
├── README.md
└── desafio-dio-argumentacao-comercial-ia.md
```

## Boas práticas e limitações

O prompt foi desenvolvido para evitar a invenção de informações sobre empresas, o uso de métricas sem fonte, promessas de resultado garantido e a recomendação indiscriminada de soluções.

As saídas geradas por IA são **sugestões de apoio à análise comercial**. Antes de enviar uma mensagem ou apresentar uma proposta, é necessário conferir as informações, investigar as necessidades e exercer julgamento profissional.

## Sobre o desafio

Este trabalho foi criado como entrega do **Desafio Criativo da DIO — “Quem Não Vende, Ajuda a Vender! O Poder da Argumentação”**.

Seu diferencial é transformar um exercício de engenharia de prompts em um material aplicável à rotina de quem desenvolve soluções digitais e busca vender de forma mais estratégica, clara e consultiva.

---

**Projeto educacional e demonstrativo.** Não há garantia de conversão comercial ou de resultados financeiros pelo uso do prompt.
