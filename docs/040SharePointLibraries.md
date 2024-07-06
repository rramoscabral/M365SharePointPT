---
layout: default
title: Biblioteca SharePoint
nav_order: 4
has_children: true
---

# Biblioteca SharePoint
{: .no_toc }


## Índice
{: .no_toc .text-delta }

1. TOC
{:toc}

<br/>

---

<a id="top" />

<a id="sharepoint" />

## Biblioteca SharePoint

Uma biblioteca é um local num site onde pode carregar, criar, atualizar e colaborar em ficheiros com membros da equipa.

Cada biblioteca apresenta uma lista de ficheiros e informações importantes sobre os ficheiros, como por exemplo quem foi a última pessoa a modificar um ficheiro. A maioria dos sites inclui uma biblioteca quando cria o site. Por exemplo, um site de pessoal tem uma biblioteca de Documentos onde pode organizar e partilhar os seus documentos.

![Document Library Upload Invoices](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryUploadInvoices.png)

À medida que precisar de mais bibliotecas, pode escolher entre várias aplicações de biblioteca prontas a usar e adicioná-las ao seu site. Também pode personalizar bibliotecas de diversas formas. Por exemplo, pode controlar a forma como os documentos são visualizados, geridos e criados. ou rastrear versões de ficheiros, incluindo quantas e qual o tipo de versão. Pode até criar visualizações, formulários e fluxos de trabalho personalizados para o ajudar a gerir os seus projetos e processos de negócio.

Existem várias formas de organizar os ficheiros numa biblioteca. Pode adicionar colunas, definir vistas e criar pastas. Cada abordagem tem as suas próprias vantagens e pode combiná-las para satisfazer as necessidades únicas da sua biblioteca e da sua equipa.


<br/>

<a id="types-of-libraries" />

<br/>

## Tipos de bibliotecas
Algumas bibliotecas são criadas quando cria um novo site, como a biblioteca Documentos num site de pessoal. Pode personalizar estas bibliotecas de acordo com os seus propósitos ou criar as suas próprias bibliotecas adicionais. Cada tipo de biblioteca tem uma finalidade específica e algumas têm um conjunto diferente de comportamentos e recursos.

> **Importante:** Pode ter menos ou mais bibliotecas disponíveis no seu site, dependendo da versão do SharePoint em que o seu site se baseia, do plano Microsoft 365 que a sua organização subscreve ou se determinadas funcionalidades estão ativadas no seu site.

<br/>

