# Sistema de Gerenciamento de Contas de Clientes

Este repositório contém um sistema simples em Python para gerenciar contas de clientes, permitindo operações como depósito, saque e exibição de extrato.

## Estrutura do Projeto

O projeto é composto por três arquivos principais:

- `cliente.py`: Define a classe `Cliente`, responsável por armazenar informações como nome e telefone do cliente.

- `conta.py`: Define a classe `Conta`, que implementa funcionalidades de uma conta bancária, incluindo depósito, saque e exibição de extrato.

- `main.py`: Arquivo de demonstração que utiliza as classes `Cliente` e `Conta` para simular operações bancárias.

## Como Usar

Para usar este projeto, siga estes passos:

1. Clone o repositório para a sua máquina local.
2. Navegue até a pasta do projeto.
3. Execute o arquivo `main.py` para ver uma demonstração das funcionalidades.

## Exemplo de Uso

```python
from Cliente import Cliente
from Conta import Conta

c1 = Cliente("João", "114444-2222")
conta = Conta(c1.get_nome(), 1222)

conta.deposita(100)
conta.saque(50)
conta.extrato()
