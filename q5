package main

import (
	"fmt"
)

// Função para contar a frequência de caracteres em uma string e retornar um mapa com os caracteres e suas frequências
func frequenciaCaracteres(str string) map[rune]int {
	frequencia := make(map[rune]int)

	for _, char := range str {
		frequencia[char]++
	}

	return frequencia
}

func main() {
	// Exemplo de uso da função
	texto := "abracadabra"
	resultado := frequenciaCaracteres(texto)

	for char, frequencia := range resultado {
		fmt.Printf("%c: %d\n", char, frequencia)
	}
}