| Tipo de biblioteca | Descrição |
| :---: | --- |
| Biblioteca de ativos (Asset library) | Para partilhar e gerir ativos de média digital, como ficheiros de imagem, áudio e vídeo, utilize uma biblioteca de ativos. Uma biblioteca de ativos torna mais fácil para os utilizadores descobrirem e reutilizarem ficheiros de média digital que outros já criaram, como logótipos e imagens corporativas. Uma biblioteca de ativos também fornece tipos de conteúdo com propriedades e visualizações para gerir e navegar em ativos de media, como miniaturas e palavras-chave de metadados. Por exemplo, pode querer gerir e armazenar imagens de marca e fragmentos de conteúdo reutilizáveis ​​de aplicações para que estejam disponíveis em toda a empresa e sejam utilizados de forma consistente.|
| Biblioteca de painéis (Dashboards library) | Contém páginas de Web Parts, páginas de Web Parts com listas de estado e painéis PerformancePoint implantados. |
| Biblioteca de ligações de dados | Para simplificar a manutenção e a gestão das ligações de dados, utilize uma biblioteca de ligações de dados. Uma biblioteca de ligação de dados é um local centralizado para armazenar ficheiros **Office Data Connection (ODC)**. Cada um destes ficheiros (.odc) contém informações sobre como localizar, fazer login, consultar e aceder a uma fonte de dados externa. A centralização de ficheiros ODC numa biblioteca de ligações de dados também possibilita a partilha, gestão e pesquisa de ficheiros de ligações de dados num site do SharePoint e ajuda a garantir que os dados e os relatórios de negócio, especialmente as folhas de cálculo, mantêm um conjunto consistente de valores e resultados de fórmulas como "uma versão da verdade".|
| Biblioteca de documentos (Document library) | Para muitos tipos de ficheiros, incluindo documentos e folhas de cálculo, utilize uma biblioteca de documentos. Pode armazenar outros tipos de ficheiros numa biblioteca de documentos, embora alguns tipos de ficheiros estejam bloqueados por motivos de segurança. Ao trabalhar com programas que não estão bloqueados, pode criar estes ficheiros na biblioteca. Por exemplo, a sua equipa de marketing pode ter a sua própria biblioteca de documentos para materiais de planeamento, comunicados de imprensa e publicações.|
| Biblioteca de formulários (Form library) | Se precisar de gerir um grupo de formulários comerciais baseados em **XML**, utilize uma biblioteca de formulários. Por exemplo, a sua organização pode querer utilizar uma biblioteca de formulários para relatórios de despesas. A configuração de uma biblioteca de formulários requer um editor XML ou um programa de design de formulários XML, como o Microsoft InfoPath. O formulário que as pessoas preenchem é apenas um ficheiro *.xml* que contém os dados (e apenas os dados) que foram introduzidos no formulário, como a data da despesa e o valor. Tudo o resto que compõe o relatório de despesas é fornecido pelo modelo de formulário. Assim que as pessoas preencherem os formulários, pode fundir os dados do formulário ou exportá-los para análise.|
| Biblioteca de imagens (Picture library) | Para partilhar uma coleção de imagens ou gráficos digitais, utilize uma biblioteca de imagens. Embora as imagens possam ser armazenadas noutros tipos de bibliotecas do SharePoint, as bibliotecas de imagens apresentam diversas vantagens. Por exemplo, numa biblioteca de imagens pode visualizar imagens numa apresentação de diapositivos, descarregar imagens para o seu computador e editar imagens com programas gráficos compatíveis, como o Microsoft Paint. Considere criar uma biblioteca de imagens se pretender armazenar fotografias de eventos de equipa ou lançamentos de produtos. Também pode criar links para imagens da sua biblioteca de outros locais do site, como wikis e blogues.|
| Biblioteca de registos (Record library) | Para manter um repositório central para armazenar e gerir os registos ou documentos comerciais importantes da sua organização, utilize uma biblioteca de registos. Por exemplo, a sua organização pode necessitar de aderir a regulamentos de conformidade que exigem um processo organizado para gerir documentos pertinentes. Um site da Central de Registos pode conter diversas bibliotecas de registos para armazenar diferentes tipos de registos. Para cada biblioteca pode definir políticas que determinam quais os registos a armazenar, como encaminhar e gerir os documentos e durante quanto tempo esses registos devem ser retidos.|
| Biblioteca de relatórios | ara simplificar a criação, a gestão e a entrega de páginas web, documentos e indicadores-chave de desempenho ou Key Performance Indicators (KPI) em inglês de métricas e metas, utilize uma biblioteca de relatórios. A biblioteca de relatórios é um local central onde pode criar e guardar relatórios, como pastas de trabalho do Excel e páginas de painel. Quando publica uma pasta de trabalho do Excel numa biblioteca de relatórios, esta é ativada com um único clique para a abrir no modo de visualização do browser, o que é uma forma conveniente de ver a pasta de trabalho sem a adicionar a uma página de Web Parts.|
| Biblioteca de Diagramas de Processo (Process Diagram Library) unidades métricas e dos EUA |Para armazenar e partilhar documentos de processos de diagramas, como os criados com o Microsoft Visio, utilize uma Biblioteca de Diagramas de Processos. As bibliotecas das unidades métricas e dos EUA são adaptadas às suas respetivas medidas.|
| Biblioteca de páginas Wiki (Wiki Page Library) | Para criar uma coleção de páginas wiki ligadas, utilize uma biblioteca de páginas wiki. Um wiki permite que várias pessoas reúnam informações num formato fácil de criar e modificar. Também pode adicionar páginas wiki que contenham imagens, tabelas, hiperligações e ligações internas à sua biblioteca. Por exemplo, se a sua equipa criar um site wiki para um projeto, o site poderá armazenar dicas e truques numa série de páginas que se ligam entre si.|



<br/>

<a id="columns" />

