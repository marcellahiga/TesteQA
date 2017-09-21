# Defina 3 KBF que você considere mais importante para o négocio.
* Garantir que o endereço de entrega seja válido 
* Login do usuário 
* Aplicação esteja validando corretamente o pedido (Quantidade,valor, formas de pagamento)
// Esteja responsivo em  desktop, IOS, android (não mais importante mas não esquecer de validar)

# Crie os planos de testes:
Caminho básico, acessar: https://www.ze.delivery/

</br><b>* Caso de uso 1: Endereço de entrega</b>
</br>Validar o campo "Endereço de Entrega":Incluir endereço invalidos
</br>Resultado esperado: Não permitir incluir endereço invalido*
</br>Validar o campo "Endereço de Entrega":Incluir endereço validos
</br>Resultado esperado: Localizar local de entrega*

</br><b>* Caso de uso 2: Login do usuário</b>
</br>Cadastrar email e senha:informar todos os dados necessários para o cadastro
</br>Resultado esperado: acessar o site com email cadastrado e senha*
</br>Logar com o Facebook:informar usuário e senha do Facebook
</br>Resultado esperado: acessar o site com usuário do Facebook*

</br><b>* Caso de uso 3:Validar Pedido</b>
</br>Quantidade e Valor dos produtos
</b>Incluir mais de um produto e validar o valor exibido 
</br>Resultado esperado:Verificar se o Total está sendo exibido corretamente de acordo com os produtos selecionados*

</b>Formas de Pagamento
</b>Exibir 3 formas de pagamentos (Credito, Debito e dinheiro)
</b>Verificar cada forma de pagamento
</b>Resultado esperado: Todas as formas de pagamentos disponiveis estejam permitindo a compra*

# Automação
Explique se seria possível utilizar automação de testes para os cenários criados e cite que ferramentas ou tecnologias utilizaria para isso, caso positivo.

* Sim, seria possivel. Podemos utilizar o Selenium, criando algum script ou até mesmo o IDE do Selenium no Front e montar uma massa de testes incluindo alguns locais(endereço) e usuários, assim testando perfomance,stress e disponibilidade
