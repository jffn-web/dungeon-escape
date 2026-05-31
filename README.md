# C-MAN

Projeto desenvolvido para a disciplina Programação Imperativa e Funcional.

## Requisitos

* Linux ou WSL
* GCC
* CLI-LIB (já incluída no repositório)

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

* W → cima
* S → baixo
* A → esquerda
* D → direita
* Q → sair

## Funcionalidades

* 2 fases
* 4 fantasmas
* Sistema de vidas
* Power-up (cereja)
* Ranking salvo em arquivo
* Lista encadeada para gerenciamento dos inimigos
* Alocação dinâmica de memória com malloc

```
```
