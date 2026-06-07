---
name: redator-de-relatorio-de-status
description: Gera relatórios de status estruturados semanais ou mensais voltados ao cliente com status RAG, riscos e decisões-chave necessárias. Use para atualizações recorrentes de status do projeto, pacotes de comitê de direção ou qualquer comunicação estruturada ao cliente sobre o progresso da entrega.
---

# Redator de Relatório de Status

## Quando Usar

Use esta skill ao gerar um relatório de status estruturado voltado ao cliente — semanal, mensal ou para um comitê de direção. É especialmente valioso quando o projeto tem múltiplos workstreams, riscos em andamento ou decisões pendentes do lado do cliente.

## Abordagem Accenture

Relatórios de status são uma ferramenta de gestão de risco, não um registro de progresso. Escale riscos cedo, sinalize decisões do cliente com prazos, e nunca deixe um status Vermelho sem ser reportado. O tom deve ser factual, não tranquilizador.

## Definições de RAG

| Status | Significado | Ação Necessária |
|---|---|---|
| Verde | No prazo — nenhum problema impactando a entrega | Reporte padrão |
| Âmbar | Em risco — problemas sendo gerenciados mas podem impactar sem ação | Plano de mitigação necessário |
| Vermelho | Fora do prazo — escalação necessária | Plano de recuperação necessário neste relatório |

## Fluxo de Trabalho

1. Cabeçalho: Nome do Projeto, Período de Reporte, Status RAG Geral, Preparado Por.
2. Seção 1 — Sumário Executivo: máximo de 3 frases — o que aconteceu, saúde geral, declaração prospectiva.
3. Seção 2 — Progresso por Workstream: uma linha por workstream com RAG, % concluído, atividades principais neste período, próximos passos.
4. Seção 3 — Principais Riscos e Problemas: tabela com Risco/Problema, Responsável, Impacto, Probabilidade, Mitigação, Data de Vencimento.
5. Seção 4 — Decisões Necessárias do Cliente: ações e decisões do lado do cliente com prazos.
6. Seção 5 — Próximos Marcos (próximas 4 semanas) com responsável e data.
7. Se o status geral for Vermelho, inclua um plano de recuperação antes da distribuição.

## Formato de Saída

```markdown
# Relatório de Status do Projeto
**Projeto:** [Nome] | **Período:** [Datas] | **Status Geral:** 🟢 / 🟡 / 🔴 | **Preparado Por:** [Nome]

## Sumário Executivo
[3 frases: o que aconteceu neste período, saúde geral, o que vem a seguir.]

## Progresso por Workstream
| Workstream | RAG | % Concluído | Neste Período | Próximos Passos |
|---|---|---|---|---|

## Riscos e Problemas
| Risco / Problema | Tipo | Responsável | Impacto | Probabilidade | Mitigação | Data |
|---|---|---|---|---|---|---|

## Decisões Necessárias do Cliente
| Decisão | Contexto | Responsável | Data de Vencimento |
|---|---|---|---|

## Próximos Marcos (Próximas 4 Semanas)
| Marco | Responsável | Data | Status |
|---|---|---|---|

## Plano de Recuperação [se Vermelho]
[Causa raiz, ações corretivas, cronograma revisado, caminho de escalação.]
```

## Padrão de Qualidade

- O Sumário Executivo deve ter três frases — não três parágrafos.
- Nunca suprima um status Vermelho; inclua um plano de recuperação.
- A seção de Decisões do Cliente deve ter responsáveis nomeados e prazos rígidos.
- Os Riscos devem incluir tanto impacto quanto probabilidade — não apenas uma descrição.
- Tom: factual, sem surpresas, sem linguagem defensiva.
