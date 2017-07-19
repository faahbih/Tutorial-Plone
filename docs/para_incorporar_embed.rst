Para incorporar <embed>
=======================

	* Primeiro é necessário configurar no painel de controle:
		* **Configuração do Site** > **TinyMCE Visual Editor**  > **Barra de Ferramentas**:
		* Ative a checkbox de **Inserir/editar multimídia**
		* Clique em salvar
	
	* Vá até **Configuração do Site**  > **Filtragem HTML**
		* Remova "object" and "embed" da lista Tags ofensivas
		* Remove "object" and "param" da lista  Tags removidas
		* Add "embed" e "iframe" na lista de Tags customizadas
		* Clique em salvar
	
	* Feito isso basta navegar até o diretório que irá usar a incorporação
	* Clique em **Adicionar Item** > **Multimídia**
		* Haverá um campo **“Código HTML a incorporar  HTML code to render the embedded media.”**, basta inserir o iframe.

	**Obs:** caso queira adicionar mais iframes na mesma página, é necessário criar uma nova página:
		* **Adicionar Item** > **Multimídia** e editá-lo com o novo iframe, em seguida volte para a página do primeiro iframe e clique em:
			+ **Edição** > **editar em corpo do texto** > clicar no ícone *advanced.scembedder_desc* e editar com o código do iframe e clicar em salvar.

	**Referência:** https://docs.plone.org/4/en/adapt-and-extend/config/safe-html.html#plone-4
