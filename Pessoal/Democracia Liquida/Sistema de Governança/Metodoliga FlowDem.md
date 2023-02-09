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
É o elemento de nível mais alto detro da metodologia FlowDem. Não existem definições ou determinações fora dos limites da esfera ou entre esferas. Define o escopo dos conflitos e decisões a serem tomados. As particulas devem pertencer a esfera em questão para poder participar nas decisões da mesma.

### Potência
Determina o poder de decisão de cada partícula. A forma de cálculo da potencia varia de acordo com a implementação específica. Em uma esfera igualitária linear cada partícula tem potencia igual a 1, ou seja um voto por partícula.

### Tópico
Determina uma categoria a qual determinada decisão pertence. Cada decisão deverá ter uma e apnenas uma única categoria. Esta limitação é fundamental para o processo de delegação, que o mesmo poderá ser definida por tópico.


### Criação e Gestão de Uma Esfera

Uma esfera determina as regras de funcinamento da democracia assim como as partículas participantes. Sugere-se definir um escopo e objetivo claro para cada esfera.

As regras de adesão de particulas, a regra para definição de potência do voto, bom como a definição de propostas pautadasnão são escopo da metodologia, ficando livre para a implamentação definir a melhor forma.

Isto implica que a gestão da esfera é livre e se enquadra em um espectro que vai de totalmente descentralizada a totalmente centralizada. 

![[CleanShot 2023-02-08 at 07.59.42.png]]

Para um modelo de governça se enquadrar na metodologia FlowDem é preciso observar algumas regras e definir alguns acordos inpendente do modelo de gestão, no que pode-se chamar de acordo de participação.

### Acordo de Participação

O acordo de participação precisa ter uma definição clara e transparente das responsabilidades e consequência do descumprimento das decisões tomadas de forma democárica. Pense neste ponto como uma cláusula de recisão em um contrato de trabalho. Como cada parte deve ser responsabilizada e restituída em caso de um (ou mais) descumprimentos.

Deve também definir as regras para definição de potência de voto. É importante que esta seja definida de forma estática para que todos os participantes tenham consentido com as mesmas a priore da adesão na esfera.

A regra de adesão à uma esfera é livre de denfição pela implementação da metodologia, mas a participação nela deve obrigatóriamente ser voluntária, pois a mesma represeta o aceite nos termos do acordo de participação.

A participação de uma particúla dentro da esfera é sempre voluntária. Cabe ao acordo de participação estabelecer regras de responsabilidade e consequência para qualquer cenário imaginável de desassociação. A não definição de qualquer situação que venha a acontecer, isente qualquer participante de qualquer responsabilidade.

### Alterações no Acordo de Participação

As regras para alteração dos termos do acordo de participação devem ser estabelecidas. Não existe definição específica para este processo, mas mediante alteração de novos termos no acordo de participação é importante observar dois pontos: 

- As partículas participantes precisam obrigatóriamente aceitar os novos termos de forma direta, não podendo haver qualquer tipo de delegação para o aceite dos novos termos.
- Deve-se respeitar tempo de transição razoável onde nenhuma decisão poderá ser tomada, a menos que estabelecido pelo acordo de participação anterior, em carater de urgência à ser regido pelo acordo anterior, mas nunca para realizar novas alterações no acorodo de participação.

O acordo de participação é um contrato entre os participantes de uma esfera. É fundamental o consentimento direto em quaisquer alterações de tal acordo, para preservar as partes. É importante observar o tempo de transição, pois durante o período transitório do acordo, enquanto as particulas não consentiram sobre os novos termos, a representatividade total da esfera será drasticamente desfigurada.

Caso algumas partículas optem por não aceitar os novos termos, as mesmas poderão deixar a esfera, assumindo as responsabilidades e direitos do acordo prévio, desde que tal vontade seja expressada durante o período de transição.

Caso determinada partícula não se pronuncie sobre o novo acordo de transição, poderá ser considerado, imediatamente ou sob prazo determinado, que a mesma abandonou a esfera. Assumindo-se assim as responsabilidades e consequências por ventura determinadas para este caso no acordo de participação prévio.

Recomenda-se criar um rito de divulgação de propostas publicadas e descrevê-lo no acordo de participação.

### Definição da Potência

A potência é um atributo de cada particula. Esta define o quanto representa o voto de determinada particula. A forma como a potência é definida, não é escopo da metodologia. Se faz necessário que a potência da particula seja conhecida antes de qualquer votação ocorrer. 

A regra de cálculo da potência deve constar no acordo de aceite. No caso de alteração do cálculo de potência,  um novo acordo deve ser gerado necessitando novo consentimento direto das partículas.


### Publicação de Proposta

Uma proposta é uma sugestão de ação ou definição de ação a ser tomada. Precisa ter uma descrição clara do que se proproe. É fundamental que cada proposta tenha um e apenas um tópico. Isso será importante para determinar a potência de votação de cada particula e contabilizar os votos  da proposta em questão.

As opçoões de voto para uma proposta, vão depender da natureza da mesma. Uma proposta para uma tomada de ação pode ter apenas duas opções: "Sim" e "Não". Por exemplo, propostas que visão responder as seguintes perguntas:

 - Devemos fazer XYZ\?
 - Devemos romper a parceria com XYZ?

Por outro lado, uma eleição de um elemento frente a vários pode ter várias opções:

- Qual deve ser o tema da festa ? 
	 - Havaiana / Super-Herói / Anos 70
- Quem deve ser responsável o novo diretor executivo ?
	- João / Maria / Pedro

É possível ainda que uma proposta queira responder a uma pergunta on a partícula pode escolher 1 ou mais opções.

