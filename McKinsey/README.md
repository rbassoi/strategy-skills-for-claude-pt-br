# 21 Skills de Estratégia Estilo McKinsey para o Claude

<img width="1024" height="1536" alt="Claude OS" src="https://github.com/user-attachments/assets/e459cb00-36f4-4f12-8abd-e420487ce177" />


> Inspirado na resolução de problemas estilo McKinsey e na prática de consultoria MBB: enquadramento preciso, lógica MECE, análise orientada por hipóteses, foco 80/20, comunicação com a resposta primeiro, e recomendações prontas para executivos. Esta coleção é independente e não oficial.

## O Que É Isso

Este repositório contém 21 skills autônomas do Claude para trabalho estratégico, agrupadas em seis domínios práticos de consultoria. Cada skill é um fluxo de trabalho pequeno e carregável que ensina o Claude a executar uma tarefa de consultoria de alto valor com um método repetível no estilo McKinsey.

Juntas, as skills operam como um sistema operacional de IA de consultoria para um engajamento completo: diagnosticar o problema, mapear o mercado, escolher um caminho estratégico, traduzir em execução, governar valor e comunicar a recomendação.

A coleção foi projetada para construtores de negócios, operadores, consultores, analistas, fundadores e equipes de estratégia que querem que o Claude trabalhe mais próximo de um consultor estilo MBB do top 1%: estruturado antes de analítico, orientado por hipóteses antes de exaustivo, e pronto para executivos antes de verboso.

```mermaid
flowchart LR
    diagnose["Diagnosticar e Enquadrar"] --> map["Mapear Mercados e Concorrência"]
    map --> choose["Escolher Estratégia e Economia"]
    choose --> execute["Construir Modelo Operacional e Execução"]
    execute --> govern["Governar Risco, Performance e Valor"]
    govern --> communicate["Alinhar e Comunicar"]
```

## Por Que Existe

A maioria dos prompts de estratégia falha porque pede insight antes de o trabalho estar estruturado. Este sistema operacional de IA de consultoria dá ao Claude uma espinha dorsal de engajamento reutilizável que o ajuda a:

✓ enquadrar a decisão real  
✓ separar sintomas de causas  
✓ tornar premissas visíveis  
✓ construir estruturas MECE  
✓ priorizar os poucos movimentos que importam  
✓ testar recomendações sob pressão antes de encontrar a realidade  
✓ comunicar de forma pronta para o conselho  

## Mapa da Coleção

```text
strategy-skills-for-claude/
│
├── pt-br/
│   ├── README.md
│   │
│   └── skills/
│       ├── 01-diagnostico-e-enquadramento/
│       │   ├── avaliacao-da-situacao.md
│       │   ├── barreiras-de-crescimento.md
│       │   └── auditoria-de-premissas.md
│       ├── 02-inteligencia-de-mercado-e-competitiva/
│       │   ├── mapeamento-de-mercado.md
│       │   ├── inteligencia-competitiva.md
│       │   ├── segmentacao-de-clientes.md
│       │   └── analise-de-pool-de-lucro.md
│       ├── 03-escolha-estrategica-e-economia/
│       │   ├── opcoes-estrategicas.md
│       │   ├── estrategia-de-precificacao.md
│       │   ├── construtor-de-caso-de-negocio.md
│       │   └── revisao-de-portfolio.md
│       ├── 04-modelo-operacional-e-execucao/
│       │   ├── design-do-modelo-operacional.md
│       │   ├── priorizador-de-iniciativas.md
│       │   └── roteiro-de-transformacao.md
│       ├── 05-risco-performance-e-governanca-de-valor/
│       │   ├── simulacao-de-guerra-estrategica.md
│       │   ├── risco-e-mitigacao.md
│       │   ├── arquiteto-de-kpis.md
│       │   └── realizacao-de-valor.md
│       └── 06-alinhamento-e-comunicacao-executiva/
│           ├── alinhamento-de-partes-interessadas.md
│           ├── construtor-de-narrativa.md
│           └── memorando-de-decisao.md
```

