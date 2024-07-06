---
layout: default
title: Power Automate com SharePoint
nav_order: 9.2
has_children: false
---

# Power Automate com SharePoint
{: .no_toc }


## Índice
{: .no_toc .text-delta }

1. TOC
{:toc}

<br/>

---

## Utilizar SharePoint com Power Automate


A Microsoft disponibliza o connector de [SharePoint](https://learn.microsoft.com/pt-pt/connectors/sharepointonline/) para o Power Automate.


- Armazenar respostas do Microsoft Forms no Power Automate.
- Sincronizar o Excel com uma lista do SharePoint.
- Gerir fluxos de aprovação.
- Trabalhe com ficheiros e listas criados com Listas Microsoft.
- Migrar a partir de fluxos de trabalho para o Power Automate.



## Ações disponíveis

O connector tem um conjuntos de ações que pode relaizar. As seguintes ações estavm disponíes em 2024-07-06.


| Ação | Descrição | 
| --- | --- | 
| Juntar anexo 	| Adiciona um novo anexo ao item de lista especificado. |
| Aprovar pedido de ingresso no site do hub |Aprove o pedido de ingresso no site do hub. Isto irá retornar um token de aprovação que pode ser utilizado para concluir o pedido de entrada utilizando a ação de site do hub de entrada. |
|  Cancelar pedido de adesão ao site do hub | Cancelar pedido de ingresso no hub. Se aplicável, terá de especificar o mesmo ID de correlação de aprovação utilizado na ação "Definir o estado de entrada no site do hub como pendente". |
|  Verifique se a versão programada do item foi publicada **(obsoleto)** |Retorna o resultado na variável de saída IsFilePublished. |
|  Check-in do ficheiro | Fazer o check-in de um ficheiro com check-out numa biblioteca de documentos, o que disponibiliza a versão do documento a outras pessoas. |
|  Confira ficheiro | Faça o check-out de um ficheiro numa biblioteca de documentos para evitar que outras pessoas editem o documento e que as suas alterações fiquem visíveis até que seja feito o check-in do documento. |
| Copiar ficheiro | Copia um ficheiro. Funciona de forma semelhante ao comando "Copiar para" nas bibliotecas do SharePoint. Retorna informações sobre o novo ficheiro após a cópia. |
| Copiar ficheiro **(obsoleto)** |Copia um ficheiro para um site SharePoint. |
|  Copiar pasta | Copia uma pasta. Funciona de forma semelhante ao comando "Copiar para" nas bibliotecas do SharePoint. Retorna informações sobre a nova pasta após a cópia. |
| Criar ficheiro | Carrega um ficheiro num site do SharePoint. Certifique-se de que escolhe uma biblioteca existente. |
| Criar item | Cria um novo item numa lista do SharePoint. |
| Criar novo conjunto de documentos | Cria um novo item da lista de conjunto de documentos. |
| Criar nova pasta | Cria uma nova pasta ou caminho de pasta. |
| Crie um link de partilha para um ficheiro ou pasta | Crie um link de partilha para um ficheiro ou pasta. |
| Apagar anexo | Exclui o anexo especificado.
| Apagar arquivo | Elimina o ficheiro especificado pelo identificador de ficheiro.| 
| Apagar item | Elimina um item de uma lista do SharePoint. |
| Descartar check-out | Se fizer o check-out de um ficheiro e não fizer alterações no mesmo, ou fizer alterações que não pretende manter, pode simplesmente descartar o check-out, em vez de guardar o ficheiro. Se a sua organização acompanhar as versões, será criada uma nova versão sempre que fizer o check-in de um ficheiro na biblioteca. Ao descartar o checkout, pode evitar a criação de novas versões quando não tiver efetuado qualquer alteração no ficheiro. |
| Extrair pasta | Extrai um ficheiro comprimido para uma pasta do SharePoint (exemplo: . zip). |
| Gerar documento utilizando o Microsoft Syntex (visualização)  | Utilize esta ação para criar documentos baseados em modelos modernos do Microsoft Syntex. Esta visualização requer uma licença Syntex. O preço está sujeito a alterações. Para mais informações, consulte: `https://docs.microsoft.com/en-us/microsoft-365/contentunderstanding/content-assembly` . |
| Obtenha todas as listas e bibliotecas | Obtenha todas as listas e bibliotecas.|
| Obtenha conteúdo de anexo | Retorna o conteúdo do ficheiro utilizando o identificador do ficheiro. O conteúdo pode ser copiado noutro local ou utilizado como anexo. |
| Obter anexos | Retorna a lista de anexos do item de lista especificado. Pode adicionar um passo "Obter conteúdo do anexo" e utilizar a propriedade "Identificador de ficheiro" devolvida por esta ação para obter o conteúdo do ficheiro. |
| Obter alterações para um item ou ficheiro (apenas propriedades) |	Retorna informação sobre colunas que foram alteradas num determinado intervalo de tempo. Nota: A lista deve estar com o Versionamento ativado. |
| Obtenha o conteúdo do ficheiro | Obtém o conteúdo do ficheiro utilizando o identificador do ficheiro. O conteúdo pode ser copiado noutro local ou utilizado como anexo. |
| Obtenha o conteúdo do ficheiro utilizando o caminho | Obtém o conteúdo do ficheiro utilizando o caminho do ficheiro. |
| Obtenha metadados de ficheiros | Obtém informações sobre o ficheiro, como o tamanho, etag, data de criação, etc. Utilize a ação "Obter propriedades do ficheiro" para obter os valores armazenados nas colunas da biblioteca. |
| Obtenha metadados de ficheiros usando caminho | Obtém informações sobre o ficheiro, como o tamanho, etag, data de criação, etc. Utilize a ação "Obter propriedades do ficheiro" para obter os valores armazenados nas colunas da biblioteca.|
| Obter propriedades do ficheiro | Obtém as propriedades guardadas nas colunas da biblioteca para o item especificado pelo ID do item. Pode adicionar um passo "Obter conteúdo do ficheiro" e utilizar a propriedade "Identificador do ficheiro" devolvida por esta ação para obter o conteúdo do ficheiro. Ao utilizar isto com o On-Premises Data Gateway, o nome da biblioteca à qual se liga pode ter de ser introduzido manualmente.
| Obter ficheiros (apenas propriedades) | Obtém as propriedades guardadas nas colunas da biblioteca para todas as pastas e ficheiros armazenados na biblioteca. Também pode filtrar os itens que correspondem a uma condição. Uma secção "Aplicar a cada" é geralmente utilizada para trabalhar com o resultado desta ação. Ao utilizar isto com o On-Premises Data Gateway, o nome da biblioteca à qual se liga pode ter de ser introduzido manualmente.|
| Obtenha metadados de pasta | Obtém informações sobre a pasta. Utiliza um identificador de ficheiro para escolher a pasta.|
| Obter metadados de pasta usando caminho | Obtém informações sobre a pasta. Utiliza um caminho de pasta para escolher a pasta. |
| Obter item | Obtém um único item pela sua ID a partir de uma lista do SharePoint. |
| Obter itens | Obtém itens de uma lista do SharePoint. |
| Obtenha visualizações de lista | Obtém visualizações de uma lista do SharePoint. |
| Obtenha listas | Obtém listas do SharePoint de um site. |
| Conceder acesso a um item ou pasta | Conceda acesso a um item ou pasta no SharePoint a pessoas específicas. |
| Junte-se ao site do hub | Junte o site solicitado ao site do hub. Será necessário um token de aprovação para concluir a associação com êxito se esse hub exigir aprovação. Se aplicável, terá de especificar o mesmo ID de correlação de aprovação utilizado na ação "Definir o estado de entrada no site do hub como pendente".
| Pasta de lista | Retorna ficheiros contidos numa pasta do SharePoint.
| Listar pasta raiz |Retorna ficheiros na pasta raiz do SharePoint. |
| Mover ficheiro |Move um ficheiro. Funciona de forma semelhante ao comando "Mover para" nas bibliotecas do SharePoint. Retorna informação sobre o novo ficheiro após a movimentação.|
| Mover pasta |Desloca uma pasta. Funciona de forma semelhante ao comando "Mover para" nas bibliotecas do SharePoint. Retorna informação sobre a nova pasta após a movimentação.|
| Resolver pessoa | Retorna um único valor de utilizador correspondente para que possa ser atribuído a uma coluna do tipo pessoa. Se não existirem correspondências ou se existirem múltiplas correspondências, esta ação causará erro. |
| Envie um pedido HTTP para o Share Point | Construa uma API REST do SharePoint para invocar. Nota – Esta ação pode executar qualquer API REST do SharePoint à qual tenha acesso. Por favor, proceda com cautela. |
| Definir o estado de aprovação de conteúdo | Define o estado de aprovação de conteúdo para um item de uma lista ou biblioteca que tenha a aprovação de conteúdo ativada. Deve fornecer uma ETag para páginas e ficheiros. Pode obter a ETag utilizando a ação Obter metadados de ficheiro. Esta ação apenas está disponível para o SharePoint Online e SharePoint 2019. |
| Definir o estado de ingresso no site do hub como pendente | Defina o estado do pedido de entrada no hub do site solicitado como pendente. A ID de Correlação de Aprovação é um parâmetro opcional que ajuda o SharePoint a identificar um pedido de entrada de hub específico. O site requerente só pode ter um pedido pendente de cada vez. |
| Pare de partilhar um item ou ficheiro |Apague todos os links que dão acesso a um item ou ficheiro e remova todas as pessoas com acesso direto, exceto os proprietários.|
| Atualizar ficheiro | Atualiza o conteúdo do ficheiro especificado pelo identificador de ficheiro. |
| Atualizar as propriedades do ficheiro |Atualiza as propriedades armazenadas em colunas de uma biblioteca para o item especificado pelo ID do item. Utilize a ação "Atualizar ficheiro" para atualizar o conteúdo do ficheiro. Ao utilizar isto com o On-Premises Data Gateway, o nome da biblioteca à qual se liga pode ter de ser introduzido manualmente.| 
| Atualizar as propriedades do ficheiro utilizando os resultados do modelo do AI Builder | Atualiza os valores armazenados nas colunas da biblioteca para um ficheiro analisado pelo modelo especificado pelo ModelId. |
| Atualizar item | Atualiza um item numa lista do SharePoint. |


## Exemplos

Os seguintes exemplos pertecem a documentção oficial da Microsoft.


**Trabalhar com ficheiros e listas**
- [Gerir permissões de ficheiros e item de lista.](https://learn.microsoft.com/pt-pt/sharepoint/dev/business-apps/power-automate/guidance/manage-list-item-file-permissions)
- [Mover ficheiros para diferentes pastas depois de aprovados no SharePoint.](https://learn.microsoft.com/pt-pt/sharepoint/dev/business-apps/power-automate/guidance/migrate-from-classic-workflows-to-power-automate-flows)
- [Criar um item no SharePoint, quando é adicionado um novo pedido no Salesforce.](https://learn.microsoft.com/pt-pt/sharepoint/dev/business-apps/power-automate/guidance/migrate-from-classic-workflows-to-power-automate-flows)
- [Obter itens de listas ou obter ficheiros de bibliotecas.](https://learn.microsoft.com/pt-pt/sharepoint/dev/business-apps/power-automate/guidance/working-with-get-items-and-get-files)
- [Crie um fluxo para uma lista ou biblioteca no SharePoint ou no OneDrive.](https://support.microsoft.com/office/create-a-flow-for-a-list-or-library-in-sharepoint-or-onedrive-a9c3e03b-0654-46af-a254-20252e580d01)
- [Editar um fluxo de cloud.](https://support.microsoft.com/office/edit-a-flow-for-a-list-in-sharepoint-b6678daa-2c82-44eb-be3f-2a9cb56301e8)


**Gerir fluxos de aprovação**

- [Personalize as as aprovações de página do SharePoint para atender às suas necessidades.](https://learn.microsoft.com/pt-pt/sharepoint/dev/business-apps/power-automate/guidance/customize-page-approvals)
- [Requeira a aprovação de documentos no SharePoint utilizando o Power Automate.](https://learn.microsoft.com/pt-pt/sharepoint/dev/business-apps/power-automate/guidance/require-doc-approval)
- [O percurso terminou os documentos para uma equipa para aprovação.](https://learn.microsoft.com/pt-pt/power-automate/customize-sharepoint-page-approvals)
