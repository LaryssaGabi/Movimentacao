# Move - Aplicativo de Movimentação de Caixa

Este é um simples aplicativo web que permite ao usuário mover uma caixa azul na tela utilizando as teclas de setas do teclado ou as teclas W, A, S, D.

## Funcionalidades

- **Movimentação da Caixa:** A caixa azul pode ser movida para cima, baixo, esquerda e direita.
  
- **Limites de Movimento:** A caixa não pode ultrapassar os limites da janela do navegador.

## Como Usar

1. Abra o arquivo HTML em um navegador da web.
   
2. Pressione as teclas de setas do teclado (cima, baixo, esquerda, direita) ou as teclas W, A, S, D para mover a caixa azul na tela.

## Detalhes do Código

- **Eventos de Teclado:** O evento `onKeyDown` no elemento `body` está associado à função `keyPress`, que é chamada sempre que uma tecla é pressionada.

- **Movimento da Caixa:** As funções `up()`, `down()`, `left()` e `right()` controlam o movimento da caixa em suas respectivas direções, ajustando as margens superiores e esquerdas da caixa de acordo.

- **Verificação de Limites:** Antes de mover a caixa em uma direção, é verificado se a nova posição da caixa ultrapassaria os limites da janela do navegador. Se ultrapassar, o movimento não é realizado.

- **Conversão para Minúsculas:** A função `keyPress` converte a tecla pressionada em minúsculas usando `toLowerCase()`, garantindo que a comparação de teclas seja consistente, independentemente da capitalização.

Esse é um projeto básico que pode ser estendido com mais funcionalidades, como animações suaves de movimento, interações com outros elementos da página, etc.