Cada arquivo markdown dentro de `skills/` é uma definição individual de skill. Para carregar uma no Claude, coloque o arquivo escolhido em uma pasta temporária e nomeie-o como `SKILL.md`.

## As 21 Skills

### 1. Diagnóstico e Enquadramento

Use quando a equipe precisa entender o problema real antes de escolher um movimento. O estilo é inspirado na McKinsey: base de fatos primeiro, disciplina de causa raiz, premissas explícitas e uma pergunta clara a responder.

| Skill | Quando Usar | Saída |
|---|---|---|
| [Avaliação da Situação](skills/01-diagnostico-e-enquadramento/avaliacao-da-situacao.md) | Você precisa da linha de base factual antes de escolher uma direção | Base de fatos, leitura de momentum, lista de questões |
| [Barreiras de Crescimento](skills/01-diagnostico-e-enquadramento/barreiras-de-crescimento.md) | O crescimento está travado e a liderança debate sintomas | Diagnóstico de restrição e plano de evidências |
| [Auditoria de Premissas](skills/01-diagnostico-e-enquadramento/auditoria-de-premissas.md) | Uma estratégia depende de crenças que podem ser frágeis | Registro de premissas e plano de teste |

### 2. Inteligência de Mercado e Competitiva

Use quando a resposta depende de onde o valor está, como os clientes diferem, como os rivais podem se comportar ou onde está o espaço atrativo.

| Skill | Quando Usar | Saída |
|---|---|---|
| [Mapeamento de Mercado](skills/02-inteligencia-de-mercado-e-competitiva/mapeamento-de-mercado.md) | Você precisa dimensionar, segmentar e mapear espaço em branco | Mapa de mercado e opções de onde atuar |
| [Inteligência Competitiva](skills/02-inteligencia-de-mercado-e-competitiva/inteligencia-competitiva.md) | Você precisa prever movimentos prováveis dos concorrentes | Mapa de movimentos dos rivais e plano de resposta |
| [Segmentação de Clientes](skills/02-inteligencia-de-mercado-e-competitiva/segmentacao-de-clientes.md) | Você precisa de grupos de clientes mais precisos para decisões estratégicas | Segmentos MECE e prioridades de segmento |
| [Análise de Pool de Lucro](skills/02-inteligencia-de-mercado-e-competitiva/analise-de-pool-de-lucro.md) | Você precisa saber onde o valor é criado e capturado | Mapa de pool de lucro e implicações estratégicas |

### 3. Escolha Estratégica e Economia

Use quando líderes precisam de escolhas, trade-offs, economias e decisões de alocação. Essas skills empurram o Claude para recomendações com consciência de opções e respaldo em evidências, em vez de advocacia de resposta única.

| Skill | Quando Usar | Saída |
|---|---|---|
| [Opções Estratégicas](skills/03-escolha-estrategica-e-economia/opcoes-estrategicas.md) | Você precisa de alternativas antes de se comprometer com um caminho | Conjunto de opções, critérios, recomendação |
| [Estratégia de Precificação](skills/03-escolha-estrategica-e-economia/estrategia-de-precificacao.md) | Poder de precificação, descontos ou monetização estão obscuros | Diagnóstico de precificação e plano de ação |
| [Construtor de Caso de Negócio](skills/03-escolha-estrategica-e-economia/construtor-de-caso-de-negocio.md) | Uma decisão precisa de economias, sensibilidades e riscos | Caso de negócio e lógica de decisão |
| [Revisão de Portfólio](skills/03-escolha-estrategica-e-economia/revisao-de-portfolio.md) | Você precisa alocar recursos entre apostas | Diagnóstico de portfólio e escolhas de alocação |

### 4. Modelo Operacional e Execução

Use quando a estratégia deve se tornar trabalho: capacidades, direitos de decisão, escolhas de iniciativas, roteiros, responsáveis e os primeiros 90 dias.

