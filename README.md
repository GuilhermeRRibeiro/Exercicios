# Exercicios
Exercícios sobre Estrutura Sequencial (entrada, processamento, saída)
(enunciado) Faça um programa para ler dois valores inteiros, e depois mostrar na tela a soma desses números com uma 
mensagem explicativa.

import java.util.Locale;
import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
		
		Locale.setDefault(Locale.US);
		Scanner sc = new Scanner(System.in);

		double largura = sc.nextDouble();
		double comprimeto = sc.nextDouble();
		double metroQuadrado = sc.nextDouble();
		
		double area = largura * comprimeto;
		double preco = area * metroQuadrado;
				
		System.out.println("AREA = " + area);
		System.out.println("PRECO = " + preco);
		
		sc.close();

	}
}

