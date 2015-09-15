# Lista de controles VTEX

#### Banner:

	<vtex:contentPlaceHolder id="ColecaoQVVT" />

output:

	<div class="box-banner">
		<a href="">
			<img width="" height="" alt="" src="" />
		</a>
	</div>

---
#### Newsletter:

	<vtex.cmc:newsletterOptIn/>

output:

	<div class="newsletter" id="NewsLetter_594549">
        <h3 class="newsletter-title">novidades</h3>
        <fieldset>
          <p>Receba novidades e promoções por email:</p>
          <input id="newsletterClientName" onfocus="newsSelect(this,'Digite seu nome');" onblur="newsLeave(this,'Digite seu nome');" class="newsletter-client-name" value="Digite seu nome" size="20" type="text" name="newsClientName">
          <input id="newsletterClientEmail" onfocus="newsSelect(this,'Digite seu e-mail');" onblur="newsLeave(this,'Digite seu e-mail');" class="newsletter-client-email" value="Digite seu e-mail" size="20" type="text" name="newsletterClientEmail">
          <input id="newsletterButtonOK" class="btn-ok newsletter-button-ok" value="ok" type="button" name="newsletterButtonOK" onclick="newsButtonClick('NewsLetter_594549')">
          <input id="newsletterLoading" type="hidden" class="newsletter-loading" value="Processando...">
          <input id="newsletterSuccess" type="hidden" class="newsletter-success" value="Obrigado por se cadastrar na Loja Exemplo!">
          <input id="newsletterSuccess2" type="hidden" class="newsletter-success2" value="Em breve entraremos em contato com você para oferecer as melhores promoções.">
          <input id="newsletterError" type="hidden" class="newsletter-error" value="
          Encontramos um erro no cadastro de suas informações.<br />Por favor, tente novamente!
        ">
          <input id="newsInternalPage" type="hidden" value="_teste_">
          <input id="newsInternalPart" type="hidden" value="newsletter">
          <input id="newsInternalCampaign" type="hidden" value="newsletter:opt-in">
        </fieldset>
        <span class="rt"></span>
        <span class="rb"></span>
        <span class="lb"></span>
        <span class="lt"></span>
      </div>




#### Links de Departamentos

    <vtex.cmc:departmentLinks/>

output:

    <ul class="menu">
  		<li class="menu-plugins"><a href="http://vtex.vtexcommercestable.com.br/plugins">Plugins</a></li>
  		<li class="menu-departamento-exemplo"><a href="http://vtex.vtexcommercestable.com.br/departamento-exemplo">Departamento Exemplo</a></li>
	</ul>


##### Menu de Departamentos

    <vtex.cmc:departmentNavigator/>

output

	<div class="menu-departamento"><span class="rt"></span><span class="rb"></span>
  		<h3 class="plugins"><span></span><a class="menu-item-texto" href="http://vtex.vtexcommercestable.com.br/plugins">Plugins</a></h3>
  		<ul class="plugins"></ul>
  		<h3 class="departamento-exemplo even"><span></span><a class="menu-item-texto" href="http://vtex.vtexcommercestable.com.br/departamento-exemplo">Departamento Exemplo</a></h3>
  		<ul class="departamento-exemplo even">
    		<li><a href="http://vtex.vtexcommercestable.com.br/departamento-exemplo/vestuario">Vestuario</a></li>
    		<li><a href="http://vtex.vtexcommercestable.com.br/departamento-exemplo/eletronicos">Eletronicos</a></li>
    		<li><a href="http://vtex.vtexcommercestable.com.br/departamento-exemplo/acessorios">Acessorios</a></li>
  		</ul>
  		<div class="brandFilter">
    		<h3>Marcas</h3>
    		<ul>
      			<li><a href="http://vtex.vtexcommercestable.com.br/marca-exemplo">Marca Exemplo</a></li>
    		</ul>
  		</div>
	</div>


##### Busca Total

    <vtex.cmc:fullTextSearchBox/>

output:

	<script type="text/javascript" language="javascript"> /*<![CDATA[*/ $(document).ready(function(){currentDept = '0'; enableFullTextSearchBox('ft309745', 'ft9325', 'ft932754892', 'ft032958', '/SEARCHTERM','Novo Digite Aqui' );}); /*]]>*/ </script>
	<fieldset class="busca"><legend>Buscar no site</legend><label>Buscar</label><select id="ft9325"><option value="">Todo o site</option><option value="8">Plugins</option><option value="4">Departamento Exemplo</option></select><input type="hidden" id="ft932754892" value=""><input id="ft309745" class="fulltext-search-box" type="text" size="20" accesskey="b"><input id="ft032958" type="button" value="Buscar" class="btn-buscar"></fieldset>



#### Product Image

	<vtex.cmc:ProductImage />

output

	<div class="apresentacao">
	<div id="setaThumbs"></div>
	<div id="show">
	<div id="include">
	<div id="image" productIndex="0">
	<img productIndex="0" id="image-main" class="sku-rich-image-main" src="http://	vtex.vtexcommercestable.com.br/arquivos/ids/138-292-292/bomba.jpg" alt="bomba" title="bomba" /></div>
	</div>
	<ul class="thumbs"> <li>
                                                    <a id='botaoZoom' href='javascript:void(0);' title='Zoom' rel='http://vtex.vtexcommercestable.com.br/arquivos/ids/138-292-292/bomba.jpg' zoom=''>
                                                        <img src='http://vtex.vtexcommercestable.com.br/arquivos/ids/155338-55-55/bomba.jpg' title='bomba' alt='bomba'/>
                                                    </a>
                                                </li></ul></div>
	</div>
