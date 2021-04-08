# teste-comprador-e-empresa
  <form action="/process_payment" method="post" id="paymentForm">
  <form action="/process_payment" method="post" id="paymentForm">
  <h3>Detalhe do comprador</h3>
    <div>
      <div>
        <label for="email">E-mail</label>
        <input id="email" name="email" type="text" value="test@test.com"/>
      </div>
      <div>
        <label for="docType"> documento CPF </label>
        <select id="docType" name="docType" data-checkout="docType" type="text"></select>
      </div>
      <div>
        <label for="docNumber">Número do documento</label>
        <input id="docNumber" name="docNumber" data-checkout="docNumber" type="text"/>
      </div>
    </div>
  <h3>Detalhes do cartão</h3>
    <div>
      <div>
        <label for="cardholderName">Titular do cartão</label>
        <input id="cardholderName" data-checkout="cardholderName" type="text">
      </div>
      <div>
        <label for="">Data de vencimento</label>
        <div>
          <input type="text" placeholder="MM" id="cardExpirationMonth" data-checkout="cardExpirationMonth"
            onselectstart="return false" onpaste="return false"
            oncopy="return false" oncut="return false"
            ondrag="return false" ondrop="return false" autocomplete=off>
          <span class="date-separator">/</span>
          <input type="text" placeholder="YY" id="cardExpirationYear" data-checkout="cardExpirationYear"
            onselectstart="return false" onpaste="return false"
            oncopy="return false" oncut="return false"
            ondrag="return false" ondrop="return false" autocomplete=off>
        </div>
      </div>
      <div>
        <label for="cardNumber">Número do cartão</label>
        <input type="text" id="cardNumber" data-checkout="cardNumber"
          onselectstart="return false" onpaste="return false"
          oncopy="return false" oncut="return false"
          ondrag="return false" ondrop="return false" autocomplete=off>
      </div>
      <div>
        <label for="securityCode">Código de segurança</label>
        <input id="securityCode" data-checkout="securityCode" type="text"
          onselectstart="return false" onpaste="return false"
          oncopy="return false" oncut="return false"
          ondrag="return false" ondrop="return false" autocomplete=off>
      </div>
      <div id="issuerInput">
        <label for="issuer">Empresa emissora</label>
        <select id="issuer" name="issuer" data-checkout="issuer"></select>
      </div>
      <div>
        <label for="installments"> Numero de Parcelas</label>

        <select type="text" id="installments" name="installments"></select>
      </div>
      <div>
        <input type="hidden" name="transactionAmount" id="transactionAmount" value="100" />
        <input type="hidden" name="paymentMethodId" id="paymentMethodId" />
        <input type="hidden" name="description" id="description" />
        <br>
        <button type="submit">Pagar</button>
        <br>
      </div>
  </div>
</form>


<form action="/process_payment" method="post" id="paymentForm">
  <form action="/process_payment" method="post" id="paymentForm">

    <form action="/process_payment" method="post" id="paymentForm">
      <form action="/process_payment" method="post" id="paymentForm">
      <h3>Detalhe da Empresa</h3>
        <div>
          <div>
            <label for="email">E-mail</label>
            <input id="email" name="email" type="text" value="test@test.com"/>
          </div>
          <div>
            <label for="docType">Tipo de nota fiscal</label>
            <select id="docType" name="docType" data-checkout="docType" type="text"></select>
          </div>
          <div>
            <label for="docNumber">Número da nota fiscal</label>
            <input id="docNumber" name="docNumber" data-checkout="docNumber" type="text"/>
          </div>
        </div>
      <h3>Detalhes da nota fiscal</h3>
        <div>
          <div>
            <label for="cardholderName">Titular da nota fiscal</label>
            <input id="cardholderName" data-checkout="cardholderName" type="text">
          </div>
          <div>
            <label for="">Data de vencimento</label>
            <div>
              <label for="">Data de entrada</label>
              <div>
                <label for="">Data de saida</label>
              </div>

              <input type="text" placeholder="MM" id="cardExpirationMonth" data-checkout="cardExpirationMonth"
                onselectstart="return false" onpaste="return false"
                oncopy="return false" oncut="return false"
                ondrag="return false" ondrop="return false" autocomplete=off>
              <span class="date-separator">/</span>
              <input type="text" placeholder="YY" id="cardExpirationYear" data-checkout="cardExpirationYear"
                onselectstart="return false" onpaste="return false"
                oncopy="return false" oncut="return false"
                ondrag="return false" ondrop="return false" autocomplete=off>
            </div>
          </div>
          <div>
            <label for="cardNumber">Número do CNPJ</label>
            <input type="text" id="cardNumber" data-checkout="cardNumber"
              onselectstart="return false" onpaste="return false"
              oncopy="return false" oncut="return false"
              ondrag="return false" ondrop="return false" autocomplete=off>
          </div>
          <div>
            <label for="securityCode">Código do Produto</label>
            <input id="securityCode" data-checkout="securityCode" type="text"
              onselectstart="return false" onpaste="return false"
              oncopy="return false" oncut="return false"
              ondrag="return false" ondrop="return false" autocomplete=off>
          </div>
          <div id="issuerInput">
            <label for="issuer">empresa emissora</label>
            <select id="issuer" name="issuer" data-checkout="issuer"></select>
          </div>
          <div>
            <label for="installments">a vista</label>
            <select type="text" id="installments" name="installments"></select>
          </div>
          <div>
            <input type="hidden" name="transactionAmount" id="transactionAmount" value="100" />
            <input type="hidden" name="paymentMethodId" id="paymentMethodId" />
            <input type="hidden" name="description" id="description" />
            <br>
            <button type="submit">Pagar</button>
            <br>
          </div>
      </div>
    </form>


    <form action="/process_payment" method="post" id="paymentForm">
      <form action="/process_payment" method="post" id="paymentForm">
   
