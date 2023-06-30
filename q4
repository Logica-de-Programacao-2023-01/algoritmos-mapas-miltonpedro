package main

import (
	"fmt"
	"sort"
	"strings"
)

// Função para verificar se duas palavras são anagramas
func saoAnagramas(palavra1, palavra2 string) bool {
	s1 := strings.Split(palavra1, "")
	s2 := strings.Split(palavra2, "")

	sort.Strings(s1)
	sort.Strings(s2)

	return strings.Join(s1, "") == strings.Join(s2, "")
}

// Função para agrupar palavras que são anagramas entre si em um mapa
func gruposAnagramas(palavras []string) map[string][]string {
	grupos := make(map[string][]string)

	for _, palavra := range palavras {
		// Verifica se a palavra já está em algum grupo existente
		for chave, grupo := range grupos {
			if saoAnagramas(p
