---
layout: default
title: 'Restrições e limitações do SharePoint'
nav_order: 6.2
has_children: false
parent: 'OneDrive'
---

# Restrições e limitações do SharePoin
{: .no_toc }


## Índice
{: .no_toc .text-delta }

1. TOC
{:toc}

<br/>

---


## Limitações de nomes e tipos de ficheiros no SharePoint e no OneDrive

Restrições e limitações que se aplicam a ficheiros, nomes de ficheiros e tipos de ficheiros ao sincronizar com o OneDrive de casa, o OneDrive empresarial ou de estudante ou o SharePoint no Microsoft 365.

> **Notas:** A 1 de maio de 2023: Carateres inválidos atualizados e nomes de ficheiros e pastas inválidos


| Restrições | Detalhes |
|---|---|
| Caracteres inválidos | ``` " * : < > ? / \ | ```|
| Nomes de ficheiros ou pastas inválidos | ```.lock, CON, PRN, AUX, NUL, COM1 - COM9, LPT1 - LPT9, vti, desktop.ini, qualquer nome de ficheiro começando por ~$. ```|
| Tipos de ficheiro inválidos ou bloqueados | A lista de ficheiros bloqueados varia de acordo com as definições da organização. |
| Unidades de rede ou mapeadas | O OneDrive não suporta links simbólicos em que o Link e o Destino estão localizados no mesmo local da biblioteca. |
| Unidades de rede ou mapeadas | O OneDrive não suporta links simbólicos em que o Link e o Destino estão localizados no mesmo local da biblioteca. |
| Privilégios elevados | O OneDrive não pode ser executado com privilégios elevados. |
| Partilhou comigo | Não pode sincronizar o agrupamento de visualização Partilhado Comigo de ficheiros de um site corporativo ou de estudante (antes do OneDrive for Business). |
| Contas de convidados | Atualmente, a sincronização de conteúdos utilizando um utilizador externo ou convidado não é compatível com o OneDrive.
| Proxies autenticados | Os proxies autenticados não são suportados no OneDrive. |
| Blocos de notas do OneNote | Os blocos de notas do OneNote têm o seu próprio mecanismo de sincronização fora do OneDrive. |





<a id="limitations-of-path-lengths-in-sharepoint-and-onedrive" />

<br/>

## Limitations of path lengths in SharePoint and OneDrive

Diferentes aplicações e versões do Office têm limites diferentes, e a combinação de limitações pode ser exclusiva da sua configuração.

Todo o caminho do ficheiro descodificado, incluindo o nome do ficheiro, **não pode conter mais de 400 caracteres** para o OneDrive, OneDrive empresarial ou de estudante e SharePoint no Microsoft 365. O limite aplica-se à **combinação do caminho da pasta e do nome do ficheiro** após a descodificação.



Por exemplo:
- Se o URL do ficheiro no SharePoint for `https://www.contoso.com/sites/marketing/documents/Shared%20Documents/Promotion/Some%20File.xlsx`, o limite aplica-se a `sites/marketing/documents/Shared Documents/Promotion/Some File.xlsx`.
- Da mesma forma, se o URL do ficheiro no OneDrive for `https://contoso-my.sharepoint.com/personal/meganb_contoso%20_com/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fmeganb%5Fcontoso%5Fcom%2FDocuments%2FContracts%2FVendor%20Quotations/Some%20File.xlsx`, o limite aplica-se a `personal/meganb_contoso_com/Documents/Contracts/Vendor Quotations/Some File.xlsx`.



Além do acima referido, se os ficheiros forem sincronizados com um PC ou Mac, serão aplicadas as seguintes limitações:
- Cada segmento do caminho (um segmento é um nome de ficheiro ou pasta como **Promoção** ou **Algum ficheiro.xlsx** nos exemplos acima) não pode ter mais de 255 caracteres devido a limitações do sistema operativo.
- O comprimento da pasta raiz do OneDrive (por exemplo, `C:\users\meganb\OneDrive - Contoso`) + o caminho relativo do ficheiro (até 400 caracteres) **não pode ter mais de 520 caracteres**.
- O nome da organização pode ser atualizado no centro de administração do M365, mas tal não será propagado para as relações de sincronização existentes (apenas para as relações recém-estabelecidas). Para que as relações existentes do Sync tenham o novo nome da organização, os utilizadores precisam de desvincular e voltar a ligar as suas contas.


