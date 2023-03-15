Tornar os testes independetes 
	O que acontece agr:
		os testes usam diversos grupos de permissoes e no inicio, sempre setam esses grupos, entretanto quanto terminam, nao deixam como antes, portanto, se rodar o teste novamente, alguns podem quebrar.

Testes instaveis
	Exemplo: um teste que vai olhar os contatos ele entra primeiro na página de contato recentes Então se por exemplo o contato que ele vai utilizar eu não tenho visitado o perfil recentemente ele não vai aparecer naquela lista então o teste vai falhar automaticamente o certo seria por exemplo a pessoa entrar em todos os contatos e procurar no campo de pesquisa o nome do contato que você quer né Essa dessa forma fica muito está


Tempo de Wait = Trocar maioria por Wait until xpath ou colocar times mais bem elaborados
Antes de deixar um teste automatizado concluido = rodar 4 vezes até o teste funcionar todas as vezes
deixar os testes mais concisos, sem duplicidade, menores, mais estáveis

AHUW-4388 = Nao funciona se estiver com outro treatment site se n for com o Hospital Israelita Albert Einstein

Principais problemas encontrados:
	Screenshots desnecessárias
	Interação com links e botões por meio das setas dos teclados
	Verificação (nem sempre verificava o que o step dizia: Verify field colours are displayed)
	Poderia ter juntado alguns steps e diminuido o tamanho do teste

Diminuir os sleeps dentro de cada teste, pensar em alguma forma de esperar a pagina carregar