# Calculadora em C — Projeto Prático 🚀

Seja muito bem-vindo(a) ao repositório deste projeto! Esta aplicação foi desenvolvida como parte das atividades práticas da disciplina, com o propósito de transformar conceitos teóricos de programação em uma ferramenta funcional, robusta e interativa.

---

## 👩‍🎓 Identificação da Estudante
* **Nome:** Stella Santana de Jesus
* **Curso:** Análise e Desenvolvimento de Sistemas
* **Instituição:** Centro Universitário do Distrito Federal (UDF)

---

## 🎯 Objetivo do Projeto
O objetivo principal foi desenvolver uma **calculadora completa em linguagem C**, capaz de executar uma ampla gama de operações matemáticas avançadas e básicas por meio de um menu interativo no terminal. Mais do que apenas realizar contas, o projeto demonstra a aplicação prática de modularização, tratamento de erros e organização de código estruturado.

---

## ⚙️ Conceitos de Programação Utilizados
Para dar vida a este software, foram empregados os pilares fundamentais da lógica de programação e da linguagem C:
* **Funções e Modularização:** O código foi dividido em sub-rotinas específicas para cada cálculo, promovendo a reutilização e a organização do código-fonte.
* **Estruturas Condicionais (`switch/case` e `if-else`):** Utilizadas para direcionar o fluxo do programa conforme a escolha do menu e para realizar validações de domínio e tratamento de erros.
* **Estruturas de Repetição (`do-while`):** Garantem que a calculadora permaneça em execução, permitindo que o usuário realize múltiplos cálculos consecutivamente até decidir encerrar o programa.
* **Entrada e Saída de Dados:** Uso de `scanf` para a captura de valores fornecidos pelo usuário e `printf` para a exibição dinâmica de menus e resultados formatados.
* **Biblioteca Matemática (`math.h`):** Integrada para viabilizar o cálculo de potências, raízes, logaritmos e funções trigonométricas.

---

## 📋 Lista das 20 Funções Implementadas
A calculadora conta exatamente com as seguintes operações:
1. Soma
2. Subtração
3. Multiplicação
4. Divisão
5. Potenciação
6. Raiz quadrada
7. Raiz cúbica
8. Seno (com entrada em radianos)
9. Cosseno (com entrada em radianos)
10. Tangente (com entrada em radianos)
11. Logaritmo natural ($\ln$)
12. Logaritmo na base 10 ($\log_{10}$)
13. Valor absoluto
14. Cálculo de porcentagem
15. Média aritmética
16. Conversão de graus para radianos
17. Conversão de radianos para graus
18. Cálculo de área do círculo
19. Cálculo de área do retângulo
20. Cálculo de hipotenusa (Teorema de Pitágoras)

---

## 🛠️ Bibliotecas Utilizadas
* `#include <stdio.h>`: Essencial para gerenciar as entradas e saídas padrão (exibição de textos na tela e leitura do teclado).
* `#include <math.h>`: Indispensável para o acesso às funções matemáticas avançadas (`pow`, `sqrt`, `sin`, `cos`, `tan`, `log`, etc.).

---

## 📂 Organização do Código
O código foi estruturado de forma limpa e sequencial:
1. **Declaração de Bibliotecas:** Importação dos recursos necessários para entrada/saída e matemática.
2. **Implementação das Funções:** Cada operação matemática foi isolada em sua própria função do tipo `double`, recebendo parâmetros e retornando o resultado obtido.
3. **Função Principal (`int main`):** Contém o laço de repetição `do-while` que mantém o menu ativo, faz a leitura da opção escolhida, recolhe os dados do usuário e invoca a função correspondente por meio de estruturas condicionais.

---

## 💻 Instruções para Compilação e Execução

Se você deseja testar este código na sua máquina, siga os passos abaixo usando um terminal com o compilador GCC instalado:

1. Clone o repositório ou baixe os arquivos para a sua máquina.
2. Abra o terminal na pasta onde o arquivo `calculadora.c` está salvo.
3. Compile o programa utilizando o comando de linkagem da biblioteca matemática (`-lm`):
   ```bash
   gcc calculadora.c -o calculadora -lm
