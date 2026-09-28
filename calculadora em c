#include <stdio.h>
#include <math.h>

// 1. Soma
double somar(double a, double b) {
    return a + b;
}

// 2. Subtração
double subtrair(double a, double b) {
    return a - b;
}

// 3. Multiplicação
double multiplicar(double a, double b) {
    return a * b;
}

// 4. Divisão
double dividir(double a, double b) {
    return a / b;
}

// 5. Potenciação
double potencia(double base, double expoente) {
    return pow(base, expoente);
}

// 6. Raiz quadrada
double raiz_quadrada(double a) {
    return sqrt(a);
}

// 7. Raiz cúbica
double raiz_cubica(double a) {
    return cbrt(a);
}

// 8. Seno (entrada em radianos)
double calcular_seno(double a) {
    return sin(a);
}

// 9. Cosseno (entrada em radianos)
double calcular_cosseno(double a) {
    return cos(a);
}

// 10. Tangente (entrada em radianos)
double calcular_tangente(double a) {
    return tan(a);
}

// 11. Logaritmo natural (ln)
double logaritmo_natural(double a) {
    return log(a);
}

// 12. Logaritmo na base 10
double logaritmo_base10(double a) {
    return log10(a);
}

// 13. Valor absoluto
double valor_absoluto(double a) {
    return fabs(a);
}

// 14. Cálculo de porcentagem (ex: a % de b)
double calcular_porcentagem(double a, double b) {
    return (a * b) / 100.0;
}

// 15. Média aritmética de dois valores
double media_aritmetica(double a, double b) {
    return (a + b) / 2.0;
}

// 16. Conversão de graus para radianos
double graus_para_radianos(double graus) {
    return graus * (3.14159265358979323846 / 180.0);
}

// 17. Conversão de radianos para graus
double radianos_para_graus(double radianos) {
    return radianos * (180.0 / 3.14159265358979323846);
}

// 18. Cálculo de área do círculo
double area_circulo(double raio) {
    return 3.14159265358979323846 * (raio * raio);
}

// 19. Cálculo de área do retângulo
double area_retangulo(double largura, double altura) {
    return largura * altura;
}

// 20. Cálculo de hipotenusa
double calcular_hipotenusa(double cateto1, double cateto2) {
    return sqrt((cateto1 * cateto1) + (cateto2 * cateto2));
}

