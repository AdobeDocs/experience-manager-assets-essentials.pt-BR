---
title: Administrar e gerenciar usuários
description: Casos de uso da administração, como implantação e gerenciamento de usuários em [!DNL Assets Essentials].
role: Admin
exl-id: ef91126f-3aee-442b-b242-a6bf4034f3dc
source-git-commit: fb4ca5b3ab85f77cc1013c2d4743530f5d48e96d
workflow-type: tm+mt
source-wordcount: '1129'
ht-degree: 1%

---

# Administrar [!DNL Assets Essentials] e adicionar usuários {#administer}

[!DNL Adobe Experience Manager Assets Essentials] é provisionada pela Adobe para seus clientes. Como parte do provisionamento, [!DNL Assets Essentials] é adicionado à organização de um cliente em [!DNL Adobe Admin Console]. Os administradores usarão [!DNL Admin Console] para gerenciar direitos de usuário para [!DNL Assets Essentials] e atribuir administradores de aplicativos para configurar permissões e formulários de metadados no [!DNL Assets Essentials].

## Implantação automática do Assets Essentials {#automatic-deployment-assets-essentials}

Depois que a solução Assets Essentials for provisionada, o administrador receberá um email do Adobe. O email contém uma mensagem de boas-vindas e um link para começar. Além disso, o Adobe inicia o processo para implantar o Assets Essentials automaticamente. O processo de implantação leva uma hora para ser concluído.