| Skill | Quando Usar | Saída |
|---|---|---|
| [Design do Modelo Operacional](skills/04-modelo-operacional-e-execucao/design-do-modelo-operacional.md) | A estratégia precisa ser traduzida em como o trabalho acontece | Capacidades, governança, direitos de decisão |
| [Priorizador de Iniciativas](skills/04-modelo-operacional-e-execucao/priorizador-de-iniciativas.md) | Muitas iniciativas competem por atenção | Roteiro classificado e lista de eliminação |
| [Roteiro de Transformação](skills/04-modelo-operacional-e-execucao/roteiro-de-transformacao.md) | Uma estratégia deve se tornar execução sequenciada | Roteiro por fases, responsáveis, riscos |

### 5. Risco, Performance e Governança de Valor

Use quando a recomendação precisa de teste de pressão, controle de risco, medição e captura de valor. O padrão é uma visão de governança pronta para o conselho, não uma lista genérica de riscos.

| Skill | Quando Usar | Saída |
|---|---|---|
| [Simulação de Guerra Estratégica](skills/05-risco-performance-e-governanca-de-valor/simulacao-de-guerra-estrategica.md) | Uma estratégia precisa de teste de pressão antes do lançamento | Teste de estresse de cenários e movimentos de resposta |
| [Risco e Mitigação](skills/05-risco-performance-e-governanca-de-valor/risco-e-mitigacao.md) | O risco estratégico precisa de um responsável e plano de resposta | Registro de riscos e contingências |
| [Arquiteto de KPIs](skills/05-risco-performance-e-governanca-de-valor/arquiteto-de-kpis.md) | As métricas são ruidosas, defasadas ou performáticas | Sistema de KPIs vinculado a decisões |
| [Realização de Valor](skills/05-risco-performance-e-governanca-de-valor/realizacao-de-valor.md) | Os benefícios devem ser rastreados após o lançamento | Livro de valor e modelo de governança |

### 6. Alinhamento e Comunicação Executiva

Use quando o trabalho deve sobreviver à reunião: prepare antecipadamente as partes interessadas, afine a história executiva e transforme a recomendação em uma decisão escrita.

| Skill | Quando Usar | Saída |
|---|---|---|
| [Alinhamento de Partes Interessadas](skills/06-alinhamento-e-comunicacao-executiva/alinhamento-de-partes-interessadas.md) | A recomendação precisa de preparação anterior à reunião | Mapa de partes interessadas e plano de engajamento |
| [Construtor de Narrativa](skills/06-alinhamento-e-comunicacao-executiva/construtor-de-narrativa.md) | Você precisa que a história funcione nos primeiros 60 segundos | História em pirâmide, SCQA, perguntas hostis |
| [Memorando de Decisão](skills/06-alinhamento-e-comunicacao-executiva/memorando-de-decisao.md) | Um executivo precisa de uma recomendação clara por escrito | Memorando de decisão com opções e próximos passos |

## Como Instalar

Este repositório mantém as 21 skills como arquivos markdown autônomos agrupados em `skills/`. O Claude espera que uma pasta de skill carregada contenha um arquivo chamado `SKILL.md`, então use uma pasta temporária pequena quando quiser instalar uma.

1. Escolha um arquivo markdown em uma das pastas de categoria `skills/`.
2. Crie uma pasta temporária com o nome da skill.
3. Copie o arquivo markdown escolhido para essa pasta como `SKILL.md`.
4. Compacte a pasta temporária se sua interface do Claude exigir upload como zip.
5. Faça o upload ou coloque-a no diretório de skills do seu Claude.
6. Teste com um prompt de estratégia claro.

Exemplo:

```bash
cd strategy-skills-for-claude/pt-br
mkdir -p upload/mapeamento-de-mercado
cp skills/02-inteligencia-de-mercado-e-competitiva/mapeamento-de-mercado.md upload/mapeamento-de-mercado/SKILL.md
cd upload
zip -r mapeamento-de-mercado.zip mapeamento-de-mercado
```

## Como Escolher uma Skill

