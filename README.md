Classe Cliente, que representa os clientes de um banco. A classe tem os seguintes atributos:
• codigo (tipo int)
• nome (tipo String)
• eClienteEspecial (tipo Boolean) //Informa se o cliente pertence a categoria Cliente Especial
• limiteCredito (tipo double) //Informe o limite de crédito do cliente
•
a) Possui um método construtor para a classe. O construtor recebe como parâmetro o código e o nome do
cliente. No construtor o atributo limiteCredito recebe zero, e o atributo eClienteEspecial recebe false.
b) Possui um método getNome. O método não tem parâmetros e retornar o atributo nome.
c) Possui um método atualizarLimite que atualiza o limite de crédito do cliente. O método recebe como
parâmetro um valor do tipo double. Caso o cliente seja especial, o seu limite de crédito é atualizado com o
valor recebido como parâmetro e o método retorna true, indicando que a operação foi realizada. Caso
contrário, o método retornará false.
d) Possui um método atualizarSituacao que atualiza a situação do cliente (o seu atributo eClienteEspecial). O método recebe como parâmetro um boolean. Além de atualizar o referido atributo com o valor recebido como
parâmetro, se este valor for false, o atributo limiteCredito será atualizado com o valor 0 (zero).
e) Possui uma classe Teste que contenha o método main. No main, possui três clientes e utiliza todos os métodos da classe
cliente.
