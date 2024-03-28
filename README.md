# Ol-Mundo-
Meu primeiro repositório...
01-Faça um programa que receba dois números, calcule e mostre a subtração do primeiro número pelo segundo.



#include <studio.h>



int main()  {    



float num1, num2, resultado;

printf("Digite o primeiro numero:");

scanf("%f", &num1);



printf("Digite o segundo numero:");

scanf("%f", &num2);

resultado = num1 - num2;

printf("A subtração de %. 2f pelo %. 2f é %.2f\n", num1, num2, resultado);



return 0;



}

02-Faça um programa que receba três números, calcule e mostre a multiplicação desses números.

#include <stdio.h>

int main ()  {

    float num1, num2, num3, resultado;    

    printf ("Digite o primeiro numero:");

    scanf("%f", &num1);

    

    printf("Digite  o segundo numero:");

    scanf("%f", &num2);

    

    printf("Digite o terceiro numero:");

    scanf("%f", &num3);

   resultado = num1*num2*num3;   

    printf("A multiplicação dos três numeros é %.2f\n", resultado);

     return 0;

}



3- Faça um programa que receba dois números, calcule e mostre a divisão do primeiro número pelo

segundo. Sabe-se que o segundo número não pode ser zero, portanto, não é necessário se preocupar

com validações.



#include <stdio.h>



int main(){

    

    float num1, num2, resultado;

    

    printf("Digite o primeiro numero:");

    scanf("%f", &num1);

    

    printf("Digite o segundo numero:");

    scanf("%f", &num2);

    

    resultado = num1 / num2 ;

    

    printf("A divisão de %.2f pelo %.2f é %.2f\n", num1, num2, resultado);

    

    return 0;

    

}





4-Faça um programa que receba duas notas, calcule e mostre a média ponderada dessas notas, considerando peso 2 para a primeira e peso 3 para a segunda.



#include <stdio.h>



int main() {

    float nota1, nota2, media;



    

    printf("Digite a nota 1: ");

    scanf("%f", &nota1);



    printf("Digite a nota 2: ");

    scanf("%f", &nota2);



    media = (nota1 * 2 + nota2 * 3) / 5;



    printf("A media ponderada das notas %.2f e %.2f e: %.2f\n", nota1, nota2, media);



    return 0;

}





5-Faça um programa que receba o preço de um produto, calcule e mostre o novo preço, sabendo-se que este sofreu um desconto de 10%.

#include <stdio.h>



int main() {

    

    float precoProduto, novoPreco;

    

    printf("Digite o preco do produto: ");

    scanf("%f", &precoProduto);

    

    novoPreco = precoProduto - (precoProduto * 0.1);

    

    printf("O novo preco do produto com 10%% de desconto é: %.2f\n", novoPreco);

    

    return 0;

}



6-Um funcionário recebe um salário fixo mais 4% de comissão sobre as vendas. Faça um programa que receba o salário fixo do funcionário e o valor de suas vendas, calcule e mostre a comissão e seu salário final.

#include <stdio.h>



int main() {

    float salarioFixo, vendas, comissao, salarioFinal;



    printf("Digite o salario fixo do funcionario: ");

    scanf("%f", &salarioFixo);



    printf("Digite o valor das vendas do funcionario: ");

    scanf("%f", &vendas);



    comissao = vendas * 0.04;



    salarioFinal = salarioFixo + comissao;



    printf("A comissao do funcionario e: %.2f\n", comissao);

    printf("O salario final do funcionario e: %.2f\n", salarioFinal);



    return 0;

}

7-Faça um programa que receba o peso de uma pessoa, calcule e mostre:

a) o novo peso, se a pessoa engordar 15% sobre o peso digitado;

b) o novo peso, se a pessoa emagrecer 20% sobre o peso digitado.

#include <stdio.h>



int main() {

    float peso, novoPesoEngordar, novoPesoEmagrecer;



    printf("Qual o peso da pessoa: ");

    scanf("%f", &peso);



    novoPesoEngordar = peso + (peso * 0.15);



    novoPesoEmagrecer = peso - (peso * 0.20);



    printf("Se a pessoa engordar 15%%, o novo peso vai ser: %.2f\n", novoPesoEngordar);

    printf("Se a pessoa emagrecer 20%%, o novo peso vai ser: %.2f\n", novoPesoEmagrecer);



    return 0;

}





8- Faça um programa que receba o peso de uma pessoa em quilos, calcule e mostre esse peso em gramas.



#include <stdio.h>



int main() {

    float pesoQuilos, pesoGramas;



    

    printf("Digite o peso da pessoa em quilos: ");

    scanf("%f", &pesoQuilos);



    

    pesoGramas = pesoQuilos * 1000;



    

    printf("O peso da pessoa em gramas e: %.2f\n", pesoGramas);



    return 0;

}





