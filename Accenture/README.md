# 10 Skills de Excelência em Vendas Accenture para o Claude

> Inspirado na prática de Excelência em Vendas, Gestão de Propostas e Crescimento de Contas da Accenture: gestão estruturada de pursuit, contra-posicionamento competitivo, valor quantificado para o cliente e comunicação pronta para executivos. Esta coleção é independente e não oficial.

## O Que É Isso

Este repositório contém 10 skills autônomas do Claude para trabalho de vendas e gestão de contas no estilo Accenture, agrupadas em seis domínios práticos. Cada skill é um fluxo de trabalho pequeno e carregável que ensina o Claude a executar uma tarefa de vendas ou pursuit de alto valor com um método repetível.

Juntas, as skills cobrem um ciclo completo de pursuit e conta: construir o briefing da proposta, criar temas vencedores, escrever o sumário executivo, gerir aprovações comerciais, contra-posicionar concorrentes, quantificar valor para o cliente, reportar status e crescer a conta.

A coleção foi projetada para gestores de pursuit, gestores de propostas, líderes de conta, diretores de vendas e equipes voltadas ao cliente que querem que o Claude trabalhe com a disciplina de um praticante de Excelência em Vendas da Accenture.

```mermaid
flowchart LR
    propose["Construir a Proposta"] --> operate["Gerir Operações de Vendas"]
    operate --> compete["Contra-posicionar Concorrentes"]
    compete --> value["Quantificar Valor para o Cliente"]
    value --> communicate["Comunicar ao Cliente"]
    communicate --> grow["Crescer a Conta"]
```

## As 10 Skills

### 1. Propostas

| Skill | Quando Usar | Saída |
|---|---|---|
| [Briefing de Início de Proposta](skills/01-propostas/briefing-de-inicio-de-proposta.md) | Iniciando um pursuit formal e alinhando a equipe | Papéis, estratégia de vitória, cronograma, mapa de concorrentes, registro de riscos |
| [Criador de Temas Vencedores](skills/01-propostas/criador-de-temas-vencedores.md) | Você precisa de posicionamento diferenciado antes de escrever a proposta | 3–5 temas vencedores com provas |
| [Redator de Sumário Executivo](skills/01-propostas/redator-de-sumario-executivo.md) | Você precisa de um sumário executivo de 1 página que lidera com valor | Sumário de 4–5 parágrafos para nível de CEO |
| [Redator de Declaração de Trabalho](skills/01-propostas/redator-de-declaracao-de-trabalho.md) | Você precisa redigir escopo, entregáveis, premissas e exclusões | SOW com 6 seções estruturadas |

### 2. Operações de Vendas

| Skill | Quando Usar | Saída |
|---|---|---|
| [Criador de Oportunidades Salesforce](skills/02-operacoes-de-vendas/criador-de-oportunidades-salesforce.md) | Criando ou atualizando uma oportunidade no myPipeline | Guia passo a passo de campos, gates de fase, gatilhos de aprovação |
| [Navegador de Mesa de Negócios](skills/02-operacoes-de-vendas/navegador-de-mesa-de-negocios.md) | Preparando uma submissão ao Deal Desk para exceções de precificação ou termos não padrão | Pacote de submissão, cronograma, critérios de aprovação |

### 3. Inteligência Competitiva

| Skill | Quando Usar | Saída |
|---|---|---|
| [Contra-posicionamento Competitivo](skills/03-inteligencia-competitiva/contra-posicionamento-competitivo.md) | Você precisa contra-posicionar TCS, Infosys, IBM, Capgemini, Deloitte ou outros | Contra-argumentos por concorrente com provas e linguagem de ghost |

### 4. Analytics

| Skill | Quando Usar | Saída |
|---|---|---|
| [Construtor de Caso de Valor para Cliente](skills/04-analytics/construtor-de-caso-de-valor-cliente.md) | Um negócio precisa de ROI quantificado e caso de negócio | VPL, ROI, payback, tabela de benefícios 3 anos |

### 5. Comunicações com Cliente

| Skill | Quando Usar | Saída |
|---|---|---|
| [Redator de Relatório de Status](skills/05-comunicacoes-com-cliente/redator-de-relatorio-de-status.md) | Você precisa de um relatório de status semanal ou mensal com RAG e riscos | Relatório de status estruturado em 5 seções |

### 6. Crescimento de Contas

| Skill | Quando Usar | Saída |
|---|---|---|
| [Identificador de Oportunidades de Crescimento](skills/06-crescimento-de-contas/identificador-de-oportunidades-de-crescimento.md) | Você precisa encontrar oportunidades de espaço em branco em uma conta existente | Tabela de oportunidades e top-3 prioridades de pursuit |

## Como Instalar

1. Escolha um arquivo markdown em uma das pastas de categoria `skills/`.
2. Crie uma pasta temporária com o nome da skill.
3. Copie o arquivo markdown escolhido para essa pasta como `SKILL.md`.
4. Compacte em `.zip` se necessário para o seu ambiente Claude.
5. Faça o upload no Claude e teste com um prompt relevante.

```bash
mkdir upload/criador-de-temas-vencedores
cp skills/01-propostas/criador-de-temas-vencedores.md upload/criador-de-temas-vencedores/SKILL.md
zip -r criador-de-temas-vencedores.zip upload/criador-de-temas-vencedores
```

## Como Escolher uma Skill

```text
Iniciando um pursuit?                              -> 01-propostas/briefing-de-inicio-de-proposta
Precisa de posicionamento para a proposta?         -> 01-propostas/criador-de-temas-vencedores
Precisa escrever o sumário executivo?              -> 01-propostas/redator-de-sumario-executivo
Precisa redigir o SOW?                             -> 01-propostas/redator-de-declaracao-de-trabalho

Criando oportunidade no Salesforce?                -> 02-operacoes-de-vendas/criador-de-oportunidades-salesforce
Precisa de aprovação do Deal Desk?                 -> 02-operacoes-de-vendas/navegador-de-mesa-de-negocios

Precisa contra-posicionar um concorrente?          -> 03-inteligencia-competitiva/contra-posicionamento-competitivo

Precisa quantificar o ROI do negócio?              -> 04-analytics/construtor-de-caso-de-valor-cliente

Precisa de relatório de status com RAG?            -> 05-comunicacoes-com-cliente/redator-de-relatorio-de-status

Precisa encontrar crescimento em uma conta?        -> 06-crescimento-de-contas/identificador-de-oportunidades-de-crescimento
```
