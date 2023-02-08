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

Caso determinada partícula não se pronuncie sobre o novo acordo de transição, poderá ser considerado, imediatamente ou sob prazo determinado, que a mesma abandonou a esfera. Assumindo-se assim as responsabilidades e consequências por ventura determinadas para este caso.
 

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
