---
name: criador-de-oportunidades-salesforce
description: Guia passo a passo para criar e manter oportunidades corretamente no Salesforce da Accenture (myPipeline). Use ao criar novas oportunidades, atualizar gates de fase ou resolver erros de preenchimento de campos no mySalesforce.
---

# Criador de Oportunidades Salesforce

## Quando Usar

Use esta skill ao criar uma nova oportunidade no myPipeline, atualizar uma oportunidade existente pelos gates de fase, ou preparar um registro para revisão de MD ou BP Financeiro.

## Abordagem Accenture

Higiene de pipeline é uma disciplina comercial, não uma tarefa administrativa. Oportunidades incompletas ou mal classificadas bloqueiam aprovações, distorcem previsões e criam risco no negócio. Preencha corretamente na primeira vez; atualize em tempo real.

## Fluxo de Trabalho

### Criando uma Nova Oportunidade

1. Faça login no mySalesforce → clique em Nova Oportunidade.
2. Preencha os campos obrigatórios:
   - Nome da Oportunidade: [Cliente] — [Serviço] — [AF]
   - Conta, MU Primária, Data de Fechamento, Fase, TCV, ACV
3. Defina o Tipo de Negócio: Novo Cliente / Expansão / Renovação / Renovação + Expansão.
4. Atribua colaboradores: Proprietário Principal, Proprietário Secundário, BP Financeiro, Líder de Entrega.
5. Selecione Grupo de Serviço e Oferta usando o alinhamento de taxonomia DTE.
6. Anexe a Descrição do Produto usando SKUs do Catálogo de Ofertas.

### Gates de Fase

| Fase | Definição | Critério de Gate |
|---|---|---|
| Fase 1 — Identificar | Oportunidade identificada | Cliente confirmou interesse |
| Fase 2 — Qualificar | Pursuit qualificado | Aprovado por MD/AD; equipe de pursuit designada |
| Fase 3 — Desenvolver | Solução em desenvolvimento | Solução e precificação em andamento |
| Fase 4 — Propor | Proposta submetida | Proposta entregue ao cliente |
| Fase 5 — Negociar | Negociação comercial | Termos contratuais em discussão |
| Fase 6 — Fechar | Contrato assinado | Contrato assinado recebido |

### Gatilhos de Aprovação

| Limiar | Aprovação Necessária |
|---|---|
| TCV > R$25M | Aprovação do Diretor |
| TCV > R$125M | Aprovação de MD + BP Financeiro |
| Desconto > 15% | Revisão do Deal Desk necessária |

## Formato de Saída

```markdown
# Checklist do Registro de Oportunidade

## Campos Obrigatórios
- Nome da Oportunidade: [Cliente]—[Serviço]—[AF]
- Conta:
- MU Primária:
- Data de Fechamento:
- Fase:
- TCV:
- ACV:
- Tipo de Negócio:

## Atribuições da Equipe
- Proprietário Principal:
- BP Financeiro:
- Líder de Entrega:

## Taxonomia
- Grupo de Serviço:
- Oferta (DTE):
- SKUs do Produto:

## Status de Aprovação
- [ ] Aprovação do Diretor (se TCV > R$25M)
- [ ] Aprovação de MD + BP Financeiro (se TCV > R$125M)
- [ ] Revisão do Deal Desk (se desconto > 15%)
```

## Padrão de Qualidade

- O formato do Nome da Oportunidade deve ser seguido exatamente para alinhamento de relatórios.
- A taxonomia DTE deve ser selecionada — não deixe o Grupo de Serviço em branco.
- A Fase deve refletir o estado comercial real — não avance fases antes da realidade.
- Acione aprovações proativamente; não espere as revisões de pipeline as revelarem.
