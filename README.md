### Caixa Eletrônico - Novas Funções
O projeto se resume em um sistema parecido a de um caixa eletrônico. Foi dado um código inicial, com poucas funções. Ao longo da construção, adicionei novas funções, fazendo com que ele ficasse ainda mais semelhante a um real.

Novas funções inseridas:

- Ao acessar o sistema, pergunte o nome do usuário e diga "Olá {Nome} é um prazer ter você por aqui!".
- Sempre que o usuário for sacar dinheiro, o valor restante não pode ser negativo, ou seja, caso o usuário tente sacar mais do que tem em saldo, a ação não deve ocorrer. Exiba uma mensagem de "Operação não autorizada".
- Sempre que o usuário for sacar dinheiro, o valor a ser sacado não pode ser igual ou menor a zero. Exiba uma mensagem de "Operação não autorizada".
- Adicionar a opção para ver o extrato (Coloque algumas compras ou depósitos fictícios).
- Adicionar a opção para fazer uma transferência. A transferência consiste em você informar o número de uma conta (pode ser qualquer número, mas obrigatoriamente um número, ou seja, nenhum outro caractere deve ser aceito), perguntar o valor da transferência e remover o valor da conta da mesma forma como na ação do saldo. Caso o usuário tente transferir mais do que tem em saldo, a ação não deve ocorrer. Exiba uma mensagem de "Operação não autorizada".
- Sempre que o usuário for transferir dinheiro, o valor a ser transferido não pode ser igual ou menor a zero, ou seja, caso o usuário tente transferir mais do que tem em saldo, a ação não deve ocorrer. Exiba uma mensagem de "Operação não autorizada".
- A ordem das opções deve ser: Saldo, Extrato, Saque, Depósito, Transferência e Sair.
- Atualize a função "erro" com as novas opções do menu.
- Caso o usuário informe um valor para depósito igual ou menor que zero, não deixe a operação ocorrer. Exiba uma mensagem de "Operação não autorizada".
- Sempre que o usuário for acessar o saldo, sacar, retirar o extrato ou transferir dinheiro é necessário que ele informe uma senha. Essa senha deve validada com uma condicional. A senha é 3589.
- Quando o usuário escolher sair do sistema, exiba uma mensagem agradecendo por utilizar os serviços do banco: "{Nome}, foi um prazer ter você por aqui!".
- Na função "inicio", utilize escolha/caso (switch/case) para validar a opção do usuário.
