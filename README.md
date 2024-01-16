# Desafio-MV

Primeiramente criei uma classe "cliente" para representar as informações de um cliente.
utilizei um "Map<String, Double>", chamado "contas" para armazenar as contas e seus saldos associados.
"GerenciamentoClientes" é a classe principal que contém o método "main".
"Clientes" é uma lista que armazenará os objetos "Cliente".
"scanner" é usado para a entrada do usuário.
O método "main"  é onde o programa começa a ser executado.
Optei por usar um loop "do-while" para continuar exibindo o menu até que o usuário escolha sair (opção 7).
Criei métodos para fazer as operações do sistema(Adicionar, listar, atualizar, remover, depositar, sacar).

Método adicionarCliente:
Solicitei informações do cliente e criei um objeto Cliente para adicionar à lista.
Usei um Map para armazenar as contas e seus saldos.

Método listarClientes:
Exibe as informações de todos os clientes armazenados na lista.

Método atualizarCliente:
Solicita o CPF do cliente a ser atualizado e permite a atualização do endereço.

Método removerCliente:
Solicita o CPF do cliente a ser removido e o remove da lista.

Métodos depositarDinheiro e sacarDinheiro:
Solicitam o CPF do cliente e o número da conta.
Verificam se a conta existe no mapa contas do cliente.
Realizam a operação de depósito ou saque, atualizando o saldo.

Método encontrarClientePorCPF:
Retorna o cliente correspondente ao CPF fornecido.
