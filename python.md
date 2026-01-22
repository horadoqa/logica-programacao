# 🐍 EXERCÍCIOS DE LÓGICA EM PYTHON (COM EXPLICAÇÃO)

Perfeito 😄
Abaixo estão **os mesmos exercícios traduzidos para Python**, com **explicação clara** para você entender a lógica e a sintaxe ao mesmo tempo.

---

## 🔹 EXERCÍCIO 1 – Soma de dois números

### 📌 Enunciado:

Leia dois números e mostre a soma.

### 🧠 Lógica:

* Ler dois valores
* Somar
* Mostrar o resultado

### ✅ Código em Python:

```python
a = int(input("Digite o primeiro número: "))
b = int(input("Digite o segundo número: "))

soma = a + b

print("Soma =", soma)
```

---

## 🔹 EXERCÍCIO 2 – Número par ou ímpar

### 📌 Enunciado:

Leia um número e diga se ele é par ou ímpar.

### 🧠 Lógica:

* Se o resto da divisão por 2 for 0 → par

### ✅ Código:

```python
n = int(input("Digite um número: "))

if n % 2 == 0:
    print("Número par")
else:
    print("Número ímpar")
```

---

## 🔹 EXERCÍCIO 3 – Média de notas

### 📌 Enunciado:

Leia 3 notas e calcule a média.
Se média ≥ 7 → Aprovado, senão → Reprovado.

### 🧠 Lógica:

* Somar as notas
* Dividir por 3
* Verificar condição

### ✅ Código:

```python
n1 = float(input("Nota 1: "))
n2 = float(input("Nota 2: "))
n3 = float(input("Nota 3: "))

media = (n1 + n2 + n3) / 3

if media >= 7:
    print("Aprovado")
else:
    print("Reprovado")
```

---

## 🔹 EXERCÍCIO 4 – Contar de 1 a 10

### 📌 Enunciado:

Mostre os números de 1 a 10.

### 🧠 Lógica:

* Usar repetição

### ✅ Código:

```python
for i in range(1, 11):
    print(i)
```

---

## 🔹 EXERCÍCIO 5 – Soma de vários números

### 📌 Enunciado:

Leia 5 números e mostre a soma total.

### 🧠 Lógica:

* Criar acumulador
* Repetir 5 vezes

### ✅ Código:

```python
soma = 0

for i in range(5):
    num = int(input("Digite um número: "))
    soma += num

print("Soma =", soma)
```

---

## 🔹 EXERCÍCIO 6 – Maior número (lista)

### 📌 Enunciado:

Leia 5 números e mostre o maior.

### 🧠 Lógica:

* Guardar em lista
* Comparar valores

### ✅ Código:

```python
numeros = []

for i in range(5):
    numeros.append(int(input("Digite um número: ")))

maior = numeros[0]

for n in numeros:
    if n > maior:
        maior = n

print("Maior número =", maior)
```

---

## 🎯 DESAFIOS (para praticar)

Tente resolver antes de ver a solução 😉

1️⃣ Tabuada de um número
2️⃣ Contar quantos números são pares
3️⃣ Criar um menu (somar, subtrair, sair)
4️⃣ Jogo de adivinhação

---

Bons estudos 😊