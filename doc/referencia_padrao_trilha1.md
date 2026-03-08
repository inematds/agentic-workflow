# Referencia Local — Padrao Visual da Trilha 1

Esta referencia complementa a skill `formato-curso` com decisoes especificas adotadas no projeto `agentic-workflow`.

## Objetivo

Padronizar a Trilha 1 para que todos os modulos sigam a mesma experiencia:

- cartao simples clicavel no topo da trilha
- cartao detalhado com topicos expansivos
- botoes `Abrir modulo` e `Ver em Modal` apenas depois da lista de topicos
- tres caixas destacadas por topico:
  - `O que e` em verde
  - `Por que aprender` em azul
  - `Conceitos-chave` em amarelo

## Regra de layout por modulo no index da trilha

1. Header do modulo
2. Lista de topicos expansivos
3. Acoes no rodape do card

As acoes nao devem aparecer antes dos topicos.

## Regra de topicos expansivos

Cada topico deve conter exatamente estas 3 secoes visuais:

### O que e

- caixa verde
- definicao curta e objetiva

### Por que aprender

- caixa azul
- impacto pratico e justificativa

### Conceitos-chave

- caixa amarela
- termos, elementos ou criterios que o aluno deve guardar

## Regra de modulo completo

Cada pagina de modulo deve conter:

1. breadcrumb
2. header com stats
3. 6 secoes principais com numero em circulo grande
4. mistura de boxes:
   - conceito principal
   - dado ou criterio tecnico
   - dica pratica
   - fazer vs evitar
   - alerta
5. resumo final
6. botao para voltar e botao para proximo modulo

## Escopo atual desta referencia

Aplica-se a:

- `curso/trilha1/index.html`
- `curso/trilha1/modulo-1-1.html`
- `curso/trilha1/modulo-1-2.html`
- `curso/trilha1/modulo-1-3.html`
- `curso/trilha1/modulo-1-4.html`
- `curso/trilha1/modulo-1-5.html`
- `curso/trilha1/modulo-1-6.html`
