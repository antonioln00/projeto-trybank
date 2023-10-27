# Bem-vindo ao TryBank!

# Sobre o Projeto
O TryBank é uma iniciativa que visa implementar um serviço de banco financeiro para atender às necessidades da nossa instituição do coração. No âmbito deste projeto, minha missão foi criar a versão inicial do TryBank, um banco fictício que contém contas e oferece funcionalidades essenciais, incluindo:

  -> Cadastro de contas
  -> Login de clientes
  -> Saque e depósito de saldo
  -> Transferência de fundos entre contas
  
Um desafio interessante deste projeto é que ainda não tínhamos aprendido a persistir dados em um banco de dados, por isso, optamos por armazenar os dados em um array. No entanto, isso significava que, toda vez que reiniciávamos o programa, os dados eram apagados e os saldos das contas zerados. Mas essa limitação foi uma oportunidade incrível de aprender a gerenciar dados em memória.

# Estrutura de Dados
Os dados da conta bancária foram armazenados em um array multidimensional. Cada array que armazena os dados tem a seguinte estrutura:

  -> Posição 0: Número da conta
  -> Posição 1: Agência
  -> Posição 2: Senha de acesso
  -> Posição 3: Saldo da conta
  
Aqui está um exemplo de como as contas seriam representadas:

int[] conta1 = new int[4] {1234, 1, 987, 0};
int[] conta2 = new int[4] {5678, 2, 765, 0};

int[][] Bank = new int[50] {conta1, conta2};

# Dicas de Implementação
Durante o desenvolvimento do projeto, foquei na separação de responsabilidades, o que garantiu que o sistema fosse escalável e permitisse futuras melhorias com facilidade. Segui a ordem dos requisitos para garantir que os métodos fossem implementados corretamente e testados de acordo com as necessidades.

# Contato
Se você quiser saber mais sobre o projeto ou discutir oportunidades de colaboração, não hesite em entrar em contato comigo através do LinkedIn.

