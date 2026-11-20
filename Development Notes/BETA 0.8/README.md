# Forja — BETA 0.8: animações e minijogos com desafio

## Animações
- **Faíscas** agora deixam rastro. Há também jatos direcionados (rebolo, brasa) e gotas de água com rastro.
- **Vapor** sai em nuvens que crescem e se desfazem. Bolhas sobem da peça mergulhada.
- **Bigorna:**
  - O martelo deixa um rastro ao descer.
  - Cada golpe solta uma onda de impacto e um clarão na peça.
- **Fornalha:**
  - O fole tem 7 quadros de compressão e solta um jato de ar a cada bombeada.
  - O fogo cresce com a bombeada, os carvões pulsam e a parede se ilumina com o calor.
  - A peça tem brilho próprio e gira quando é virada.
- **Têmpera:**
  - A peça entra na água com respingos e ondas. A ponta esfria antes do talão.
  - O brilho do metal aparece através da água.
- **Afiação:**
  - A pedra gira de verdade, com raios e textura em movimento.
  - A lâmina é puxada pelo fio da pedra, e o fio brilha trecho a trecho conforme é afiado.
  - A lâmina muda de cor quando esquenta (palha e depois azul) e respinga água.
- **Acabamento:**
  - A peça flutua sobre a bancada.
  - Um brilho de polimento atravessa só os pixels da peça, com estrelinhas cintilando.

## Minijogos com mais desafio

### Fornalha
- Agora você **bombeia** o fole (cada toque é um sopro), em vez de segurar.
- Nos metais nobres, a faixa ideal se mexe sozinha.
- Aparecem **eventos**:
  - **Corrente de ar:** esfria rápido; bombeie mais.
  - **Brasa viva:** o calor sobe sozinho; pare de bombear.
  - **VIRE A PEÇA:** aperte F ou clique direito antes da barra acabar, senão um lado queima e a maturação cai.
- Testes: quem joga bem tira 1.00; quem bombeia a esmo, 0.20.

### Têmpera, em 3 fases
1. Mergulhe no vermelho-cereja.
2. Agite a peça quando cada anel fechar sobre ela: 4 a 8 vezes, conforme o metal, em ritmo irregular nos metais nobres.
3. Tire quando o vapor entrar na faixa dourada (cedo demais fica mole; tarde demais fica quebradiça).

Testes: 0.99 bem jogado e 0.37 mal jogado.

### Afiação
- A lâmina passa pela pedra em **8 trechos**, e cada trecho pede uma pressão diferente: a ponta pede mão leve, o talão aguenta firme.
- Pressão demais **superaquece** a lâmina e para de afiar. Para resfriar, molhe com F ou clique direito.
- Testes: 1.00 bem jogado e 0.15 mal jogado.

### Acabamento
- São **3 golpes de precisão**, em pontos diferentes da peça. Cada um é mais rápido que o anterior, e os metais nobres aceleram ainda mais.
- Cada golpe perfeito vale +2% (até +6% no total).
