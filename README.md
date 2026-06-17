# Jokenpo-C

## Sobre o Projeto

Este projeto é uma implementação do clássico jogo **Jokenpô (Pedra, Papel e Tesoura)** desenvolvida na linguagem C.

O programa permite que o usuário escolha uma das opções disponíveis enquanto o computador realiza uma escolha aleatória. Ao final da partida, o sistema compara as jogadas e exibe o resultado (vitória, derrota ou empate).

Este projeto foi desenvolvido com o objetivo de praticar conceitos fundamentais da programação em C, como estruturas condicionais, geração de números aleatórios, entrada e saída de dados e organização de código.

---

## Funcionalidades

* Escolha entre Pedra, Papel ou Tesoura.
* Jogada aleatória do computador.
* Verificação automática do vencedor.
* Exibição do resultado da partida.
* Interface simples pelo terminal.

---

## Tecnologias Utilizadas

* Linguagem C
* Compilador GCC

---

## Conceitos Aplicados

* Variáveis e tipos de dados
* Estruturas condicionais (`if`, `else if`, `else`)
* Estruturas de decisão (`switch`)
* Biblioteca `stdlib.h`
* Biblioteca `time.h`
* Geração de números aleatórios
* Entrada e saída de dados com `scanf` e `printf`

---

## Como Executar

### Compilar

```bash
gcc jokenpo.c -o jokenpo
```

### Executar

```bash
./jokenpo
```

No Windows:

```bash
jokenpo.exe
```

---

## Estrutura do Projeto

```text
jokenpo/
│
├── jokenpo.c
└── README.md
```

---

## Exemplo de Execução

```text
=== JOKENPÔ ===

1 - Pedra
2 - Papel
3 - Tesoura

Escolha uma opção: 1

Computador escolheu: Tesoura

Você venceu!
```

---

## Autor

Desenvolvido por Guilherme Faria como parte dos estudos em Ciência da Computação e programação na linguagem C.

