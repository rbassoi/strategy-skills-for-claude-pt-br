---
name: opcoes-estrategicas
description: Gera e compara opções estratégicas com critérios de decisão claros, trade-offs e lógica de recomendação. Use para opções de estratégia, seleção de caminho, escolhas de crescimento, escolhas de entrada em mercado, construir-comprar-parceria ou perguntas do tipo "quais são nossas opções?".
---

# Opções Estratégicas

## Quando Usar

Use esta skill quando o usuário precisa de alternativas antes de se comprometer com uma estratégia. Ela ajuda a evitar falsas binaridades e cria um caminho defensável das opções à recomendação.

## Abordagem Estilo McKinsey

Desenvolva um pequeno conjunto de opções distintas e viáveis. Compare-as com critérios de decisão que importam. Recomende um caminho com trade-offs visíveis.

## Fluxo de Trabalho

1. Esclareça a decisão estratégica e as restrições.
2. Gere opções mutuamente distintas.
3. Defina critérios de decisão.
4. Avalie cada opção em atratividade, viabilidade, risco, economias e fit estratégico.
5. Identifique híbridos ou sequenciamento se útil.
6. Recomende o melhor caminho e o que precisa ser verdade.

## Formato de Saída

```markdown
# Opções Estratégicas

## Decisão
[Decisão sendo tomada.]

## Opções
| Opção | Descrição | Vantagem | Trade-Off | O Que Precisa Ser Verdade |
|---|---|---|---|---|

## Avaliação
| Critério | Opção A | Opção B | Opção C |
|---|---|---|---|

## Recomendação
[Opção preferida e racional.]

## Próximos Testes
[Evidências necessárias antes de comprometer.]
```

## Padrão de Qualidade

- As opções devem ser meaningfully diferentes.
- Os critérios devem refletir a decisão do usuário, não atratividade genérica.
- Inclua trade-offs e riscos.
- Declare qual evidência mudaria a recomendação.
