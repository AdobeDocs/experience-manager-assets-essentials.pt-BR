---
title: Organize seus ativos digitais
description: Mover, excluir, copiar, renomear, atualizar e criar versões de seus ativos no [!DNL Assets Essentials].
role: User,Leader
contentOwner: AG
exl-id: b01e98b9-0cc2-47c5-9f5b-79b8e6bef39f
source-git-commit: cd7af0c946a042430e62528fa6aa19bdab139f67
workflow-type: tm+mt
source-wordcount: '614'
ht-degree: 100%

---

# Gerenciar ativos {#manage-assets}

É possível realizar várias tarefas de gerenciamento de ativos digitais (DAM) facilmente usando a interface amigável do [!DNL Assets Essentials]. Após adicionar os ativos, é possível pesquisar, baixar, mover, copiar, renomear, excluir, atualizar e editar seus ativos.

Use o [!DNL Assets Essentials] para realizar as seguintes tarefas de gerenciamento de ativos. Quando você seleciona um ativo, as seguintes opções são exibidas na barra de ferramentas na parte superior.

![Opções da barra de ferramentas ao selecionar um ativo](assets/toolbar-image-selected.png)

*Figura: Opções disponíveis na barra de ferramentas para uma imagem selecionada.*

* ![ícone de desmarcar](assets/do-not-localize/close-icon.png) Desmarcar a seleção.
* ![ícone de detalhes](assets/do-not-localize/edit-in-icon.png) Clique para visualizar um ativo e exibir os metadados detalhados. Ao visualizar, você pode exibir as versões e editar uma imagem.
* ![ícone de download](assets/do-not-localize/download-icon.png) Baixar o ativo selecionado para o sistema de arquivos local.
* ![ícone de excluir](assets/do-not-localize/delete-icon.png) Excluir o ativo ou a pasta selecionada.
* ![ícone de check-out](assets/do-not-localize/checkout-icon.png) Fazer check-out do ativo selecionado.
* ![ícone de copiar](assets/do-not-localize/copy-icon.png) Copiar o arquivo ou pasta selecionada.
* ![ícone de mover](assets/do-not-localize/move-icon.png) Mover o ativo ou pasta selecionada para um local diferente na hierarquia do repositório.
* ![ícone de renomear](assets/do-not-localize/rename-icon.png) Renomear o ativo ou a pasta selecionada. Use um nome exclusivo, caso contrário, a renomeação falhará com um aviso. Você pode tentar novamente com um novo nome.
* ![ícone de atribuir tarefa](assets/do-not-localize/review-delegate-icon.png) Atribuir tarefas a outros usuários para colaborar em um ativo.

É possível exibir as mesmas opções nas miniaturas de ativos.

![Opções na miniatura de ativos para gerenciar um ativo](assets/options-on-thumbnail.png)

O [!DNL Assets Essentials] exibe somente as opções relevantes na barra de ferramentas que dependem do tipo do ativo selecionado.

![Opções da barra de ferramentas ao selecionar um ativo](assets/toolbar-folder-selected.png)

*Figura: Opções disponíveis na barra de ferramentas para uma pasta selecionada.*

![Opções da barra de ferramentas ao selecionar um ativo](assets/toolbar-pdf-selected.png)

*Figura: Opções disponíveis na barra de ferramentas para um arquivo PDF selecionado.*

## Baixar e distribuir ativos {#download}

É possível selecionar um ou mais ativos ou pastas, ou uma combinação dos dois, e baixar os selecionados para o sistema de arquivos local. É possível editar os ativos e carregá-los novamente ou distribuí-los fora do [!DNL Assets Essentials]. Além disso, é possível [baixar as representações](/help/add-delete.md#renditions) de um ativo.

## Controle de versão de ativos {#versions-of-assets}

<!-- 
TBD: query for engineering: How many versions are maintained. What happens when we reach that limit? Are old versions automatically removed? -->

O [!DNL Assets Essentials] realiza o controle de versão dos ativos quando eles são carregados novamente, após serem atualizados ou editados. Você pode visualizar o histórico de versões e a lista de versões antigas para restaurar uma versão antiga dos ativos como a versão mais recente, que pode então ser revertida para a versão anterior, se necessário. As versões de ativos são criadas nos seguintes cenários:

* Fazer upload de um novo ativo com o mesmo nome de arquivo de um ativo existente e para a mesma pasta de um ativo existente. O [!DNL Assets Essentials] fornece a opção de substituir o ativo anterior ou de salvar o novo ativo como uma versão. Consulte [fazer upload de ativos duplicados](/help/add-delete.md#resolve-upload-fails).

   ![Criar versões ao fazer uploads](assets/uploads-manage-duplicates.png)

   *Figura: Ao fazer upload de um ativo com o mesmo nome de um ativo existente, você pode criar uma versão do ativo.*

* Edite uma imagem e clique em **[!UICONTROL Salvar como versão]**. Consulte [editar imagens](/help/edit-images.md).

   ![Salvar imagem editada como uma versão](assets/edit-image2.png)

   *Figura: Salvar a imagem editada como uma versão.*

* Abra as versões de um ativo existente. Clique em **[!UICONTROL Nova versão]** e faça upload de uma versão mais recente do ativo para o repositório.

   ![Opção de fazer upload de uma nova versão de um ativo do histórico de versões](assets/view-asset-versions2.png)

### Exibir versões de um ativo {#view-versions}

Ao fazer upload de uma cópia duplicada ou modificada de um ativo, você pode criar suas versões. O controle de versão permite revisar ativos históricos e reverter para uma versão anterior, caso necessário.

Para exibir as versões, abra a pré-visualização de um ativo e clique em **[!UICONTROL Versões]** ![Ícone Versões](assets/do-not-localize/versions-clock-icon.png) na barra lateral direita. Para visualizar uma versão específica, selecione-a. Para reverter para ela, clique em **[!UICONTROL Tornar a mais recente]**.

Você também pode criar versões na linha do tempo de versões. Selecione a versão mais recente, clique em **[!UICONTROL Nova versão]** e faça upload de uma nova cópia do ativo a partir do sistema de arquivos local.

![Visualizar versões de um ativo](assets/view-asset-versions1.png)

*Figura: visualizar versões de um ativo, reverter para uma versão anterior ou fazer upload de outra nova versão.*
