package main

import (
	"fmt"
)

// Função para mesclar dois mapas e retornar um novo mapa contendo todos os elementos dos mapas de entrada
func mesclarMapas(m1, m2 map[string]string) map[string]string {
	merged := make(map[string]string)

	for key, value := range m1 {
		merged[key] = value
	}

	for key, value := range m2 {
		merged[key] = value
	}

	return merged
}

func main() {
	// Exemplo de uso da função
	map1 := map[string]string{
		"chave1": "valor1",
		"chave2": "valor2",
	}
	map2 := map[string]string{
		"chave2": "valor2_novo",
		"chave3": "valor3",
	}

	resultado := mesclarMapas(map1, map2)

	for key, value := range resultado {
		fmt.Printf("%s: %s\n", key, value)
	}
}
