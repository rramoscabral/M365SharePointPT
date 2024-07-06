---
layout: default
title: Aprovações do SharePoint sem fluxo de trabalho
nav_order: 5
has_children: true
---

# Aprovações do SharePoint sem fluxo de trabalho
{: .no_toc }


## Índice
{: .no_toc .text-delta }

1. TOC
{:toc}

<br/>

---


<a id="top" />

<a id="sharepoint-approvals-without-workflow" />

## Aprovações do SharePoint sem fluxo de trabalho

Os fluxos de trabalho do SharePoint podem ajudá-lo a automatizar os seus processos de negócio, tornando-os mais consistentes e mais eficientes. O fluxo de trabalho de aprovação permite encaminhar documentos e outros itens armazenados no SharePoint para uma ou mais pessoas para aprovação.

Na versão SharePoint Online e no SharePoint 2019, os fluxos de trabalho do SharePoint estão a ser substituídos pelo [Microsoft Power Automate](https://powerautomate.microsoft.com).

No SharePoint 2010, os fluxos de trabalho foram desativados desde 1 de agosto de 2020 para novos locatários e removidos dos locatários existentes a 1 de novembro de 2020. Se estiver a utilizar fluxos de trabalho do SharePoint 2010, recomendamos a migração para o Power Automate ou outras soluções compatíveis. Para obter mais informações, consulte Descontinuação do fluxo de trabalho do SharePoint 2010.

Se pretender utilizar o Power Automate para criar fluxos de trabalho aprovados, necessitará do licenciamento do Power Platform Dataverse.

Mas com uma biblioteca de documentos SharePoint é possível definir aprovações sem fluxos.

E tudo isto será feito com as funcionalidades existentes do SharePoint.

- Recurso de controlo de versão numa biblioteca de documentos.
- Recurso de aprovação de conteúdos numa biblioteca de documentos.
- Recurso de alertas numa biblioteca de documentos.



<br/>

<a id="document-version-controls" />

<br/>

## Controlos de versão do documento

Um dos recursos existentes do SharePoint que iremos utilizar é o controlo de versão.

A colaboração de documentos, a coautoria e as atualizações de listas com seres humanos são muito melhores com o controlo de versões ativado. As pessoas cometem erros e o versionamento fornece a rede de segurança.

O versionamento cria um registo histórico de todas as alterações, com data/hora e indicação do utilizador que efetuou a alteração, por ficheiro/item de lista. O utilizador final poderá visualizar, eliminar e restaurar uma versão se tiver as permissões corretas na biblioteca ou lista.

Assim o primeiro passo é habilitar o versionament



<br>

### Ativar o versionamento

No SharePoint Online ou no local (On-Premises), o controlo de versão é ativado nos ecrãs Configurações de lista ou Configurações de biblioteca clicando em  **Definições de controlo de versão (Versioning settings)**. 

![Library Settings](https://www.rramoscabral.com/training/assets/MSSharePoint/LibrarySettings.png)



É fornecida uma interface para permitir controlar quantas versões deseja manter. O utilizador deve ter o recurso de permissão Gerir Listas para ativar o controlo de versão.

<br/>

### Desativar o versionamento

Se puder Ativar o versionamento, pode Desativar o versionamento. A desativação do versionamento não exclui as versões antigas. Os utilizadores finais não recebem qualquer notificação sobre esta alteração.

> **Nota:** Um alerta: como proprietário do website, se desativar o controlo de versão e não informar os seus utilizadores finais, eles irão notificá-lo. Em pessoa.

<br/>


### Versões principais versus versões secundárias

As bibliotecas podem ter versões principais, representadas por números inteiros (12.0), e versões secundárias, representadas por números decimais (12.3). Se a sua biblioteca estiver configurada para utilizar Check In/Check Out, cada alteração realizada por um utilizador com um documento com check-out criará uma versão secundária

As listas geralmente têm apenas versões principais.


> **Nota:** todas as versões são contabilizadas na utilização do armazenamento do SharePoint, assim como os ficheiros nas lixeiras e os ficheiros preservados devido a políticas de retenção.



<br/>

<a id="require-approval-of-items-in-a-list-or-library" />

<br/>


## Exigir aprovação de itens numa lista ou biblioteca

As listas e as bibliotecas contêm frequentemente informações confidenciais, como orçamentos de campanhas de marketing ou iniciativas de recursos humanos. Pode ser importante ter apenas versões “oficiais” de itens ou ficheiros visíveis para utilizadores específicos.

Pode exigir a aprovação de um item ou ficheiro antes que o conteúdo fique visível para utilizadores específicos. Ao exigir aprovação, as organizações podem aplicar um nível significativo de qualidade e segurança ao seu conteúdo confidencial


1. Navegue até à lista para a qual pretende solicitar aprovação.

1. Selecione **Definições (Settings)** ![Setting icon](https://www.rramoscabral.com/training/assets/MSSharePoint/IconSettings.png), em seguida **Definições da lista (List settings)**.

1. Na secção **Definições gerais (General settings)**, selecione **Definições de controlo de versão (Versioning settings)**.

     ![Versioning settings](https://www.rramoscabral.com/training/assets/MSSharePoint/LibrarySettingsVersioningSettings.png)

1. Na secção **Aprovação de conteúdo (Content Approval section)** , selecione **Sim (Yes)** em resposta à pergunta **Exigir aprovação de conteúdo para os itens enviados? (Require content approval for submitted items?)** Na secção **Histórico de versões (Version History)**do item , especifique se pretende criar versões sempre que um item for editado. Também pode optar por limitar o número de versões retidas.

    - Depois de ativar a aprovação de conteúdo, também terá a oportunidade de definir o controlo de versão principal ou secundária e a segurança do item de rascunho.

    ![Versioning Settings ContentApproval](https://www.rramoscabral.com/training/assets/MSSharePoint/VersioningSettingsContentApproval.png)


1. Na secção **Segurança do item de rascunho (Draft Item Security)**, determine quais os utilizadores que podem ver os itens de rascunho na lista.

    > **Dica:** Se necessitar de aprovação de conteúdo para uma lista ou biblioteca que já contenha itens, todos os itens da biblioteca serão marcados como Aprovados.

1. Pode escolher qualquer um dos seguintes:
    - Utilizadores que podem ler itens da lista.
    - Apenas utilizadores que podem editar itens da lista.
    - Apenas os utilizadores que podem aprovar itens na lista e o autor do item (está definido para si por defeito)


1. Selecione **OK**.


1. Verá uma coluna chamada  **Aproval Status (Aproval Status)**.

    ![Approval Status Column](https://www.rramoscabral.com/training/assets/MSSharePoint/ApprovalStatusColumn.png)


Agora qualquer documento que seja carregado na biblioteca terá de ser aprovado. O que significa que os documentos que se encontram no estado Pendente ou Rejeitado só serão vistos pelo remetente, e estes são os aprovadores. Depois de aprovados, serão vistos por todos



