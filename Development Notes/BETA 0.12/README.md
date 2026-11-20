# Forja — BETA 0.12: cada peça com o seu minijogo

Toda peça de toda receita agora é produzida no lugar certo e com o minijogo da sua etapa. No fim, o ferreiro crava a sua marca.

## Quem faz cada peça

| Peça | Onde | Minijogo |
|---|---|---|
| Lâmina, cabeça, ponta, bossa | Forja | fornalha, bigorna, têmpera e rebolo (como antes) |
| Guarda, pomo, tsuba, kashira, virola, aro do escudo | Forja, nos **Moldes de Fundição** | **Fundição** (novo) |
| Empunhadura, cabo longo, haste | Marcenaria, no Torno | torno (como antes) |
| Cunha, tábuas do escudo | Marcenaria, no **Cavalete** | **Serra** (novo) |
| Montagem | Marcenaria, na Mesa de Montagem | planta (agora o escudo também é montado) |
| Acabamento | Salão, na **Mesa do Ferreiro** | **Marca do Ferreiro** (novo) |

## Fundição (Moldes, no salão da forja)
- Segure ESPAÇO para **inclinar o cadinho**. O metal derretido escorre e cai no molde **com atraso**: solte antes de chegar na linha.
- Cada molde tem um medidor:
  - **faixa dourada:** no ponto;
  - **abaixo:** a peça sai **incompleta**;
  - **acima:** **rebarba**.
- O cadinho **esfria**. Abaixo da marca de calor o metal engrossa, escorre pela metade e deixa **junta fria** (−15%).
- Moldes por receita:

  | Receita | Moldes |
  |---|---|
  | Espada e faca | guarda + pomo |
  | Katana | tsuba + kashira |
  | Lança | virola |
  | Escudo | aro |

- Metais nobres pedem mais precisão: a faixa encolhe, o atraso aumenta e o cadinho esfria mais rápido.

## Serra (Cavalete, na marcenaria)
- **Cunha:** 1 madeira rende 2 cunhas, com 2 cortes. A cunha trava a cabeça de enxada, picareta, machado e martelo.
- **Tábuas de escudo:** 2 madeiras, com 3 cortes.
- **Como serrar:**
  - Segure para **empurrar** e solte para **puxar**.
  - Só um **vai e vem completo** avança o corte.
  - Serrar **rápido demais** (ponteiro no vermelho) **desvia da linha**, e a fenda fica torta.
- Madeiras duras aguentam menos velocidade e pedem mais passadas.

## Marca do Ferreiro (nova Mesa do Ferreiro, no salão)
- Substitui os antigos "golpes de acabamento".
- A mesa é nova: carvalho escuro, manta de couro, punções, tás de aço e uma placa de latão com a sua marca (a inicial do seu nome).
- O minijogo tem duas fases:
  1. **Posicionar:** aperte quando a punção passar sobre o alvo da peça.
  2. **Força:** pare o ponteiro na faixa dourada. Fraco demais deixa a marca apagada; forte demais **amassa a peça**.
- A marca fica gravada na peça. Uma marca boa dá até **+6% na nota**.
- Uma marca perfeita dá ainda a etiqueta **"Marca do Ferreiro"** e **+5% de valor**.

## Outros detalhes
- A antiga Bancada agora é só o **Livro de receitas**.
- O livro de receitas mostra o que cada peça precisa: cabo, cunha e peças fundidas.
- A nota final leva em conta a fundição (peso 0,12). A nota da madeira junta cabo e cunha.

## Testes (jogador automático)

| Minijogo | Bem jogado | Mal jogado |
|---|---|---|
| Fundição | 1,00 | 0,44 |
| Serra | 1,00 (Pinho, Carvalho e Ébano) | 0,10–0,12 (serrando com pressa) |
| Marca | 1,00 | 0,10 |

- Fluxo completo testado:
  - **enxada:** cunhas → montagem com cunha → marca;
  - **escudo:** tábuas → fundição do aro → montagem → marca.
- Fornalha, têmpera e afiação continuam com as notas de antes.
