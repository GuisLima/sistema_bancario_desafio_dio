# Sistema de Operações Bancárias em Python

Este é um programa simples em Python que simula um sistema de operações bancárias, permitindo ao usuário realizar depósitos, saques, verificar extrato e saldo.

## Funcionalidades

O programa oferece as seguintes funcionalidades:

1. **Depósito**: Permite que o usuário deposite um valor na conta.
2. **Saque**: Permite que o usuário saque um valor da conta, respeitando o limite diário de operações e o saldo disponível.
3. **Extrato**: Mostra ao usuário o histórico de operações realizadas e o saldo atual.
4. **Sair**: Encerra o programa.

## Instruções de Uso

Ao iniciar o programa, o usuário encontrará um menu com as opções disponíveis. Ele pode escolher uma das opções digitando o número correspondente:

- `1`: Realizar um depósito.
- `2`: Realizar um saque.
- `3`: Ver o extrato e saldo.
- `0`: Sair do programa.

Caso o usuário escolha uma opção inválida, o programa solicitará que ele insira novamente.

## Restrições

- **Limite de Saque**: O usuário pode sacar até R$ 500,00 por operação.
- **Limite Diário de Operações**: O usuário pode realizar até 3 operações por dia.

## Exemplo de Uso

```python
Olá! Seja bem-vindo, neste sistema você poderá realizar operações bancárias.

============ MENU ============
       [1] - DEPOSITO
       [2] - SACAR
       [3] - EXTRATO
       [0] - SAIR
===============================       

Digite a opção desejada: 1
Digite o valor que deseja depositar: 1000
O valor R$ 1000.00 foi depositado com sucesso!

============ MENU ============
       [1] - DEPOSITO
       [2] - SACAR
       [3] - EXTRATO
       [0] - SAIR
===============================       

Digite a opção desejada: 2
Digite o valor que deseja sacar: 200
