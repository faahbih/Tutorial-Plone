Para incorporar <embed>
=======================

	Primeiro é necessário configurar em **configuração do site** > **TinyMCE Visual Editor**  > Barra de Ferramentas:
	ative a checkbox de Inserir/editar multimídia
clique em salvar.
Vá até configuração do site  > HTML Filtering
Remova "object" and "embed" da lista Tags ofensivas
Remove "object" and "param" da lista  Tags removidas
Add "embed" e "iframe" na lista de Tags customizadas
clique em salvar.
feito isso basta navegar até o diretório que irá usar a incorporação
clique em adicionar item > Multimídia
haverá um campo “Código HTML a incorporar  HTML code to render the embedded media.”, basta inserir o iframe.
obs: caso queira adicionar mais iframes na mesma página, é necessário criar uma nova página (adicionar item > multimídia e editá-lo com o novo iframe), em seguida voltar para a página do primeiro iframe e ir em Edição > editar em corpo do texto > clicar no ícone advanced.scembedder_desc e clicar em salvar.
referência: https://docs.plone.org/4/en/adapt-and-extend/config/safe-html.html#plone-4
