# Anotacoes-OPENXAVA

<p><strong>@View(name="nomeDaView")</strong> == defini quais atributos serão mostrados na tela, pode-se criar várias <em>views</em>, de modo que outras entidades possam visualizar do modo desejado esta classe.</p>
<p><strong>@ReferenceView</strong> == referencia uma view especifica da entidade. A entidade cria suas views através do <emph>@View(name="", members = "")</emph> </p>
<p><strong>@DisplaySize</strong> ==  </p>
<p><strong>@NoFrame</strong> == não cria um quadro (frame) separando uma propriedade da outra, deixando os campos como se fosse de uma única propriedade.</p>
<p><strong>@DescriptionList</strong> == cria um combo box com os objetos da propriedade definida. </p>
<p><strong>@Money</strong> == para definir uma propriedade que vai usar recursos referente a dinheiro.</p>
<p><strong>@Files</strong> == para uma propriedade que irá tabalhar com fotos, documentos.</p>
<p><strong>@TextArea</strong> ==  mesma função do textarea do HTML</p>
<p><strong>@DefaultValueCalculator</strong> == define um valor para inicializar a propriedade, o <em>OpenXava</em> já possue algumas classes como por exemplo <em>CurrentYearCalculator.class</em>, esta retorna o ano atual. Neste endereço estão os calculators do openxava ==  <a href="https://www.openxava.org/OpenXavaDoc/apidocs/org/openxava/calculators/package-summary.html" target="_blank">calculators.</a>. <strong>@DefaultValueCalculator(value=NextNumberForYearCalculator.class,
    properties=@PropertyValue(name="year")</strong> == exemplo de aplicação, importante notar o parâmetro year sendo passado, este é um atributo que esta sendo passado para a classe NextNumberForYearCalculator, ou seja, o parâmetro year esta passando um valor para ser usado pela classe NextNumberForYearCalculator.</p>


