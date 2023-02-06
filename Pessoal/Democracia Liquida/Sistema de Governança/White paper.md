# FlowDem - Uma metodologia de democracia líquida 

## Introdução

Democracia líquida é uma metodologia de governança democrática onde todos os participantes podem votar diretamente para a definição de uma proposta ou resolução de um confilto. Este sistema se difere da democracia direta permitindo aos seus participantes delegar seu poder decisão para outros participantes. Diferente do sistema de democracia representativa, neste modelo os participantes podem alterar a delegação do seu poder de voto a qualquer momento, não sendo necessário um rito específico, como eleições gerais.

Este modelo de governança visa otimizar a representatividade de cada participante. Este modelo prevalece ainda sobre a democracia direta uma vez que quando você delega diretamente para cada indivíduo a responsabilidade sobre cada decisão, este não consegue conjugar as atividades cotidianas com o a dedicação necessária para tomar uma decisão bem informada sobre determinado tópico. 

Por outro lado este modelo também supera o da democracia representativa, tendo em vista que tembém resolve a questão da decisão bem informada e é superior na trasição da representatividade, não tendo que esperar ritos específicos em períodos especificos para refletir mudanças de preferências de representatividade.

O FlowDem é um framework genérico para implementação de diversas variações de democracia líquida. Define regras base que podem ser extendidas para suprir necessidades fora do escpo base inicial.

## Conceitos Chave

### Proposta
Representa uma necessidade de resolução de conflito ou definição sobre uma ação a ser tomada por um grupo de pessoas dentro do FlowDem. 

### Voto
Representa a vontade de participantes sobre uma proposta específica

### Partícula
Menor unidade dentro capaz de votar dentro do FlowDem. Indivíduos ou organizações de indivíduos que intrinssicamente opinam sobre propostas de forma consoante com apenas um voto. A forma para se chegar nesta decisão não cabe de definição por parte do FlowDem, importando apenas que se chegue a uma e somente uma decisão a respeito do voto. Caso haja dissonancia não resolvida dentro da decisão de uma partícula, a mesma deverá ser dividida ou dissolvida para a criação de duas ou mais partículas independentes onde cada uma deverá ter apenas uma decisão.

### Esfera
Define o escopo dos conflitos e decisões a serem tomados. As particulas devem pertencer a esfera em questão para poder participar nas decisões da mesma.

### Potência
Determina o poder de decisão de cada partícula. A forma de cálculo da potencia varia de acordo com a implementação específica. Em uma esfera igualitária linear cada partícula tem potencia igual a 1, ou seja um voto por partícula.

### Tópico
Determina uma categoria a qual determinada decisão pertence. Cada decisão deverá ter uma e apnenas uma única categoria. Esta limitação é fundamental para o processo de delegação, que o mesmo poderá ser definida por tópico.


### Criação e Gestão de Uma Esfera
- Qualquer um pode iniciar uma nova esfera
- A regra de adesão à esfera não é escopo da metodologia, ficando livre para a implementação definir
- Tipos de gestão de esfera (espectro de totalmente gerenciada à totalmente descentralizada)
- Definição clara de consequências sobre o descumprimento das decisões tomadas de forma democrática.
- A inclusão e participação em uma esfera deve obrigatoriamente ser voluntária e representa o aceite nos termos de responsabilidade/consequencia e gestão da esfera. 
- Alteraçao nos termos deve necessáriamente se consentida de forma direta e indelegável.
- A não aceitação explicita por particulas de novos termos inativa a particula participante, isenta as mesmas de qualquer responsabilidade podendo inavalidar seu poder de voto, tornando-as efetivamente não participantes da esfera. 
- Período de transição - Após alteração de termos, deve existir período de transição razoável, onde votações são suspensas. As regras para o termino deste período (minimo aceite, tempo máximo de transição) deve ser estipulado no termo de gestão .
- Fica a cargo da implementação definir regras para validação da alteração dos termos de gestão. A não validação a priore, mantém válido o último termo anterior de gestão, salve expresso explicitamente regra contrária.

### Anatomia da proposta
 - Qual a estrutura básica de uma proposta

### Processo Decisório
- Uma vez pautada uma decisão como se dá a votação
- Quais os prazos que precisam ser definidos
- Momento em que se realiza a apuração
- Alteração de delegação entre a proposta ser pautada e ser apurada

### Delegação de Voto
 - Parte fundamental da metodologia
 - Soma da pontencia
 - Delegação em multinível
 - Referência circular de delegação não é permitida

### Definição de tópicos
 - Não é estabelecida pela metodologia
 - Acompanha espectro de gestão da esfera
 - Exclusão de tópicos e delegaçao de votos ??
 - Desassociação de uma particula com votos delegados. O poder de voto retorna as partículas delegadoras originalmente.

### Definição da potência
 - Não é estabelecida pela metodologia.
 - Podem ser usados quaisquer critérios (ainda que arbitrários) para definição
 - Alteração na regra de definição implica necessariamente na atualização dos termos de gestão da esfera, necessitando assim de consentimento direto das particulas.
