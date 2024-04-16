# Calculadora-de-Fatorial

---

# Calculadora de Fatorial

Este programa em C calcula o fatorial de um número inteiro não negativo inserido pelo usuário.

## Como usar o programa

1. Compile o código-fonte usando um compilador C, como o gcc:

```
gcc -o calculadora_fatorial calculadora_fatorial.c
```

2. Execute o programa compilado:

```
./calculadora_fatorial
```

3. Insira o número inteiro não negativo para calcular o fatorial quando solicitado.

4. O programa calculará o fatorial do número inserido e exibirá o resultado.

## Exemplo de Uso

```
Informe um número para o fatorial:
5
5! = 120
```

## Como funciona

1. O programa solicita que o usuário insira um número inteiro não negativo.
2. Se o número inserido for não negativo, o programa calcula o fatorial desse número.
3. O fatorial de um número é o produto de todos os números inteiros positivos menores ou iguais a ele.
4. O resultado é exibido na saída padrão.

## Observações

- O programa presume que o número inserido pelo usuário é um número inteiro não negativo.
- A função `setlocale` é utilizada para configurar a localidade para "Portuguese", permitindo a exibição correta de caracteres especiais em português.

---
