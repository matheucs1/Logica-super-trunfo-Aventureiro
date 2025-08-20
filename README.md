# Logica-super-trunfo-Aventureiro

#  Super Trunfo de Cidades

Este programa em C simula uma comparação entre duas cartas de cidades brasileiras, inspirada no jogo Super Trunfo. O jogador cadastra duas cidades e escolhe um atributo para compará-las. A carta com o melhor valor vence!

##  Requisitos

- Compilador C 
- Terminal ou console para entrada de dados

##  Como compilar

Abra o terminal na pasta onde está o arquivo `.c` e execute:


Isso criará um executável chamado super_trunfo.
 Como executar
Após compilar, execute o programa com:
./super_trunfo


Você será guiado para cadastrar duas cidades e depois escolher um atributo para comparação.

 Fluxo do programa
- Cadastro da Carta 1:
- Estado (letra de A-H)
- Código da carta (ex: A01)
- Nome da cidade
- População
- Área (km²)
- PIB (em bilhões de reais)
- Número de pontos turísticos
- Cadastro da Carta 2 (mesmos campos)
- Escolha do atributo para comparação:
Escolha o atributo para comparação:
1 - População
2 - Área
3 - PIB
4 - Pontos Turísticos
5 - Densidade Demográfica
6 - PIB per capita
Digite sua opção:


-Regras de comparação
- População, Área, PIB, Pontos Turísticos, PIB per capita → vence quem tiver o maior valor.
- Densidade Demográfica → vence quem tiver o menor valor.
Em caso de empate, o programa exibirá: Resultado: Empate!
-Exemplo de uso
Cadastro da Carta 1:
Estado (letra de A-H): A
Código da carta (ex: A01): A01
Nome da Cidade: Belo Horizonte
População: 2500000
Área (em km²): 330.9
PIB (em bilhões de reais): 105.3
Número de Pontos Turísticos: 15

Cadastro da Carta 2:
Estado (letra de A-H): B
Código da carta (ex: B02): B02
Nome da Cidade: Curitiba
População: 1900000
Área (em km²): 434.9
PIB (em bilhões de reais): 95.7
Número de Pontos Turísticos: 20

Escolha o atributo para comparação:
1 - População
2 - Área
3 - PIB
4 - Pontos Turísticos
5 - Densidade Demográfica
6 - PIB per capita
Digite sua opção: ex -> 6

Comparação das cartas:
Atributo: PIB per capita
Belo Horizonte: 42120.00 reais
Curitiba: 50368.42 reais
Resultado: Curitiba venceu!


 Observações
- O programa não valida entradas incorretas (como letras em campos numéricos).
- Use com atenção e digite os dados corretamente.
