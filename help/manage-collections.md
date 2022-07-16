---
title: Gerenciar coleções
description: Uma coleção é um conjunto de ativos no Experience Manager Assets Essentials. Use coleções para compartilhar ativos entre usuários.
exl-id: 33c889f5-c989-4772-9591-db62f50e5c80
source-git-commit: f273e1e3c8a290e0beee0423da00c63013062c43
workflow-type: tm+mt
source-wordcount: '686'
ht-degree: 76%

---

# Gerenciar coleções {#manage-collections}

Uma coleção é um conjunto de ativos no Experience Manager Assets Essentials. Use coleções para compartilhar ativos entre usuários.

Diferente de pastas, uma coleção pode incluir ativos de locais diferentes.

<!--
You can share collections with various users that are assigned different levels of privileges, including viewing, editing, and so on.
-->

Você pode compartilhar várias coleções com um usuário. Cada coleção contém referências a ativos. A integridade referencial dos ativos é mantida entre as coleções.

![Coleções](assets/collections.png)

Você pode executar as seguintes tarefas para gerenciar e usar coleções:

* [Criar uma coleção](#create-collection)

* [Adicionar ativos a uma coleção](#add-assets-to-collection)

* [Remover ativos de uma coleção](#remove-assets-from-collection)

* [Exibir e editar metadados da coleção](#view-edit-collection-metadata)

* [Baixar uma coleção](#download-collection)

* [Excluir uma coleção](#delete-collection)

## Criar uma coleção {#create-collection}

Para criar uma coleção:

1. Clique em **[!UICONTROL Coleções]** no painel à esquerda, e clique em **[!UICONTROL Criar coleção]**.

1. Especifique um título e uma descrição opcional para a coleção.

1. Selecione se precisar criar uma coleção Privada ou uma coleção Pública. Uma coleção Pública está disponível para exibição e edição para todos os usuários. No entanto, uma coleção Privada está disponível para o criador e os usuários com privilégios de administrador.

1. Clique em **[!UICONTROL Salvar]** para criar a coleção.

![Criar coleção](assets/create-collection.png)

<!--
   
   for viewing and editing only to users with the appropriate [permissions](#manage-collection-access).

-->

## Adicionar ativos a uma coleção {#add-assets-to-collection}

Para adicionar ativos a uma coleção:

1. Clique em **[!UICONTROL Ativos]** no painel à esquerda e selecione o(s) ativo(s).

1. Clique em **[!UICONTROL Adicionar à coleção]**.

1. Na caixa de diálogos [!UICONTROL Coleções], selecione as coleções às quais adicionar os ativos selecionados.

1. Clique em **[!UICONTROL Adicionar]** para adicionar o ativo às coleções selecionadas.

Para adicionar ativos à coleção, você também pode clicar em **[!UICONTROL Coleções]** no painel à esquerda. Depois clique na coleção à qual adicionar ativos, clique em **[!UICONTROL Adicionar à coleção]**, selecione o(s) ativo(s) e clique em **[!UICONTROL Selecionar]**.

## Criar uma coleção inteligente {#create-smart-collection}

Salve os resultados da pesquisa como uma coleção inteligente para atualizar dinamicamente o conteúdo da coleção. Se houver ativos adicionados ao repositório do Assets Essentials que se encaixem nos critérios de pesquisa definidos ao criar a coleção inteligente, o conteúdo da coleção inteligente será atualizado automaticamente.

Para criar uma coleção inteligente:

1. Clique em **[!UICONTROL Filtro]** e [definir os critérios de pesquisa](search.md##refine-search-results).

1. Clique em **[!UICONTROL Salvar como]** e depois selecione **[!UICONTROL Coleção inteligente]**.

1. No [!UICONTROL Criar coleção inteligente] , especifique um título e uma descrição para a coleção inteligente.

1. Selecionar **[!UICONTROL Coleção pública]** se você precisar que todos os usuários acessem a coleção. Selecionar **[!UICONTROL Coleção privada]** se você precisar de um grupo limitado de usuários para acessar a coleção.

1. Clique em **[!UICONTROL Criar]** para criar a coleção inteligente.

![Criar coleção inteligente](assets/create-smart-collection.png)


## Remover ativos de uma coleção {#remove-assets-from-collection}

Para remover ativos de uma coleção:

1. Clique em **[!UICONTROL Coleções]** no painel à esquerda para exibir a lista de coleções.

1. Clique na coleção e selecione o(s) ativo(s) que precisa(m) ser removido(s) da coleção.

1. Clique em **[!UICONTROL Remover]**.

<!--

## Manage access to a Private collection {#manage-collection-access}

The permission management for collections function in the same manner as folders in [!DNL Assets Essentials]. Administrators can manage the access levels for collections available in the repository. As an administrator, you can create user groups and assign permissions to those groups to manage access levels. You can also delegate the permission management privileges to user groups at the collection-level.

For more information, see [Manage permissions for folders and collections](manage-permissions.md).

-->

<!--

## Search a collection {#search-collections}

Click **[!UICONTROL Collections]** in the left rail and use the Search box to specify a text as the criteria to search for a collection. [!DNL Assets Essentials] uses the specified text to search collection names, metadata including tags defined for a collection and returns appropriate results.

>[!NOTE]
>
>Assets Essentials performs search in collections available at the root level. It does not perform search in assets and folders available in collections.

-->

## Exibir e editar metadados da coleção {#view-edit-collection-metadata}

Os metadados da coleção incluem dados sobre a coleção, como título e descrição.

Para exibir e editar metadados da coleção:

1. Clique em **[!UICONTROL Coleções]** no painel à esquerda, selecione uma coleção e clique em **[!UICONTROL Detalhes]**.
1. Visualize os metadados da coleção usando a guia **[!UICONTROL Básico]**.
1. Modifique os campos de metadados, conforme necessário. Você pode modificar o [!UICONTROL Título], a [!UICONTROL Descrição] e os campos do [!UICONTROL Autor].

![Metadados de coleção](assets/collection-metadata.png)

## Compartilhar links para coleções {#share-collection-links}

O [!DNL Assets Essentials] permite gerar um link e compartilhar coleções e ativos dentro de coleções com participantes externos, que não têm acesso ao aplicativo [!DNL Assets Essentials]. Você pode definir uma data de expiração para o link e, em seguida, compartilhá-la com outras pessoas usando o método de comunicação preferido, como email ou serviços de mensagens. Os recipients do link podem visualizar ativos e baixá-los.

![Compartilhar link para ativos](assets/share-link-collections.png)

Para mais informações sobre como compartilhar links de coleção com participantes externos, consulte [Compartilhar links para ativos](share-links-for-assets.md).

## Baixar uma coleção {#download-collection}

Para baixar uma coleção:

1. Clique em **[!UICONTROL Coleções]** no painel à esquerda.

1. Selecione a coleção que você precisa baixar e clique em **[!UICONTROL Baixar]**.

1. Na caixa de diálogo [!UICONTROL Baixar ativo], clique em **[!UICONTROL OK]**.

A coleção é baixada como um arquivo .ZIP no computador local.

## Excluir uma coleção {#delete-collection}

Para excluir uma coleção:

1. Clique em **[!UICONTROL Coleções]** no painel à esquerda.

1. Selecione a coleção que precisa ser excluída.

1. Clique em **[!UICONTROL Excluir]**.

## Próximas etapas {#next-steps}

* Forneça feedback sobre o produto usando a opção de [!UICONTROL Feedback] disponível na interface do Assets Essentials

* Forneça feedback sobre a documentação usando as opções [!UICONTROL Editar esta página] ![editar a página](assets/do-not-localize/edit-page.png) ou [!UICONTROL Registrar um problema] ![criar um problema do GitHub](assets/do-not-localize/github-issue.png) disponíveis na barra lateral direita

* Entre em contato com o [Atendimento ao cliente](https://experienceleague.adobe.com/?support-solution=General&amp;lang=pt-BR#support)
