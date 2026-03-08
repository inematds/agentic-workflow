# Plano de Curso Completo — Agentic em 3 Trilhas

## 1. Analise do conteudo atual do projeto

O projeto hoje esta concentrado em materiais de apoio dentro de `doc/` e ainda nao possui a estrutura do curso em HTML.

### Arquivos principais encontrados

- `doc/conteudo_agentic_sessao.md`
- `doc/agentic_workflows_guia_completo.md`
- `doc/resuam todo os topicos.txt`
- imagens e um video em `doc/`

### O que o conteudo atual cobre bem

- definicao de Agentic AI e workflows agentic
- diferenca entre chatbot, automacao tradicional e agentic
- framework WAT: Workflows, Agent, Tools
- exemplo de newsletter automatizada
- planejamento basico do sistema
- uso de credenciais e `.env`
- testes e melhoria continua
- narrativa de mercado, valor, ROI e venda consultiva

### Problema principal do material atual

O conteudo esta forte em introducao, posicionamento e narrativa comercial, mas ainda esta raso na parte de implementacao, arquitetura, operacao e progressao pedagogica.

### Lacunas para transformar em curso completo

- fundamentos tecnicos minimos para iniciantes
- desenho de workflows reais passo a passo
- ferramentas, APIs, webhooks e formatos de dados
- contexto, memoria, estado e persistencia
- skills, MCP e integracoes
- avaliacao, testes, observabilidade e custo
- seguranca, guardrails e limites operacionais
- deploy, agendamento e operacao em producao
- estudos de caso completos
- exercicios, projetos e entregaveis por modulo

## 1.1 Direcao recomendada para preencher as lacunas

Se o objetivo e formar talento de **engenheiro de agentic**, o curso deve reduzir teoria passiva e aumentar treino operacional.

### Foco recomendado

- projetar tools com schema claro e limites explicitos
- decompor problemas em workflows testaveis
- definir entradas, saidas e criterios de sucesso
- inspecionar traces e depurar falhas de execucao
- criar evals e graders para medir qualidade
- trabalhar com aprovacoes humanas e guardrails
- operar integracoes reais com estado, memoria e logs
- fazer deploy, observabilidade e melhoria continua

### O que evitar como foco central

- excesso de aula motivacional sobre futuro do mercado
- excesso de comparacao conceitual sem implementacao
- demos bonitas sem criterios de confiabilidade
- modulos muito genericos sobre IA sem artefato pratico

## 2. Recomendacao de estrutura em 3 trilhas

A melhor divisao para este projeto e separar o curso por maturidade e objetivo:

1. Trilha 1: Fundamentos Agentic
2. Trilha 2: Construcao e Operacao de Sistemas Agentic
3. Trilha 3: Aplicacao de Mercado, Consultoria e Produtos

Essa divisao aproveita o material atual nas trilhas 1 e 3 e cria uma trilha 2 mais tecnica, que hoje e a maior lacuna do projeto.

## 3. Estrutura detalhada das trilhas

## Trilha 1 — Fundamentos Agentic

### Objetivo

Dar base conceitual e tecnica minima para quem ainda esta saindo de chatbot e automacao tradicional.

### Modulos sugeridos

#### Modulo 1. O que e Agentic AI

- conceito central
- por que isso importa agora
- diferenca entre chatbot, automacao e agentic
- tipos de problemas que agentic resolve melhor

#### Modulo 2. Fundamentos tecnicos sem enrolacao

- como APIs funcionam
- o que sao webhooks
- JSON, arquivos, entradas e saidas
- variaveis de ambiente e credenciais

#### Modulo 3. Estrutura WAT

- Workflows
- Agent
- Tools
- como cada parte se conecta
- quando usar fluxo deterministico vs fluxo agentico

#### Modulo 4. Como pensar em objetivos, contexto e restricoes

- objetivo claro
- criterios de sucesso
- entradas obrigatorias
- saidas esperadas
- regras e limites do agente

#### Modulo 5. Skills, ferramentas e contexto reutilizavel

- o que e uma skill
- como organizar instrucoes reutilizaveis
- padroes de tool use
- contexto de marca, estilo e negocio

#### Modulo 6. Primeiro workflow agentic guiado

- exemplo simples de pesquisa + estruturacao + entrega
- decomposicao em etapas
- erros mais comuns de iniciantes

### O que pode ser reaproveitado do projeto atual

- quase todo o conteudo conceitual atual
- comparacoes entre chatbot, automacao e agentic
- WAT
- exemplo de newsletter

## Trilha 2 — Construcao e Operacao de Sistemas Agentic

