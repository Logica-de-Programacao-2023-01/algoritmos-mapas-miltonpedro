package main

import (
	"fmt"
	"strings"
)

// Função para contar a ocorrência de cada palavra em uma string e retornar um mapa com as palavras e suas ocorrências
func contarPalavras(str string) map[string]int {
	words := strings.Fields(str)
	wordCount := make(map[string]int)

	for _, word := range words {
		wordCount[word]++
	}

	return wordCount
}

func main() {
	// Exemplo de uso da função
	texto := "o rato roeu a roupa do rei de roma"
	resultado := contarPalavras(texto)

	for palavra, ocorrencias := range resultado {
		fmt.Printf("%s: %d\n", palavra, ocorrencias)
	}
}
