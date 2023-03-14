
3 Pontos Centrais
	1-> Preciso validar que o produto atenda as necessidades do cliente
	2-> Tenho que antecipar comportamentos inesperados e alertar os riscos ao meu time
	3-> É minha missão disseminar essa mentalidade dentre meus amigos



Técnicas de Teste
	Partição de Equivalência --> Divide os dados em classes de equivalência onde todas as partições devem ser testadas.
		Partição Inválida --> São dados que devem ser rejeitados pelo componente ou sistema
		Partição Válida --> São dados que devem ser aceitos pelo componente ou sistema
	Análise de Valor Limite --> Utilizada apenas para valores numéricos ou sequenciais, trabalhando sempre no limite de cada valor (entre o mínimo e máximo aceitável). A técnica de análise de valor limite está relacionada com a técnica de partição de equivalência. Relacionada com a Partição de Equivalência.
	Tabela de Decisão --> Analisa as combinações entre as condições de um teste e define qual será o resultado esperado.
		Vantagens: Decisões complexas de negócios ou não tão complexas podem ser adicionadas a Tabela de Decisão;
		Auxilia a fazer combinações efetivas e a garantir uma melhor cobertura de testes;
		Simples representação e de simples interpretação, pode ser utilizada pelo Desenvolvimento e Negócios.
		Desvantagem: A maior desvantagem será quando aumentar a possibilidade de dados de entrada a tabela aumentará também.


Métricas de Teste no Cascata 
	Cobertura de Testes
		- Caso de teste por requisito planejados versus executados
		- Casos de teste por risco planejados versus executados

	Casos de Teste
		- Casos de teste por status (sucesso, falha, block)
		- Casos de teste planejados versus executados

	Defeitos
		- Defeitos corrigidos versus identificados
		- Defeitos por severidade e propriedade
		- Defeitos por idade

ATDD segue os mesmos princípios do TDD, mas agora o que se espera testar são exemplos de funcionalidades ao invés de um único método de uma classe. Além disso, quem desenvolve atua com QA e PO para pensar nos exemplos de como provar que aquilo funciona sob a perpsectiva do usuário.

No BDD, temos uma escrita estruturada e criada de maneira colaborativa. Os comportamentos da aplicação através de cenários e essa definição é feita com base no negócio junto ao PO, QA e Dev.

No TDD, ao invés de pensar em quais tabelas do banco dados, classes métodos ou APIs terão de ser criadas, a pessoa que desenvolve irá pensar em quais testes podem provar que os métodos de uma classe que será desenvolvida funciona como esperado.

Métricas de Qualidade Ágil
	Estórias de Usuários
		Aceitação de estória de usuário
	Revisões 
		Eficácia da Revisão
	Defeitos
		Vazamento de defeito
		Eficiência de remoção de defeitos
	Cobertura
		Cobertura de código
	Satisfação dos Clientes
		Net Promoter Score (NPS)

Como contribuir nas Refinaments:
	1 - Remova ambiguidades e incompletude
	2 - Identifque riscos
	3 - Encontre dependências

Em testes práticos on-line e off-line, a eficiência e abrangência são o segredo da vitória:
	Testar mais com menos, usando técnicas do módulo sobre como identificar o que testar
	Aplicar abordagens de teste e conversar conforme o que aprendeu
	Usar testes não funcionais
	Escrever testes automatizados usando melhores práticas
	Versionar o código fonte de testes

Ouça atentamente, anote e responda de maneira sincera, clara e objetiva:
	Mapas mentais são muito bons para entrevistas para que haja entendimento
	Entenda claramente o que os recrutadores tem a falar
	Processe sua mensagem e a envie assim que conseguir concebê-la
	Informe sua visão de forma clara
	Faça pausas ao descrever algo

Tenha perguntas para fazer ao recrutador:
		Fundamente-se em o que você viu durante a pesquisa da empresa
		Baseie suas perguntas com base no nível do entrevistador
		Uma pergunta por vez
		Escute a resposta e estejam prontos a interagir
		Mescle seus medos com o caminho e a estretágeia da empresa

Métricas Únicas de Teste
	- Eficiência na remoção de defeitos (DRE) -> Defeitos / (Defeitos + Falhas)
	exemplo: Se na Sprint 2 achamos 65 defeitos, e em produção 35 defeitos, calcula-se:
		65 / (65+35).
	- Densidade de defeitos
	- Tempo médio para falhar
	- Tempo médio com a falha
	- Métricas de cobertura
	- Ciclos de teste
	- Requisitos testados

Revisões de artefatos: Código Fonte
	Checklist:
		É facil entender o código?
		O código obedece às convenções acordadas pelo time?
		Há codigo morto?
		Há algum comentário desnecessário?
		Todos os laços tem um final alcançavel?
		Todos os comandos de debug foram removidos?
		Os testes contidos testam o que se propõe a testar?

Revisões de artefatos UX:
	Checklist:
		Ações repeptitivas ou atividades frequentes parecem simples?
		Os usuários podem se recuperar facilmente de erros:
		Obter ajuda está impedindo o progresso do usuário?
		A ação primária é visualmente distinta das ações secundárias?
		Elementos interativos são característicos?
		O envio do formulario é confirmado de maneira visualmente distinta?
		Mensagens de alerta são consistentes?
		A navegação é consistente?

Revisões de artefatos de requisitos:
	Checklist:
		Ortografia e gramática utilizadas estão de acordo com o idioma utilizado?
		Os requisitos cobrem todos os elementos de interação que serão apresentadas ao usuário?
		Há informações ambíguas, duplicadas ou incompletas no requisito?
		Há regras conflitantes?
		Pré requisitos e dependências foram expostas?