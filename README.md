# Calculadora de Partidas Rankeadas

## Descrição
Este projeto consiste em uma função em JavaScript que calcula o nível de um jogador em um jogo ranqueado, com base no número de vitórias e derrotas.

## Tecnologias Utilizadas
- JavaScript
- Visual Studio Code

## Funcionalidades
A função recebe como parâmetros o número de vitórias e derrotas do jogador e retorna uma mensagem indicando o saldo de vitórias e o nível do jogador, de acordo com as seguintes faixas:

- Menos de 10 vitórias: Ferro
- De 11 a 20 vitórias: Bronze
- De 21 a 50 vitórias: Prata
- De 51 a 80 vitórias: Ouro
- De 81 a 90 vitórias: Diamante
- De 91 a 100 vitórias: Lendário
- Mais de 100 vitórias: Imortal

## Utilização
Para utilizar a função, basta chamar a função `calcularNivel(vitorias, derrotas)` passando como argumentos o número de vitórias e o número de derrotas do jogador.

Exemplo:
```javascript
const resultado = calcularNivel(75, 25);
console.log(resultado);
