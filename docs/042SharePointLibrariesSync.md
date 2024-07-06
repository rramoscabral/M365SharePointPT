---
layout: default
title: Sincronize as bibliotecas do SharePoint com o seu computador
nav_order: 4.2
has_children: true
---

# Sincronize as bibliotecas do SharePoint com o seu computador
{: .no_toc }


## Índice
{: .no_toc .text-delta }

1. TOC
{:toc}

<br/>

---




<a id="sync-sharepoint-libraries-to-your-computer" />

## Sincronize as bibliotecas do SharePoint com o seu computador

Se a sua organização tiver uma subscrição empresarial ou de estudante do Microsoft 365 ou utilizar o SharePoint Server 2019 e o Microsoft Teams, pode sincronizar os seus ficheiros do Microsoft SharePoint e do Microsoft Teams com uma pasta no seu computador.

Isto permite-lhe trabalhar diretamente no Explorador de Ficheiros do Windows e aceder aos ficheiros mesmo quando estiver offline. E quando voltar a estar online, todas as alterações feitas nesses ficheiros serão sincronizadas automaticamente.

<br/>

<a id="sync-sharepoint-and-teams-files-with-your-computer" />

<br/>


## Sincronize ficheiros do SharePoint e do Teams com o seu computador

1. No **iniciador de aplicações (app launcher)** do Microsoft 365, selecione SharePoint ou Teams e selecione o site com os ficheiros que pretende sincronizar.


1. Selecione **Documentos (Documents)** ou navegue até à subpasta que pretende sincronizar. 

1. Selecione **Sincronizar (Sync)**. (Só precisa de o fazer uma vez num computador para configurar a sincronização nesse computador. Depois de configurar a sincronização, os ficheiros serão sincronizados automaticamente.)

    ![SharePoint Document Library Sync](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibrarySync.png)