<br/>

## Colunas

Por predefinição, as bibliotecas rastreiam o nome de um ficheiro, bem como informações sobre o estado de um ficheiro, como por exemplo se foi feito o check-in. Mas pode especificar colunas adicionais que ajudam o seu grupo a categorizar e rastrear ficheiros, como um nome da campanha ou número do projeto ou outras informações importantes para a sua equipa. Tem várias opções para o tipo de coluna que cria, incluindo uma única linha de texto, uma lista suspensa de opções, um número que é calculado a partir de outras colunas ou até o nome e a fotografia de uma pessoa no seu website.

As colunas fornecem cabeçalhos de coluna que facilitam a ordenação e a filtragem de documentos. Ao visualizar ficheiros numa biblioteca, pode classificar ou filtrar temporariamente os ficheiros apontando para o nome de uma coluna e clicando na seta para baixo ao lado do nome. Isto é útil se precisar de ver os ficheiros de uma determinada forma, mas terá de repetir os passos na próxima vez que visualizar a biblioteca.


<br/>

### Criar coluna

Pode adicionar a maioria dos tipos de colunas, tipos de colunas, colunas de sites ou adicionar colunas existentes à biblioteca.

Para adicionar uma coluna:
1. Navegue até à lista ou biblioteca na qual pretende criar uma coluna
1. À direita do nome da última coluna na parte superior da lista ou biblioteca, seleccione **+ Adicionar coluna (+ Add column)** ou **+**.
    ![Document Library Add Column](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryAddColumn.png)


    > **Nota:** Se estiver a utilizar o ambiente clássico do SharePoint Online ou uma versão do SharePoint Server ira ter um resultado diferente.


1. No menu de seleção (dropdown), selecione o tipo de coluna pretendido.

    - A adição de uma coluna não irá mostrar todos os tipos de dados. Para visualizar mais tipos de dados selecione **Mais... (More...)**.

        | Tipo de dados | Descrição |
        | --- | --- | 
        | Única linha de texto (Single line of text) | Utilizado para recolher e exibir pequenas quantidades de texto não formatado numa única linha (255 caracteres).|
        | Múltiplo (Multiple) | Utilizado para recolher e apresentar texto formatado ou texto extenso e números em mais do que uma linha, como a descrição de um item (63.999 caracteres).|
        | Localização (Location) | Adicione dados de localização avançados do Bing Maps ou do diretório da sua organização. |
        | Número (Number) | Utilizado para armazenar valores numéricos que não são valores monetários.|
        | Sim/Não (Yes/No) | Utilizado para armazenar informações verdadeiras/falsas ou sim/não, como por exemplo se alguém vai comparecer a um evento.|
        | Pessoa ou Grupo (Person or Group) | Utilizado para fornecer uma lista pesquisável de pessoas e grupos que as pessoas podem escolher ao adicionar ou editar um item. |
        | Data e hora (Date and time) | Utilizado para armazenar datas do calendário ou datas e horas. |
        | Escolha (Choice) | Utilizado para permitir que as pessoas escolham de uma lista de opções que fornece. |
        | Hiperligação (Hyperlink) | Utilizado para armazenar uma hiperligação para uma página Web, gráfico ou outro recurso. |
        | Moeda (Currency) | Utilizado para adicionar um único ficheiro de imagem do seu dispositivo a um item de uma lista ou biblioteca.|
        | Imagem (Image) | Use to add a single image file from your device to an item in a list or a library.|
        | Metadados Geridos (Managed Metadata) | Utilizado para permitir que os utilizadores do website selecionem valores de um conjunto específico de termos geridos e apliquem esses valores ao seu conteúdo.|

1. No painel Criar uma coluna, no campo Nome, introduza um título ou um cabeçalho de coluna.

1. Introduza qualquer outra informação necessária. O número de campos varia de acordo com o tipo de coluna escolhido. O exemplo acima é para um campo **Número (Number)**.

1. Selecione Guardar.


<br/>


### Alterar uma coluna

Pode modificar as colunas nas listas e bibliotecas editando a coluna selecionada. Pode utilizar o painel de detalhes ou propriedades.

  ![Document Library Edit Column](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryEditColumn.png)


