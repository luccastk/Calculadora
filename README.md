# Calculadora Simples em Python

Este projeto é uma calculadora simples implementada em Python. Ele suporta as quatro operações aritméticas básicas: adição, subtração, multiplicação e divisão. O usuário pode selecionar a operação desejada e fornecer os números para obter o resultado.

## Funcionalidades

- **Adição**: soma dois números.
- **Subtração**: subtrai um número do outro.
- **Multiplicação**: multiplica dois números.
- **Divisão**: divide dois números, com verificação de divisão por zero.
- **Validação de entrada**: garante que o usuário insira números válidos.

## Como usar

1. Clone o repositório para a sua máquina local:

   ```bash
   git clone https://github.com/luccastk/calculadora.git
   ```

2. ```bash
    cd calculadora
    ```

3. ```bash
    python calculator.py
    ```

## Exemplos de Uso

```bash
Selecione a operação:
1. Adição
2. Subtração
3. Multiplicação
4. Divisão

Digite a escolha (1/2/3/4): 1
Digite o primeiro número: 5
Digite o segundo número: 10
5.0 + 10.0 = 15.0
Deseja realizar outra operação? (s/n): s
```

## Requisitos
- Python 3.x

## Tratamentos de Erros
- **Divisão por zero**: O programa verifica se há ocorrência no segundo número é um zero e exibe uma mensagem de erro.
- **Entrada inválida**: O programa verifica se o usuário digitou uma opção inválida.