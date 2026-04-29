# 📌 Atividade de LP

Este projeto é um programa em linguagem C que reúne diversos exercícios fundamentais de lógica de programação, organizados em um menu interativo com **33 opções**.

O objetivo principal é praticar estruturas de controle, manipulação de dados, arrays, strings e conceitos matemáticos básicos e avançados.

## 🚀 Funcionalidades

O programa apresenta um menu robusto com diversas categorias:

### 📊 Cálculos Matemáticos
*   **Médias:** Implementações com diferentes estruturas (`if`, `if/else`, `switch`).
*   **Fatorial:** Calculado via `do/while`, `while` e `for`.
*   **Sequências:** Fibonacci e Progressão Aritmética (P.A).
*   **Operações:** Exponenciação e Raiz quadrada.

### 🔢 Manipulação de Vetores
*   Busca de maior e menor número.
*   Exibição de listas em ordem inversa.
*   Multiplicação de valores por um escalar.

### 🔤 Manipulação de Strings
*   Comparação de palavras e identificação de palíndromos (palavras e frases).
*   Conversão para maiúsculo/minúsculo e concatenação.
*   Tratamento de listas de nomes.

### 🧮 Matrizes
*   Soma, subtração e multiplicação de matrizes.
*   Multiplicação por escalar.

### 🎮 Extras
*   **Cara ou Coroa:** Simulação baseada em números aleatórios.
*   **Jogo 21:** Blackjack simplificado contra a máquina.

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** C
*   **Bibliotecas Standard:** 
    * `stdio.h`, `stdlib.h`, `time.h`, `math.h`, `string.h`

---

## ▶️ Como Executar

Para rodar o projeto, utilize o terminal e siga os comandos abaixo:

**1. Compilação:**
gcc programa.c -o programa -lm
2. Execução:

Linux / macOS:

Bash
./programa
Windows:

Bash
programa.exe
🎯 Objetivo do Projeto
Este projeto foi desenvolvido com foco em:

Praticar a lógica de programação pura.

Consolidar conceitos fundamentais da linguagem C.

Explorar diferentes formas de resolver o mesmo problema técnico.

⚠️ Observações
[!IMPORTANT]
Algumas funções utilizadas são dependentes de ambiente:

Limpeza de tela: O código utiliza system("cls"), que é um comando nativo do Windows.

Buffer do teclado: O uso de fflush(stdin) pode apresentar comportamento inesperado dependendo do compilador (especialmente no GCC/Linux).

Compatibilidade: Funções como strupr() podem não ser padrão em todos os ambientes ou bibliotecas.

📚 Possíveis Melhorias
[ ] Organização: Refatorar o código utilizando funções/procedimentos.

[ ] Segurança: Implementar validação de entradas do usuário para evitar erros de execução.

[ ] Lógica de Jogo: Evoluir o Jogo 21 para gerenciar um baralho real (evitar repetição de cartas).

[ ] Interface: Criar uma versão com interface gráfica (GUI).

__

##👨‍💻 Autor
Desenvolvido por Felipe Soares
