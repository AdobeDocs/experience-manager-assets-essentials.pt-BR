---
title: Gerenciar seus ativos digitais
description: Mova, exclua, copie, renomeie, atualize e faça a versão de seus ativos em [!DNL Assets Essentials].
role: User,Leader
contentOwner: AG
source-git-commit: 5bae37e18ac587aaacaa004e5ec02775888d7f9a
workflow-type: tm+mt
source-wordcount: '585'
ht-degree: 0%

---


# Gerenciar ativos {#manage-assets}

Você pode realizar várias tarefas de gerenciamento de ativos digitais (DAM) facilmente usando a interface amigável de [!DNL Assets Essentials]. Após adicionar os ativos, você pode pesquisar, baixar, mover, copiar, renomear, excluir, atualizar e editar seus ativos.

Use [!DNL Assets Essentials] para realizar as seguintes tarefas de gerenciamento de ativos. Quando você seleciona um ativo, as seguintes opções são exibidas na barra de ferramentas na parte superior.

![Opções da barra de ferramentas ao selecionar um ativo](assets/toolbar-image-selected.png)

*Figura: Opções disponíveis na barra de ferramentas para uma imagem selecionada.*

* ![desmarcar ](assets/do-not-localize/close-icon.png) íconeDesmarque a seleção.
* ![ícone de detalhes ](assets/do-not-localize/edit-in-icon.png) Clique em para visualizar um ativo e visualizar os metadados detalhados. Ao visualizar, você pode exibir as versões e editar uma imagem.
* ![ícone ](assets/do-not-localize/download-icon.png) de downloadBaixe o ativo selecionado no seu sistema de arquivos local.
* ![ícone excluir ](assets/do-not-localize/delete-icon.png) Excluir o ativo ou a pasta selecionada.
* 

   <!-- ![checkout icon](assets/do-not-localize/checkout-icon.png) --> Checkout an asset.
* ![ícone copiar ](assets/do-not-localize/copy-icon.png) Copie o arquivo ou a pasta selecionada.
* ![ícone mover ](assets/do-not-localize/move-icon.png) o ativo ou a pasta selecionada para um local diferente na hierarquia do repositório.
* ![ícone ](assets/do-not-localize/rename-icon.png) renomearRenomeie o ativo ou a pasta selecionada. Use um nome exclusivo, caso contrário, a renomeação falhará com um aviso. Você pode tentar novamente com um novo nome.
* 
   <!-- ![assign task icon](assets/do-not-localize/assign-task-icon.png) --> Assign tasks to other users to collaborate on an asset.

É possível exibir as mesmas opções nas miniaturas de ativos.

![Opções na miniatura de ativos para gerenciar um ativo](assets/options-on-thumbnail.png)

[!DNL Assets Essentials] exibe somente as opções relevantes na barra de ferramentas que dependem do tipo do ativo selecionado.

![Opções da barra de ferramentas ao selecionar um ativo](assets/toolbar-folder-selected.png)

*Figura: Opções disponíveis na barra de ferramentas para uma pasta selecionada.*

![Opções da barra de ferramentas ao selecionar um ativo](assets/toolbar-pdf-selected.png)

*Figura: Opções disponíveis na barra de ferramentas para um arquivo PDF selecionado.*

## Baixar e distribuir ativos {#download}

Você pode selecionar um ou mais ativos ou pastas ou uma combinação dos dois e baixar a seleção para o sistema de arquivos local. Você pode editar os ativos e fazer upload novamente ou distribuir os ativos fora de [!DNL Assets Essentials]. Você também pode [baixar as representações](/help/add-delete.md#renditions) de um ativo.

## Controle de versão de ativos {#versions-of-assets}

<!-- 
TBD: query for engineering: How many versions are maintained. What happens when we reach that limit? Are old versions automatically removed? -->

[!DNL Assets Essentials] versões dos ativos quando os ativos são carregados novamente e são atualizados ou editados. Você pode visualizar o histórico de versões, versões anteriores e restaurar uma versão anterior dos ativos como a versão mais recente, que é revertida para uma versão anterior, se necessário. As versões de ativos são criadas nos seguintes cenários:

* Faça upload de um novo ativo com o mesmo nome de arquivo de um ativo existente e na mesma pasta do ativo existente. [!DNL Assets Essentials] O solicita a substituição do ativo anterior ou o salvamento do novo ativo como uma versão. Consulte [fazer upload de ativos duplicados](/help/add-delete.md#resolve-upload-fails).

   ![Criar versões ao carregar](assets/uploads-manage-duplicates.png)

   *Figura: Ao fazer upload de um ativo chamado o mesmo que um ativo existente, você pode criar uma versão do ativo.*

* Edite uma imagem e clique em **[!UICONTROL Save as Version]**. Consulte [editar imagens](/help/edit-images.md).

   ![Salvar imagem editada como versão](assets/edit-image2.png)

   *Figura: Salve a imagem editada como uma versão.*

* Abra as versões de um ativo existente. Clique em **[!UICONTROL New Version]** e faça upload de uma versão mais recente do ativo no repositório.

   ![Opção para carregar uma nova versão de um ativo do histórico de versões](assets/view-asset-versions2.png)

### Exibir versões de um ativo {#view-versions}

Ao carregar uma cópia duplicada ou uma cópia modificada de um ativo, você pode criar suas versões. O controle de versão permite revisar ativos históricos e reverter para uma versão anterior, se necessário.

Para exibir versões, abra a visualização de um ativo e clique no ícone **[!UICONTROL Versions]** ![Versões](assets/do-not-localize/versions-clock-icon.png) na barra lateral direita. Para visualizar uma versão específica, selecione-a. Para reverter para ele, clique em **[!UICONTROL Make Latest]**.

Você também pode criar versões na linha do tempo das versões. Selecione a versão mais recente, clique em **[!UICONTROL New Version]** e faça upload de uma nova cópia do ativo de seu sistema de arquivos local.

![Exibir versões de um ativo](assets/view-asset-versions1.png)

*Figura: Exibir versões de um ativo, reverter para uma versão anterior ou fazer upload de outra nova versão.*
