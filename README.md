DESAFIO SISTEMA BANCÁRIO - DIO

---OBJETIVO GERAL ---

Separar as funções existentes de saque, deposito e extrato em funções. Criar duas novas funções: 
	1 - cadastrar usuário (cliente)
	2 - cadastrar conta bancária (vincular com usuário)

Precisamos deixar o nosso código mais modularizado, para isso vamos criar funções para as operações existentes:
	- SACAR, 
	- DEPOSITAR 
	- EXTRATO (visualizar histórico)

---SEPARAÇÃO DAS FUNÇÕES ---
Devemos criar funções para todas as operações do sistema.
Para exercitar tudo o que aprendemos neste módulo, cada função vai ter uma regra na passagem de argumentos. o retorno
 e a forma como serão chamadas, pode ser definida por você da forma quue achar melhor.

SAQUE
Afunção saque deve receber os argumentos apenas ´pr nome (keyword only)> Sugestão de argumentos: saldo, valor, extrato,
limite, numero_saques, limite_saques. Sugestão de retorno: saldo e extrato.

DEPÓSITO
A função depósito deve receber os argumentos apenas por posição (positional only). Sugestão de argumentos: saldo, valor, extrato. 
Sugestão de retorno: saldo e extrato.

EXTRATO
A função extrato deve receber os argumentos por posição e nome (positional only e keyword only). Argumentos posicionais:
saldo, argumentos nomeados: extrato.

NOVAS FUNÇÕES
Precisamos criar duas novas funções: criar usuário e criar conta corrente.
Fique a vontade para adicionar mais funções, exemplo: listar contas.

CRIAR USUÁRIO (CLIENTE)
O  programa deve armazenar os usuários em uma lista, um usuário é composto por nome, data de nascimento, cpf e endereço. 
O endereço é uma string com o formado: logradouro, número - bairro - cidade/sigla estado. Deve ser arnazenado somente os números do cpf. 
Não podemos cadastrar 2 usuários com o mesmo CPF. 

CRIAR CONTA CORRENTE
O programa deve armazenar contas em uma lista, uma conta é composta por: agência, número da conta e usuário. 
O número da conta é sequencial, iniciandi em 1.
O número da agencia é fixo: "0001". O usuário pode ter mais de uma conta, mas uma conta pertence a somente um usuário.

DICA 
Para vincular um usuário a uma conta, filtre a lista de usuários buscando o número do CPF informado para cada usuário da lista.











