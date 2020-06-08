# portugol_tabuada
Código de tabuada em portugol

programa
{
	
	funcao inicio()
	{
		inteiro numero,contador,limite,resultado
		
		contador = 0

		escreva("Digite um número para ver sua tabuada: ")
		leia(numero)
		escreva("Digite o limite da tabuada: ")
		leia(limite)

		faca{
			
			resultado = numero * contador
			escreva(numero + " X " + contador + " = " + resultado + "\n" )
			contador++
			
		}enquanto(contador<=limite)
	}
}
