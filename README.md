# Chess System - Java

## Sobre o Projeto

Este projeto implementa um sistema de xadrez utilizando a linguagem Java. A estrutura segue um modelo orientado a objetos dividido em duas camadas principais:

- **Camada de Xadrez (Chess layer)**: Contém as regras do jogo e a lógica das peças.
- **Camada do Tabuleiro (Board layer)**: Responsável pela manipulação das posições e movimentação das peças no tabuleiro.

## Estrutura do Projeto

O projeto é estruturado em classes organizadas conforme o diagrama UML fornecido. As principais classes são:

### Camada de Xadrez (Chess Layer)
- `ChessMatch`: Gerencia a partida de xadrez, incluindo turnos, xeque e xeque-mate.
- `ChessPiece`: Representa uma peça de xadrez genérica, sendo estendida por classes específicas como `King`, `Queen`, `Rook`, etc.
- `ChessPosition`: Define posições específicas do jogo de xadrez (exemplo: "e4").
- `ChessException`: Lida com exceções específicas do jogo de xadrez.
- `Color`: Enum que define as cores das peças (`BLACK`, `WHITE`).

### Camada do Tabuleiro (Board Layer)
- `Board`: Representa o tabuleiro do jogo.
- `Piece`: Classe base para todas as peças do tabuleiro.
- `Position`: Define uma posição genérica no tabuleiro com coordenadas de linha e coluna.
- `BoardException`: Trata exceções específicas do tabuleiro.

## Como Executar o Projeto

1. **Clone o repositório**:
   ```sh
   git clone https://github.com/seu-usuario/chess-system-java.git
   ```

2. **Abra o projeto em uma IDE compatível** (Eclipse, IntelliJ IDEA ou VS Code com suporte a Java).

3. **Compile e execute a aplicação** através da classe principal `program.java` disponível em `Application`.
   
   ```sh
   javac program.java
   java program
   ```

## Funcionalidades
- Movimentação das peças de acordo com as regras oficiais do xadrez.
- Verificação de xeque e xeque-mate.
- Gerenciamento do turno dos jogadores.
- Possibilidade de promoção de peões.
- Validação de movimentos inválidos.

## Tecnologias Utilizadas
- **Linguagem**: Java
- **Paradigma**: Programação Orientada a Objetos (POO)
- **IDE recomendada**: Eclipse, IntelliJ IDEA, VS Code

## Autor
Desenvolvido por [Seu Nome]. Sinta-se à vontade para contribuir ou relatar problemas!

## Licença
Este projeto está sob a licença MIT. Para mais detalhes, consulte o arquivo `LICENSE`.

