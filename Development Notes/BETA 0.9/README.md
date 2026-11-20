# Forja — BETA 0.9: árvore de habilidades de verdade

A lista de cartões virou uma **árvore em forma de constelação**:

- **Raiz no centro:** "Aprendiz da Forja", de onde todo caminho parte.
- **Seis ramos em volta**, cada um com 3 níveis que se afastam do centro:

  | Ramo | Posição |
  |---|---|
  | Mestre da Martelada | em cima |
  | Senhor das Chamas | em cima, à direita |
  | Artesão Supremo | embaixo, à direita |
  | Alquimista dos Metais | embaixo |
  | Mestre Comerciante | embaixo, à esquerda |
  | Forjador Arcano | em cima, à esquerda |

- **Seis talentos híbridos** (losangos) entre ramos vizinhos. Cada um exige o nível I dos dois lados:

  | Talento | Ramos | Efeito |
  |---|---|---|
  | **Ritmo do Fogo** | Martelada + Chamas | a Fúria da Forja acende com 6 acertos, em vez de 8 |
  | **Têmpera Viva** | Chamas + Artesão | 40% menos eventos na fornalha |
  | **Olho de Ourives** | Artesão + Alquimia | golpes de acabamento 20% mais lentos |
  | **Contrato Selado** | Alquimia + Comércio | +10% de reputação |
  | **Lenda Viva** | Comércio + Arcano | vendas +8% |
  | **Martelo Rúnico** | Arcano + Martelada | metais nobres com 30% menos notas extras na bigorna |

## Regras
- Cada nó exige o nó anterior do caminho, um nível mínimo do ferreiro e um custo em pontos:

  | Nó | Nível do ferreiro | Custo |
  |---|---|---|
  | Nível I | 1 | 1 ponto |
  | Nível II | 3 | 1 ponto |
  | Nível III | 6 | 2 pontos |
  | Híbrido | 4 | 2 pontos |

- Os níveis III exclusivos entre si continuam valendo e aparecem ligados por um **traço vermelho**.

## Visual
- Caminhos aprendidos ficam em **dourado com brilho**. O que dá para aprender agora aparece **tracejado e animado**; o que ainda não dá, apagado.
- Clicar num nó abre o **quadro de detalhes**: descrição, ramo e nível, lista de requisitos (✓ cumprido / ✗ faltando), aviso de exclusividade e o botão **Aprender**.
- No celular, o quadro de detalhes fica embaixo da árvore.
