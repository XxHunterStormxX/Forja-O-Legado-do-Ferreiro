# Forja — BETA 0.14: toda peça começa na Mesa de Montagem

- A **Mesa de Montagem** saiu da marcenaria e foi para o **salão da forja**, no fundo, no lugar da antiga bancada de receitas, entre a fornalha e a loja.
- **Toda peça começa nela, sem exceção.** É na mesa que você escolhe a planta (a receita) e o metal e começa a peça. A mesma mesa recebe a peça no fim, para a montagem na planta.
  - O botão **Receitas** do topo continua abrindo o livro para consulta. Longe da mesa, o botão de começar aparece como **"Vá à Mesa de Montagem para começar"**.
  - Com uma peça em andamento, a mesa abre o menu da peça (continuar ou descartar).
- **Reparos começam na Fornalha.** Ao interagir com ela sem peça em andamento, aparece a lista de reparos (e o Tenkai) para iniciar. Na lista de encomendas, o botão desses trabalhos diz **"Inicie na Fornalha"** quando você está longe dela.
- **Marcenaria:** no lugar da mesa ficou uma pilha de tábuas. Continuam lá o Torno (cabos), o Cavalete (cunhas e tábuas) e a Pilha de Madeiras.
- Textos do tutorial, das dicas e dos avisos atualizados para o novo fluxo.

## Testes

| Situação | Resultado |
|---|---|
| Começar uma peça longe da mesa | recusa com aviso |
| Começar uma peça na mesa | começa, e a próxima etapa é Aquecer |
| Começar um reparo na mesa | recusa |
| Começar um reparo na Fornalha | abre o menu e inicia |
| Montar uma enxada na mesa do salão (cabo + cunha) | nota 1,00, segue para Marcar |
