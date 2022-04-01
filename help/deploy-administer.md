---
title: Administrar e gerenciar usuários
description: Casos de uso de administração, como implantação e gerenciamento de usuários no [!DNL Assets Essentials].
role: Admin
exl-id: ef91126f-3aee-442b-b242-a6bf4034f3dc
source-git-commit: fb4ca5b3ab85f77cc1013c2d4743530f5d48e96d
workflow-type: tm+mt
source-wordcount: '1129'
ht-degree: 88%

---

# Administrar [!DNL Assets Essentials] e adicionar usuários {#administer}

O [!DNL Adobe Experience Manager Assets Essentials] é provisionado pela Adobe para seus clientes. Como parte do provisionamento, o [!DNL Assets Essentials] é adicionado à organização de um cliente no [!DNL Adobe Admin Console]. Os administradores usarão [!DNL Admin Console] para gerenciar direitos de usuário para [!DNL Assets Essentials] e atribuir administradores de aplicativos para configurar permissões e formulários de metadados no [!DNL Assets Essentials].

## Implantação automática do Assets Essentials {#automatic-deployment-assets-essentials}

Depois que a solução Assets Essentials é provisionada, o administrador recebe um email da Adobe. O email contém uma mensagem de boas-vindas e um link para começar a trabalhar. Além disso, a Adobe inicia o processo de implantação do Assets Essentials automaticamente. Esse processo leva uma hora para ser concluído.