```text
Precisa de verdade sobre a situação atual?          -> 01-diagnostico-e-enquadramento/avaliacao-da-situacao
Precisa desbloquear o crescimento?                  -> 01-diagnostico-e-enquadramento/barreiras-de-crescimento
Precisa testar crenças estratégicas?                -> 01-diagnostico-e-enquadramento/auditoria-de-premissas

Precisa encontrar espaços atrativos?                -> 02-inteligencia-de-mercado-e-competitiva/mapeamento-de-mercado
Precisa entender os rivais?                         -> 02-inteligencia-de-mercado-e-competitiva/inteligencia-competitiva
Precisa de melhores grupos de clientes?             -> 02-inteligencia-de-mercado-e-competitiva/segmentacao-de-clientes
Precisa encontrar onde o dinheiro é feito?          -> 02-inteligencia-de-mercado-e-competitiva/analise-de-pool-de-lucro

Precisa de opções antes de decidir?                 -> 03-escolha-estrategica-e-economia/opcoes-estrategicas
Precisa de melhor monetização?                      -> 03-escolha-estrategica-e-economia/estrategia-de-precificacao
Precisa das economias de um movimento?              -> 03-escolha-estrategica-e-economia/construtor-de-caso-de-negocio
Precisa alocar entre apostas?                       -> 03-escolha-estrategica-e-economia/revisao-de-portfolio

Precisa redesenhar como o trabalho acontece?        -> 04-modelo-operacional-e-execucao/design-do-modelo-operacional
Precisa cortar a lista de iniciativas?              -> 04-modelo-operacional-e-execucao/priorizador-de-iniciativas
Precisa de um plano de entrega?                     -> 04-modelo-operacional-e-execucao/roteiro-de-transformacao

Precisa testar a realidade sob pressão?             -> 05-risco-performance-e-governanca-de-valor/simulacao-de-guerra-estrategica
Precisa de controle de risco estratégico?           -> 05-risco-performance-e-governanca-de-valor/risco-e-mitigacao
Precisa de melhores métricas?                       -> 05-risco-performance-e-governanca-de-valor/arquiteto-de-kpis
Precisa fazer os benefícios persistirem?            -> 05-risco-performance-e-governanca-de-valor/realizacao-de-valor

Precisa ganhar aprovação antes da reunião?          -> 06-alinhamento-e-comunicacao-executiva/alinhamento-de-partes-interessadas
Precisa da história?                                -> 06-alinhamento-e-comunicacao-executiva/construtor-de-narrativa
Precisa de uma decisão executiva escrita?           -> 06-alinhamento-e-comunicacao-executiva/memorando-de-decisao
```

## Exemplos de Prompts

```text
Use a skill de mapeamento-de-mercado para dimensionar a oportunidade de um produto de pagamentos B2B no Brasil.
```

```text
Use a skill de auditoria-de-premissas para testar sob pressão nossa estratégia de expansão antes da reunião do conselho.
```

```text
Use a skill de construtor-de-narrativa para transformar esta recomendação em uma história executiva estilo McKinsey.
```

```text
Use a skill de priorizador-de-iniciativas para reduzir esta lista de 18 projetos para os 3 que importam.
```

## Padrões de Design Utilizados

Esta coleção segue o guia de construção de skills do Claude:

✓ cada definição de skill inclui frontmatter válido de `SKILL.md`  
✓ nomes de arquivo de skill usam kebab-case  
✓ o frontmatter inclui `name` e `description`  
✓ as descrições incluem o que a skill faz e quando usá-la  
✓ as skills estão agrupadas em seis domínios de consultoria para seleção mais fácil  
✓ as instruções são concisas e acionáveis  
✓ cada skill inclui um fluxo de trabalho, formato de saída e padrão de qualidade  

## Nota de Posicionamento

"Estilo McKinsey" refere-se a uma escola de resolução de problemas estratégicos: diagnóstico estruturado de questões, pensamento MECE, análise orientada por hipóteses, foco 80/20, comunicação em pirâmide e design rigoroso de recomendações. É apropriado descrevê-las como inspiradas na McKinsey, no estilo McKinsey, ou baseadas em frameworks comuns do estilo McKinsey. Evite qualquer formulação que implique autoria, afiliação ou endosso da McKinsey.

## Padrão de Qualidade

Cada skill foi projetada para empurrar o Claude a produzir outputs que sejam:

✓ orientados a decisões  
✓ estruturados antes de analíticos  
✓ conscientes de evidências  
✓ conscientes de premissas  
✓ legíveis por executivos  
✓ específicos o suficiente para agir  