Pode alterar a ordem de apresentação das colunas: 
- Selecione o título da coluna que pretende mover e arraste-o e largue-o no local apropriado.
- Ou pode selecionar o ícone Chevron com seta para baixo para expandir os detalhes. na parte superior de qualquer coluna e seleccione Definições da coluna > Mover para a esquerda ou Mover para a direita.

<br/>

### Alterar valor

Dependendo do tipo de dados uma coluna pode alterar o valor em todos os documentos ou manualmente em cada documento.




<br/>

### Apagar uma coluna

Quando já não precisar de uma coluna numa lista ou biblioteca, pode eliminá-la. Ou pode eliminar uma coluna de site do SharePoint.

1. Vá para a lista ou biblioteca da qual pretende excluir uma coluna.
1. u num site do SharePoint, selecione **Definições (Settings)** >  **Conteúdo do site (Site Contents)**, e selecione o nome da sua lista ou biblioteca.
1. Selecione o cabeçalho da coluna que pretende eliminar e, no menu, selecione **Definições da coluna (Column settings)** > **Editar (Edit)**.
1. Na parte inferior do painel Editar coluna, selecione **Eliminar (Delete)**.
1. Para eliminar permanentemente a coluna e os dados da coluna, selecione **Eliminar (Delete)**.




<br/>

<a id="views" />

<br/>

## Visualizações (Views)

WOs utilizadores desejarão frequentemente ver: todos os documentos relacionados com um projeto específico, todos os documentos que pertencem a um determinado departamento ou agrupar os documentos por mês de vencimento? Se espera visualizar os ficheiros de uma determinada forma com frequência, pode definir uma visualização. Pode utilizar esta vista sempre que trabalhar com a biblioteca. Quando cria uma vista, esta é adicionada à lista pendente Vistas atuais, localizada na faixa da biblioteca.

Uma vista de biblioteca é uma seleção de colunas numa página que exibe itens numa biblioteca e geralmente define uma ordem de classificação, filtro, agrupamento e layout personalizado específicos. As bibliotecas podem ter opiniões pessoais e opiniões públicas. Qualquer pessoa que tenha sido atribuída ao grupo Membros no site (que tenha o nível de permissão Contribuir) pode criar uma vista pessoal para ver os ficheiros de uma determinada forma ou filtrar apenas os ficheiros que pretende ver. Se tiver permissão para conceber uma biblioteca, pode criar uma vista pública que qualquer pessoa poderá utilizar ao visualizar a biblioteca. Também pode tornar qualquer vista pública a vista predefinida, para que as pessoas vejam automaticamente essa vista da biblioteca.

Se os membros do seu grupo visualizarem as bibliotecas num dispositivo móvel, pode até criar visualizações móveis que forneçam limites, como o número de itens apresentados numa visualização, que sejam ideais para a largura de banda e as limitações dos dispositivos.


<br/>



### Criar uma visualização