### Objetivo

Ensinar como desenhar, construir, testar e operar sistemas agentic de verdade.

### Modulos sugeridos

#### Modulo 1. Arquitetura de um sistema agentic

- entrada, planejamento, execucao e saida
- componentes do sistema
- orquestracao
- separacao entre agente, tools e runtime

#### Modulo 2. Design de workflows confiaveis

- decomposicao de tarefas
- pontos de decisao
- fallback
- retry
- checkpoints
- human in the loop

#### Modulo 3. Ferramentas e integracoes

- leitura e escrita de arquivos
- consumo de API
- banco de dados
- email
- scraping e pesquisa
- geracao de artefatos
- design de tool schema e contratos de entrada/saida
- quando exigir confirmacao humana antes da acao

#### Modulo 4. Memoria, contexto e persistencia

- contexto temporario vs persistente
- historico de execucao
- armazenamento de estado
- como evitar perda de contexto

#### Modulo 5. Testes, evals e depuracao

- testes de fluxo
- casos limite
- validacao de saida
- rastreabilidade
- como medir qualidade
- traces e trace grading
- graders objetivos e subjetivos
- regressao entre versoes de prompt, tool e workflow

#### Modulo 6. Seguranca e governanca

- escopo de acesso do agente
- protecao de credenciais
- acoes destrutivas
- confirmacoes humanas
- compliance basico
- isolamento de dados nao confiaveis
- prompt injection e uso de saídas estruturadas

#### Modulo 7. Deploy e operacao

- execucao local
- execucao agendada
- webhooks
- filas
- monitoramento
- custos e limites
- observabilidade por trace
- estrategia de retry e fallback em producao

#### Modulo 8. Projeto pratico completo

- construir um workflow de ponta a ponta
- documentar arquitetura
- testar
- publicar

### Lacuna atual do projeto

Essa trilha quase nao existe no material atual e precisa ser produzida praticamente do zero.

### Formato ideal dessa trilha

Cada modulo deve terminar com um artefato de engenharia observavel:

- arquivo de especificacao do workflow
- contrato JSON de tools
- suite minima de eval
- checklist de seguranca
- log ou trace analisado
- mini projeto executavel

## Trilha 3 — Aplicacao de Mercado, Consultoria e Produtos

### Objetivo

Transformar conhecimento tecnico em valor de negocio, servico, consultoria ou produto.

### Modulos sugeridos

#### Modulo 1. Identificando gargalos reais

- como diagnosticar processos
- onde agentic gera valor
- quando NAO usar agentic

#### Modulo 2. Casos de uso por area

- marketing e conteudo
- vendas e CRM
- atendimento
- operacoes
- financeiro
- RH

#### Modulo 3. Escopo e proposta

- discovery
- mapa do processo atual
- desenho da solucao futura
- riscos e premissas

#### Modulo 4. ROI e precificacao

- horas economizadas
- custo evitado
- aumento de receita
- preco por valor entregue

#### Modulo 5. Entrega para cliente

- onboarding
- coleta de acessos
- validacao
- rollout
- handoff e manutencao

#### Modulo 6. Portfolio e produto

- transformar um projeto em case
- empacotar servicos
- criar oferta recorrente
- evoluir de freelancer para parceiro estrategico

#### Modulo 7. Capstone de negocio

- diagnosticar uma empresa
- propor workflow
- calcular ROI
- desenhar implementacao

### O que pode ser reaproveitado do projeto atual

- analogia do gargalo
- valor gerado vs preco por hora
- caminho freelancer -> consultor -> parceiro estrategico

## 4. Ordem pedagogica recomendada

Se o aluno fizer o curso completo:

1. Trilha 1 primeiro
2. Trilha 2 depois
3. Trilha 3 por ultimo

Se o publico for mais tecnico:

1. Trilha 1 condensada
2. Trilha 2 completa
3. Trilha 3 como especializacao

Se o publico for consultor, estrategista ou dono de agencia:

1. Trilha 1
2. Trilha 3
3. Trilha 2 como aprofundamento tecnico

## 5. Reorganizacao sugerida do conteudo atual

### Conteudo que ja pode virar aulas rapidamente

- introducao ao agentic
- comparativo com chatbot e automacao
- framework WAT
- exemplo de workflow de newsletter
- por que o mercado esta crescendo
- habilidades e modelos de negocio

### Conteudo novo que precisa ser criado prioritariamente

- fundamentos tecnicos: API, webhook, JSON, auth, `.env`
- design de workflow e orquestracao
- tools e integracoes na pratica
- memoria e contexto
- testes e evals
- deploy e operacao
- seguranca e guardrails
- 2 ou 3 projetos praticos completos

