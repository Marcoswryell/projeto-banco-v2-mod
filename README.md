# Sistema Bancário Simples

Este é um sistema bancário simples em Python que permite gerenciar clientes, contas e transações como depósitos e saques. O projeto foi modificado por **Marcos Uriel**.

## Funcionalidades

- Criação de clientes e contas bancárias.
- Realização de depósitos e saques.
- Exibição de extratos de contas.
- Limite de saques diários e controle de transações.

## Estrutura do Código

- **Classe `Cliente`**: Representa um cliente e suas contas.
- **Classe `Conta`**: Representa uma conta bancária, com funcionalidades para depósito e saque.
- **Classe `ContaCorrente`**: Extensão da classe `Conta`, adicionando limites de saques.
- **Classe `Transacao`**: Classe abstrata para representar transações bancárias.
- **Classes `Saque` e `Deposito`**: Representam as transações de saque e depósito, respectivamente.
- **Classe `Historico`**: Armazena o histórico de transações de uma conta.
- **Funções de Menu**: Permitem interação com o usuário, incluindo a realização de operações bancárias.

## Como Executar

1. Certifique-se de ter Python instalado.
2. Execute o script em um ambiente Python.
3. Siga as instruções do menu para interagir com o sistema.

## Licença

Este projeto é de uso livre.




