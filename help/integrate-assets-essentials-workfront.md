---
title: Integrar o Assets Essentials ao Adobe Workfront
description: Integre o Assets Essentials ao aplicativo Adobe Workfront para que você possa acessar o repositório Assets Essentials no aplicativo Workfront.
exl-id: 47c2963d-57f0-463e-8d5b-5e5af9928f77
source-git-commit: 1bb5f1aa1bb03b38964f13f40dc2d2d675a0480f
workflow-type: tm+mt
source-wordcount: '634'
ht-degree: 16%

---

# Integrar o Assets Essentials ao Adobe Workfront {#integrate-assets-essentials-workfront}

![Preferência para alternar entre temas escuro e claro](assets/cce-workfront.png)

## A história até agora

Depois [configuração do Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) e [integração de aplicativos Creative Cloud com Assets Essentials](integrate-assets-essentials-creative-cloud.md), é possível integrar o aplicativo Adobe Workfront com o Assets Essentials.

## Objetivo

* **Público**: Administradores do Adobe Workfront

* **Objetivo**: Integre o Assets Essentials ao aplicativo Adobe Workfront para que você possa acessar o repositório Assets Essentials no aplicativo Workfront.

## Visão geral

[[!DNL Adobe Workfront]](https://www.workfront.com/) é um aplicativo de gerenciamento de trabalho que ajuda você a gerenciar todo o ciclo de vida do trabalho em um único local. A integração nativa entre [!DNL Adobe Workfront] e [!DNL Assets Essentials] permite que as organizações melhorem a velocidade do conteúdo e o tempo de comercialização ao conectar intrinsecamente o trabalho e o gerenciamento de ativos. No contexto do gerenciamento de trabalho, os usuários têm acesso aos documentos e imagens necessários na mesma solução.

Execute as seguintes tarefas para integrar o Workfront com o Experience Manager Assets Essentials:

* [Adicionar usuários aos perfis de produto do Workfront](#add-users-to-product-profiles)

* [Adicionar usuários aos perfis de produto do Assets Essentials](#add-workfront-users-assets-essentials-product-profiles)

* [Configurar a integração do Experience Manager Assets Essentials](#configure-assets-essentials-integration)

## Adicionar usuários aos perfis de produto do Workfront {#add-users-to-product-profiles}

Para adicionar usuários aos perfis de produto do Workfront:

1. Acesso [Admin Console](https://adminconsole.adobe.com) para sua organização, clique em **[!UICONTROL Produtos]** na barra superior, clique em **[!UICONTROL Workfront]** e clique na primeira instância da lista. Não clique na segunda e terceira instâncias da lista.

   ![Perfil de administrador do Admin Console](assets/workfront-instances.png)

   O Admin Console exibe o único perfil de produto disponível.

1. Para adicionar um usuário a um perfil de produto, clique no perfil, em **[!UICONTROL Adicionar usuário]**, forneça os detalhes do usuário e clique em **[!UICONTROL Salvar]**.

   ![Adicionar perfil de administrador de usuários](assets/add-users-workfront.png)

   Ao adicionar um usuário, ele recebe um convite por email para começar. Você pode desativar os convites por email nas configurações do perfil de produto no [!DNL Admin Console].

1. Para remover um usuário de um grupo, clique no grupo, selecione um usuário existente e selecione **[!UICONTROL Remover usuário]**.

Para obter mais informações sobre como criar usuários e administradores de sistema no Workfront com o Adobe Admin Console, consulte [Gerenciar usuários no Adobe Admin Console](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FAdministration_and_Setup%2FAdd_users%2FCreate_and_manage_users%2Fadmin-console.htm&amp;_LANG=enus).

## Adicionar usuários aos perfis de produto do Assets Essentials {#add-workfront-users-assets-essentials-product-profiles}

Atribua os usuários do Workfront a um dos seguintes perfis de produto do Assets Essentials:

* **[!DNL Assets Essentials]Usuários** Ter acesso à interface completa do usuário do Assets Essentials. Esses usuários podem fazer upload, organizar, marcar e encontrar ativos digitais no aplicativo Assets Essentials. Além disso, os usuários têm acesso à experiência de seleção de ativos incorporados no [!DNL Adobe Workfront] aplicativo.
* **[!DNL Assets Essentials]Usuários do consumidor**: têm acesso à experiência de seleção de ativos incorporados no [!DNL Adobe Workfront] aplicativo.

Além disso, também há **[!DNL Assets Essentials]Administradores** perfil de produto que fornece acesso administrativo ao aplicativo.

Para obter mais informações sobre como atribuir usuários a perfis de produtos do Assets Essentials, consulte [Atribuir usuários a perfis de produto do Assets Essentials](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Configurar a integração do Experience Manager Assets Essentials {#configure-assets-essentials-integration}

Depois de adicionar usuários aos perfis de produto do Workfront e Assets Essentials usando o Admin Console, você pode [configurar a integração do Experience Manager Assets Essentials com o Adobe Workfront](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2F_workfront-for-aem-asset-essentials.htm).

Após configurar a integração, é possível:

* [Vincular ativos e pastas do Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Flink-to-aem.htm&amp;_LANG=enus)

* [Enviar um documento para o Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fsend-to-aem.htm&amp;_LANG=enus)

* [Prova de um ativo vinculado ao Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fproof-linked-asset-aem.htm)

* [Exibir ou baixar um ativo vinculado do Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fview-download-asset.htm)
