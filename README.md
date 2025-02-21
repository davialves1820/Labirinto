# Labirinto com Backtracking
Esta atividade consciste em um labirinto desenvolvido em Python, utilizando a biblioteca pygame para visualização e a biblioteca numpy para manipulação das matrizes que representam o labirinto. O objetivo é permitir que o jogador encontre o prêmio no labirinto utilizando o algoritmo de backtracking.

## Arquivos
- _pycache_: Contém o arquivo executável;
- maze.py: Arquivo de implementação do labirinto;
- main_maze.py: Arquivo principal que cria um labirinto;
- labirinto1.txt: Arquivo que tem os dígitos binários base para a construção do labirinto

## Execução do código

```
python main_maze.py
```

## Lógica do Backtracking
A função backtracking consciste nos seguintes passos:
- Criar uma nova pilha.
- Localizar a posição inicial do jogador.
- Inserir essa posição na pilha.
- Enquanto a lista não estiver vazia executa o looping while.
- Retira a localização do topo da pilha.
- Se a posição conter o prêmio encerra-se o looping.
- Se não move o jogador para essa posição e examina as posições vizinhas.
- Se uma posição vizinha for válida adiciona ao topo da pilha.
- Repete o processo enquanto a pilha não for vazia.

