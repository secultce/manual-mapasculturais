# Como pequisar no Mapa da Cultura

{% hint style="success" %}
Dica para quem deseja se aprofundar na análise de dados.
{% endhint %}

### Busca pela página inicial

Ao acessar o mapa você terá acesso à página inicial do sistema. Existem duas áreas que valem a pena comentar.

![1 Campo de busca geral \| 2 Cabe&#xE7;alho com as entidades do mapa](../.gitbook/assets/pequisar-do-mapa-da-cultura01.png)

1. Campo de busca geral
2. Cabeçalho com as entidades do mapa

{% hint style="info" %}
Para fazer buscas não é necessário ter uma conta ou estar logado na plataforma.
{% endhint %}

O campo de busca onde  lê-se **“digite uma palavra-chave”**

![Em destaque: Digite um palavra-chave](../.gitbook/assets/pequisar-do-mapa-da-cultura02.png)

Nesse campo você pode escrever uma palavra chave qualquer: nome de agente, espaço, evento, oportunidade \(ficha de inscrição\) ou projeto, assim como tags que por ventura possa ter sido cadastrada no sistema. Depois de escrito verás que existe logo ao lado o botão de `buscar`.

![](../.gitbook/assets/pequisar-do-mapa-da-cultura03.png)

Atente que o sistema não fará busca em todo o banco de dados uma vez que ao clicar em busca cinco opções aparecem: eventos, agentes, espaços, projetos e oportunidades: mapa dos agentes, mapas dos eventos, mapa dos espaços, lista de projetos e lista de oportunidades \(incluindo editais\). 

Ao escolher uma destas opções o sistema te levará ao mapa que corresponde aos resultados da entidade escolhida: agentes, eventos, espaços,  lista dos projetos ou a lista de oportunidades.

Note que durante toda a navegação o cabeçalho estará presente com os atalhos para as entidades **`EVENTOS`, `ESPAÇOS`, `AGENTES`, `PROJETOS` e `OPORTUNIDADES`**.

### Busca pela entidade

Você pode ir diretamente a elas para fazer a busca dentro de cada um destes bancos.

![Atalho para as entidades: Evento. espa&#xE7;o, agentes. projetos e oportunidades](../.gitbook/assets/pequisar-do-mapa-da-cultura04.png)

Uma vez dentro de cada uma das entidades existem uma série de opções de filtros para refinar a sua busca. Cada uma das entidades possuem alguns filtros específicos.

Ao clicar sobre a entidade `Agentes` toda a base de agentes cadastrados, com localização pública, aparecerá no mapa. Cada ponto mostra a quantidade de agentes cadastrados na região. Você pode ampliar o zom para visualizar cada agente individualmente.

![Mapa Agentes](../.gitbook/assets/pequisar-do-mapa-da-cultura05.png)

### Como filtrar a busca

Logo abaixo do campo **‘buscar agentes”** haverá o número total de agentes. O número entre parênteses são os agentes que optaram por deixar privada sua localização. Estes não aparecem no mapa mas aparecem no modo de lista da qual comentaremos mais a frente.

![Buscar Agentes](../.gitbook/assets/pequisar-do-mapa-da-cultura06.png)

Ao lado do campo **“buscar agentes”** existe o campo **“selecione áreas”**. Esse é um filtro da área de atuação do agente ou agentes\(s\) que se quer buscar.

![Selecionar &#xE1;reas \| Todos](../.gitbook/assets/pequisar-do-mapa-da-cultura07.png)

Mais ao lado existe um campo onde lê-se **“todos”**. Esse é um filtro para buscar agentes individuais, agentes coletivos ou ambos. A diferença entre estes agentes será mencionada mais adiante.

![Coletivo \| Individual \| Todos](../.gitbook/assets/pequisar-do-mapa-da-cultura08.png)

Na faixa cinza logo abaixo dos campos que acabamos de mencionar existe o contador. Conforme for acionando os filtros ou realizando buscas com palavras chaves, logo ao lado do contador, as ações aparecerão para que possa eventualmente editá-las servindo também como lembrete da busca.

Também é possível filtrar os agentes a partir de uma determinada área. Basta  clicar na ferramenta de seleção de área e depois clicar e arrastar o mouse na região do mapa que se deseja analisar. No exemplo abaixo foram encontrados 726 agentes.

![](../.gitbook/assets/pequisar-do-mapa-da-cultura-09.png)

{% hint style="info" %}
Estas opções de filtro também estão disponíveis para a busca de eventos e espaços.
{% endhint %}

### Visualizar resultados no modo de lista

Para visualizar as informações no modo de lista, basta clicar no ícone na lateral direita. 

![](../.gitbook/assets/pequisar-do-mapa-da-cultura-10.png)

Todos os agentes selecionados aparecerão junto com as seguintes informações:

* Nome social
* Foto
* Descrição curta
* Tipo de agente \(individual ou coletivo\)
* Área de atuação
* Tags \(palavras-chaves\)

Clicando no foto você poderá acessar o perfil do agente cadastro.

{% hint style="info" %}
Neste exemplo utilizamos o mesmo filtro da área delimitada, mas dessa vez o sistema contabilizou 1.126 agentes. Isso ocorre porque no modo de visualização de lista são considerados todos os cadastros de uma determinada área incluindo aqueles que optaram por tornar sua localização com privada, pois no modo listagem não se consegue individualizar a localização do agente. 
{% endhint %}

No modo listagem é possível organizar o resultado de acordo com o nome ou data de criação e por ordem crescente ou decrescente.

![](../.gitbook/assets/pequisar-do-mapa-da-cultura-11.png)

### Exportar para planilha ou compartilhar o resultado da busca

Por fim é possível exportar o resultado da sua busca para uma planilha, basta clicar no botação de exportar dados que fica o lado do botão de visualizar resultado como listagem. O sistema irá baixar uma planilha no formato excel \(.xls\) com todos os dados públicos dos agentes selecionados incluindo os contatos públicos e os links para redes sociais.

![](../.gitbook/assets/pequisar-do-mapa-da-cultura-12.png)

{% hint style="warning" %}
O sistema pode demorar para exportar buscas com muitos resultados \(acima de 5 mil\).
{% endhint %}

{% hint style="info" %}
Com o auxílio de um programador você pode fazer buscas mais complexas utilizando a API do mapa cultural &gt;&gt; [http://docs.mapasculturais.org/apidoc/index.html?doctype=api](http://docs.mapasculturais.org/apidoc/index.html?doctype=api)
{% endhint %}

 E o botão para compartilhar o resultado da pesquisa esta ao lado esquerdo do botão de exportar. Ele gerará o link  da sua pesquisa pesquisa para você compartilhar com outras pessoas. Esse foi o link gerado para a nossa busca por região:

{% embed url="https://mapacultural.secult.ce.gov.br/busca/\#\#\(global:\(enabled:\(agent:!t\),filterEntity:agent,locationFilters:\(circle:\(center:\(lat:-4.806364708499984,lng:-39.5947265625\),radius:100082\),enabled:circle\),viewMode:list\)\)" %}

{% hint style="info" %}
Não é preciso ter cadastro no mapa para visualizar as buscas.
{% endhint %}

{% hint style="success" %}
As informações do link que você gerou serão autalizadas automaticamente, ou seja, se novos agentes entrarem no mapas e estiverem dentro do filtro especificado, eles automaticamente aparecerão no link de que você compartilhou.
{% endhint %}

