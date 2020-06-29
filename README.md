Código Portugol
{
	
	funcao inicio()
	{
		//cria uma caixa vazia
		cadeia cor 
		escreva ("digite uma cor:")
		//pega o que eu digitei e colocar dentro da caixa
		leia(cor)
		//pega o conteudo da caixa e verifica se é igual a verde
		se(cor == "verde"){
			escreva("R$ 10,00")
	} senao se(cor == "azul"){
		escreva("R$ 20,00")
	}senao se (cor == "amarelo"){
		escreva("R$ 30,00")
	} senao se (cor == "vermelha"){
		escreva("R$ 40,00")
	}
	senao {
		escreva("cor invalida")
		}		
	}
}
