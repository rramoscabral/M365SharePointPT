---
layout: default
title: 'Power Automate'
nav_order: 9
has_children: true
---

# Power Automate
{: .no_toc }


## Índice
{: .no_toc .text-delta }

1. TOC
{:toc}

<br/>

---

## Power Automate para Microsoft 365

![Imagem quebrada](https://www.rramoscabral.com/training/assets/logos/MSPowerAutomate.png) 

O Power Automate é um serviço de fluxo de trabalho online (online workflow em inglês) que permite criar uma sequência de ações para automatizar tarefas.

Para utilizar o Power Automate, só precisa de um navegador Web e uma conta do Microsoft 365 com a licença ativa.

Pode ser utilizado numa grande variedade de dispositivos e navegadores. 
- Para os navegadores, utilize a versão mais atualizada compatível com o seu sistema operativo: Microsoft Edge, Safari, Chrome ou Firefox. A aplicação Power Automate para ambiente de trabalho também está disponível para os sistemas operativos Windows 10 e 11.
- Para obter os melhores resultados num dispositivo móvel, utilize a aplicação móvel Power Automate para iOS, Android e Windows. 


Exemplos de tarefas que pode automatizar com Power Automate:
- Responder instantaneamente a emails ou notificações de alta prioridade.
- Capturar, rastrear e acompanhar as novas vendas potenciais.
- Copiar todos os anexos de email para sua conta do OneDrive for Business.
- Obter dados sobre sua empresa e compartilhar essas informações com a equipe.
- Automatizar fluxos de trabalho de aprovação.


Pode aceder ao Power Automate de duas maneiras:
- Versão atual: `https://make.powerautomate.com/`.
- Versão com funcionalidades em desenvolvimento ativas:`https://make.preview.powerautomate.com/`.

<br/>

## Fluxo de automação

Um fluxo de automação tem a seguinte regra:
1.	Contem sempre um **gatilho (trigger)** ou acionador é ação inicial do fluxo. Não é permitido ter mais do que um gatilho. 
1.	Um ou mais **ações (actions)** que são as operações que o fluxo ira realizar após o gatilho ser invocado.


A seguinte figura representa um fluxo do Power Automate em que cada vez que recebe um e-mail obtém dados do perfil do Microsoft 365 e vai criar um output de dados personalizado com a informação do e-mail e da pessoa na organização que envio ou e-mail.

![Imagem quebrada](https://www.rramoscabral.com/training/assets/MSPowerAutomate/MSPowerAutomateFlow.png)

- O gatilho é **When a new email arrives**.
- As ações sequenciais é **Get my profile** e a seguir **Compose**.

A ação **compose** só é executada se a ação anterior **Get my profile** for executada com sucesso.


A combinação de gatilhos e ações permite criar automações personalizadas e eficientes para as necessidades específicas.

<br/>


### Gatilho (trigger)

É um evento que inicia um fluxo de cloud e o Power Automate tem várias maneiras de poder ser executado.

| Tipo de fluxo | Descrição |
| :---: | --- | 
| Instantâneos/manuais  | Executado manualmente ou através de toque de um botão no seu dispositivo móvel. |
| Programados           | Executado num horário definido. Pode escolher quando (data e hora) e frequência (mensal/diária/por hora, e muito mais). |
| Automatizados         | Executado após a ocorrência de um evento. Por exemplo ao receber um e-mail pode criar um fluxo que obtenha dados do e-mail recebido. |

<br/>

### Ações (actions)

As ações são as operações específicas num fluxo que é uma tarefa individual como obter informação, enviar um e-mail, criar um item numa lista do SharePoint, entre outras.

<br/>

## Modelos do Power Automate

Os modelos são fluxos pré-construídos para cenários populares e comuns. A Microsoft e a comunidade de Power Automate disponibilizam imensos modelos (templates) prontos a trabalhar e podem ser adaptados as suas necessidades.

Para utilizar um, basta ter acesso aos serviços do modelo e introduzir as definições necessárias.

Pode aceder aos modelos na sua conta de Power Automate ao selecionar a opção **Templates** ou no seguinte endereço `https://make.powerautomate.com/templates/` e pesquisar pelo nome do produto que pretende ligar ou obter dados como por exemplo **SharePoint**.


![Imagem quebrada](https://www.rramoscabral.com/training/assets/MSPowerAutomate/MSPowerAutomateTemplates.png) 



<br/>

## Perguntas Frequentes (FAQ's)

- Quantos fluxos posso ter?
    * O número depende do tipo de licença que tive. O Power Automate oferece uma grande flexibilidade em termos de licenciamento e preços para abranger uma vasta gama de casos de utilização. Contacte o seu administrador para obter detalhes sobre a sua licença atual ou consulte os detalhes do preço.

- Posso partilhar os fluxos que crio?
    * Sim. Pode adicionar colegas de trabalho ou grupos da sua organização como proprietários para que possam editar e gerir os fluxos. Ou, para fluxos que podem ser executados manualmente, pode conceder a outras pessoas ou grupos da sua organização permissão para os executar.

- O Power Automate está disponível no local?
    * Não, o Power Automate é um serviço na nuvem. No entanto, pode ligar-se de forma segura aos seus próprios serviços no local através do seu gateway de dados no local.