#### Product Name

	<vtex.cmc:productName />

output

	<div class="fn productName  Bomba---Vermelha ">Bomba - Vermelha</div><input id="___rc-p-id"  type="hidden" value="6" /><input id="___rc-p-dv-id"  type="hidden" value="8" /><input id="___rc-p-sku-ids"  type="hidden" value="19" /><input id="___rc-p-kit-ids"  type="hidden" value="" />


#### Product Description

	<vtex.cmc:productDescriptionShort />

output





VTEX tag = <vtex.cmc:ProductImage zoom="on"/>

              <div class="apresentacao">
                <div id="setaThumbs"></div>
                <div id="show">
                  <div id="include">
                    <div id="image" productIndex="0">
                      <img productIndex="0" id="image-main" class="sku-rich-image-main" src="http://vtex.vtexcommercestable.com.br/arquivos/ids/138-292-292/bomba.jpg" alt="bomba" title="bomba" /></div>
                  </div>
                  <ul class="thumbs">
                    <li>
                      <a id='botaoZoom' href='javascript:void(0);' title='Zoom' rel='http://vtex.vtexcommercestable.com.br/arquivos/ids/138-292-292/bomba.jpg' zoom=''>
                        <img src='http://vtex.vtexcommercestable.com.br/arquivos/ids/155338-55-55/bomba.jpg' title='bomba' alt='bomba' />
                      </a>
                    </li>
                  </ul>
                </div>
              </div>
              <!-- /end VTEX tag -->


<!-- VTEX tag = <vtex.cmc:productName/> --><div class="fn productName  Bomba---Vermelha ">Bomba - Vermelha</div><input id="___rc-p-id"  type="hidden" value="6" /><input id="___rc-p-dv-id"  type="hidden" value="8" /><input id="___rc-p-sku-ids"  type="hidden" value="19" /><input id="___rc-p-kit-ids"  type="hidden" value="" /><!-- /end VTEX tag -->

<!-- VTEX tag = <vtex.cmc:productReference/> -->
              <div class="productReference SKU1008">SKU1008</div>
              <!-- /end VTEX tag -->


<!-- VTEX tag = <vtex.cmc:skuReference/> -->
              <div class="skuReference"></div>
              <!-- /end VTEX tag -->


<!-- VTEX tag = <vtex.cmc:skuPrice/> -->
              <div class="plugin-preco">
                <p productIndex="0" class="descricao-preco"><em productIndex="0" class="valor-de" style="display:block">De: <strong productIndex="0" class="skuListPrice">R$ 15,00</strong></em><em productIndex="0" class="valor-por">Por: <strong productIndex="0" class="skuBestPrice">R$ 8,00</strong></em><em productIndex="0" class="valor-dividido" style="display:none"><span><span>ou <label productIndex="0" class="skuBestInstallmentNumber">1</label>X de</span> <strong><label productIndex="0" class="skuBestInstallmentValue">R$ 8,00</label></strong></span></em>
                  <p productIndex="0" class="preco-a-vista" style="display:block">Preço a vista: <strong productIndex="0" class="skuPrice">R$ 8,00</strong></p><em productIndex="0" class="economia-de">Economia de <span productIndex="0" class="economy">R$ 7,00</span></em></p>
              </div>
              <script>
              $('.plugin-preco').price(6);
              </script>
              <!-- /end VTEX tag -->



<!-- VTEX tag = <vtex.cmc:stockKeepingUnitSelection /> -->
              <div class="sku-selector-container sku-selector-container-0" /></div>
            <script>
            $('.sku-selector-container-0').skuSelector(skuJson_0, {
              forceInputType: 'radio',
              selectSingleDimensionsOnOpening: 'true'
            });
            </script>
            <!-- A viewpart skuRichSelection esta obsoleta. Use a viewpart skuSelection para renderizar no modo de exibicao configurado -->
            <!-- /end VTEX tag -->



<!-- VTEX tag = <vtex.cmc:BuyButton/> --><a target="_top" class="buy-button buy-button-ref" href="https://vtex.vtexcommercestable.com.br/checkout/cart/add?sku=19&qty=1&seller=1&sc=1" style="display:block">Comprar</a>
            <script>
            $('.buy-button-ref').buyButton(6, {
              salesChannel: 1
            }, {})
            </script>
            <p class="unavailable-button" style="display:none">Produto Esgotado</p>
            <input type="hidden" class="buy-button-amount" value="1">
            <div class="portal-notify-me-ref"></div>
            <script>
            var notifyMeOptions = {
              'strings': {
                "title": "Avise-Me",
                "explanation": "\r\n    Para ser avisado da disponibilidade deste Produto, basta preencher os campos abaixo.\r\n  ",
                "loading": "Carregando...",
                "success": "Cadastrado com sucesso, assim que o produto for disponibilizado você receberá um email avisando.",
                "error": "Não foi possível cadastrar. Tente mais tarde.",
                "emailErrorMessage": "O endereço de e-mail informado é inválido."
              }
            };
            $('.portal-notify-me-ref').notifyMe(6, notifyMeOptions);
            </script>
            <!-- /end VTEX tag -->




<!-- VTEX tag = <vtex.cmc:evaluationRate/> --><strong>Opinião dos Consumidores:</strong><span id="spnRatingProdutoTop" class="rating-produto avaliacao0">0</span>
            <!-- /end VTEX tag -->




<!-- VTEX tag = <vtex.cmc:ProductDescription/> -->
            <div class="productDescription">Bomba de brinde para teste de promoção</div>
            <!-- /end VTEX tag -->
