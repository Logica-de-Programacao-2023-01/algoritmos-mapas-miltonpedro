package main

import (
	"fmt"
)

// Função para calcular o valor que cada pessoa deve receber ou pagar para igualar as despesas
func calcularContas(despesas map[string]float64) map[string]float64 {
	totalDespesas := 0.0
	quantidadePessoas := len(despesas)
	valorPorPessoa := 0.0
	resultado := make(map[string]float64)

	// Calcular o total das despesas
	for _, valor := range despesas {
		totalDespesas += valor
	}

	// Calcular o valor que cada pessoa deve receber ou pagar
	if quantidadePessoas > 0 {
		valorPorPessoa = totalDespesas / float64(quantidadePessoas)
		for pessoa, valor := range despesas {
			resultado[pessoa] = valor - valorPorPessoa
		}
	}

	return resultado
}

func main() {
