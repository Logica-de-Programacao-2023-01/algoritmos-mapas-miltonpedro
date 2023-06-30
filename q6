package main

import (
	"fmt"
)

// Função para somar as contagens de palavras de uma lista de mapas e retornar um único mapa com a contagem total
func somaContagens(contagens []map[string]int) map[string]int {
	resultado := make(map[string]int)

	for _, contagem := range contagens {
		for palavra, quantidade := range contagem {
			resultado[palavra] += quantidade
		}
	}

	return resultado
}

func main() {
	// Exemplo de uso da função
	contagens := []map[string]int{
		{"hello": 2, "world": 1},
		{"hello": 3, "world": 2, "go": 1},
		{"hello": 1, "gopher": 4},
	}

	resultado := somaContagens(contagens)

	for palavra, quantidade := range resultado {
		fmt.Printf("%s: %d\n", palavra, quantidade)
	}
}