<br/>

<a id="limitations-of-file-upload-and-download-sizes-in-sharepoint-and-onedrive" />

<br/>

## Limitações de tamanhos de upload e download de ficheiros no SharePoint e no OneDrive

Restrições e limitações para os tamanhos de upload e download de ficheiros.


| Máximo | Upload | Download |
| --- | :---: | :---:| 
| Sincronizar | 250GB | 250GB |
| Ficheiros individuais| 250GB | 250GB | 
| Ficheiros dentro de ficheiro comprimido no formato zip | 20GB | 20GB| 

> **Nota:** em 3 de março de 2021, o tamanho máximo de carregamento de ficheiros foi atualizado para 250 GB.



### Limite de versões do SharePoint Server

As versões do SharePoint Server suportam apenas até 260 caracteres para comprimentos de ficheiro e caminho

**A versão mais antiga do Office tem um limite inferior**

| Application | Limit |
| :---: | --- |
| Word 2002       | O comprimento total do caminho e do nome do ficheiro, incluindo a extensão do nome do ficheiro, excede os 255 caracteres.|
| PowerPoint 2002 | O comprimento total do caminho e do nome do ficheiro, incluindo a extensão do nome do ficheiro, excede os 256 caracteres..|
| Access 2002     | O comprimento total do caminho e do nome do ficheiro, incluindo a extensão do nome do ficheiro, excede os 249 caracteres.|
| Excel 2002      | O comprimento total do caminho e do nome do ficheiro, incluindo a extensão do nome do ficheiro, excede os 218 caracteres.|
| Outlook 2002    | O comprimento total do caminho e do nome do ficheiro, incluindo a extensão do nome do ficheiro, excede os 255 caracteres.|

> **Nota:** Esta limitação inclui três caracteres que representam a unidade, os caracteres nos nomes das pastas, a barra invertida entre pastas e os caracteres no nome do ficheiro.



<br/>

<a id="file-upload-and-download-sizes-in-sharepoint-and-onedrive" />

<br/>

## Limitações de partilha no SharePoint e no OneDrive

Existe um limite de 50.000 itens (atualizado a 12 de abril de 2021) que podem ser partilhados numa pasta e em quaisquer subpastas.

There is a limit of 50,000 items (updated on 12 April 2021) that can be shared within a folder and any sub-folders.

Para ultrapassar esta restrição, mova alguns itens para outra pasta que não esteja na pasta original ou escolha ficheiros individuais para partilhar.

Poderá receber a seguinte mensagem de erro **Não pode partilhar este item porque já foram partilhados muitos itens nesta biblioteca (You can’t share this item because too many items have already been shared in this library)** ao tentar partilhar mais de 50.000 itens.

Não pode sincronizar o agrupamento de ficheiros do modo de visualização Partilhado comigo a partir de um site OneDrive empresarial ou de estudante.

Poderá receber a seguinte mensagem de erro **A entrega falhou para estes destinatários ou grupos erro ao partilhar ao tentar partilhar (Delivery has failed to these recipients or groups error when sharing)** para um endereço que não está associado a uma conta Microsoft.


<br/>

<a id="switch-between-classic-and-modern-lists-and-libraries" />

<br/>

## Alternar entre listas e bibliotecas clássicas e modernas

Para alternar entre visualizações clássicas e modernas de listas e bibliotecas.

1. Na experiência moderna para uma lista ou biblioteca de documentos, selecione Definições Ícone de definições Ícone de definições ![Settings icon](https://www.rramoscabral.com/training/assets/MSSharePoint/IconSettings.png), em seguida, selecione **Definições de lista (List settings)** ou **Definições de biblioteca (Library settings)**.
1. Na experiência clássica, as **Definições de lista (List settings)** ou **Definições de biblioteca (Library settings)** existem na faixa de opções (ribbon).
1. No final da lista de definições, selecione Definições avançadas e selecione **Listar experiência (List experienc)**.
1. Selecione uma das três opções e, para guardar, selecione **OK**.



