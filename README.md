# Skills de Estratégia e Vendas para o Claude

Uma coleção de skills prontas para uso no Claude, cobrindo dois universos de consultoria: **estratégia corporativa estilo McKinsey** e **excelência em vendas e gestão de contas estilo Accenture**. Todas as skills estão em português brasileiro.

---

## Bibliotecas Disponíveis

### McKinsey — 21 Skills de Estratégia

Skills de resolução de problemas estratégicos: enquadramento de problemas, inteligência de mercado, escolha estratégica, modelo operacional, governança de valor e comunicação executiva.

**Inspiração:** lógica MECE, análise orientada por hipóteses, foco 80/20, comunicação com a resposta primeiro.

→ [Ver biblioteca McKinsey](McKinsey/README.md)

### Accenture — 10 Skills de Vendas e Contas

Skills de gestão de pursuit, propostas, operações de vendas, inteligência competitiva e crescimento de contas.

**Inspiração:** gestão estruturada de pursuit, temas vencedores respaldados por evidências, governança comercial explícita, valor quantificado para o cliente.

→ [Ver biblioteca Accenture](Accenture/README.md)

---

## Estrutura do Repositório

```text
strategy-skills-for-claude/
│
├── README.md                          ← este arquivo
│
├── McKinsey/                          ← 21 skills de estratégia (PT-BR)
│   ├── README.md
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
│
└── Accenture/                         ← 10 skills de vendas e contas (PT-BR)
    ├── README.md
    └── skills/
            ├── 01-propostas/
            │   ├── briefing-de-inicio-de-proposta.md
            │   ├── criador-de-temas-vencedores.md
            │   ├── redator-de-sumario-executivo.md
            │   └── redator-de-declaracao-de-trabalho.md
            ├── 02-operacoes-de-vendas/
            │   ├── criador-de-oportunidades-salesforce.md
            │   └── navegador-de-mesa-de-negocios.md
            ├── 03-inteligencia-competitiva/
            │   └── contra-posicionamento-competitivo.md
            ├── 04-analytics/
            │   └── construtor-de-caso-de-valor-cliente.md
            ├── 05-comunicacoes-com-cliente/
            │   └── redator-de-relatorio-de-status.md
            └── 06-crescimento-de-contas/
                    └── identificador-de-oportunidades-de-crescimento.md
```

---

## Mapa Rápido de Skills

### McKinsey — Estratégia

| Precisa de... | Skill |
|---|---|
| Entender a situação atual | `avaliacao-da-situacao` |
| Desbloquear crescimento | `barreiras-de-crescimento` |
| Testar crenças estratégicas | `auditoria-de-premissas` |
| Mapear e dimensionar mercado | `mapeamento-de-mercado` |
| Entender concorrentes | `inteligencia-competitiva` |
| Segmentar clientes | `segmentacao-de-clientes` |
| Encontrar onde o lucro está | `analise-de-pool-de-lucro` |
| Gerar opções antes de decidir | `opcoes-estrategicas` |
| Melhorar monetização | `estrategia-de-precificacao` |
| Quantificar economics de um movimento | `construtor-de-caso-de-negocio` |
| Alocar recursos entre apostas | `revisao-de-portfolio` |
| Traduzir estratégia em operação | `design-do-modelo-operacional` |
| Cortar lista de iniciativas | `priorizador-de-iniciativas` |
| Criar plano de execução | `roteiro-de-transformacao` |
| Testar estratégia sob pressão | `simulacao-de-guerra-estrategica` |
| Controlar riscos estratégicos | `risco-e-mitigacao` |
| Desenhar métricas | `arquiteto-de-kpis` |
| Garantir captura de benefícios | `realizacao-de-valor` |
| Ganhar aprovação antes da reunião | `alinhamento-de-partes-interessadas` |
| Construir a narrativa executiva | `construtor-de-narrativa` |
| Escrever recomendação para liderança | `memorando-de-decisao` |

### Accenture — Vendas e Contas

| Precisa de... | Skill |
|---|---|
| Abrir um pursuit | `briefing-de-inicio-de-proposta` |
| Posicionar a proposta | `criador-de-temas-vencedores` |
| Escrever o sumário executivo | `redator-de-sumario-executivo` |
| Redigir o SOW | `redator-de-declaracao-de-trabalho` |
| Criar oportunidade no Salesforce | `criador-de-oportunidades-salesforce` |
| Submeter ao Deal Desk | `navegador-de-mesa-de-negocios` |
| Contra-posicionar concorrentes | `contra-posicionamento-competitivo` |
| Quantificar ROI para o cliente | `construtor-de-caso-de-valor-cliente` |
| Reportar status com RAG | `redator-de-relatorio-de-status` |
| Encontrar crescimento na conta | `identificador-de-oportunidades-de-crescimento` |

---

## Como Instalar uma Skill

Cada arquivo `.md` é uma skill autônoma. Para usar no Claude:

1. Escolha o arquivo da skill que você quer usar.
2. Crie uma pasta temporária com o nome da skill.
3. Copie o arquivo para essa pasta com o nome `SKILL.md`.
4. Compacte em `.zip` se necessário para o seu ambiente Claude.
5. Faça upload no Claude e teste com um prompt relevante.

```bash
# Exemplo — McKinsey
mkdir upload/simulacao-de-guerra-estrategica
cp McKinsey/skills/05-risco-performance-e-governanca-de-valor/simulacao-de-guerra-estrategica.md \
   upload/simulacao-de-guerra-estrategica/SKILL.md

# Exemplo — Accenture
mkdir upload/criador-de-temas-vencedores
cp accenture/pt-br/skills/01-propostas/criador-de-temas-vencedores.md \
   upload/criador-de-temas-vencedores/SKILL.md
```

---

## Quando Usar Cada Biblioteca

**Use McKinsey quando** o problema é estratégico: qual mercado entrar, como alocar capital, por que o crescimento travou, como estruturar a execução, como comunicar uma recomendação ao conselho.

**Use Accenture quando** o trabalho é comercial ou operacional de vendas: abrir um pursuit, escrever uma proposta, contra-posicionar concorrentes, justificar ROI para aprovação interna, reportar progresso ao cliente, ou identificar crescimento em contas existentes.

As duas bibliotecas se complementam: McKinsey define a estratégia, Accenture executa a venda e entrega.
