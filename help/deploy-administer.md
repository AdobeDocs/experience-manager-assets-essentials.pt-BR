---
title: Implantar e gerenciar usuários
description: Casos de uso da administração, como implantação e gerenciamento de usuários em [!DNL Assets Essentials].
role: Admin
source-git-commit: a1dc66213f602bce5b5a2ec0ba99084c7f7b1ee1
workflow-type: tm+mt
source-wordcount: '855'
ht-degree: 2%

---


# Implante [!DNL Assets Essentials] e adicione usuários {#administer}

[!DNL Adobe Experience Manager Assets Essentials] é provisionada pela Adobe para seus clientes. Como parte do provisionamento, [!DNL Assets Essentials] é adicionado à organização de um cliente em [!DNL Adobe Admin Console]. Os clientes também têm acesso a [!DNL Experience Manager Cloud Manager] como uma ferramenta de implantação e a [!DNL Admin Console] para gerenciar os direitos do usuário para a solução [!DNL Assets Essentials].

Os administradores executam as seguintes tarefas:

* [ [!DNL Assets Essentials]](#deploy-essentials) Implantar para a organização.
* [Gerencie o ](#add-users-to-essentials) acesso de usuários dos membros da organização ao  [!DNL Assets Essentials].
* Opcionalmente, [exibir o status do serviço e logs](#view-logs).

## Implantar [!DNL Assets Essentials] {#deploy-essentials}

Após o provisionamento, o direito [!DNL Assets Essentials] é adicionado à organização em [!DNL Admin Console]. Antes que a solução esteja disponível para o usuário, um administrador da organização deve implantá-la. O administrador faz uma implantação única usando a interface do usuário [!DNL Cloud Manager]. Após a implantação inicial, o Adobe faz a manutenção e as atualizações do serviço. Depois que a solução for provisionada, o administrador receberá um email do Adobe. O email contém uma mensagem de boas-vindas e um link para começar. Para implantar, siga estas etapas:

1. No link do email, acesse e faça logon em [Admin Console](https://adminconsole.adobe.com). Se você tiver acesso de administrador a mais de uma conta da organização, selecione a organização apropriada ou alterne para ela usando o alternador na barra superior. A placa de produto para [!DNL Assets Essentials] está visível no [!DNL Admin Console].

   ![[!DNL Assets Essentials] cartão em  [!DNL Admin Console]](assets/essentials-in-admin-console.png)

   *Figura:  [!DNL Assets Essentials] cartão em  [!DNL Admin Console].*

1. Adicione-se como administrador ao perfil de produto `AEM Assets Essentials - Cloud Manager` no [!DNL Admin Console]. Você pode adicionar outro membro de sua organização ou adicionar mais de um administrador.

1. Clique em ![adicionar ícone](assets/do-not-localize/add-icon.svg) a [!UICONTROL Select product profiles] e selecione [!UICONTROL Deployment Manager - Assets Essentials] como o **[!UICONTROL product profile]**. O usuário adicionado nesta etapa recebe um email do Adobe com acesso a [!DNL Cloud Manager] e pode fazer a implantação.

   ![Adicione um administrador e selecione um perfil de produto em  [!DNL Admin Console]](assets/adminconsole-user1.png)

   *Figura: Adicione um administrador e selecione um perfil de produto em  [!DNL Admin Console].*

1. Para acessar [!DNL Cloud Manager], clique no link no email com acesso a [!DNL Cloud Manager]. Como alternativa, acesse [https://experience.adobe.com/#/cloud-manager/](https://experience.adobe.com/#/cloud-manager/) em seu navegador.

1. Na interface do usuário do Cloud Manager, clique em **[!UICONTROL Add Program]** no canto superior direito.

1. Forneça um nome de sua escolha e, opcionalmente, carregue uma imagem (ela representa o programa em [!DNL Cloud Manager]) e clique em **[!UICONTROL Create]**. [!DNL Cloud Manager] leva alguns minutos para configurar o programa.

1. Quando o programa estiver pronto, passe o ponteiro do mouse sobre o bloco e clique em ![adicionar ícone do ambiente](assets/do-not-localize/add-environment-icon.png).

1. Para adicionar [!DNL Assets Essentials] serviço à organização, clique em **[!UICONTROL Add Environment]**, selecione um nome e uma região de implantação e clique em **[!UICONTROL Save]**. Não é possível alterar a região de implantação posteriormente. Tente corresponder a região de implantação de [!DNL Assets Essentials] com a região de implantação da outra solução com a qual você pretende usar [!DNL Assets Essentials]. A correspondência é garantir o acesso mais rápido possível à rede para ativos digitais e a menor latência possível.

   ![Adicionar um ambiente em  [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

   *Figura: Adicione um ambiente em  [!DNL Cloud Manager] para começar a usar o  [!DNL Assets Essentials].*

1. Após vários minutos, quando o ambiente for criado com êxito, você poderá acessar o [!DNL Admin Console] e adicionar os usuários de sua organização à solução [!DNL Assets Essentials]. Clique no ícone ![opções](assets/do-not-localize/options-ellipses-icon.png) e selecione a opção **[!UICONTROL Manage Access]**.

   ![Ambiente pronto em  [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Figura: Um ambiente no  [!DNL Cloud Manager] que está pronto para uso.*

## Gerenciamento de usuários {#add-users-to-essentials}

Um administrador gerencia quais usuários têm acesso a [!DNL Assets Essentials]. Os administradores usam [!DNL Adobe Admin Console] para adicionar ou remover o acesso do usuário. [!DNL Assets Essentials] O tem os dois tipos de acesso de usuário a seguir disponíveis.

* **[!DNL Assets Essentials]** O usuário deve ter acesso a toda a interface do usuário. Esses usuários podem fazer upload, organizar, marcar e encontrar ativos digitais.
* **[!DNL Assets Essentials]Usuários** do consumidor: tenha acesso à experiência de seleção de ativos incorporados no editor de modelo de  [!DNL Adobe Journey Optimizer] email. Para obter mais informações, consulte [Use [!DNL Assets Essentials] in [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

Em [!DNL Admin Console], esses dois tipos de acesso são representados por dois [!UICONTROL Product Profiles]. Para adicionar e remover membros de sua organização a qualquer um dos perfis, siga estas etapas:

1. Acesse [!DNL Admin Console] para sua organização, clique em **[!UICONTROL Products]** na barra superior, clique em **[!UICONTROL AEM Assets Essentials]** e em [!DNL Assets Essentials] ambiente. [!DNL Assets Essentials] O tem dois perfis de produto que representam o acesso de usuários regulares e de consumidores.

   ![Dois perfis para dois tipos de usuários](assets/adminconsole-user-types.png)

   *Figura: Dois perfis estão disponíveis para adicionar os dois tipos de usuários.*

1. Para adicionar um usuário a um grupo, clique no grupo, selecione **[!UICONTROL Add User]**, forneça os detalhes do usuário e clique em **[!UICONTROL Save]**. Quando você adiciona um usuário, ele recebe um convite por email para começar. Você pode desativar os convites por email nas configurações do perfil de produto em [!DNL Admin Console].

   ![Adicionar um usuário a  [!DNL Assets Essentials]](assets/adminconsole-add-user.png)

   *Figura: Adicione um usuário ao  [!DNL Assets Essentials] do  [!DNL Admin Console].*

1. Para remover um usuário de um grupo, clique no grupo, selecione um usuário existente e selecione **[!UICONTROL Remove User]**.

>[!TIP]
>
>Em [!DNL Admin Console], é possível gerenciar os usuários em massa usando arquivos CSV. Para saber mais, consulte [[!DNL Admin Console] documentação](https://helpx.adobe.com/enterprise/using/accounts.html).

## Exibir o status do serviço e os logs de acesso {#view-logs}

Após o provisionamento, os administradores implantam [!DNL Assets Essentials] apenas uma vez. Após a implantação inicial, o Adobe faz a manutenção e as atualizações do serviço. Os administradores podem usar a interface do usuário [!DNL Cloud Manager] para verificar o status do serviço e baixar os registros de acesso recentes.

1. Quando os usuários relatarem problemas, verifique o status do serviço de [!DNL Assets Essentials] na interface **[!UICONTROL Program Overview]**. Durante o funcionamento normal da solução, o status é `Running`. Se [!DNL Cloud Manager] exibir qualquer outro status, crie um tíquete de suporte na seção de suporte [!DNL Admin Console].

   ![O status de  [!DNL Assets Essentials] em  [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Figura: O status normal de  [!DNL Assets Essentials] no  [!DNL Cloud Manager] é  `Running`.*

1. Para baixar os logs de acesso recentes, clique no ícone ![options](assets/do-not-localize/options-ellipses-icon.png), selecione **[!UICONTROL Download Logs]** e siga as instruções na tela. Você pode auditar as solicitações de acesso HTTPS usando os logs.

   ![ Opção para baixar os logs de acesso](assets/cloudmanager-download-logs.png)

   *Figura: Opção para baixar os logs de acesso.*

>[!MORELIKETHIS]
>
>* [[!DNL Admin Console] ajuda](https://helpx.adobe.com/enterprise/using/admin-console.html)
>* [[!DNL Cloud Manager] ajuda](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=pt-BR)
>* [Documentação do Adobe Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html)
>* [Notas de versão](release-notes.md)
* [Comece a usar [!DNL Assets Essentials]](get-started.md)

