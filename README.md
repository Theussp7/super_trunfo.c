# Super Trunfo - Jogo de Comparação de Países (Versão em C)

Este é o jogo **Super Trunfo**, onde você pode comparar cartas de países com base em diferentes atributos, como **população**, **área**, **PIB**, **número de pontos turísticos** e **densidade demográfica**.

O objetivo do jogo é escolher um atributo e comparar duas cartas de países. A carta com o maior valor (ou menor no caso da **densidade demográfica**) vence. Em caso de empate, o jogo informará que houve um empate.

## Funcionalidades

- **Menu interativo** para o jogador escolher o atributo para comparação.
- **Comparação** dos atributos entre duas cartas de países.
- **Exibição do vencedor** ou mensagem de empate.
- **Opção para sair** do jogo.

## Como Jogar

1. Compile o código em C.
2. Execute o programa.
3. Escolha um atributo para comparação entre dois países (Brasil e Alemanha, neste exemplo).
4. O programa exibirá os valores dos atributos para as duas cartas e mostrará quem venceu ou se houve empate.
5. Você pode repetir a comparação ou sair do jogo.

## Atributos Disponíveis para Comparação

- **População**: Número total de habitantes do país.
- **Área**: Área total do país em quilômetros quadrados.
- **PIB**: Produto Interno Bruto (em bilhões de USD) do país.
- **Número de pontos turísticos**: Quantidade de pontos turísticos conhecidos no país.
- **Densidade Demográfica**: Número de habitantes por quilômetro quadrado (quanto menor, melhor).

## Como Compilar e Executar

### Passo 1: Compilando o código

Use um compilador de C, como o `gcc`, para compilar o código.

```bash
gcc super_trunfo.c -o super_trunfo
Passo 2: Executando o programa
Após compilar, execute o programa com o seguinte comando:

bash
Copiar
Editar
./super_trunfo
Exemplo de Execução
bash
Copiar
Editar
Escolha o atributo para comparação:
1 - População
2 - Área
3 - PIB
4 - Número de pontos turísticos
5 - Densidade demográfica
Digite o número da opção desejada (ou '0' para sair): 1

Você escolheu comparar pelo atributo: População
Brasil - População: 211049527
Alemanha - População: 83166711

O vencedor é: Brasil
Estrutura do Código
Estrutura Carta: Cada carta representa um país e armazena as informações de nome, população, área, PIB, número de pontos turísticos e densidade demográfica.

Função comparar_cartas: Compara os valores de dois países com base no atributo escolhido.

Função exibir_menu: Exibe o menu para o jogador escolher o atributo a ser comparado.

Função main: Controla o fluxo do jogo, exibe o menu e chama as funções para comparar as cartas.

Exemplo de Cartas
O jogo utiliza as cartas dos seguintes países (pode-se expandir conforme desejar):

Brasil:

População: 211.049.527

Área: 8.515.767 km²

PIB: 2055.5 bilhões de USD

Pontos turísticos: 50

Densidade demográfica: 24.8 habitantes/km²

Alemanha:

População: 83.166.711

Área: 357.022 km²

PIB: 3846.2 bilhões de USD

Pontos turísticos: 75

Densidade demográfica: 232.6 habitantes/km²

Como Contribuir
Se você deseja contribuir para o projeto, fique à vontade para fazer um fork e enviar um pull request com melhorias. Algumas ideias de melhorias incluem:

Adicionar mais países ao conjunto de cartas.

Implementar um sistema de pontuação baseado no número de vitórias.

Melhorar o tratamento de entradas inválidas.

Adicionar mais regras personalizadas de comparação.