int main() {
    int opcao;
    double n1, n2, resultado;

    do {
        printf("\n========================================\n");
        printf("          CALCULADORA EM C (20 FUNCOES)   \n");
        printf("========================================\n");
        printf(" 1. Soma\n");
        printf(" 2. Subtracao\n");
        printf(" 3. Multiplicacao\n");
        printf(" 4. Divisao\n");
        printf(" 5. Potenciacao\n");
        printf(" 6. Raiz quadrada\n");
        printf(" 7. Raiz cubica\n");
        printf(" 8. Seno\n");
        printf(" 9. Cosseno\n");
        printf("10. Tangente\n");
        printf("11. Logaritmo natural\n");
        printf("12. Logaritmo na base 10\n");
        printf("13. Valor absoluto\n");
        printf("14. Calculo de porcentagem\n");
        printf("15. Media aritmetica\n");
        printf("16. Conversao de graus para radianos\n");
        printf("17. Conversao de radianos para graus\n");
        printf("18. Calculo de area do circulo\n");
        printf("19. Calculo de area do retangulo\n");
        printf("20. Calculo de hipotenusa\n");
        printf(" 0. Sair\n");
        printf("----------------------------------------\n");
        printf("Escolha uma opcao: ");
        scanf("%d", &opcao);

        if (opcao == 0) {
            printf("Encerrando o programa...\n");
            break;
        }

        switch (opcao) {
            case 1:
            case 2:
            case 3:
            case 4:
            case 5:
            case 14:
            case 15:
            case 19:
            case 20:
                printf("Digite o primeiro valor: ");
                scanf("%lf", &n1);
                printf("Digite o segundo valor: ");
                scanf("%lf", &n2);
                break;
            case 6:
            case 7:
            case 8:
            case 9:
            case 10:
            case 11:
            case 12:
            case 13:
            case 16:
            case 17:
            case 18:
                printf("Digite o valor: ");
                scanf("%lf", &n1);
                break;
            default:
                printf("Opcao invalida! Tente novamente.\n");
                continue;
        }

        switch (opcao) {
            case 1:
                resultado = somar(n1, n2);
                printf("Resultado: %.2lf\n", resultado);
                break;
            case 2:
                resultado = subtrair(n1, n2);
                printf("Resultado: %.2lf\n", resultado);
                break;
            case 3:
                resultado = multiplicar(n1, n2);
                printf("Resultado: %.2lf\n", resultado);
                break;
            case 4:
                if (n2 == 0) {
                    printf("Erro: Divisao por zero nao permitida!\n");
                } else {
                    resultado = dividir(n1, n2);
                    printf("Resultado: %.2lf\n", resultado);
                }
                break;
            case 5:
                resultado = potencia(n1, n2);
                printf("Resultado: %.2lf\n", resultado);
                break;
            case 6:
                if (n1 < 0) {
                    printf("Erro: Numero negativo para raiz quadrada!\n");
                } else {
                    resultado = raiz_quadrada(n1);
                    printf("Resultado: %.2lf\n", resultado);
                }
                break;
            case 7:
                resultado = raiz_cubica(n1);
                printf("Resultado: %.2lf\n", resultado);
                break;
            case 8:
                resultado = calcular_seno(n1);
                printf("Resultado: %.2lf\n", resultado);
                break;
            case 9:
                resultado = calcular_cosseno(n1);
                printf("Resultado: %.2lf\n", resultado);
                break;
            case 10:
                resultado = calcular_tangente(n1);
                printf("Resultado: %.2lf\n", resultado);
                break;
            case 11:
                if (n1 <= 0) {
                    printf("Erro: Dominio invalido para logaritmo natural!\n");
                } else {
                    resultado = logaritmo_natural(n1);
                    printf("Resultado: %.2lf\n", resultado);
                }
                break;
            case 12:
                if (n1 <= 0) {
                    printf("Erro: Dominio invalido para logaritmo na base 10!\n");
                } else {
                    resultado = logaritmo_base10(n1);
                    printf("Resultado: %.2lf\n", resultado);
                }
                break;
            case 13:
                resultado = valor_absoluto(n1);
                printf("Resultado: %.2lf\n", resultado);
                break;
            case 14:
                resultado = calcular_porcentagem(n1, n2);
                printf("Resultado: %.2lf\n", resultado);
                break;
            case 15:
                resultado = media_aritmetica(n1, n2);
                printf("Resultado: %.2lf\n", resultado);
                break;
            case 16:
                resultado = graus_para_radianos(n1);
                printf("Resultado: %.2lf radianos\n", resultado);
                break;
            case 17:
                resultado = radianos_para_graus(n1);
                printf("Resultado: %.2lf graus\n", resultado);
                break;
            case 18:
                if (n1 < 0) {
                    printf("Erro: Raio nao pode ser negativo!\n");
                } else {
                    resultado = area_circulo(n1);
                    printf("Resultado: %.2lf\n", resultado);
                }
                break;
            case 19:
                if (n1 < 0 || n2 < 0) {
                    printf("Erro: Medidas nao podem ser negativas!\n");
                } else {
                    resultado = area_retangulo(n1, n2);
                    printf("Resultado: %.2lf\n", resultado);
                }
                break;
            case 20:
                if (n1 < 0 || n2 < 0) {
                    printf("Erro: Catetos nao podem ser negativos!\n");
                } else {
                    resultado = calcular_hipotenusa(n1, n2);
                    printf("Resultado: %.2lf\n", resultado);
                }
                break;
        }

    } while (opcao != 0);

    return 0;
}
