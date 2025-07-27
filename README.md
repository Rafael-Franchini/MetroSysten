# 🚇 Sistema de Controle de Metrô — Trabalho Prático de POO (C++)

Projeto desenvolvido para a disciplina **Algoritmos e Programação Orientada a Objetos I (APOO - I)**, sob orientação do professor **Maurício Acconcia Dias**.

## 👥 Integrantes

- Rafael Franchini — 109179  
- Danilo Muller — 105918  
- Otávio Fadini — 108999  

---

## 📌 Objetivo

Simular um **sistema metroviário** baseado em **estruturas de grafos** em **C++ com orientação a objetos**, permitindo a construção, manipulação e consulta de uma rede de estações e conexões.

---

## 🧠 Conceitos Utilizados

- **Grafos não direcionados e ponderados**
- **Matriz de adjacência** e **lista de adjacência**
- **Programação orientada a objetos**
- Algoritmos básicos de manipulação de grafos

---

## 🧰 Funcionalidades Implementadas

### ✅ Básico

- [x] Criar grafo (matriz e lista)
- [x] Adicionar estação (com nome e sigla)
- [x] Remover estação
- [x] Adicionar link entre estações com tempo/distância
- [x] Remover link entre estações
- [x] Exibir grafo (lista, matriz ou ambos)
- [x] Exibir número de arestas do grafo

### 🔜 Em desenvolvimento / não implementado

- [ ] Busca por estação (BFS e DFS)
- [ ] Caminho entre duas estações
- [ ] Menor caminho (ex: Dijkstra)
- [ ] Árvore geradora mínima (ex: Kruskal/Prim)
- [ ] Caminho que visita todas as estações uma vez (heurística de TSP)

---

## 🖥️ Execução

### Pré-requisitos

- Compilador C++ (ex: Code::Blocks, Visual Studio ou g++)
- Terminal com suporte a `system("cls")` (Windows)

### Como compilar

```bash
g++ trabalhoPOO.cpp -o metro
```

### Como executar

```bash
./metro
```

---

## 📄 Estrutura do Código

- `class estacao`: representa cada estação do metrô.
- `class metro`: representa o grafo contendo as estações e as ligações (arestas).
- `main()`: exibe um menu interativo para manipulação do sistema.

---

## 📷 Exemplo de Uso

```txt
1 criar o grafo (lista e matriz adjacencia)
2 adicionar estacao
3 remover estacao
7 encontrar o minimo de arestas
8 imprimir o sistema (lista/matriz)
9 adicionar link entre estacoes
10 remover link
0 sair
```




