# C-MAN

Projeto desenvolvido para a disciplina Programação Imperativa e Funcional.

## Requisitos

* Linux ou WSL
* GCC
* CLI-LIB

## Compilação

```bash
make
```

ou

```bash
gcc src/main.c cli-lib/src/keyboard.c cli-lib/src/screen.c cli-lib/src/timer.c -I cli-lib/include -o cman
```

## Execução

```bash
./cman
```

## Controles

* W = cima
* A = esquerda
* S = baixo
* D = direita
* Q = sair

## Funcionalidades

* 2 fases
* 4 fantasmas
* Sistema de vidas
* Power-up (cereja)
* Ranking de pontuação
* Lista encadeada para os inimigos
* Alocação dinâmica de memória com malloc

## Vídeo de demonstração

https://youtu.be/oHU82x-z944
