-- Exercício 1
 Escreva uma classe chamada Pessoa com os seguintes atributos: nome, idade, implemente também um construtor obrigatório (com os parâmetros: nome e idade) e o método mostraDados() que exibe os dados da pessoa no console.
 Escrever uma outra classe chamada Aluno,  ela deve herdar de Pessoa, tal classe possui as seguintes características:  atributos: número de matrícula, nome do curso que está cursando, um construtor para inicializar os atributos e sobrescrita do método mostraDados() para exibir também o nome do curso.
O  programa em Java deve: Perguntar ao usuário,  se ele deseja instanciar um aluno ou uma pessoa. Criar o objeto correspondente, e chamar o método mostraDados() para exibir os dados da pessoa ou do aluno. 

-- Exercício 2
 Crie uma classe chamada Veículo com os atributos: marca e ano. Implemente um construtor obrigatório (com os parâmetros: marca e ano) métodos getters e setters e um método mostraInfo() que exibe as informações do veículo no console. Depois, crie uma classe chamada Carro, que herda de Veiculo, com os seguintes atributos adicionais: numeroDePortas e tipoCombustivel. Implemente um construtor para inicializar todos os atributos e sobrescreva o método mostraInfo() para também exibir o número de portas e o tipo de combustível. Faça uma classe Principal para validar a implementação da herança, assim crie um objeto do tipo Carro e defina algumas entradas, feito isso chame o método mostraInfo().

-- Exercício 3
 Uma loja comercial possui três tipos de funcionários: funcionários comuns, vendedores e administradores. Para todos os funcionários, a empresa precisa registrar o nome, o RG, o valor da hora trabalhada e a quantidade de horas trabalhadas, além de ter um método para calcular o holerite e outro para exibir seus dados.
obs.: no caso do funcionário comum, o holerite é calculado multiplicando o valor da hora pelo número de horas trabalhadas no período. Nome e RG são itens obrigatórios na criação de um novo objeto. Os vendedores possuem um salário base, mas também ganham comissão com base em suas vendas. Os administradores possuem um salário fixo mensal, mas podem ganhar adicionais com base em horas extras. Os vendedores devem ter um método que registre cada venda (valor unitário e quantidade), acumulando o total vendido e a comissão durante o mês, e um método que feche o período, zerando esses acumuladores. A comissão é de 5% sobre cada venda, e o percentual pode ser alterado (valor entre 0 e 1).  O holerite do vendedor é o salário base somado à comissão acumulada, e o método de exibição deve imprimir também o salário base, o total vendido, a comissão e o holerite. 

No caso dos administradores, as horas extras são acumuladas e pagas com 50% de adicional sobre o valor da hora normal, que é calculado dividindo o salário base por 200 (jornada mensal). O holerite do administrador é o salário base somado ao valor total das horas extras, e o método de exibição deve imprimir também o salário base, a quantidade de horas extras, o valor das horas extras e o holerite. Finalize criando uma classe para testar as funcionalidades desenvolvidas, instanciando um objeto de cada cargo e exibindo seus dados e holerites.


-- Exercício 4
Crie uma classe chamada Produto com os atributos: nome (String), preco (double), quantidadeEstoque (int)
 A classe deve possuir: um construtor obrigatório para inicializar os atributos, métodos getters e setters para os atributos, um método mostrarDados() que exibe as informações do produto, e um método calcularValorTotalEstoque() que retorna o valor total em estoque (preço × quantidade).


 Crie uma subclasse chamada ProdutoImportado, que herda de Produto, e possui um atributo adicional: taxaImportacao (double). Essa classe deve: ter um construtor para inicializar todos os atributos (inclusive os herdados), sobrescrever o método mostrarDados() para exibir também o valor final do produto com a taxa de importação, sobrescrever o método calcularValorTotalEstoque() para considerar o preço acrescido da taxa de importação.


O programa deve:
Perguntar ao usuário quantos produtos deseja cadastrar.
Para cada produto, perguntar se deseja cadastrar um Produto ou um Produto Importado.
Criar os objetos correspondentes, armazenando-os em um vetor.
Ao final, percorrer o vetor e exibir os dados.
Mostrar também o valor total em estoque de todos os produtos cadastrados.




