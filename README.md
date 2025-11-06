
# Jogo de Batalha Naval em Linguagem C
Este projeto é uma implementação em linguagem C do clássico jogo Batalha Naval, dividido em três níveis de complexidade: Novato, Aventureiro e Mestre. Cada nível introduz novos conceitos de programação com vetores, matrizes, loops aninhados e condicionais.


🔰 Nível Novato
Objetivo
Criar um tabuleiro 10x10 e posicionar dois navios:

Um navio na horizontal.
Um navio na vertical.
Conceitos aplicados

Matrizes bidimensionais.
Vetores unidimensionais.
Loops aninhados para exibição.
Regras

Os navios têm tamanho fixo de 3 posições.
As posições são definidas diretamente no código.
As posições ocupadas pelos navios são marcadas com o valor 3.


⚔️ Nível Aventureiro
Objetivo
Expandir o tabuleiro com mais navios, incluindo posicionamento diagonal.
Conceitos aplicados

Manipulação de matrizes com loops aninhados.
Validação de limites do tabuleiro.
Regras

Quatro navios no total:Dois navios horizontais/verticais.
Dois navios diagonais (principal e secundária).
As posições ocupadas continuam sendo marcadas com 3.


🧠 Nível Mestre
Objetivo
Implementar habilidades especiais com áreas de efeito:

Cone
Cruz
Octaedro
Conceitos aplicados

Matrizes de habilidades (5x5).
Loops aninhados com condicionais.
Sobreposição de matrizes no tabuleiro.
Regras

As áreas afetadas pelas habilidades são marcadas com o valor 5.
O tabuleiro exibe:0 para água.
3 para navio.
5 para área de habilidade.
As habilidades são centradas em pontos definidos no código.


📦 Organização do Código

Cada nível está em um arquivo .c separado.
Os códigos são comentados para facilitar o entendimento.
O projeto pode ser compilado com gcc ou qualquer compilador C padrão.


🚀 Como Executar
gcc nivel_novato.c -o novato
./novato

gcc nivel_aventureiro.c -o aventureiro
./aventureiro

gcc nivel_mestre.c -o mestre
./mestre




📌 Observações

Este projeto é parte de um desafio prático proposto pela Oceanic Games.
O foco está na manipulação de vetores e matrizes, não na lógica completa do jogo.
Ideal para iniciantes em programação C que desejam aprender estruturas de dados básicas.


