Super Trunfo - Jogo de Comparação de Países
Este é um jogo de Super Trunfo baseado em cartas de países, onde o jogador escolhe dois atributos para comparar entre dois países. O objetivo é comparar os países com base em diferentes aspectos (como população, área, PIB, pontos turísticos e densidade demográfica) e ver qual carta "vence" em cada rodada, com base na soma dos atributos escolhidos.

Funcionalidades
O jogador pode escolher dois atributos diferentes para comparar entre as cartas.

O sistema compara as cartas com base nos dois atributos escolhidos e calcula a soma dos valores.

O vencedor é determinado pela maior soma dos valores dos atributos escolhidos.

O jogo lida com empates, declarando "Empate!" caso a soma dos valores seja igual.

Menus dinâmicos para garantir que o jogador não escolha o mesmo atributo duas vezes.

Atributos para Comparação
População: A população total do país.

Área: A área territorial do país, em km².

PIB: Produto Interno Bruto do país, em bilhões de USD.

Pontos turísticos: O número de pontos turísticos registrados no país.

Densidade Demográfica: O número de habitantes por km² (menor valor vence).

Como Jogar
Escolha dois atributos: O jogador escolhe dois atributos diferentes para comparar as cartas.

Comparação das cartas: O sistema compara as cartas dos países com base nos atributos escolhidos.

Resultado: O sistema exibe as comparações, as somas dos atributos e declara o vencedor ou empate.

Execução
Para rodar o programa:

Compilação: Compile o código utilizando um compilador C (como gcc):

bash
Copiar
Editar
gcc super_trunfo.c -o super_trunfo
Execução: Após a compilação, execute o programa:

bash
Copiar
Editar
./super_trunfo
Exemplo de Execução
bash
Copiar
Editar
Escolha o primeiro atributo para a comparação:
1 - População
2 - Área
3 - PIB
4 - Pontos turísticos
5 - Densidade Demográfica
Digite o número da opção desejada: 1

Escolha o segundo atributo para a comparação:
1 - População
2 - Área
3 - PIB
4 - Pontos turísticos
5 - Densidade Demográfica
Digite o número da opção desejada: 2

Comparação entre Brasil e Alemanha
Atributo 1: População
Brasil - Valor: 211049527.00
Alemanha - Valor: 83166711.00

Atributo 2: Área
Brasil - Valor: 8515767.00
Alemanha - Valor: 357022.00

Soma dos atributos:
Brasil - Soma: 211049527.00
Alemanha - Soma: 83166711.00

O vencedor é: Brasil

Deseja jogar novamente? (1 - Sim / 0 - Não): 1
Estrutura do Código
Função comparar_atributo: Responsável por comparar dois atributos das cartas dos países.

Função exibir_menu: Exibe o menu de atributos disponíveis para o jogador escolher.

Função exibir_resultado: Exibe os detalhes da comparação, incluindo os valores dos atributos e o vencedor.

Função main: Controla o fluxo do jogo, permitindo que o jogador escolha os atributos e veja o resultado da comparação.

Tecnologias Utilizadas
Linguagem de Programação: C

Compilador: gcc (GNU Compiler Collection)

Contribuição
Se você quiser contribuir com este projeto, fique à vontade para abrir uma issue ou submeter um pull request.
