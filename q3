package main

import (
	"fmt"
)

// Função para calcular a soma de todos os valores de um mapa com valores inteiros
func somaValoresMapa(m map[string]int) int {
	sum := 0

	for _, value := range m {
		sum += value
	}

	return sum
}

func main() {
	// Exemplo de uso da função
	mapa := map[string]int{
		"chave1": 10,
		"chave2": 20,
		"chave3": 30,
	}

	resultado := somaValoresMapa(mapa)

	fmt.Println(resultado) // Output: 60
}
