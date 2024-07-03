# Questão 1

<p>Uma instituição financeira solicita que para cadastrar uma conta bancária, é necessário informar:</p>
<ol>
    <li>o número da conta,</li>
    <li>o nome do titular da conta,</li>
    <li>e o valor de depósito inicial que o titular depositou ao abrir a conta.</li>
</ol>

<p>O valor de depósito inicial, é opcional, ou seja:</p>
<ul>
    <li>se o titular não tiver dinheiro a depositar no momento de abrir sua conta, o depósito inicial não será feito e o saldo inicial da conta será, naturalmente, zero.</li>
</ul>
     

<p><em>Importante:</em> Após a conta ser aberta, o número da conta nunca poderá ser alterado. Já o nome do titular pode ser alterado (pois uma pessoa pode mudar de nome quando contrai matrimônio por exemplo).</p>

<p>O saldo da conta não pode ser alterado livremente. É preciso haver um mecanismo para proteger isso. </p>

<p>O saldo só aumenta por meio de depósitos, e só diminui por meio de saques. </p>

<p>Para cada saque realizado, a instituição cobra uma taxa de $ 3.50. </p>

<p><strong>Observação:</strong> a conta pode ficar com saldo negativo se o saldo não for suficiente para realizar o saque e/ou pagar a taxa.</p>

<p>Disponibilizamos um programa que solicita os dados de cadastro da conta, dando opção para que seja ou não informado o valor de depósito inicial. Em seguida, realizar um depósito e depois um saque, sempre 
mostrando os dados da conta após cada operação.</p>

<p>Você deve implementar a classe “ContaBancaria” para que o programa funcione conforme dois cenários de teste abaixo:</p>

<p>Exemplo 1:</p>

<p>Entre o número da conta: <strong>5447</strong></p>
<p>Entre o titular da conta: <strong>Milton Gonçalves</strong></p>
<p>Haverá depósito inicial (s/n)? <strong>s</strong></p>
<p>Entre o valor de depósito inicial: <strong>350.00</strong></p>

</br>

<p>Dados da conta:</p>
<p><em><strong>Conta 5447, Titular: Milton Gonçalves, Saldo: $ 350.00</strong></em></p>

</br>

<p>Entre um valor para depósito: <strong>200</strong></p>
<p>Dados da conta atualizados:</p>
<p><em><strong>Conta 5447, Titular: Milton Gonçalves, Saldo: $ 550.00</strong></em></p>

</br>

<p>Entre um valor para saque: <strong>199</strong></p>
<p>Dados da conta atualizados:</p>
<p><em><strong>Conta 5447, Titular: Milton Gonçalves, Saldo: $ 347.50</strong></em></p>

</br>
</br>

<p>Exemplo 2:</p>

<p>Entre o número da conta: <strong>5139</strong></p>
<p>Entre o titular da conta: <strong>Elza Soares</strong></p>
<p>Haverá depósito inicial (s/n)? <strong>n</strong></p>

</br>

<p>Dados da conta:</p>
<p><em><strong>Conta 5139, Titular: Elza Soares, Saldo: $ 0.00</strong></em></p>

</br>

<p>Entre um valor para depósito: <strong>300.00</strong></p>
<p>Dados da conta atualizados:</p>
<p><em><strong>Conta 5139, Titular: Elza Soares, Saldo: $ 300.00</strong></em></p>

</br>

<p>Entre um valor para saque: <strong>298.00</strong><p>
<p>Dados da conta atualizados:<p>
<p><em><strong>Conta 5139, Titular: Elza Soares, Saldo: $ -1.50</strong></em><p>
