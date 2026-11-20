# Forja — BETA 0.13: salão novo, câmera e correções no celular

## Salão maior e organizado
- A forja ficou **2,6× maior** (640×400 em vez de 400×240) e foi dividida em duas áreas, separadas por colunas de madeira:

  | Área | Piso | O que fica nela |
  |---|---|---|
  | Forja e metalurgia (esquerda) | pedra | fornalha, fole e carvão; bigorna; tanque de têmpera; rebolo; Moldes de Fundição; Mesa do Ferreiro; **bancada de serralheiro** (morsa, limas, arco de serra); suporte de armas; caixotes de minério; barril e banquinho |
  | Loja (direita) | tábuas | estoque, quadro de encomendas, expositor, quarto, balcão; **mesa de exposição** (mostra mais peças do estoque); **parede de troféus**; bancos; plantas; **tapete** da porta da rua até o balcão |

- A **bancada do livro de receitas foi removida**. O livro abre:
  - pelo botão **Receitas** do topo;
  - pela **Fornalha**;
  - pela **Mesa do Ferreiro**.
- Com uma peça em andamento, a Mesa do Ferreiro também abre o menu da peça (continuar ou descartar).
- A porta da marcenaria continua no fundo da forja.

## Câmera
- A câmera **segue o personagem**, centrada nele, e está **mais próxima** (zoom de cerca de 1,25×).
- Ela para nas bordas do salão e acompanha com suavidade. A marcenaria usa a mesma câmera.
- Clicar ou tocar para andar continua funcionando.
- Os minijogos continuam com a tela inteira, como antes.

## Celular
- **Resolução:** a vista do salão agora se adapta ao formato da tela e ocupa a tela toda, sem faixas pretas, com o celular deitado ou em pé. A tela também se ajusta ao girar o celular e quando a barra do navegador aparece ou some.
- **Áudio picotando:**
  - a música passou a ser agendada com mais folga (0,35 s em vez de 0,15 s), então engasgos de desenho não picotam mais as notas;
  - se o jogo ficar para trás (por exemplo, ao voltar de outro app), ele pula as notas atrasadas em vez de tocar todas de uma vez;
  - no celular, o áudio usa um buffer maior, que evita estalos;
  - o atraso extra é **descontado no ritmo da bigorna** e nos outros minijogos, então o tempo das notas continua certo;
  - o áudio pausa quando o jogo vai para segundo plano e volta ao reabrir.

## Testes
- Visão geral do mapa conferida em imagem.
- Clique para andar com a câmera, atendimento no balcão, ida e volta da marcenaria e a troca de resolução entre salão e minijogo testados.
- Tamanhos de celular emulados: 844×390 (deitado) e 390×844 (em pé).
- Bigorna com o áudio ligado: 1,000 (ferro e prata). Fornalha, têmpera e afiação continuam com as mesmas notas.
- O áudio não foi testado num celular de verdade, nem de ouvido.
