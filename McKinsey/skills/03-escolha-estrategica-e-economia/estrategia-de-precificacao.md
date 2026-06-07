---
name: estrategia-de-precificacao
description: Diagnostica poder de precificação, disposição a pagar, descontos, empacotamento e oportunidades de monetização. Use para estratégia de precificação, vazamento de desconto, monetização, empacotamento, aumento de preço, precificação por valor, precificação de renovação ou melhoria de margem.
---

# Estratégia de Precificação

## Quando Usar

Use esta skill quando o usuário precisa melhorar a monetização, diagnosticar descontos, aumentar preços, redesenhar empacotamento ou entender a disposição a pagar.

## Abordagem Estilo McKinsey

Conecte o preço ao valor, segmentos de clientes, alternativas competitivas e comportamento de vendas. Separe preço de tabela, preço realizado, descontos, mix e empacotamento.

## Fluxo de Trabalho

1. Defina a pergunta de precificação e o objetivo econômico.
2. Colete arquitetura de preços, dados de desconto, win-loss, churn, margem e contexto de concorrentes.
3. Diagnostique vazamentos em preço de tabela, descontos, mix, empacotamento e governança.
4. Avalie disposição a pagar por segmento ou caso de uso.
5. Gere movimentos de precificação e riscos.
6. Recomende um plano de ação de precificação e design de teste.

## Formato de Saída

```markdown
# Estratégia de Precificação

## Objetivo de Precificação
[Crescimento, margem, retenção, adoção ou simplificação.]

## Diagnóstico
| Área | Evidência | Problema | Impacto |
|---|---|---|---|

## Lógica de Preço por Segmento
| Segmento | Driver de Valor | Sinal de Disposição a Pagar | Movimento de Precificação |
|---|---|---|---|

## Movimentos Recomendados
1. [Movimento]
2. [Movimento]
3. [Movimento]

## Riscos e Testes
[Riscos, mitigações e design de piloto.]
```

## Padrão de Qualidade

- Não recomende um movimento de preço sem lógica de segmento.
- Separe realização de preço de precificação de tabela.
- Inclua risco do cliente e risco de execução de vendas.
- Recomende uma sequência de teste ou rollout.