- Em quais plataformas devemos lançar a promoção X ? 
	 - Twitter / Facebook / Instagram
- quais propostas devem ser votadas na próxima semana ? 
	 - Proposta A / Proposta B / Proposta C / Proposta D

Neste caso, uma particula que escolha mais de uma opção, teria seus votos distribuidos igualmente entre as opções selecionadas.

É possível ainda permitir que particulas escolham opções com pesos diferentes para cada opção:

 - Como o orçamento deve ser distribuído ? 
	 - Manutenção do escritório / Equipamentos / Marketing/ Distribuição de Bônus

Neste modelo, cada opção receberia o percentual determinado da potência de voto.

Qualquer tipo de votação é permitido dentro da metodologia FlowDem, desde que sejam respeitadas a representatividade de cada partícula defina pela potência de voto da mesma.

Em questões mais simples de resposta "Sim"/"Não" fica evidente a ação a ser tomada mediante o resultado da votação. Para casos mais complexos, deve estar claro e transparente qual ação a ser tomada frente o resultado da votação. Pode ser um percentual mínimo de votos para que aquela opção seja levada em conta. Ou ainda, uma ordem de prioridade definida de acordo com o percentual  atingido de cada opção.

No momento da publicação da proposta é necessário ter estipulado o início e fim da votação. Período no qual as partículas deverão votar. Isso pode ser uma determinação fixa da esfera ou uma determinação dinâmica por proposta. Recomenda-se estipular uma regra duração mínima para propostas no termo de aceite, para evitar votações relampago que inviabilizem as partículas de tomaram conhecimento e participarem na votação.

Recomenda-se criar um rito de divulgação de propostas publicadas e descrevê-lo no acordo de participação.

É preciso definir se a votação será pública ou privada. Isto determina se o voto de cada partícula será público ou não.


### Delegação de Voto

Este mecanismo é fundamental para a metodologia e é o que caracteriza este modelo de governança como o de uma democracia líquida. Consiste na possibilidade de determinada partícula delegar seu poder de decisão para outra partícula da mesma esfera.

Isto pode ser feito por tópico. Onde a partícula de origem transfere seu poder de voto para a partícula de destino apenas para propostas de determinado tópico. Ou de forma geral, onde a particula de origem transfere seu poder de voto em todo e qualquer tópico para partícula de destino.

A delegação de voto pode ser alterada a qualquer momento, sem necessidade de qualquer tipo de notificação. Cada delegação de voto que uma partícula recebe, aumenta sua potência de voto no mesmo montante da potência da partícula de origem no tópicos aplicáveis.

Uma partícula que possua votos delegados também pode delegar seu poder de voto para outra partícula. Com isso a partícula de destino recebe a potencia de todos os votos delgados à particula de origem. Funciona como uma forma de delegação indireta. Que pode ocorrer em multiníveis. 

É preciso tomar cuidado no entanto para não formar uma delegação cíclica. Isto é quando a partícula de origem é também a partícula de destino. Imagine um cenário com três partículas: P1, P2 e P3. Se P1 delegar seus votos para P2 e P2 delegar seus votos para P3, P3 não poderia delegar seus votos para P1, ou então uma delegação cíclica ocorreria.

![[CleanShot 2023-02-09 at 09.56.09.png]]


Delegações cíclicas não são permitidas pois criar uma ambiguidade sob quem pertence o poder de voto.

### Anatomia da Proposta

A proposta deve descrever a decisão a ser tomada. Não existe um formato definido (texto, vídeo, audio, etc). Desde de que a informação seja clara.

Toda a proposta deve pertencer a um e apenas um tópico. Isso é importante para definir a potencia de voto de cada partícula e suas delegações aplicáveis.

É preciso determinar as opções disponíveis para a definição da decisão a ser tomada conforme descrito no item **"Publicação de Proposta"**. Isso implica em determinar quais ações serão tomadas de acordo com o resultado da votação. 

Existe a possibilidade ainda de determinar um percentual mínimo de quorum necessário para que a votação seja válida. Caso o votação termine sem o quorum necessário, a votação é cancelada e uma nova proposta deve ser submetida.

Recomenda-se criar um rito de divulgação de propostas publicadas e descrevê-lo no acordo de participação.

### Processo Decisório
Uma vez que proposta for publicada para votação se obeservará o prazo de votação, período no qual as partículas devem se pronunciar sobre a proposta.

A potencia de cada partícula se soma ao score da opção escolhida por cada partícula. Durante o processo decisório, é permitida a alteração na delegação de votos, o que afeta o score de cada opção ao longo do processo. No momento do término do período de votação, é avaliada a potência de voto de cada partícula junto com a opção escolhida. Neste momento o score é apurado e não mais poderá ser alterado.

Após a apuração dos scores de cada opção chega-se ao resultado e a ação a ser tomada é definida.

### Definição de tópicos
Os tópicos determinam uma categoria ao qual propostas pertencem. Não é escopo da metodologia o processo de definição dos tópicos. O mesmo pode variar de acordo com o espectro de centralização da esfera.
É fundamental no entanto observar que as delegações devem ser escolhas diretas e voluntárias de cada partícula e como este pode estar relacionado à um tópico, uma vez que haja alteração que descaracterize o tópico original, as delegações se tornam inválidas e a potência de voto de cada partícula relativa a este tópico retornam a particula original.
Isto deve ser segiudo mesmo em casos onde um tópico é desmembrado em outros. Não deve existir qualquer transferência de delegação para os novos tópicos, uma vez que isso caracterizaria escolha feita no lugar da partícula original.
