---
title: Integrar o Assets Essentials ao Adobe Workfront
description: Integre o Assets Essentials ao aplicativo do Adobe Workfront para poder acessar o repositório do Assets Essentials no aplicativo do Workfront.
exl-id: 47c2963d-57f0-463e-8d5b-5e5af9928f77
source-git-commit: 1bb5f1aa1bb03b38964f13f40dc2d2d675a0480f
workflow-type: ht
source-wordcount: '634'
ht-degree: 100%

---

# Integrar o Assets Essentials ao Adobe Workfront {#integrate-assets-essentials-workfront}

![Preferência para alternar entre temas escuro e claro](assets/cce-workfront.png)

## A história até agora

Depois de [configurar o Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) e [integrar os aplicativos da Creative Cloud ao Assets Essentials](integrate-assets-essentials-creative-cloud.md), é possível integrar o aplicativo do Adobe Workfront ao Assets Essentials.

## Objetivo

* **Público-alvo**: administradores do Adobe Workfront

* **Objetivo**: integrar o Assets Essentials ao aplicativo do Adobe Workfront para poder acessar o repositório do Assets Essentials no aplicativo do Workfront.

## Visão geral

[[!DNL Adobe Workfront]](https://www.workfront.com/) é um aplicativo de gerenciamento de trabalho que ajuda você a gerenciar todo o ciclo de vida do trabalho em um único local. A integração nativa entre o [!DNL Adobe Workfront] e o [!DNL Assets Essentials] permite que as organizações melhorem a velocidade do conteúdo e o prazo para comercialização, conectando intrinsecamente o gerenciamento de trabalho e de ativos. No contexto do gerenciamento de trabalho, os usuários têm acesso aos documentos e imagens necessários na mesma solução.

Execute as seguintes tarefas para integrar o Workfront ao Experience Manager Assets Essentials:

* [Adicionar usuários aos perfis de produto do Workfront](#add-users-to-product-profiles)

* [Adicionar usuários aos perfis de produto do Assets Essentials](#add-workfront-users-assets-essentials-product-profiles)

* [Configure a integração do Experience Manager Assets Essentials](#configure-assets-essentials-integration)

## Adicionar usuários aos perfis de produto do Workfront {#add-users-to-product-profiles}

Para adicionar usuários aos perfis de produto do Workfront:

1. Acesse o [Admin Console](https://adminconsole.adobe.com) da sua organização, clique em **[!UICONTROL Produtos]** na barra superior, selecione **[!UICONTROL Workfront]** e clique na primeira instância da lista. Não clique na segunda nem na terceira instância da lista.

   ![Perfil de administrador do Admin Console](assets/workfront-instances.png)

   O Admin Console exibe o único perfil de produto disponível.

1. Para adicionar um usuário a um perfil de produto, clique no perfil, selecione **[!UICONTROL Adicionar usuário]**, forneça os detalhes do usuário e clique em **[!UICONTROL Salvar]**.

   ![Adicionar perfil de administrador de usuários](assets/add-users-workfront.png)

   Ao adicionar um usuário, ele recebe um convite por email para começar. Você pode desativar os convites por email nas configurações do perfil de produto no [!DNL Admin Console].

1. Para remover um usuário de um grupo, clique no grupo, selecione um usuário existente e selecione **[!UICONTROL Remover usuário]**.

Para obter mais informações sobre como criar usuários e administradores de sistema no Workfront com o Adobe Admin Console, consulte [Gerenciar usuários no Adobe Admin Console](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FAdministration_and_Setup%2FAdd_users%2FCreate_and_manage_users%2Fadmin-console.htm&amp;_LANG=enus).

## Adicionar usuários aos perfis de produto do Assets Essentials {#add-workfront-users-assets-essentials-product-profiles}

Atribua os usuários do Workfront a um dos seguintes perfis de produto do Assets Essentials:

* Usuários do **[!DNL Assets Essentials]** têm acesso à interface completa do Assets Essentials. Esses usuários podem fazer upload, organizar, marcar e encontrar ativos digitais no aplicativo do Assets Essentials. Além disso, os usuários têm acesso à experiência de seleção de ativos incorporada no aplicativo do [!DNL Adobe Workfront].
* Usuários consumidores do **[!DNL Assets Essentials]**: têm acesso à experiência de seleção de ativos incorporada no aplicativo do [!DNL Adobe Workfront].

Além disso, também há o perfil de produto de Administradores do **[!DNL Assets Essentials]** que fornece acesso administrativo ao aplicativo.

Para obter mais informações sobre como atribuir usuários a perfis de produtos do Assets Essentials, consulte [Atribuir usuários a perfis de produto do Assets Essentials](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Configure a integração do Experience Manager Assets Essentials {#configure-assets-essentials-integration}

Depois de adicionar usuários aos perfis de produto do Workfront e do Assets Essentials usando o Admin Console, você pode [configurar a integração do Experience Manager Assets Essentials com o Adobe Workfront](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2F_workfront-for-aem-asset-essentials.htm).

Após configurar a integração, é possível:

* [Vincular ativos e pastas do Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Flink-to-aem.htm&amp;_LANG=enus)

* [Enviar um documento para o Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fsend-to-aem.htm&amp;_LANG=enus)

* [Criar uma prova de um ativo vinculado do Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fproof-linked-asset-aem.htm)

* [Exibir ou baixar um ativo vinculado do Experience Manager Assets Essentials](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fview-download-asset.htm)
