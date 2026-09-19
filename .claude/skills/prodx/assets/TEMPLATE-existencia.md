---
kind: existencia
schema: expx-schema-v1
pd_id: <PD-AAAA-NNNN>
data: <AAAA-MM-DD>
desfecho: <existe | existe_parcial | nao_existe>
confianca: <alta | reduzida>
tem_memox: <true | false>
tem_relatorios_runx: <true | false>
tem_modulex: <true | false>
modulo_encontrado: <id | ->
---

# <PD-ID> — Verificação de existência

## 1. O que foi procurado

<Os substantivos do problema, não do pedido. Liste os termos e os
sinônimos que a casa usa, em português e em inglês.>

**Termos:** <termo, termo, termo>
**Sinônimos tentados:** <sinônimo, sinônimo>

## 2. Onde foi procurado

| # | Lugar | Achado |
|---|-------|--------|
| 1 | Mapa de funcionalidades do PRODUTO.md | <achado ou "nada encontrado"> |
| 2 | Índice do memox | <achado, ou "memox não instalado"> |
| 3 | Telas, rotas e relatórios do sistema | <achado ou "nada encontrado"> |
| 4 | Relatórios de uso do runx | <achado, ou "sem relatórios"> |
| 5 | Pedidos já avaliados no INDICE.md | <PD-ID e veredito, ou "nada encontrado"> |
| 6 | Catálogo do modulex | <id, fatias N, esforço faixa — **NÃO é evidência de existência**; ou "modulex não instalado"> |

<Registrar onde se procurou e NÃO se achou é o que impede a próxima
pessoa de repetir a busca.>

<A linha 6 responde outra pergunta: não "o sistema já faz", mas "alguém
já resolveu isso antes, em outro projeto". Ela NÃO determina o desfecho
— os cinco primeiros lugares determinam. Módulo pronto tratado como
existência devolve `ja_existe` para funcionalidade que ninguém
instalou, e o cliente recebe um texto explicando onde encontrar uma
tela que não está lá. O que o módulo muda é o P4, não este estágio.>

## 3. Desfecho

**<EXISTE | EXISTE PARCIAL | NAO EXISTE>**

## 4. Evidência principal

<Regra 5: "acho que já tem" não é resposta. Uma das formas:
tela + caminho no menu · rota + arquivo:linha · arquivo:linha ·
ID da ocorrência + trecho citado · PD-ID + veredito.>

## 5. Se EXISTE PARCIAL — o que falta

**Falta:** <exatamente o que falta, em termos de trabalho>
**Tamanho relativo ao pedido:** <menor \| igual> — <justificativa>

<Se o esforço para completar é menor que o do pedido original, é PARCIAL
e vale muito registrar: normalmente transforma um pedido grande num
ajuste pequeno. Isto é a base do escopo mínimo do P4.>

## 6. Se EXISTE — onde está e como se chega

**Caminho:** <Menu > Submenu > Tela>
**Perfil necessário:** <perfil>
**Como se chega ao resultado:** <em uma linha, na linguagem do usuário>
**Problema de descoberta?** <sim | nao> — <se sim, é achado de produto>

## 7. Pedidos anteriores relacionados

| PD-ID | Veredito | Motivo | Ainda vale? |
|-------|----------|--------|-------------|
