# SomaNumeroPAReIMPAR
Algoritmo que pede ao usuário a entrada de números inteiros positivos, o programa salva todos os números pares e ímpares e no final faz a soma dos PARES e a soma dos ÍMPARES.

programa //by Rehfeld13
{

	funcao inicio()
	{
	inteiro num, somaPar = 0, somaImpar = 0

	escreva("Escreva um número inteiro positivo: ")
	leia(num)

	enquanto (num>0) {

		se (num%2==0){
			somaPar = somaPar + num
			escreva ("Escreva um número inteiro positivo: ")
		     leia(num)
			}senao{
				
				somaImpar = somaImpar + num
				escreva ("Escreva um número inteiro positivo: ")
				leia(num)
				
			}
				
		}
		escreva ("A soma dos números pares é: "+somaPar+ " e a soma dos ímpares é: "+somaImpar)
