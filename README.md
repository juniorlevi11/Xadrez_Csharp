# Jogo de Xadrez em C#

Este repositório contém a implementação de um jogo de **xadrez** utilizando a linguagem **C#** e **técnicas de Orientação a Objetos**. O projeto foi desenvolvido no **Visual Studio** e utiliza o **.NET Framework** ou **.NET Core/5+** (dependendo da versão escolhida) para criar uma versão funcional e extensível de um jogo de xadrez.

## Tecnologias Utilizadas

- **Visual Studio**: IDE utilizada para o desenvolvimento.
- **C#**: Linguagem de programação.
- **.NET Framework** / **.NET Core**: Framework utilizado para o desenvolvimento do projeto.

## Funcionalidades

O jogo de xadrez implementado neste repositório permite:

- **Movimentação de peças**: Cada peça do tabuleiro (rei, rainha, bispo, cavalo, torre e peão) possui movimentação específica.
- **Validação de movimentos**: O jogo verifica se os movimentos são válidos de acordo com as regras do xadrez.
- **Controle de turno**: Alternância entre os jogadores de forma adequada, seguindo as regras do jogo.
- **Detecção de xeque e xeque-mate**: O sistema identifica quando um rei está em xeque ou quando ocorre o xeque-mate.
- **Tabuleiro de xadrez visual**: O jogo é representado em um tabuleiro com peças dispostas conforme as regras clássicas do xadrez.

## Técnicas de Orientação a Objetos Aplicadas

A estrutura do jogo foi desenvolvida utilizando várias técnicas de orientação a objetos:

- **Enumerados**: Para representar os tipos de peças, cores e estados do jogo.
- **Associações**: Relacionamento entre as peças e o tabuleiro, bem como entre as peças e os jogadores.
- **Encapsulamento**: Proteção dos dados de cada peça e do estado do jogo, com métodos de acesso controlados.
- **Construtores**: Para inicializar as peças e o tabuleiro com seus valores padrões.
- **Palavra-chave `this`**: Para referenciar a instância da classe em métodos e construtores.
- **Sobrecarga de Métodos**: Métodos que realizam verificações ou ações específicas com base nos parâmetros passados (por exemplo, movimento de peças).
- **Herança**: Utilização de herança para as diferentes classes de peças, como `Peça`, `Rei`, `Rainha`, etc., permitindo reutilização de código.
- **Sobrescrição de Métodos (Override)**: Personalização do comportamento de métodos herdados, como a validação do movimento de cada tipo de peça.
- **Elementos Estáticos**: Variáveis e métodos estáticos para controlar o estado global do jogo, como a verificação de xeque.
- **Exceções**: Tratamento de erros e exceções, como movimentos inválidos ou jogadas ilegais.
- **Classe Abstrata**: A classe `Peça` é abstrata, sendo estendida pelas classes específicas de cada tipo de peça.

## Estruturas de Dados Aplicadas

- **Matriz**: Utilizada para representar o tabuleiro de xadrez (8x8), onde cada posição pode conter uma peça ou estar vazia.
- **Conjuntos**: Utilizados para armazenar as jogadas válidas de uma peça, evitando duplicação e facilitando a verificação de movimentos.

## Como Rodar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
