# Grade Final — Engenharia Agentic em 3 Trilhas

## Visao geral

- Curso: Engenharia Agentic
- Trilhas: 3
- Modulos: 18
- Formato: teoria aplicada + laboratorio + projeto
- Resultado esperado: formar engenheiro de agentic com foco em workflow, tools, evals, seguranca e operacao

## Trilha 1 — Fundamentos Agentic

### Modulo 1. O que e Agentic AI e como pensar como engenheiro

- Aula 1: chatbot, automacao e agentic
- Aula 2: objetivo, contexto, restricao e saida
- Aula 3: criterios de sucesso e falha
- Aula 4: decomposicao de tarefas
- Aula 5: quando usar fluxo fixo e quando usar decisao do agente
- Aula 6: laboratorio de especificacao de workflow
- Entregavel: spec de workflow em linguagem natural + contrato de entrada e saida

### Modulo 2. Fundamentos tecnicos que sustentam workflows

- Aula 1: APIs, requests e respostas
- Aula 2: JSON, arquivos e parsers
- Aula 3: webhooks e eventos
- Aula 4: autenticacao, secrets e .env
- Aula 5: erros de integracao e contratos
- Aula 6: laboratorio de consumo de API
- Entregavel: mini integracao com input, output e tratamento de erro

### Modulo 3. Framework WAT na pratica

- Aula 1: workflow, agent e tools
- Aula 2: limites de cada camada
- Aula 3: orquestracao minima
- Aula 4: handoffs e composicao
- Aula 5: observabilidade inicial
- Aula 6: laboratorio WAT
- Entregavel: mapa arquitetural simples

### Modulo 4. Tool design e schemas

- Aula 1: como descrever bem uma tool
- Aula 2: schemas de entrada e saida
- Aula 3: validacao e tipos
- Aula 4: erros recuperaveis e nao recuperaveis
- Aula 5: aprovacoes humanas
- Aula 6: laboratorio de tool calling
- Entregavel: 3 tools com schema e casos de teste

### Modulo 5. Contexto, memoria e reutilizacao

- Aula 1: contexto de sessao
- Aula 2: memoria persistente
- Aula 3: arquivos de configuracao
- Aula 4: skills e instrucoes reutilizaveis
- Aula 5: contexto de marca e negocio
- Aula 6: laboratorio de memoria
- Entregavel: workflow com estado minimo persistido

### Modulo 6. Primeiro mini projeto agentic

- Aula 1: pesquisa
- Aula 2: sintese
- Aula 3: validacao
- Aula 4: entrega estruturada
- Aula 5: revisao por criterio
- Aula 6: demo final
- Entregavel: assistente de pesquisa e sintese

## Trilha 2 — Construcao e Operacao de Sistemas Agentic

### Modulo 1. Arquitetura de sistemas agentic

- Aula 1: runtime e componentes
- Aula 2: etapas de execucao
- Aula 3: pontos de decisao
- Aula 4: filas, estados e persistencia
- Aula 5: fronteiras entre deterministico e agentico
- Aula 6: laboratorio de arquitetura
- Entregavel: diagrama operacional do sistema

### Modulo 2. Design de workflows confiaveis

- Aula 1: decomposicao confiavel
- Aula 2: checkpoints
- Aula 3: fallback e retry
- Aula 4: human in the loop
- Aula 5: recuperacao de falha
- Aula 6: laboratorio de robustez
- Entregavel: workflow com fallback e checkpoint

### Modulo 3. Integracoes reais

- Aula 1: arquivos e storage
- Aula 2: APIs e rate limit
- Aula 3: banco de dados
- Aula 4: email e notificacao
- Aula 5: scraping e pesquisa
- Aula 6: laboratorio de integracao
- Entregavel: pipeline com 3 integracoes

### Modulo 4. MCP e interoperabilidade

- Aula 1: arquitetura MCP
- Aula 2: resources, prompts e tools
- Aula 3: capability negotiation
- Aula 4: MCP server simples
- Aula 5: inspector e debug
- Aula 6: laboratorio MCP
- Entregavel: MCP server ou cliente simples funcional

### Modulo 5. Evals, traces e depuracao

- Aula 1: casos de teste
- Aula 2: graders
- Aula 3: trace analysis
- Aula 4: regressao entre versoes
- Aula 5: tuning sem quebrar o que ja funciona
- Aula 6: laboratorio de eval
- Entregavel: suite minima de eval + analise de trace

### Modulo 6. Seguranca e guardrails

- Aula 1: escopo de tools
- Aula 2: acoes destrutivas
- Aula 3: prompt injection
- Aula 4: dados nao confiaveis
- Aula 5: controles humanos
- Aula 6: laboratorio de seguranca
- Entregavel: checklist de risco e politica de aprovacao

### Modulo 7. Deploy e operacao

- Aula 1: execucao local e remota
- Aula 2: schedulers e webhooks
- Aula 3: logs e monitoramento
- Aula 4: custo, latencia e taxa de falha
- Aula 5: runbooks operacionais
- Aula 6: laboratorio de deploy
- Entregavel: workflow implantado com logs e metricas

### Modulo 8. Projeto principal de engenharia

- Aula 1: definicao do caso
- Aula 2: implementacao
- Aula 3: observabilidade
- Aula 4: seguranca
- Aula 5: avaliacao
- Aula 6: apresentacao final
- Entregavel: workflow agentic de ponta a ponta

## Trilha 3 — Mercado, Consultoria e Produtos

### Modulo 1. Diagnostico de gargalos reais

- Aula 1: mapear processo
- Aula 2: achar desperdicio
- Aula 3: escolher problema elegivel
- Aula 4: quando nao usar agentic
- Aula 5: risco e prioridade
- Aula 6: laboratorio de discovery
- Entregavel: mapa de oportunidade

### Modulo 2. Casos de uso por area

- Aula 1: marketing
- Aula 2: vendas
- Aula 3: atendimento
- Aula 4: operacoes
- Aula 5: financeiro e RH
- Aula 6: laboratorio de adaptacao setorial
- Entregavel: backlog de casos de uso

### Modulo 3. Escopo tecnico-comercial

- Aula 1: as-is e to-be
- Aula 2: premissas
- Aula 3: riscos
- Aula 4: escopo minimo viavel
- Aula 5: cronograma e dependencia
- Aula 6: laboratorio de proposta
- Entregavel: proposta de implementacao

### Modulo 4. ROI e precificacao

- Aula 1: tempo economizado
- Aula 2: erro reduzido
- Aula 3: custo evitado
- Aula 4: receita gerada
- Aula 5: preco por valor
- Aula 6: laboratorio de calculo
- Entregavel: calculadora de ROI

### Modulo 5. Entrega e adocao

- Aula 1: onboarding
- Aula 2: acessos e credenciais
- Aula 3: validacao de aceite
- Aula 4: rollout
- Aula 5: manutencao e SLA
- Aula 6: laboratorio de handoff
- Entregavel: plano de rollout

### Modulo 6. Portfolio, oferta e produto

- Aula 1: construir case
- Aula 2: empacotar oferta
- Aula 3: recorrencia
- Aula 4: posicionamento
- Aula 5: evolucao freelancer para parceiro
- Aula 6: laboratorio de oferta
- Entregavel: pagina de oferta ou case

### Modulo 7. Capstone de negocio

- Aula 1: diagnostico
- Aula 2: desenho da solucao
- Aula 3: ROI
- Aula 4: plano de execucao
- Aula 5: pitch
- Aula 6: banca final
- Entregavel: proposta completa para empresa real
