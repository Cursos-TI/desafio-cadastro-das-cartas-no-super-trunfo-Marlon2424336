## 📝 Documentação do Projeto

### Super Trunfo - Países — Nível Novato: Cadastro de Cartas

--

### 🎯 Objetivo do Projeto

Este projeto tem como finalidade criar a estrutura inicial do jogo "Super Trunfo - Países", focando apenas no **cadastro de duas cartas** que representam cidades. Cada carta contém informações que, futuramente, poderão ser usadas para comparação de atributos.

---

### 📌 Funcionalidades Implementadas

* Leitura dos dados de duas cartas pelo terminal com `scanf`
* Armazenamento de atributos individuais por cidade
* Exibição de todos os dados das duas cartas com `printf`, de forma organizada

---

### 🧩 Atributos das Cartas

Cada cidade (ou carta) possui os seguintes atributos:

| Atributo          | Tipo     | Exemplo        |
| ----------------- | -------- | -------------- |
| Código da Cidade  | `char[]` | A01, B02, etc. |
| Nome da Cidade    | `char[]` | Salvador       |
| População         | `int`    | 1500000        |
| Área              | `float`  | 605.80         |
| PIB               | `float`  | 75.30          |
| Pontos Turísticos | `int`    | 12             |

---

### 📥 Entrada de Dados

Os dados são inseridos pelo usuário no terminal. O programa solicita os dados de cada carta, um por vez, como neste exemplo:

```
=== Cadastro da Carta 1 ===
Código da cidade: A01
Nome da cidade: Recife
População: 1490000
Área (em km²): 218.5
PIB (em bilhões): 45.7
Número de pontos turísticos: 10
```

---

### 📤 Saída do Programa

Após o cadastro, os dados são exibidos em blocos organizados com `printf`, como neste exemplo:

```
--- Dados da Carta 1 ---
Código: A01
Nome: Recife
População: 1490000
Área: 218.50 km²
PIB: 45.70 bilhões
Pontos turísticos: 10
```

---

### 🔧 Técnicas Utilizadas

* Uso de variáveis separadas para cada carta
* `scanf` para entrada de dados (inclusive com leitura de strings compostas via ` %[^\n]`)
* `printf` com formatação (`%.2f` para floats)
* Sem estruturas de repetição ou decisão, conforme regra do desafio Novato

---


