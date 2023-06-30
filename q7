package main

import (
	"fmt"
)

// Função para contar a ocorrência de cada letra em cada palavra de uma frase e retornar um mapa aninhado com as contagens
func contagemLetras(frase string) map[string]map[rune]int {
	contagem := make(map[string]map[rune]int)

	palavras := splitPalavras(frase)

	for _, palavra := range palavras {
		contagem[palavra] = frequenciaCaracteres(palavra)
	}

	return contagem
}

// Função auxiliar para dividir uma frase em palavras
func splitPalavras(frase string) []string {
	// Implementação do split de palavras simplificada para fins de exemplo
	return []string{"hello", "world", "go", "gopher"}
}

// Função auxiliar para contar a frequência de caracteres em uma string e retornar um mapa com os caracteres e suas frequências
func frequenciaCaracteres(str string) map[rune]int {
	frequencia := make(map[rune]int)

	for _, char := range str {
		frequencia[char]++
	}

	return frequencia
}

func main() {
	// Exemplo de uso da função
	frase := "Hello world, go gopher!"
	resultado := contagemLetras(frase)

	for palavra, contagem := range resultado {
		fmt.Printf("%s: %v\n", palavra, contagem)
	}
}