9- Faça um programa que calcule e mostre a área de um trapézio.

Sabe-se que: A = ((base maior + base menor) * altura)/2



#include <stdio.h>



int main() {

    float baseMaior, baseMenor, altura, area;



    

    printf("Digite o valor da base maior do trapezio: ");

    scanf("%f", &baseMaior);



    printf("Digite o valor da base menor do trapezio: ");

    scanf("%f", &baseMenor);



    printf("Digite o valor da altura do trapezio: ");

    scanf("%f", &altura);

   

    area = ((baseMaior + baseMenor) * altura) / 2;  

    printf("A area do trapezio e: %.2f\n", area);



    return 0;

}





10- Faça um programa que calcule e mostre a área de um quadrado. Sabe-se que: A = lado * lado.



#include <stdio.h>



int main() {

    float lado, area;

  printf("Digite o valor do lado do quadrado: ");

    scanf("%f", &lado);



    area = lado * lado;

    

    printf("A area do quadrado e: %.2f\n", area);



    return 0;

}



11- Faça um programa que calcule e mostre a área de um losango. Sabe-se que: A = (diagonal maior * diagonal menor)/2.



#include <stdio.h>



int main() {



    float diagonalMaior, diagonalMenor, area;

  printf("Digite o valor da diagonal maior do losango: ");

    scanf("%f", &diagonalMaior);



    printf("Digite o valor da diagonal menor do losango: ");

    scanf("%f", &diagonalMenor);



    area = (diagonalMaior * diagonalMenor) / 2;



    printf("A area do losango e: %.2f\n", area);



    return 0;

}





12- Faça um programa que receba o valor do salário mínimo e o valor do salário de um funcionário, calcule e mostre a quantidade de salários mínimos que esse funcionário ganha.



#include <stdio.h>



int main() {

    float salarioMinimo, salarioFuncionario, quantidadeSalarios;



    // Recebendo o valor do salário mínimo

    printf("Digite o valor do salario minimo: ");

    scanf("%f", &salarioMinimo);



    // Recebendo o valor do salário do funcionário

    printf("Digite o valor do salario do funcionario: ");

    scanf("%f", &salarioFuncionario);



    // Calculando a quantidade de salários mínimos que o funcionário ganha

    quantidadeSalarios = salarioFuncionario / salarioMinimo;

    // Mostrando a quantidade de salários mínimos

    printf("O funcionario ganha %.2f salarios minimos.\n", quantidadeSalarios);



    return 0;

}







13-Faça um programa que calcule e mostre a tabuada de um número digitado pelo usuário.

Exemplo:

Digite um número: 5

5 × 0 = 0

5 × 1 = 5

5 × 2 = 10

5 × 3 = 15

5 × 4 = 20



5 × 5 = 25

5 × 6 = 30

5 × 7 = 35

5 × 8 = 40

5 × 9 = 45

5 × 10 = 50



#include <stdio.h>



int main() {

    int numero, i;



    // Recebendo o número do usuário

    printf("Digite um numero: ");

    scanf("%d", &numero);



    // Calculando e exibindo a tabuada do número

    printf("Tabuada do %d:\n", numero);

    for (i = 0; i <= 10; i++) {

        printf("%d x %d = %d\n", numero, i, numero * i);

    }



    return 0;

}





14-Faça um programa que receba o ano de nascimento de uma pessoa e o ano atual, calcule e mostre:

a) a idade dessa pessoa em anos;

b) a idade dessa pessoa em meses;

c) a idade dessa pessoa em dias;

d) a idade dessa pessoa em semanas.



#include <stdio.h>



int main() {

    int anoNascimento, anoAtual, idadeAnos, idadeMeses, idadeDias, idadeSemanas;



    printf("Digite o ano de nascimento da pessoa: ");

    scanf("%d", &anoNascimento);



    printf("Digite o ano atual: ");

    scanf("%d", &anoAtual);



    idadeAnos = anoAtual - anoNascimento;



    idadeMeses = idadeAnos * 12;



    idadeDias = idadeAnos * 365;



    idadeSemanas = idadeDias / 7;



    printf("Idade da pessoa em anos: %d\n", idadeAnos);

    printf("Idade da pessoa em meses: %d\n", idadeMeses);

    printf("Idade da pessoa em dias: %d\n", idadeDias);

    printf("Idade da pessoa em semanas: %d\n", idadeSemanas);



    return 0;

}





15- João recebeu seu salário e precisa pagar duas contas atrasadas. Em razão do atraso, ele deverá pagar

multa de 2% sobre cada conta. Faça um programa que calcule e mostre quanto restará do salário de

João.





#include <stdio.h>



