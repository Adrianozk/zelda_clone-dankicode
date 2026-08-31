# Zelda Clone em Java

Projeto de estudo de um jogo 2D inspirado em Zelda, desenvolvido em Java durante o curso de desenvolvimento de games da Danki Code. O objetivo foi praticar a construção dos principais componentes de um jogo sem utilizar uma engine pronta.

> **Status:** projeto em desenvolvimento. Ainda não existe uma versão 1.0; por isso, o código permanece na branch [`adriano-dev`](https://github.com/Adrianozk/zelda_clone-dankicode/tree/adriano-dev).

## Funcionalidades implementadas

- Loop principal com atualização e renderização a 60 FPS
- Mapas baseados em tiles carregados a partir de imagens
- Movimento e animação do personagem
- Colisão com paredes e entidades
- Câmera acompanhando o jogador
- Inimigos com movimentação e sistema de dano
- Coleta de vida, arma e munição
- Disparos pelo teclado e em direção ao cursor do mouse
- Interface com vida e quantidade de munição
- Progressão automática entre dois níveis
- Tela de Game Over e reinicialização da partida

## Controles

| Ação | Controle |
| --- | --- |
| Movimentação | `WASD` ou setas direcionais |
| Atirar na direção do personagem | `Espaço` ou `Enter` |
| Atirar em direção ao cursor | Clique do mouse |
| Reiniciar após Game Over | `Enter` |

## Como executar

O projeto foi criado no Eclipse e utiliza Java AWT/Swing, sem dependências externas.

1. Clone o repositório:

```bash
git clone https://github.com/Adrianozk/zelda_clone-dankicode.git
cd zelda_clone-dankicode
```

2. Acesse a branch de desenvolvimento:

```bash
git switch adriano-dev
```

3. No Eclipse, selecione **File → Import → Existing Projects into Workspace** e escolha a pasta clonada.
4. Execute a classe `src/com/adriano/main/Game.java`.

## Estrutura do projeto

```text
src/com/adriano/
├── entities/   # jogador, inimigos, itens e projéteis
├── graficos/   # sprites e interface
├── main/       # loop, entrada e renderização
└── world/      # câmera, mapas, tiles e colisões

res/
├── level*.png
└── spritesheet*.png
```

## Próximos passos

Entre as ideias ainda não concluídas estão:

- Menu inicial e sistema de pausa
- Boss battle
- Itens que alterem ataque ou defesa
- Salvamento e carregamento da partida
- Áudio e música

## Contexto

Este repositório registra o aprendizado obtido durante o curso de desenvolvimento de games da Danki Code. A implementação acompanha os conceitos apresentados no curso e contém a evolução realizada por Adriano Luís Fernandes ao longo dos exercícios.