1. 1. Na barra de comando da sua lista, seleccione **Opções de visualização (View Options)** ![View Options Icon](https://www.rramoscabral.com/training/assets/MSSharePoint/ViewAllItems.png) de listas.


    > Se Opções de visualização Opções de visualização de listas não estiver visível, verifique se não está a editar a lista ou se não selecionou um ou mais itens. Além disso, pode não ter permissão. Nesse caso, contacte o administrador do Microsoft 365 ou os proprietários do site ou da lista.

1. Select **Criar nova vista (Create new view)**.

    > **Important:** If you don't see **Criar nova vista (Create new view)**, significa que as atualizações mais recentes ainda não chegaram até si.

1. Em **Nome da vista (View name)**, introduza um nome para a sua vista.

1. Em **Mostrar como (Show as)**, selecione **Lista (List)** ou **Calendário (Calendar)** for the type of view you want to create.

1. Se selecionar a visualização do calendário, introduza uma data de início e uma data de fim no calendário.

1. Para alterar a forma como o título dos itens aparece no calendário, seleccione Mais opções e seleccione na lista **Título dos itens no calendári (Title of items on calendar)**.

1. Quando terminar, selecione **Criar (Create)**.

<br/>


### Mudar uma visualização


Pode fazer algumas alterações diretamente na vista de lista. Para tal, clique no nome da coluna. Pode alterar a ordem dos itens, filtrá-los, agrupá-los, adicionar colunas e alterar outras definições de colunas. Quando terminar, clique em Opções de visualização e em Guardar visualização como. Guarde a visualização com o seu nome atual ou introduza um novo nome para criar uma nova visualização.

<br/>

### Apagar uma visualização

1. Na barra de comando da sua lista, seleccione **Opções de visualização (View Options)** ![View Options Icon](https://www.rramoscabral.com/training/assets/MSSharePoint/ViewAllItems.png) de listas.

1. Selecione o nome da visualização que pretende eliminar.

1. Selecione novamente Opções de visualização e selecione **Editar visualização atual (Edit current view)**.

1. Na página Editar visualização, selecione  **Apagar (Delete)** e selecione **OK**.


<br/>

<a id="alerts" />

<br/>



## Alertas

Para se manter atualizado quando os seus documentos ou itens do Microsoft SharePoint no seu site forem alterados, crie alertas. Pode configurar um alerta para uma lista, biblioteca, pasta, ficheiro ou item de lista. Por exemplo, pode configurar um alerta para uma pasta específica numa biblioteca, sem receber alertas quando ocorrem alterações no resto da biblioteca.

### Get alerts on item changes in SharePoint

Pode receber um alerta sempre que um ficheiro, ligação ou pasta for alterado numa biblioteca de documentos do SharePoint. Dependendo do item (ficheiro, pasta, ligação), poderá ver diferentes opções ao definir um alerta.

1. Vá para a lista ou biblioteca.

1. Selecione o ficheiro, ligação ou pasta para o qual pretende receber um alerta.

1. Na lista de opções da lista ou biblioteca, **... (reticências ou ellipses em inglês)**,  e selecione **Alertar-me (Alert Me)**.

1. Na caixa de diálogo **Alertar-me quando os itens mudam (Alert me when items change)**  seleccione e altere as opções pretendidas.

1. Para guardar, selecione OK.

<br/>

### Receba alertas sobre todas as alterações numa biblioteca de documentos no SharePoint

1. Vá para a lista ou biblioteca e certifique-se de que nenhum item está selecionado.

1. Na lista de opções da lista ou biblioteca, selecione **... (reticências ou ellipses em inglês)** e selecione **Alertar-me (Alert Me*)**. 

1. Na caixa de diálogo **Alerte-me quando os itens mudarem (Alert me when items change)** , altere ou preencha as opções pretendidas.

1. Selecione OK.


<br/>

### Cancel alerts in SharePoint

1. Para visualizar os seus alertas de uma página do site, na lista de opções da lista ou biblioteca, selecione **... (reticências ou ellipses em inglês)**  e selecione **Gerir os meus alertas (Manage My Alert)**
1. Selecione o alerta que pretende eliminar.
1. Selecione **Apagar alertas selecionados (Delete Selected Alerts)**.
1. Para eliminar, selecione **OK** .


<br/>

<a id="file-activity-in-a-document-library" />

<br/>

## Atividade de arquivo numa biblioteca de documentos

O SharePoint monitoriza as alterações e atualizações de ficheiros na sua biblioteca. Pode ver as alterações que foram feitas (criadas, editadas, apagadas) e quando (há 18 horas, ontem, na semana passada). Só pode visualizar atividades em ficheiros e documentos individuais ou em toda a sua biblioteca. A atividade está disponível nos últimos 60 dias.

<br/>

### Ver a atividade do arquivo numa biblioteca de documentos

1. Abra a biblioteca de documentos
1. Select **Abrir painel de detalhes (Open the details pane)** ![Icon Details Pane](https://www.rramoscabral.com/training/assets/MSSharePoint/IconDetailsPane.png).
1. Verifique a secção **Atividade (Activity)** para ver as atividades mais recentes dos seus **ficheiros**.
1. Para fechar o painel de detalhes, seleccione Abrir o painel de detalhes Informação ou Abrir novamente **painel de detalhes (details pane)** ![Icon Details Pane](https://www.rramoscabral.com/training/assets/MSSharePoint/IconDetailsPane.png).

