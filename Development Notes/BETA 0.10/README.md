# Forja — BETA 0.10: a Marcenaria

Uma **sala nova**. Para entrar, use a porta de madeira no fundo da forja (parede de baixo, à esquerda do vaso). Nela ficam:

- **Pilha de Madeiras:** as toras na estante mostram o seu estoque de cada madeira.
- **Torno:** faz os cabos.
- **Mesa de Montagem:** junta as peças sobre uma planta (blueprint).
- **Painel de cabos:** os cabos prontos ficam pendurados na parede.

Se um cliente chega enquanto você está na marcenaria, um balão pisca perto da porta.

## Madeiras

| Madeira | Custo | Valor da peça | No torno | Requisito |
|---|---|---|---|---|
| Pinho | 5 | ×1,00 | macio: corta rápido, fácil passar do ponto | — |
| Freixo | 9 | ×1,12 | equilibrado, a madeira clássica de cabo | — |
| Carvalho | 13 | ×1,22 | duro: o formão responde devagar | reputação 15 |
| Nogueira | 20 | ×1,35 | margem de erro pequena | reputação 35 |
| Ébano | 38 | ×1,55 | duríssimo: pede as 2 passadas e precisão máxima | reputação 70 |

## Torno (minijogo novo)

A peça gira entre as pontas e um **gabarito** mostra o perfil do cabo:

- O traço fica **verde** onde a peça já está no ponto, **dourado** onde ainda está grossa e **vermelho** onde o formão foi fundo demais.
- **Segure ESPAÇO/clique** para afundar o formão; solte para ele recuar.
- O formão faz **2 passadas** (ida e volta).
- **O que é cortado não volta.** Passar do ponto estraga aquele trecho. Se o cabo ficar fino demais, ele sai frágil e perde metade da nota.

Há três tipos de cabo:

| Cabo | Madeira gasta | Serve para |
|---|---|---|
| Empunhadura | 1 | faca, espada e katana |
| Cabo longo | 1 | enxada, picareta, machado e martelo |
| Haste | 2 | lança |

## Mesa de Montagem: a planta (minijogo novo)

Peças com cabo agora têm a etapa **Montar** entre a forja e o acabamento:

1. Escolha um cabo pronto (e a madeira dele).
2. Nas armas com guarda, escolha também o **estilo**:

   | Estilo | Guarda e pomo | Valor | Velocidade das peças |
   |---|---|---|---|
   | Clássico | guarda reta e pomo de disco | normal | normal |
   | Nobre | guarda curva e pomo de roda | +10% | 25% mais rápidas |
   | Real | guarda em anel e pomo de pera (dourados) | +20% | 50% mais rápidas |

3. As peças entram na planta **uma de cada vez**, correndo no trilho. Aperte ESPAÇO quando a peça passar pela **marca dourada**. Um encaixe torto **fica torto** no desenho e na nota.

Ordem das peças em cada planta:

| Planta | Ordem |
|---|---|
| Espada, faca e katana | lâmina → guarda (tsuba) → empunhadura → pomo (kashira) |
| Enxada, picareta, machado e martelo | cabo → cabeça → cunha |
| Lança | haste → virola → ponta |

A planta tem as cotas com o nome de cada peça e a nota do encaixe. Metais nobres fazem as peças correrem mais rápido e de forma irregular.

## Na nota e no valor
- Entram na nota final: o **acabamento do cabo** (peso 0,10) e a **montagem** (peso 0,15).
- O valor da peça é multiplicado pela **madeira** e pelo **estilo**. O resultado mostra a etiqueta "Cabo de …".
- Essas receitas não gastam mais "madeira" ao começar: a madeira vai no cabo. O escudo continua gastando Pinho.

## Testes
| Minijogo | Bem jogado | Mal jogado |
|---|---|---|
| Torno (5 madeiras) | 0,93–1,00 | 0,11–0,25 (aleatório) |
| Montagem | 1,00 | 0,10–0,31 (aleatório) |

- Fluxo completo testado pela interface: sala → torno → mesa → acabamento → resultado com a madeira.
- Sair do torno com Esc devolve a madeira.
- Os minijogos antigos continuam com as mesmas notas.