## 6. Sugestao de projetos ancora do curso

Para dar unidade ao curso, recomendo 3 projetos principais:

1. Assistente de pesquisa e sintese
   - bom para Trilha 1
2. Workflow agentic de conteudo ou operacao com tools
   - bom para Trilha 2
3. Diagnostico e proposta agentic para empresa real
   - bom para Trilha 3

## 6.1 Projetos praticos recomendados para desenvolver talento de engenharia agentic

Para o curso ficar realmente formador, recomendo trocar parte das aulas expositivas por laboratorios progressivos.

### Laboratorio 1. Tool calling basico

- desenhar 3 tools com schema
- testar entradas validas e invalidas
- observar quando o agente chama a tool errada
- refinar descricao e parametros

### Laboratorio 2. Workflow deterministico + etapa agentica

- separar o que deve ser fixo do que pode ser decidido pelo agente
- criar checkpoints
- validar saida final contra criterios objetivos

### Laboratorio 3. Memoria e estado

- salvar historico minimo
- retomar uma execucao
- distinguir contexto de sessao e contexto persistente

### Laboratorio 4. Evals e trace debugging

- criar dataset pequeno de casos
- rodar avaliacao
- analisar traces
- corrigir falha sem piorar casos que ja funcionavam

### Laboratorio 5. Seguranca e aprovacao humana

- limitar escopo de tools
- bloquear operacoes destrutivas sem aprovacao
- testar cenarios de entrada maliciosa

### Laboratorio 6. MCP na pratica

- expor ou consumir um MCP server simples
- testar recursos, prompts e tools
- inspecionar capacidades e erros de integracao

### Laboratorio 7. Deploy e operacao

- colocar um workflow para rodar por evento ou agendamento
- instrumentar logs
- medir custo, latencia e taxa de falha

## 6.2 Rubrica de talento do engenheiro de agentic

O aluno deve sair do curso conseguindo demonstrar:

- clareza para definir objetivo operacional
- habilidade de decompor tarefas em etapas confiaveis
- criterio para decidir entre fluxo fixo e decisao do agente
- dominio de tool design e schemas
- capacidade de depurar traces e falhas reais
- habilidade de medir qualidade com evals
- nocao forte de seguranca, aprovacoes e escopo
- maturidade para operar workflows em producao

## 7. Referencias externas confiaveis para preencher as lacunas

As recomendacoes abaixo sao baseadas em documentacao oficial e especificacoes primarias. A inferencia pedagogica aqui e: essas fontes apontam que formar um bom engenheiro de agentic exige treinar principalmente workflow design, tool use, seguranca, evals e observabilidade.

### OpenAI

- Agents SDK: handoffs, tools, streaming e traces
- Agent Builder e Node Reference: composicao de workflows e controle de fluxo
- Agent Evals, Trace Grading, Graders e Prompt Optimizer: medicao, regressao e melhoria continua
- Safety in building agents: guardrails, aprovacoes, dados nao confiaveis e reducao de risco

### Anthropic

- implementacao de tool use: definicao de tools, schemas e melhores praticas
- web search, bash e code execution: padroes de integracao reais
- streaming de tools e eficiencia de tokens: tradeoffs operacionais

### MCP

- lifecycle e capability negotiation: arquitetura e interoperabilidade
- tools: contrato de exposicao e human-in-the-loop
- inspector: depuracao de servidores MCP
- design principles: composabilidade e convergencia de padroes

## 8. Conclusao

O projeto atual ja tem um bom nucleo para abrir um curso, mas ainda nao esta pronto como curso completo. A base existente sustenta bem:

- a promessa do tema
- a introducao conceitual
- a comparacao de modelos
- a camada de valor de negocio

O que falta para fechar um curso forte e principalmente a trilha tecnica intermediaria, com construcao, operacao, testes e casos praticos.

Se o foco for desenvolvimento de talento de engenharia agentic, a decisao correta e reorganizar o curso para que o aluno produza artefatos, depure falhas, rode avaliacoes e opere workflows reais, em vez de apenas consumir explicacoes conceituais.

## 9. Proxima acao recomendada

Se a ideia for transformar isso em produto educacional agora, a sequencia mais eficiente e:

1. fechar a grade final das 3 trilhas
2. definir modulos por trilha
3. mapear o conteudo atual para cada modulo
4. listar as aulas novas necessarias
5. criar o `index.html` do curso e os `index.html` de cada trilha
6. produzir os modulos em HTML no formato INEMA.CLUB