No link do email, acesse e faça logon no [Admin Console](https://adminconsole.adobe.com). Se você tiver acesso de administrador a mais de uma conta da organização, selecione a organização apropriada ou alterne para ela usando o botão na barra superior. Quando o processo de implantação automática é concluído, o cartão de produto do [!DNL AEM Assets Essentials] fica visível no [!DNL Admin Console].

![Implantação do Assets Essentials](assets/assets-essentials-deployment.png)

Após a implantação bem-sucedida da solução Assets Essentials, os administradores precisam executar as seguintes tarefas:

* [Configurar grupos de usuários, estrutura de pastas e atribuir permissões](manage-permissions.md) para a solução. Seguir [práticas recomendadas](permission-management-best-practices.md) para garantir uma configuração de permissões simples e eficaz.
* [Gerenciar o acesso de usuário](#add-users-to-essentials) ao [!DNL Assets Essentials] de membros da organização.
* Ou, opcionalmente, [visualizar o status e os logs do serviço](#view-logs).

>[!NOTE]
>
>Se o Assets Essentials for provisionado antes de 06 de janeiro de 2022, execute as [etapas de implantação no Cloud Manager](#deploy-essentials) antes de gerenciar o acesso de usuário dos membros da organização.


## Gerenciamento de usuários {#add-users-to-essentials}

Um administrador gerencia quais usuários tem acesso ao [!DNL Assets Essentials]. Os administradores usam o [!DNL Adobe Admin Console] para adicionar ou remover o acesso do usuário. O [!DNL Assets Essentials] tem dois tipos de acesso de usuário disponíveis, os quais são descritos a seguir.

* **[!DNL Assets Essentials]Administradores** ter acesso administrativo ao aplicativo. Além de todos os recursos do usuário final, os administradores de aplicativos neste grupo podem gerenciar permissões para qualquer pasta e grupo/usuário em todo o repositório de aplicativos.
* Usuários do **[!DNL Assets Essentials]** têm acesso à interface completa. Esses usuários podem fazer upload, organizar, marcar e encontrar ativos digitais.
* Usuários consumidores do **[!DNL Assets Essentials]**: têm acesso à experiência de seleção de ativos incorporada no editor de modelo de email do [!DNL Adobe Journey Optimizer]. Para obter mais informações, consulte [Usar o [!DNL Assets Essentials] no [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html?lang=pt-BR).

Em [!DNL Admin Console], esses três tipos de acesso são representados por três [!UICONTROL Perfis de produto]. Para adicionar e remover membros de sua organização em qualquer um dos perfis, siga estas etapas:

1. Acesse o [!DNL Admin Console] da sua organização, clique em **[!UICONTROL Produtos]** na barra superior, clique em **[!UICONTROL AEM Assets Essentials]** e, em seguida, clique no ambiente [!DNL Assets Essentials]. [!DNL Assets Essentials] O tem três perfis de produto que representam o acesso de usuários administradores, regulares e consumidores.

   ![Três perfis para três tipos de usuários](assets/admin-console-admin-profile.png)
   <!-- Need to update screenshot to include 3 profiles -->

   *Figura: Três perfis estão disponíveis para adicionar os três tipos de usuários.*

1. Para adicionar um usuário a um grupo, clique no grupo, selecione **[!UICONTROL Adicionar usuário]**, forneça os detalhes do usuário e clique em **[!UICONTROL Salvar]**. Ao adicionar um usuário, ele recebe um convite por email para começar. Você pode desativar os convites por email nas configurações do perfil de produto no [!DNL Admin Console].

   ![Adicionar um usuário ao [!DNL Assets Essentials]](assets/adminconsole-add-user.png)

   *Figura: adicionar um usuário ao [!DNL Assets Essentials] no [!DNL Admin Console].*

1. Para remover um usuário de um grupo, clique no grupo, selecione um usuário existente e selecione **[!UICONTROL Remover usuário]**.

>[!TIP]
>
>No [!DNL Admin Console], é possível gerenciar os usuários em massa usando arquivos CSV. Para saber mais, consulte a [[!DNL Admin Console] documentação](https://helpx.adobe.com/br/enterprise/using/accounts.html).

## Visualizar o status do serviço e os logs de acesso {#view-logs}

Após o provisionamento, os administradores implantam o [!DNL Assets Essentials] apenas uma vez. Após a implantação inicial, a Adobe faz a manutenção e as atualizações do serviço. Os administradores podem usar a interface do [!DNL Cloud Manager] para verificar o status do serviço e baixar os logs de acesso recentes.

1. Quando os usuários relatarem problemas, verifique o status do serviço do [!DNL Assets Essentials] na interface da **[!UICONTROL Visão geral do programa]**. Durante o funcionamento normal da solução, o status é `Running`. Se o [!DNL Cloud Manager] exibir qualquer outro status, crie um tíquete de suporte na seção de suporte do [!DNL Admin Console].

   ![O status do [!DNL Assets Essentials] no [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Figura: O status normal do [!DNL Assets Essentials] no [!DNL Cloud Manager] é `Running`.*

1. Para baixar os logs de acesso recentes, clique no ![ícone de opções](assets/do-not-localize/options-ellipses-icon.png), selecione **[!UICONTROL Baixar logs]** e siga as instruções na tela. É possível auditar as solicitações de acesso HTTPS usando os logs.

   ![ Opção para baixar os logs de acesso](assets/cloudmanager-download-logs.png)

   *Figura: Opção para baixar os logs de acesso.*

## Implantar [!DNL Assets Essentials] {#deploy-essentials}

>[!NOTE]
>
>Execute essas etapas somente se o Assets Essentials tiver sido provisionado antes de 6 de janeiro de 2022.

Após o provisionamento, o direito ao [!DNL Assets Essentials] é adicionado à sua organização no [!DNL Admin Console]. Antes que a solução esteja disponível para o usuário, um administrador da organização deve implantá-la. O administrador faz uma implantação única usando a interface do usuário do [!DNL Cloud Manager]. Após a implantação inicial, a Adobe faz a manutenção e as atualizações do serviço. Depois que a solução for provisionada, o administrador receberá um email da Adobe. O email contém uma mensagem de boas-vindas e um link para começar a trabalhar. Para implantação, siga estas etapas:

1. No link do email, acesse e faça logon no [Admin Console](https://adminconsole.adobe.com). Se você tiver acesso de administrador a mais de uma conta da organização, selecione a organização apropriada ou alterne para ela usando o botão na barra superior. O cartão do produto do [!DNL Assets Essentials] estará visível no [!DNL Admin Console].

   Cartão do ![[!DNL Assets Essentials] no [!DNL Admin Console]](assets/essentials-in-admin-console.png)

   *Figura: Cartão do [!DNL Assets Essentials] no [!DNL Admin Console].*

   >[!NOTE]
   >
   >Se você conseguir visualizar o cartão do **[!UICONTROL AEM Assets Essentials]** na seção de produtos em vez do cartão do **[!UICONTROL AEM Assets Essentials - Cloud Manager]**, a implantação do Assets Essentials já está concluída. Você pode pular as etapas restantes.

1. Adicione a si mesmo como administrador ao perfil do produto `AEM Assets Essentials - Cloud Manager` no [!DNL Admin Console]. Em vez de adicionar a si mesmo, também é possível adicionar outro membro de sua organização ou adicionar mais de um administrador.

1. Clique no ![ícone de adicionar](assets/do-not-localize/add-icon.svg) para [!UICONTROL Selecionar perfis de produto], e selecione [!UICONTROL Gerenciador de implantação - Assets Essentials] como **[!UICONTROL perfil do produto]**. O usuário adicionado nesta etapa recebe um email da Adobe com acesso ao [!DNL Cloud Manager] e pode fazer a implantação.

   ![Adicionar um administrador e selecionar um perfil de produto no [!DNL Admin Console]](assets/adminconsole-user1.png)

   *Figura: Adicionar um administrador e selecionar um perfil de produto no [!DNL Admin Console].*

1. Para acessar o [!DNL Cloud Manager], clique no link do email com acesso ao [!DNL Cloud Manager]. Como alternativa, acesse [https://experience.adobe.com/#/cloud-manager/](https://experience.adobe.com/#/cloud-manager/) no seu navegador.

1. Na interface do Cloud Manager, clique em **[!UICONTROL Adicionar programa]** no canto superior direito.

1. Forneça um nome de sua escolha; opcionalmente, faça upload de uma imagem (ela representa o programa em [!DNL Cloud Manager]); em seguida, clique em **[!UICONTROL Criar]**. O [!DNL Cloud Manager] leva alguns minutos para configurar o programa.

1. Quando o programa estiver pronto, passe o mouse sobre o bloco e clique em ![ícone de adicionar ambiente](assets/do-not-localize/add-environment-icon.png).

1. Para adicionar o serviço do [!DNL Assets Essentials] à sua organização, clique em **[!UICONTROL Adicionar ambiente]**, selecione um nome e uma região de implantação e clique em **[!UICONTROL Salvar]**. Não é possível alterar a região de implantação posteriormente. Tente selecionar uma região de implantação para o [!DNL Assets Essentials] que corresponda à região de implantação da outra solução com a qual você pretende usar o [!DNL Assets Essentials]. A correspondência é para garantir aos ativos digitais o acesso mais rápido possível à rede e a menor latência possível.

   ![Adicionar um ambiente no [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

   *Figura: Adicionar um ambiente no [!DNL Cloud Manager] para começar a usar o [!DNL Assets Essentials].*

1. Após vários minutos, quando o ambiente tiver sido criado com êxito, você poderá acessar o [!DNL Admin Console] e adicionar os usuários da organização à solução [!DNL Assets Essentials]. Clique em ![ícone de opções](assets/do-not-localize/options-ellipses-icon.png) e selecione a opção **[!UICONTROL Gerenciar acesso]**.

   ![Ambiente pronto no [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Figura: Um ambiente no [!DNL Cloud Manager] pronto para uso.*

>[!MORELIKETHIS]
>
>* Ajuda com o [[!DNL Admin Console] ](https://helpx.adobe.com/br/enterprise/using/admin-console.html)
>* Ajuda com o [[!DNL Cloud Manager] ](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=pt-BR)
>* [Documentação do Adobe Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=pt-BR)
>* [Notas de versão](release-notes.md)
>* [Introdução ao uso do [!DNL Assets Essentials]](get-started.md)

