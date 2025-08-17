Jogo da Memória Numérica

🛠️ Tecnologias Utilizadas

   HTML5
Estrutura da página (elementos semânticos, grid do tabuleiro, botões).
 
   CSS3
Estilos básicos (cores, layout, tipografia).
Animações de flip card (virar cartas).
Fonte importada do Google Fonts (Inter).

   Tailwind CSS (via CDN)
Framework utilitário para estilização rápida e responsiva.
Usado para botões, grid, tipografia e espaçamentos.

   JavaScript (ES6+)
Lógica do jogo (embaralhar cartas, checar ordem, reiniciar).
Uso de async/await para temporizador de memorização.
Manipulação de DOM (document.querySelector, addEventListener).

 SVG (ícone de interrogação) (na versão inicial)


📋 Regras de Negócio 

   Início do Jogo
O jogador deve clicar em “Iniciar Jogo” para começar.
As cartas (de 1 até N) são embaralhadas e exibidas na tela.

  Memorização
O jogador tem 10 segundos para memorizar a posição das cartas.
Durante esse tempo, todas as cartas ficam viradas para cima.
Uma contagem regressiva é exibida na tela.

  Desafio
Após os 10 segundos, todas as cartas são viradas para baixo.
O jogador deve clicar nas cartas em ordem crescente (1, 2, 3, ... até o último número).

  Acertos
Se o jogador clicar no número correto, a carta vira para cima e o jogo continua.
Uma mensagem informa o próximo número esperado.

  Erro
Se o jogador clicar em uma carta fora da ordem correta:
O jogo mostra uma mensagem de erro.
Todas as cartas são reveladas novamente.
O jogo é reiniciado automaticamente.

  Vitória
O jogador vence quando consegue clicar em todas as cartas na ordem correta.
Uma mensagem de parabéns é exibida.

  Reinício
O botão “Iniciar Jogo” pode ser usado a qualquer momento para começar novamente.
Saldo positivo: “Parabéns! Seu saldo está positivo.”
Saldo negativo: “Atenção! Seu saldo está negativo.”
Saldo igual a zero: “Seu saldo está zerado.”