1. Se o seu browser solicitar permissão para utilizar o **Microsoft OneDrive**, confirme se está tudo bem.

    > **Importante:** Se aparecer um ecrã a indicar **Qual a biblioteca que pretende sincronizar? (Which library do you want to sync?)**, o seu site não foi configurado para sincronizar com a aplicação de sincronização do OneDrive. Se for o administrador de TI da sua organização, consulte Permitir que os utilizadores sincronizem ficheiros do SharePoint com a nova aplicação de sincronização do OneDrive. Se não for o administrador de TI e os seus ecrãs não se parecerem com os deste artigo, consulte Sincronizar ficheiros do SharePoint com a aplicação de sincronização do OneDrive (Groove.exe) ou contacte o seu departamento de TI.

    Os ficheiros são depois sincronizados com uma pasta no seu PC que tem o nome da sua organização (por exemplo,`%userprofile%\[organization-name]). Esta pasta é adicionada automaticamente ao painel esquerdo do explorador de ficheiros do Windows. Não pode optar por sincronizar com um local diferente.

1. Para sincronizar os ficheiros noutro computador, aceda a esse computador e siga novamente estes passos.


### Alterar as definições de sincronização

Para alterar as pastas que são sincronizadas para um site ou para interromper a sincronização de todos os ficheiros de um site, siga os seguintes passos:


1. Selecione o ícone azul da nuvem OneDrive na área de notificação da barra de tarefas do Windows.

    ![OneDrive SyncClient with blue cloud and white cloud icons](https://www.rramoscabral.com/training/assets/MSOneDrive/WindowsTaskbar.png)
    
    > Fonte da imagem: Microsoft

    (Pode ser necessário selecionar a seta Mostrar ícones ocultos O botão Mostrar ícones ocultos junto à área de notificação para que o ícone do OneDrive seja apresentado. Se o ícone não for apresentado na área de notificação, o OneDrive poderá não estar a ser executado. Selecione Iniciar, digite **OneDrive** na caixa de pesquisa e selecione **OneDrive** nos resultados da pesquisa.)

   ![Windows system tray with arrow indicating hidden icons](https://www.rramoscabral.com/training/assets/MSOneDrive/WindowsTaskbarShowHiddenIcons.png)
   
   > Fonte da imagem: Microsoft


1. Selecione **Dwfinições (Settings)** [OneDrive Help and Settings icon](https://www.rramoscabral.com/training/assets/MSOneDrive/IconSettings.png) **Ajuda e definições (Help & Settings)** > **Definições (Settings)**.


1. Para ver uma lista de todos os seus sites sincronizados, selecione o separador Conta.

    ![Screenshot of account settings in the OneDrive sync client.](https://www.rramoscabral.com/training/assets/MSOneDrive/AccountTab.png)
    > Fonte da imagem: Microsoft

1. Para alterar as pastas que está a sincronizar, selecione **Escolher pastas (Choose folders)** para essa biblioteca e selecione as pastas que pretende sincronizar. Para interromper a sincronização de um site, selecione **Parar sincronização (Stop sync)** junto ao site. (As cópias dos ficheiros permanecem no seu computador. Pode eliminá-los se desejar.)


<br/>

<a id="add-shortcut-to-onedrive" />

<br/>

## Adicionar atalho ao OneDrive

Quando alguém partilha uma pasta no Microsoft OneDrive, SharePoint ou Teams, pode adicionar um atalho à pasta partilhada no OneDrive para encontrar e trabalhar facilmente com os ficheiros. Estes atalhos aparecem no OneDrive na Web, no Windows File Explorer, no Mac Finder, no Teams e nas aplicações móveis do OneDrive.

Um administrador global da Microsoft ou um administrador do SharePoint pode desativar **Adicionar atalho ao OneDrive (Add shortcut to OneDrive)**.

1. No OneDrive, no painel de navegação, selecione **Partilhado (Shared)** > **Partilhado comigo (Shared with me)**.

1. Encontre a pasta que pretende adicionar e clique no círculo no bloco da pasta para a selecionar.

1. Selecione Adicionar atalho aos Meus ficheiros..

    ![SharePoint Document Library add shortcut to OneDrive](https://www.rramoscabral.com/training/assets/MSSharePoint/DocumentLibraryAddShortcuToOneDrive.png)

    - Ou pode clicar com o botão direito do rato na pasta e selecionar Adicionar atalho aos **Meus ficheiros (My files)**.

    - Numa biblioteca partilhada no SharePoint ou no Microsoft Teams, pode selecionar Adicionar atalho aos Meus Ficheiros para adicionar um atalho a toda a biblioteca ou selecionar a pasta específica que pretende adicionar e, em seguida, selecionar Adicionar atalho aos **Meus ficheiros (My files)**.

<br/>

### Mover um atalho para uma pasta partilhada

Pode mover um atalho para uma pasta como qualquer outro ficheiro ou pasta.

> **Nota:** Ao mover um atalho de uma pasta para uma pasta partilhada, o atalho não altera as suas permissões de partilha. As pessoas que atualmente não têm acesso ao atalho não poderão aceder ao seu conteúdo, mas poderão renomear ou remover o atalho.



1.Selecione o atalho que pretende mover. Para tal, na vista de lista, marque o círculo que aparece à esquerda do item quando passa o ponteiro sobre ele. Na vista Blocos ou Foto, verifique o círculo no canto superior direito do bloco ao passar o ponteiro sobre o mesmo. Também pode selecionar vários itens para os mover juntos, como um grupo.

1. Na navegação superior, selecione **Mover para (Move to)**.

1. No painel Mover para, navegue até à pasta de destino e selecione **Mover (Move)**.

    - Se pretender criar uma nova pasta para guardar o item, selecione **Nova pasta (New folder)**.

    > **Dica:*** Em vez de utilizar o botão **Mover para (Move to)** , pode selecionar o atalho que pretende mover e arrastá-lo para a pasta de destino.

<br/>

### Encontre pastas partilhadas no seu OneDrive

As pastas partilhadas que adicionou ao OneDrive aparecem no site do OneDrive na vista **Os meus ficheiros (My files)** .

Num PC com Windows, encontre a pasta OneDrive com o nome da sua organização no Windows Explorer. Por exemplo, **OneDrive - Contoso**. Num computador Mac, utilize o Finder para localizar a pasta OneDrive.


> **Notas:** Se tiver a aplicação de sincronização do OneDrive, mas a pasta partilhada não sincronizar com o seu computador, a sincronização seletiva pode estar ativada. Isto não é comum, mas para corrigir, encontre o ícone da cloud OneDrive na área de notificação do Windows (se usar um Mac, vá à barra de menus).


1. Selecione o ícone da nuvem OneDrive.
1. Selecione **Ajuda e definiçõe (Help & Settings)** > **Definições (Settings)**.
1. No separador **Conta (Account)** selecione **Escolher pastas (Choose folders)** e marque as caixas das pastas que pretende sincronizar.
<br/>

### Mover ficheiros e pastas partilhadas no seu OneDrive

Quando move ficheiros entre pastas partilhadas, estes perdem as permissões existentes e obtêm as permissões da pasta para a qual os moveu. Por exemplo, se mover um item para uma pasta de leitura apenas, o item também se tornará de leitura apenas. Mover um item de uma pasta partilhada para uma pasta não partilhada significa que esse item deixará de ser partilhado com ninguém. Se mover itens apenas dentro de uma pasta partilhada, não haverá qualquer alteração em nenhuma das permissões atribuídas.

Embora possa mover ficheiros partilhados, não é possível mover pastas partilhadas no OneDrive.com. Se sincronizar o OneDrive com o seu computador, qualquer pasta partilhada movida será copiada para o local de destino e removida do OneDrive. Ainda está disponível na sua lista partilhada.

Pode renomear pastas partilhadas adicionadas ao OneDrive. O novo nome dado à pasta só será visível para si e aparecerá com esse nome em qualquer lugar onde aceda ao OneDrive, incluindo o OneDrive.com, a aplicação OneDrive no seu computador ou as aplicações móveis do OneDrive. A alteração do nome não será visível para o proprietário da pasta partilhada nem para qualquer outra pessoa com permissão para aceder à pasta.

> **Nota:** No entanto, renomear ou alterar qualquer conteúdo da pasta é visível para outras pessoas que partilhem a pasta.


<br/>

### Remover ou eliminar ficheiros e pastas partilhadas do seu OneDrive


Os ficheiros eliminados de uma pasta partilhada no OneDrive.com são enviados para a reciclagem apenas do proprietário da pasta partilhada. No entanto, se sincronizar o OneDrive num computador, os itens eliminados de uma pasta partilhada aparecerão na reciclagem do computador.

> **Nota:** Apenas o proprietário de uma pasta partilhada pode restaurar um item eliminado da pasta.

Para remover uma pasta partilhada no OneDrive.com:

1. Na vista **Os meus ficheiros (My files)**, selecione a pasta partilhada que pretende remover.

1. Selecione **Remover atalho (Remove shortcut)**.
    
    - Isto apenas remove a pasta do seu OneDrive. Pode ainda ser acedida na sua lista partilhada e não afeta o proprietário ou qualquer outra pessoa que partilhe a pasta. Se eliminar a pasta, esta será eliminada do OneDrive de todos e o proprietário da pasta terá de a restaurar.

    > **Nota:** Se sincronizar o OneDrive com um ou mais computadores, a remoção de uma pasta partilhada do OneDrive também a removerá desses computadores.

Se uma pasta já não for partilhada consigo, será removida do OneDrive. Para recuperar o acesso à pasta, peça ao proprietário ou ao editor para a partilhar consigo novamente.

