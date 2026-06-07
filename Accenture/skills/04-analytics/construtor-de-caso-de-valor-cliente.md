---
name: construtor-de-caso-de-valor-cliente
description: Constrói um ROI quantificado e narrativa de caso de negócio para apresentações ao cliente e aprovação interna de negócios. Use para casos de investimento, justificativa de ROI, pacotes de aprovação de negócio ou qualquer situação onde o cliente ou stakeholder interno precisa de benefícios quantificados.
---

# Construtor de Caso de Valor para Cliente

## Quando Usar

Use esta skill quando um negócio requer um caso de valor quantificado — seja para o cliente justificar aprovação interna ou para a Accenture justificar o investimento no pursuit. Adequada para programas de transformação, implementações de tecnologia, decisões de outsourcing e qualquer engajamento onde o custo da inação deve ser tornado visível.

## Abordagem Accenture

Expresse valor na moeda e nos termos de negócio do cliente — não na linguagem de serviços da Accenture. Use estimativas conservadoras com premissas explícitas. O caso de valor deve sobreviver ao escrutínio do CFO do cliente e do BP Financeiro da Accenture.

## Fluxo de Trabalho

1. Seção 1 — Problema do Estado Atual: quantifique o custo da inação (receita perdida, custo operacional, exposição a risco, custo de compliance).
2. Seção 2 — Solução Proposta: resuma o engajamento em 2–3 frases em linguagem simples.
3. Seção 3 — Resumo de Benefícios: categorize benefícios como Redução de Custo, Crescimento de Receita, Mitigação de Risco ou Valor Estratégico.
4. Seção 4 — Resumo Financeiro: calcule Investimento Total, Benefícios Totais (3 anos), VPL, ROI % e Período de Payback.
5. Seção 5 — Premissas: liste todas as premissas principais que fundamentam os números.
6. Expresse todos os valores na moeda do cliente.
7. Use estimativas conservadoras; declare níveis de confiança para cada categoria de benefício.

## Formato de Saída

```markdown
# Caso de Valor para o Cliente

## Problema do Estado Atual
[Custo da inação: receita perdida quantificada, custo operacional, exposição a risco ou custo de compliance.]

## Solução Proposta
[2–3 frases em linguagem simples descrevendo o engajamento.]

## Resumo de Benefícios
| Categoria | Ano 1 | Ano 2 | Ano 3 | Total 3 Anos |
|---|---|---|---|---|
| Redução de Custo | | | | |
| Crescimento de Receita | | | | |
| Mitigação de Risco | | | | |
| Valor Estratégico | | | | |
| **Total** | | | | |

## Resumo Financeiro
| Métrica | Valor |
|---|---|
| Investimento Total | |
| Benefícios Totais (3 anos) | |
| VPL | |
| ROI % | |
| Período de Payback | |

## Premissas Principais
[Lista numerada de premissas que fundamentam cada categoria de benefício, com nível de confiança (A/M/B).]

## Análise de Sensibilidade
| Premissa | Caso Base | Caso Pessimista | Impacto no VPL |
|---|---|---|---|
```

## Padrão de Qualidade

- Todos os benefícios devem ser categorizados — nunca apresente um total único indiferenciado.
- As premissas devem ser numeradas, específicas e testáveis.
- Inclua análise de sensibilidade para as 2–3 premissas mais estruturais.
- Use estimativas conservadoras: se o caso pessimista ainda torna o negócio atrativo, diga isso.
- Evite falsa precisão: arredonde os números adequadamente e declare os níveis de confiança.
