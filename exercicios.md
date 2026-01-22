# 🧠 EXERCÍCIOS DE LÓGICA COM RESOLUÇÃO

Perfeito 👍
Abaixo estão **exercícios de lógica de programação com resolução explicada**, começando do **nível iniciante** e avançando aos poucos. Vou usar **pseudocódigo / Portugol**, porque ajuda a focar na lógica (não na linguagem).

---

## 🔹 EXERCÍCIO 1 – Soma de dois números

### 📌 Enunciado:

Leia dois números e mostre a soma deles.

### 🧠 Lógica:

1. Ler o primeiro número
2. Ler o segundo número
3. Somar
4. Mostrar o resultado

### ✅ Resolução (Portugol):

```
algoritmo "Soma"
var
   a, b, soma: inteiro
inicio
   leia(a)
   leia(b)
   soma <- a + b
   escreva("Soma = ", soma)
fimalgoritmo
```

---

## 🔹 EXERCÍCIO 2 – Número par ou ímpar

### 📌 Enunciado:

Leia um número e diga se ele é par ou ímpar.

### 🧠 Lógica:

* Número par → resto da divisão por 2 é 0

### ✅ Resolução:

```
algoritmo "ParImpar"
var
   n: inteiro
inicio
   leia(n)
   se (n % 2 = 0) entao
      escreva("Número par")
   senao
      escreva("Número ímpar")
   fimse
fimalgoritmo
```

---

## 🔹 EXERCÍCIO 3 – Média de notas

### 📌 Enunciado:

Leia 3 notas e calcule a média.
Se média ≥ 7 → Aprovado, senão → Reprovado.

### 🧠 Lógica:

* Somar notas
* Dividir por 3
* Verificar condição

### ✅ Resolução:

```
algoritmo "Media"
var
   n1, n2, n3, media: real
inicio
   leia(n1)
   leia(n2)
   leia(n3)
   media <- (n1 + n2 + n3) / 3

   se (media >= 7) entao
      escreva("Aprovado")
   senao
      escreva("Reprovado")
   fimse
fimalgoritmo
```

---

## 🔹 EXERCÍCIO 4 – Contar de 1 a 10

### 📌 Enunciado:

Mostre os números de 1 a 10.

### 🧠 Lógica:

* Começar em 1
* Repetir até 10
* Incrementar

### ✅ Resolução:

```
algoritmo "Contador"
var
   i: inteiro
inicio
   para i de 1 ate 10 faca
      escreva(i)
   fimpara
fimalgoritmo
```

---

## 🔹 EXERCÍCIO 5 – Soma de vários números

### 📌 Enunciado:

Leia 5 números e mostre a soma total.

### 🧠 Lógica:

* Criar acumulador
* Repetir 5 vezes
* Somar cada número

### ✅ Resolução:

```
algoritmo "SomaNumeros"
var
   i, num, soma: inteiro
inicio
   soma <- 0

   para i de 1 ate 5 faca
      leia(num)
      soma <- soma + num
   fimpara

   escreva("Soma = ", soma)
fimalgoritmo
```

---

## 🔹 EXERCÍCIO 6 – Maior número (vetor)

### 📌 Enunciado:

Leia 5 números e mostre o maior.

### 🧠 Lógica:

* Guardar números em vetor
* Comparar um por um

### ✅ Resolução:

```
algoritmo "MaiorNumero"
var
   v: vetor[1..5] de inteiro
   i, maior: inteiro
inicio
   para i de 1 ate 5 faca
      leia(v[i])
   fimpara

   maior <- v[1]

   para i de 2 ate 5 faca
      se (v[i] > maior) entao
         maior <- v[i]
      fimse
   fimpara

   escreva("Maior = ", maior)
fimalgoritmo
```

---

## 🎯 DESAFIOS (tente sozinho)

1️⃣ Fazer a tabuada de um número
2️⃣ Contar quantos números são pares
3️⃣ Criar um menu (somar, subtrair, sair)
4️⃣ Jogo de adivinhação

---

### 🚀 Próximo passo

* [🐍 EXERCÍCIOS DE LÓGICA EM PYTHON (COM EXPLICAÇÃO)](./python.md)

Bons estudos 😊
