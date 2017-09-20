# Defina 3 KBF que você considere mais importante para o négocio.
* Garantir que o endereço de entrega seja válido 
* Login do usuário 
* Aplicação esteja validando corretamente o pedido (Quantidade,valor, formas de pagamento)
// Esteja responsivo em  desktop, IOS, android (não mais importante mas não esquecer de validar)

# Crie os planos de testes:
Caminho básico, acessar: https://www.ze.delivery/

* Caso de uso 1: Endereço de entrega
Validar o campo "Endereço de Entrega": Incluir endereço invalidos
Resultado esperado: Não permitir incluir endereço invalido

Validar o campo "Endereço de Entrega": Incluir endereço validos
Resultado esperado: Localizar local de entrega

* Caso de uso 2: Login do usuário
Cadastrar email e senha: informar todos os dados necessários para o cadastro

Resultado esperado: acessar o site com email cadastrado e senha

Logar com o Facebook: informar usuário e senha do Facebook

Resultado esperado: acessar o site com usuário do Facebook

* Caso de uso 3: Validar Pedido
Quantidade
Incluir produtos
Resultado esperado: Verificar se o Total está sendo exibido corretamente de acordo com os produtos selecionados

Formas de Pagamento
Exibir 3 formas de pagamentos (Credito, Debito e dinheiro)
Verificar cada forma de pagamento
Resultado esperado: Todas as formas de pagamentos disponiveis estejam permitindo a compra

# Automação
Explique se seria possível utilizar automação de testes para os cenários criados e cite que ferramentas ou tecnologias utilizaria para isso, caso positivo.

* Sim, seria possivel. Podemos utilizar o Selenium, criando algum script ou até mesmo o IDE do Selenium no Front e montar uma massa de testes incluindo alguns locais(endereço) e usuários, assim testando perfomance,stress e disponibilidade
