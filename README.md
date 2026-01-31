# MazeOfMonsters

## Sobre o projeto

MazeOfMonsters é um projeto em C desenvolvido no âmbito de LI2, que implementa um jogo de exploração de labirintos com foco em lógica de jogo e organização modular do código. O projeto está estruturado por componentes, separando responsabilidades como geração de mapa, movimentação, visão, entidades (jogador e monstros) e itens.

## Group P1_02

A104187 - Marco António Fernandes Brito
A104352 - Pedro de Seabra Vieira
A104176 - Pedro Filipe Maneta Pinto


### Organização do código (módulos)

- `generateMap.c`: geração/criação do mapa do labirinto
- `move.c`: regras de movimento e validações
- `vision.c`: sistema de visão/alcance (ex.: visibilidade no mapa)
- `player.c`: estado e ações do jogador
- `monstros.c`: lógica e comportamento de monstros
- `weapons&potions.c`: gestão de itens (armas e poções)
- `windows.c`: camada de interface/apresentação em terminal
- `jogo.c`: ciclo principal e coordenação do gameplay
- `main.c`: ponto de entrada da aplicação
- `dictionary.h`: estruturas, definições e utilitários partilhados

### Compilação

O projeto inclui um `Makefile` para automatizar a compilação.
