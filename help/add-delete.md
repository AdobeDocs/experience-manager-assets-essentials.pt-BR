---
title: Fazer upload de ativos no repositório
description: Fazer upload de ativos para [!DNL Assets Essentials], exiba os status de upload e resolva os problemas de upload.
role: User
exl-id: a85a4455-4456-48af-aee9-f05300677605
source-git-commit: cd7af0c946a042430e62528fa6aa19bdab139f67
workflow-type: tm+mt
source-wordcount: '747'
ht-degree: 0%

---

# Fazer upload de ativos {#add-assets}

Para adicionar novos ativos para trabalhar, faça upload de alguns ativos do seu sistema de arquivos local. <!-- TBD: Many of the [common file formats are supported](/help/supported-file-formats.md). -->

Você pode usar os seguintes métodos para carregar um ou mais ativos ou uma pasta contendo ativos:

* Arraste ativos ou pastas na interface do usuário e siga as instruções na tela.
* Clique em **[!UICONTROL Adicionar ativos]** na barra de ferramentas e adicione alguns arquivos à caixa de diálogo de upload.

<!-- TBD: Update this GIF
![Asset and nested folder upload demo](assets/do-not-localize/upload-assets.gif) -->

Você pode usar qualquer um desses métodos para fazer upload de ativos após criar uma pasta. Para criar uma pasta vazia, clique em **[!UICONTROL Criar pasta]** na barra de ferramentas. Ao [!DNL Assets Essentials] O oferece uma funcionalidade de pesquisa de texto completo e eficiente, e você também pode usar pastas para organizar melhor seus ativos.

Depois de selecionar os arquivos, você obtém uma caixa de diálogo de confirmação para adicionar mais arquivos ou remover arquivos já selecionados. Para adicionar mais arquivos a uma seleção, clique em **[!UICONTROL Procurar]** e selecione **[!UICONTROL Procurar arquivos]** ou **[!UICONTROL Procurar pastas]**. Adicione mais arquivos ou pastas da mesma pasta ou de uma diferente.

Depois que todos os arquivos forem enfileirados, clique em **[!UICONTROL Upload]**.

![Upload de arquivos e pastas](assets/upload-browse-files-folders.png)

*Figura: Antes de fazer upload dos ativos selecionados, é possível adicionar ou remover ativos da fila.*

>[!CAUTION]
>
>Use ativos que não têm espaço em branco nos nomes de arquivos. As respostas aos comentários não funcionam para esses ativos.

## Exibir o progresso e o status do upload {#upload-progress}

Ao fazer upload de muitos ativos ou pastas aninhadas para [!DNL Assets Essentials], alguns ativos podem deixar de ser carregados por vários motivos, como problemas duplicados de ativos e de rede.

Para rastrear o progresso do upload, clique em **[!UICONTROL Andamento do upload]** na barra de ferramentas. Um painel exibe o progresso do upload de todos os ativos.

Para exibir um subconjunto de ativos com base no progresso ou status do upload, use o filtro na **[!UICONTROL Andamento do upload]** barra lateral. Os vários filtros são exibir todos os ativos, uploads concluídos, uploads em andamento, ativos em fila a serem carregados, uploads pausados, ativos duplicados e ativos que não foram carregados.

![Filtrar o progresso do upload com base no status do upload](assets/filter-upload-progress.png)

*Figura: Filtre os ativos que você tentou fazer upload com base no status de upload ou no progresso do upload.*

Imediatamente após o upload dos ativos, [!DNL Assets Essentials] processa os ativos para gerar miniaturas e processar metadados. Para muitos ativos, o processamento leva algum tempo. Se não vir uma miniatura e vir uma mensagem de processamento na miniatura do espaço reservado, verifique a pasta novamente após alguns minutos. Durante o processamento, entre outras coisas, [!DNL Assets Essentials] gera as representações, adiciona tags inteligentes e indexa os detalhes do ativo para pesquisa.

![Os ativos são processos após o upload e o bloco exibe o processamento](assets/upload-processing.png)

*Figura: Os ativos carregados exibem o processamento no bloco que são processados.*

## Representações de ativos {#renditions}

[!DNL Assets Essentials] processa os ativos carregados em tempo quase real e, para muitos tipos de arquivos compatíveis, gera representações. Criadas para imagens, as representações são versões redimensionadas da imagem carregada. Você pode baixar não apenas o ativo, mas também as representações para usar uma versão apropriada. É possível exibir todas as representações de um ativo ao [visualizar um ativo](/help/navigate-view.md#preview-assets).

![Representações](assets/renditions-view-download.png)

*Figura: Exiba e baixe as representações.*

## Gerenciar uploads com falha {#resolve-upload-fails}

Se o upload de um ativo suportado falhar por algum motivo, clique em **[!UICONTROL Tentar novamente]** do [!UICONTROL Andamento do upload] painel.

![Tentar novamente um upload com falha](assets/upload-retry.png)

*Figura: Tente novamente se um arquivo suportado não for carregado por algum motivo.*

Se você tentar fazer upload de ativos duplicados, os ativos não serão carregados até que você confirme explicitamente o upload. No início, os ativos duplicados são marcados como uploads com falha. Para resolver, basta criar uma versão, excluir e substituir os ativos existentes ou criar uma cópia duplicada renomeando o ativo. Você pode resolver essas falhas um ativo de cada vez ou fazer isso em massa para todas as duplicatas com falha de uma só vez.

![Gerenciar ativos duplicados, um de cada vez](assets/uploads-manage-duplicates.png)

*Figura: Para ativos duplicados que não são carregados por padrão, resolva o problema um ativo de cada vez.*

![Gerenciar todos os uploads com falha em massa](assets/upload-progress-manage-failed-uploads.png)

*Figura: Para ativos duplicados que não são carregados por padrão, resolva os problemas para todos os ativos de uma só vez.*

>[!TIP]
>
>Você pode fazer upload de ativos para o repositório DAM diretamente de dentro de seu [!DNL Creative Cloud] aplicativos de desktop. Veja como [[!DNL Assets Essentials] integra-se ao [!DNL Adobe Asset Link]](/help/integration.md).

## Excluir ativos ou pastas {#delete-assets}

Os usuários podem excluir ativos ou pastas individuais que não são mais necessários. Para excluir um ativo ou uma pasta, siga um destes procedimentos:

* Use a opção disponível na miniatura de um ativo ou de uma pasta.

   ![Opções na miniatura de ativos para gerenciar um ativo](assets/options-on-thumbnail.png)

   *Figura: As ações para arquivos e pastas estão disponíveis no ativo ou no bloco de pastas.*

* Selecione um ativo ou uma pasta e clique em **[!UICONTROL Excluir]** ![ícone excluir](assets/do-not-localize/delete-icon.png) na barra de ferramentas.
