---
name: navegador-de-mesa-de-negocios
description: Navega aprovações do Deal Desk, exceções de precificação, matriz de descontos e termos comerciais para negócios grandes ou não padrão. Use quando o negócio requer uma exceção de precificação, termos de pagamento não padrão, estrutura de risco-recompensa ou complexidade comercial entre múltiplas MUs.
---

# Navegador de Mesa de Negócios

## Quando Usar

Use esta skill quando um negócio requer revisão do Deal Desk por causa de níveis de desconto, termos comerciais não padrão, precificação baseada em resultado, licenciamento de IP ou estrutura multinacional. Submeta com no mínimo 10 dias úteis antes da data de entrega da proposta.

## Abordagem Accenture

O Deal Desk é um controle comercial, não um obstáculo burocrático. Envolva-o cedo, empacote a submissão completamente e aborde os três motivos mais comuns de rejeição antes de submeter. Uma submissão rejeitada atrasa o negócio e sinaliza baixa disciplina comercial para a liderança.

## Fluxo de Trabalho

### Quando a Aprovação do Deal Desk é Necessária

- Qualquer desconto que exceda os limiares padrão da tabela de preços (tipicamente > 10–15%)
- Termos de pagamento não padrão além de 30 dias
- Estruturas de precificação baseadas em risco-recompensa ou resultado
- Negócios envolvendo licenciamento de IP, compartilhamento de receita ou componentes de equity
- Negócios multinacionais ou entre múltiplas MUs

### Processo de Submissão

1. Prepare o pacote de submissão: Resumo da Oportunidade, Modelo de Precificação (P&L), Estratégia de Vitória, Avaliação de Risco, Inteligência Competitiva.
2. Preencha o formulário de intake do Deal Desk no Portal de Negócios.
3. Designar BP Financeiro para revisar e endossar o P&L antes da submissão.
4. Submeta com no mínimo 10 dias úteis antes da data de entrega da proposta.
5. Acompanhe o status de aprovação; escale se não houver resposta em 5 dias úteis.
6. Atualize o mySalesforce com os termos comerciais aprovados após a aprovação.

### Motivos Comuns de Rejeição

| Motivo | Prevenção |
|---|---|
| Margem negativa sem justificativa aprovada | Inclua plano de melhoria de margem ou justificativa estratégica |
| Falta de assinatura na avaliação de risco | Obtenha assinatura do líder de entrega e de risco antes da submissão |
| Racional competitivo incompleto para o desconto | Documente evidências de precificação dos concorrentes e necessidade de vitória |

## Formato de Saída

```markdown
# Pacote de Submissão ao Deal Desk

## Resumo da Oportunidade
[Cliente, tamanho do negócio, linhas de serviço, data de fechamento, tipo de negócio.]

## Exceção de Precificação Solicitada
[Exceção específica: % de desconto, termos não padrão, estrutura de precificação.]

## Justificativa
[Necessidade de vitória, evidência competitiva, importância estratégica.]

## Resumo do P&L
| Cenário | Receita | Custo | Margem % |
|---|---|---|---|

## Avaliação de Risco
[Risco de entrega, risco comercial e mitigações — assinado pelo Líder de Entrega.]

## Inteligência Competitiva
[Evidência de precificação dos concorrentes ou taxas de mercado justificando a exceção.]

## Cronograma
- Data de submissão:
- Aprovação necessária até:
- Data de entrega da proposta:

## Aprovações Necessárias
- [ ] Endosso do BP Financeiro
- [ ] Assinatura da avaliação de risco
- [ ] Aprovação do Diretor / MD (conforme aplicável)
```

## Padrão de Qualidade

- Nunca submeta com margem negativa sem uma justificativa estratégica escrita.
- O endosso do BP Financeiro é inegociável antes da submissão.
- O racional competitivo deve incluir evidências específicas — não afirmações.
- Submeta 10+ dias úteis antes da data de entrega da proposta sem exceção.