int main() {

    float salarioJoao, conta1, conta2, totalContas, multaTotal, salarioRestante;



    printf("Digite o salario de Joao: ");

    scanf("%f", &salarioJoao);



    printf("Digite o valor da primeira conta atrasada: ");

    scanf("%f", &conta1);



    printf("Digite o valor da segunda conta atrasada: ");

    scanf("%f", &conta2);



    totalContas = conta1 + conta2;



    multaTotal = totalContas * 0.02;



    float valorTotalAPagar = totalContas + multaTotal;



    salarioRestante = salarioJoao - valorTotalAPagar;



    printf("O total a pagar por Joao e: %.2f\n", valorTotalAPagar);

    printf("O salario restante de Joao e: %.2f\n", salarioRestante);



    return 0;

}





16- Faça um programa que receba o valor dos catetos de um triângulo, calcule e mostre o valor da hipo-

tenusa.





#include <stdio.h>





int main() {

    float cateto1, cateto2, hipotenusa;

    printf("Digite o valor do primeiro cateto: ");

    scanf("%f", &cateto1);



    printf("Digite o valor do segundo cateto: ");

    scanf("%f", &cateto2);



    hipotenusa = sqrt(cateto1 * cateto1 + cateto2 * cateto2);



    printf("O valor da hipotenusa e: %.2f\n", hipotenusa);



    return 0;

}


17- Faça um programa que receba o raio, calcule e mostre:
a) o comprimento de uma esfera; sabe-se que C = 2 * p R;
b) a área de uma esfera; sabe-se que A = p R2
;
c) o volume de uma esfera; sabe-se que V = 3⁄4 * p R3

#include <stdio.h>


#define PI 3.14159

Int main() {
    Float raio, comprimento, area, volume;

    
    Printf(“Digite o raio da esfera: “);
    Scanf(“%f”, &raio);

    
    Comprimento = 2 * PI * raio;

    
    Area = PI * raio * raio;

    
    Volume = (3.0 / 4) * PI * pow(raio, 3);

    
    Printf(“O comprimento da esfera e: %.2f\n”, comprimento);
    Printf(“A area da esfera e: %.2f\n”, area);
    Printf(“O volume da esfera e: %.2f\n”, volume);

    Return 0;
}




18-Faça um programa que receba uma temperatura em Celsius, calcule e mostre essa temperatura em
Fahrenheit. Sabe-se que F = 180*(C + 32)/100.
 #include <stdio.h>
Int main() {

    Float temperaturaCelsius, temperaturaFahrenheit;

    
    Printf(“Digite a temperatura em Celsius: “);
    Scanf(“%f”, &temperaturaCelsius);

    
    temperaturaFahrenheit = (temperaturaCelsius * 9 / 5) + 32;

    
    printf(“A temperatura em Fahrenheit e: %.2f\n”, temperaturaFahrenheit);

    return 0;
}


19- Sabe-se que, para iluminar de maneira correta os cômodos de uma casa, para cada m2, deve-se usar 18 W De potência. Faça um programa que receba as duas dimensões de um cômodo (em metros), calcule e mostre
A sua área (em m2) e a potência de iluminação que deverá ser utilizada.

#include <stdio.h>

Int main() {
    Float comprimento, largura, area, potencia_iluminacao;

    
    Printf(“Digite o comprimento do comodo em metros: “);
    Scanf(“%f”, &comprimento);

    Printf(“Digite a largura do comodo em metros: “);
    Scanf(“%f”, &largura);

    
    Area = comprimento * largura;

    
    Potencia_iluminacao = area * 18;

    
    Printf(“A area do comodo e: %.2f m2\n”, area);
    Printf(“A potencia de iluminacao necessaria e: %.2f W\n”, potencia_iluminacao);

    Return 0;
}


 20- Faça um programa que receba a medida do ângulo formado por uma escada apoiada no chão e a distância em que a escada está da parede, calcule e mostre a medida da escada para que se possa alcançar
sua ponta.
 #include <stdio.h>

int main() {
    float angulo_graus, distancia_parede, comprimento_escada;

    printf("Digite a medida do angulo em graus: ");
    scanf("%f", &angulo_graus);
    

    float angulo_radianos = angulo_graus * (PI / 180.0);
    

    printf("Digite a distancia da escada ate a parede: ");
    scanf("%f", &distancia_parede);
    

    comprimento_escada = distancia_parede / sin(angulo_radianos);
    

    printf("O comprimento da escada para alcancar sua ponta e: %.2f\n", comprimento_escada);

    return 0;
}


21-Faça um programa que receba o número de horas trabalhadas, o valor do salário mínimo e o número
De horas extras trabalhadas, calcule e mostre o salário a receber, de acordo com as regras a seguir:
a) a hora trabalhada vale 1/8 do salário mínimo;
b) a hora extra vale ¼ do salário mínimo;                                                  c) o salário bruto equivale ao número de horas trabalhadas multiplicado pelo valor da hora trabalhada;
d) a quantia a receber pelas horas extras equivale ao número de horas extras trabalhadas multiplicado pelo valorda hora extra;
e) o salário a receber equivale ao salário bruto mais a quantia a receber pelas horas extras.
 #include <stdio.h>