No link do email, acesse e faça logon no [Admin Console](https://adminconsole.adobe.com). Se você tiver acesso de administrador a mais de uma conta da organização, selecione a organização apropriada ou alterne para ela usando o alternador na barra superior. Quando o processo de implantação automática estiver concluído, o cartão do produto para [!DNL AEM Assets Essentials] é visível no [!DNL Admin Console].

![Implantação do Assets Essentials](assets/assets-essentials-deployment.png)

Os administradores precisam executar as seguintes tarefas após a implantação bem-sucedida da solução Assets Essentials:

* [Configurar grupos de usuários, estrutura de pastas e atribuir permissões](manage-permissions.md) para a solução. Seguir [práticas recomendadas](permission-management-best-practices.md) para garantir uma configuração de permissões simples e eficaz.
* [Gerenciar o acesso do usuário](#add-users-to-essentials) de membros da organização [!DNL Assets Essentials].
* Opcionalmente, [exibir status e logs do serviço](#view-logs).

>[!NOTE]
>
>Se o Assets Essentials for provisionado antes de 06 de janeiro de 2022, execute o [etapas de implantação no Cloud Manager](#deploy-essentials) antes de gerenciar o acesso do usuário dos membros da organização.


## Gerenciamento de usuários {#add-users-to-essentials}

Um administrador gerencia a quais usuários tem acesso [!DNL Assets Essentials]. Os administradores usam [!DNL Adobe Admin Console] para adicionar ou remover o acesso do usuário. [!DNL Assets Essentials] O tem os dois tipos de acesso de usuário a seguir disponíveis.

* **[!DNL Assets Essentials]Administradores** ter acesso administrativo ao aplicativo. Além de todos os recursos do usuário final, os administradores de aplicativos neste grupo podem gerenciar permissões para qualquer pasta e grupo/usuário em todo o repositório de aplicativos.
* **[!DNL Assets Essentials]Usuários** têm acesso à interface do usuário completa. Esses usuários podem fazer upload, organizar, marcar e encontrar ativos digitais.
* **[!DNL Assets Essentials]Usuários do consumidor**: têm acesso à experiência de seleção de ativos incorporados no [!DNL Adobe Journey Optimizer] editor de modelo de email. Para obter mais informações, consulte [Use [!DNL Assets Essentials] em [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

Em [!DNL Admin Console], esses três tipos de acesso são representados por três [!UICONTROL Perfis de produto]. Para adicionar e remover membros de sua organização a qualquer um dos perfis, siga estas etapas:

1. Acesso [!DNL Admin Console] para sua organização, clique em **[!UICONTROL Produtos]** na barra superior, clique em **[!UICONTROL AEM Assets Essentials]** e, em seguida, clique em [!DNL Assets Essentials] ambiente. [!DNL Assets Essentials] O tem três perfis de produto que representam o acesso de usuários administradores, regulares e consumidores.

   ![Três perfis para três tipos de usuários](assets/admin-console-admin-profile.png)
   <!-- Need to update screenshot to include 3 profiles -->

   *Figura: Três perfis estão disponíveis para adicionar os três tipos de usuários.*

1. Para adicionar um usuário a um grupo, clique no grupo e selecione **[!UICONTROL Adicionar usuário]**, forneça os detalhes do usuário e clique em **[!UICONTROL Salvar]**. Quando você adiciona um usuário, ele recebe um convite por email para começar. Você pode desativar os convites por email nas configurações do perfil de produto em [!DNL Admin Console].

   ![Adicionar um usuário a [!DNL Assets Essentials]](assets/adminconsole-add-user.png)

   *Figura: Adicionar um usuário a [!DNL Assets Essentials] from [!DNL Admin Console].*

1. Para remover um usuário de um grupo, clique no grupo, selecione um usuário existente e selecione **[!UICONTROL Remover usuário]**.

>[!TIP]
>
>Em [!DNL Admin Console], é possível gerenciar os usuários em massa usando arquivos CSV. Para saber mais, consulte [[!DNL Admin Console] documentação](https://helpx.adobe.com/enterprise/using/accounts.html).

## Exibir o status do serviço e os logs de acesso {#view-logs}

Após o provisionamento, os administradores implantam [!DNL Assets Essentials] só uma vez. Após a implantação inicial, o Adobe faz a manutenção e as atualizações do serviço. Os administradores podem usar o [!DNL Cloud Manager] interface do usuário para verificar o status do serviço e baixar os logs de acesso recentes.

1. Quando os usuários relatarem problemas, verifique o status do serviço de [!DNL Assets Essentials] no **[!UICONTROL Visão geral do programa]** interface. Durante o funcionamento normal da solução, o estado é `Running`. If [!DNL Cloud Manager] exibe qualquer outro status, crie um tíquete de suporte no [!DNL Admin Console] seção de suporte.

   ![O status de [!DNL Assets Essentials] em [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Figura: O status normal de [!DNL Assets Essentials] em [!DNL Cloud Manager] é `Running`.*

1. Para baixar os logs de acesso recentes, clique em ![ícone opções](assets/do-not-localize/options-ellipses-icon.png), selecione **[!UICONTROL Baixar logs]** e siga as instruções na tela. Você pode auditar as solicitações de acesso HTTPS usando os logs.

   ![ Opção para baixar os logs de acesso](assets/cloudmanager-download-logs.png)

   *Figura: Opção para baixar os logs de acesso.*

## Implantar [!DNL Assets Essentials] {#deploy-essentials}

>[!NOTE]
>
>Execute essas etapas somente se a Assets Essentials tiver sido provisionada antes de 6 de janeiro de 2022.

Após o provisionamento, [!DNL Assets Essentials] o direito é adicionado à organização em [!DNL Admin Console]. Antes que a solução esteja disponível para o usuário, um administrador da organização deve implantá-la. O administrador faz uma implantação única usando [!DNL Cloud Manager] interface do usuário. Após a implantação inicial, o Adobe faz a manutenção e as atualizações do serviço. Depois que a solução for provisionada, o administrador receberá um email do Adobe. O email contém uma mensagem de boas-vindas e um link para começar. Para implantar, siga estas etapas:

1. No link do email, acesse e faça logon no [Admin Console](https://adminconsole.adobe.com). Se você tiver acesso de administrador a mais de uma conta da organização, selecione a organização apropriada ou alterne para ela usando o alternador na barra superior. A placa de produto para [!DNL Assets Essentials] é visível no [!DNL Admin Console].

   ![[!DNL Assets Essentials] cartão em [!DNL Admin Console]](assets/essentials-in-admin-console.png)

   *Figura: [!DNL Assets Essentials] cartão em [!DNL Admin Console].*

   >[!NOTE]
   >
   >Se você puder exibir a variável **[!UICONTROL AEM Assets Essentials]** na seção produtos em vez de **[!UICONTROL AEM Assets Essentials - Cloud Manager]** , a implantação do Assets Essentials já está concluída. É possível ignorar as etapas restantes.

1. Adicione a si mesmo como administrador ao `AEM Assets Essentials - Cloud Manager` perfil de produto no [!DNL Admin Console]. Você pode adicionar outro membro de sua organização ou adicionar mais de um administrador.

1. Clique em ![ícone adicionar](assets/do-not-localize/add-icon.svg) para [!UICONTROL Selecionar perfis de produto]e selecione [!UICONTROL Gerenciador de implantação - Assets Essentials] como **[!UICONTROL perfil de produto]**. O usuário adicionado nesta etapa recebe um email do Adobe com acesso a [!DNL Cloud Manager] e podem fazer a implantação.

   ![Adicione um administrador e selecione um perfil de produto em [!DNL Admin Console]](assets/adminconsole-user1.png)

   *Figura: Adicione um administrador e selecione um perfil de produto em [!DNL Admin Console].*

1. Para acessar [!DNL Cloud Manager], clique no link do email com acesso a [!DNL Cloud Manager]. Como alternativa, acesse [https://experience.adobe.com/#/cloud-manager/](https://experience.adobe.com/#/cloud-manager/) no seu navegador.

1. Na interface do usuário do Cloud Manager, clique em **[!UICONTROL Adicionar programa]** no canto superior direito.

1. Forneça um nome de sua escolha e, opcionalmente, carregue uma imagem (ela representa o programa em [!DNL Cloud Manager]) e, em seguida, clique em **[!UICONTROL Criar]**. [!DNL Cloud Manager] leva alguns minutos para configurar o programa.

1. Quando o programa estiver pronto, passe o ponteiro do mouse sobre o bloco e clique em ![ícone adicionar ambiente](assets/do-not-localize/add-environment-icon.png).

1. Para adicionar [!DNL Assets Essentials] para sua organização, clique em **[!UICONTROL Adicionar ambiente]**, selecione um nome e uma região de implantação e clique em **[!UICONTROL Salvar]**. Não é possível alterar a região de implantação posteriormente. Tente corresponder à região de implantação de [!DNL Assets Essentials] com a região de implantação da outra solução com a qual você pretende usar [!DNL Assets Essentials]. A correspondência é garantir o acesso mais rápido possível à rede para ativos digitais e a menor latência possível.

   ![Adicionar um ambiente em [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

   *Figura: Adicionar um ambiente em [!DNL Cloud Manager] para começar a usar [!DNL Assets Essentials].*

1. Após vários minutos, quando o ambiente for criado com êxito, você poderá acessar a variável [!DNL Admin Console] e adicionar os usuários da organização a [!DNL Assets Essentials] solução. Clique em ![ícone opções](assets/do-not-localize/options-ellipses-icon.png) e selecione o **[!UICONTROL Gerenciar acesso]** opção.

   ![Ambiente pronto em [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Figura: Um ambiente em [!DNL Cloud Manager] que está pronto para uso.*

>[!MORELIKETHIS]
>
>* [[!DNL Admin Console] ajuda](https://helpx.adobe.com/enterprise/using/admin-console.html)
>* [[!DNL Cloud Manager] ajuda](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=pt-BR)
>* [Documentação do Adobe Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html)
>* [Notas de versão](release-notes.md)
>* [Introdução ao uso [!DNL Assets Essentials]](get-started.md)

