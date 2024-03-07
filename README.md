```
def verifica_fibonacci(num):
    a, b = 0, 1
    while b < num:
        a, b = b, a + b
    if b == num:
        return f"{num} pertence à sequência de Fibonacci."
    else:
        return f"{num} não pertence à sequência de Fibonacci."

numero = int(input("Digite um número: "))
print(verifica_fibonacci(numero))
```