Int main() {
    Float horas_trabalhadas, salario_minimo, horas_extras, valor_hora, valor_hora_extra, salario_bruto, salario_total;

    
    Printf(“Digite o numero de horas trabalhadas: “);
    Scanf(“%f”, &horas_trabalhadas);

    Printf(“Digite o valor do salario minimo: “);
    Scanf(“%f”, &salario_minimo);

    Printf(“Digite o numero de horas extras trabalhadas: “);
    Scanf(“%f”, &horas_extras);

    Valor_hora = salario_minimo / 8.0;
    Valor_hora_extra = salario_minimo / 4.0;

    Salario_bruto = horas_trabalhadas * valor_hora;
    Float quantia_horas_extra = horas_extras * valor_hora_extra;

    Salario_total = salario_bruto + quantia_horas_extra;
    
    Printf(“O salario a receber e: %.2f\n”, salario_total);

    Return 0;
}

22-Faça um programa que receba o número de lados de um polígono convexo, calcule e mostre o número
De diagonais desse polígono. Sabe-se que ND = N * (N – 3)/2, em que N é o número de lados do
Polígono.

#include <stdio.h>

Int main() {
    Int num_lados, num_diagonais;

    Printf(“Digite o numero de lados do poligono convexo: “);
    Scanf(“%d”, &num_lados);

    Num_diagonais = num_lados * (num_lados – 3) / 2;

    Printf(“O numero de diagonais do poligono convexo e: %d\n”, num_diagonais);

    Return 0;
}

 23-Faça um programa que receba a medida de dois ângulos de um triângulo, calcule e mostre a medida do
Terceiro ângulo. Sabe-se que a soma dos ângulos de um triângulo é 180 graus.

#include <stdio.h>

Int main() {
    Float angulo1, angulo2, angulo3;

    Printf(“Digite a medida do primeiro ângulo: “);
    Scanf(“%f”, &angulo1);

    Printf(“Digite a medida do segundo ângulo: “);
    Scanf(“%f”, &angulo2);


    Angulo3 = 180 – (angulo1 + angulo2);


    Printf(“A medida do terceiro ângulo e: %.2f\n”, angulo3);

    Return 0;
}


24-Faça um programa que receba a quantidade de dinheiro em reais que uma pessoa que vai viajar possui. Ela
Vai passar por vários países e precisa converter seu dinheiro em dólares, marco alemão e libra esterlina. Sabe-
-se que a cotação do dólar é de R$ 1,80; do marco alemão, de R$ 2,00; e da libra esterlina, de R$ 3,57. O
Programa deve fazer as conversões e mostrá-las.

 #include <stdio.h>

Int main() {
    Float dinheiro_reais, dinheiro_dolares, dinheiro_marcos, dinheiro_libras;
    Const float cotacao_dolar = 1.80;
    Const float cotacao_marco = 2.00;
    Const float cotacao_libra = 3.57;


    Printf(“Digite a quantidade de dinheiro em reais: “);
    Scanf(“%f”, &dinheiro_reais);


    Dinheiro_dolares = dinheiro_reais / cotacao_dolar;
    Dinheiro_marcos = dinheiro_reais / cotacao_marco;
    Dinheiro_libras = dinheiro_reais / cotacao_libra;


    Printf(“Quantidade de dinheiro em Dolares: %.2f\n”, dinheiro_dolares);
    Printf(“Quantidade de dinheiro em Marcos: %.2f\n”, dinheiro_marcos);
    Printf(“Quantidade de dinheiro em Libras: %.2f\n”, dinheiro_libras);

    Return 0;
}

25-Faça um programa que receba uma hora (uma variável para hora e outra para minutos), calcule e
Mostre:
a) a hora digitada convertida em minutos;
b) o total dos minutos, ou seja, os minutos digitados mais a conversão anterior;
c) o total dos minutos convertidos em segundos.
#include <stdio.h>

Int main() {
    Int hora, minutos, total_minutos, total_segundos;


    Printf(“Digite a hora: “);
    Scanf(“%d”, &hora);
    Printf(“Digite os minutos: “);
    Scanf(“%d”, &minutos);

    Total_minutos = hora * 60 + minutos;


    Total_minutos += minutos;


    Total_segundos = total_minutos * 60;


    Printf(“A hora digitada convertida em minutos: %d\n”, hora * 60);
    Printf(“O total dos minutos: %d\n”, total_minutos);
    Printf(“O total dos minutos convertidos em segundos: %d\n”, total_segundos);

    Return 0;
}

