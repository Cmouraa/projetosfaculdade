# Meusprojetos.Java

Aqui eu aprendi sobre a funcao "Vetor" em Java.

package lista05exercicio01;

import java.util.Scanner;

/**
 *
 * @Carlos dos santos
 */
public class Lista05Exercicio01 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner input = new Scanner(System.in);

        Integer[] vetor = new Integer[10];
        Integer maior = -1;
        Integer temp = 0;
        for (int i = 0; i < 10; i++) {
            do {// garantir que somente numeros positivos serao informados
                System.out.println("informe um numero maior ou igual a zero:");
                temp = input.nextInt();
                if (temp < 0) {
                    System.out.println("\nAtencao, numero digitado invalido\n");
                }
            } while (temp < 0);// garantir que somente numero positivos serao informados
            vetor[i] = temp; //salvando um numero valido no vetor [i]
            if (temp > maior) { // descobrindo o maior numero de todos
                maior = temp;
            
            }}
                System.out.println("o menor numero e" + maior);
            }

        }
