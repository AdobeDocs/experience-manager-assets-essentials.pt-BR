---
title: Administrar o Experience Manager Assets Essentials
description: Configure o acesso ao aplicativo do Assets Essentials usando o Admin Console e gerencie as tarefas que podem ser executadas após fazer logon no aplicativo Assets Essentials.
source-git-commit: 1f01dd340f79d1c2d9748232c2b1a589ae7f8545
workflow-type: tm+mt
source-wordcount: '1399'
ht-degree: 53%

---


# Administrar o Experience Manager Assets Essentials {#administer-assets-essentials}

![Preferência para alternar entre temas escuro e claro](assets/cce-assets.png)

## Objetivo

* **Público**: Administradores do Assets Essentials

* **Objetivo**: Configure o acesso ao aplicativo do Assets Essentials usando o Admin Console e gerencie as tarefas que podem ser executadas após fazer logon no aplicativo Assets Essentials.

## Visão geral {#overview}


O [!DNL Adobe Experience Manager Assets Essentials] é provisionado pela Adobe para seus clientes. Como parte do provisionamento, o [!DNL Assets Essentials] é adicionado à organização de um cliente no [!DNL Adobe Admin Console]. Os administradores usam [!DNL Admin Console] para gerenciar direitos de usuário para [!DNL Assets Essentials] e atribuir administradores de aplicativos para configurar permissões e formulários de metadados no [!DNL Assets Essentials].

O diagrama do fluxo de dados a seguir ilustra a sequência de tarefas que um administrador deve executar para configurar e gerenciar o Assets Essentials:

![Fluxo de administração do Assets Essentials](assets/permissions-management-cce-next.svg)

## Acesse o Admin Console {#access-admin-console}

Depois que a solução Assets Essentials é provisionada, o administrador recebe um email da Adobe. O email contém uma mensagem de boas-vindas e um link para começar a trabalhar. Além disso, a Adobe inicia o processo de implantação do Assets Essentials automaticamente. Esse processo leva uma hora para ser concluído.

No link do email, acesse e faça logon no [Admin Console](https://adminconsole.adobe.com). Se você tiver acesso de administrador a mais de uma conta da organização, selecione a organização apropriada ou alterne para ela usando a [seletor de organização](https://helpx.adobe.com/br/enterprise/using/admin-console.html). Quando o processo de implantação automática é concluído, o cartão de produto do [!DNL AEM Assets Essentials] fica visível no [!DNL Admin Console].

![Implantação do Assets Essentials](assets/admin-console-cards.png)

## Gerenciar tarefas do Admin Console {#manage-admin-console-tasks}

Execute as seguintes tarefas no Admin Console:

* [Adicionar usuários aos perfis de produtos](#add-users-to-product-profiles)

* [Adicionar grupos de usuários](#add-user-groups)

* [Adicionar usuários aos grupos](#add-users-to-user-groups)

### Adicionar usuários aos perfis de produtos {#add-users-to-product-profiles}

Adicione usuários aos perfis de produtos para que eles tenham acesso ao aplicativo do Assets Essentials.

Para adicionar usuários aos perfis de produtos:

1. Acesso [Admin Console](https://adminconsole.adobe.com) para sua organização, clique em **[!UICONTROL Produtos]** na barra superior, clique em **[!UICONTROL AEM Assets Essentials]** e, em seguida, clique na instância para [!DNL Assets Essentials]. O nome da instância pode ser diferente do da captura de tela abaixo.
   >[!NOTE]
   >
   >[!DNL Cloud Manager] A instância é para uso administrativo especial, como verificar o status do serviço e obter acesso aos logs de serviço, e não pode ser usada para adicionar usuários ao produto. Para obter mais informações, consulte [guia de administração](deploy-administer.md#view-service-status-and-access-logs-view-logs).

   ![Perfil de administrador do Admin Console](assets/assets-essentials-instance.png)

   O [!DNL Assets Essentials] tem três perfis de produto que representam o acesso para administradores, usuários comuns e consumidores.

   ![Perfil de administrador do Admin Console](assets/admin-console-admin-profile.png)

1. Para adicionar um usuário ao produto, clique em um dos três perfis de produto do Assets Essentials, selecione **[!UICONTROL Adicionar usuário]**, forneça os detalhes do usuário e clique em **[!UICONTROL Salvar]**.

   ![Adicionar perfil de administrador de usuários](assets/add-users-admin-profile.png)

   Ao adicionar um usuário, ele recebe um convite por email para começar. Você pode desativar os convites por email nas configurações do perfil de produto no [!DNL Admin Console].

1. Para remover um usuário de um grupo, clique no grupo, selecione um usuário existente e selecione **[!UICONTROL Remover usuário]**.

   >[!NOTE]
   >
   >Você deve adicionar um usuário ao perfil de produto Administrador do Assets Essentials no Admin Console para que ele execute tarefas administrativas no aplicativo Assets Essentials. Essas tarefas incluem [Criar estrutura de pastas](#create-folder-structure), [Gerenciar permissões para pastas](#manage-permissions-for-folders)e [Configurar o Forms de metadados](#metadata-forms).

### Adicionar grupos de usuários {#add-user-groups}

Crie grupos de usuários e atribua seus usuários aos grupos de usuários. Esses grupos de usuários estarão disponíveis no aplicativo Assets Essentials para definir permissões em pastas.

Você pode adicionar usuários a grupos de usuários (1) e adicionar [usuários a Perfis de produto do Assets Essentials (2)](#add-admin-users). No entanto, não é possível adicionar grupos de usuários diretamente aos Perfis de produto do Assets Essentials (3).

![Adicionar usuários a grupos e perfis de produtos](assets/user-groups-product-profiles.svg)

Para obter informações sobre como gerenciar grupos de usuários, consulte `Create user groups` e `Edit user groups`, disponíveis em [Gerenciar grupos de usuários](https://helpx.adobe.com/br/enterprise/using/user-groups.html).

>[!NOTE]
>
>Se o Admin Console estiver configurado para usar um sistema externo para gerenciar atribuições de usuários/grupos, como conectores do Azure ou do Google, ferramenta de sincronização de usuários ou API REST do User Management, seus grupos e atribuições de usuários serão configurados automaticamente. Para obter mais informações, consulte [Usuários do Adobe Admin Console](https://helpx.adobe.com/br/enterprise/using/users.html).


### Adicionar usuários aos grupos {#add-users-to-user-groups}

Depois de criar grupos de usuários, você pode começar a adicionar usuários aos grupos de usuários.

Para obter informações sobre como gerenciar a adição de usuários a grupos de usuários, consulte `Add users to groups`, disponível em [Gerenciar grupos de usuários](https://helpx.adobe.com/br/enterprise/using/user-groups.html#add-users-to-groups).

## Gerenciar tarefas de administração do Assets Essentials {#manage-assets-essentials-tasks}

Depois de executar as tarefas do Admin Console, você pode executar as seguintes tarefas de administração no aplicativo Assets Essentials:

* [Criar estrutura de pastas](#create-folder-structure)

* [Gerenciar permissões para pastas](#manage-permissions-for-folders)

* [Configurar o Forms de metadados](#metadata-forms)

>[!NOTE]
>
>Para gerenciar essas tarefas, especialmente o gerenciamento de permissões, o usuário deve ter direitos de administração de aplicativos; ele precisa ser adicionado ao [Perfil de produto do Administrador Assets Essentials](#add-users-to-product-profiles).


### Criar estrutura de pastas {#create-folder-structure}

Você pode usar os seguintes métodos para criar uma estrutura de pastas no repositório do Assets Essentials:

* Clique na opção **[!UICONTROL Criar pasta]**, disponível na barra de ferramentas, para criar uma pasta vazia.

* Clique na opção **[!UICONTROL Adicionar ativos]**, disponível na barra de ferramentas, para [fazer upload de uma estrutura de pastas disponível em seu computador local](add-delete.md).

Crie uma estrutura de pastas que funcione bem com os objetivos de negócio da organização. Se estiver carregando uma estrutura de pastas existente no repositório do Assets Essentials, você deverá revisar a estrutura. Para obter mais informações, consulte [Práticas recomendadas para o gerenciamento eficaz de permissões](permission-management-best-practices.md).

Considere os seguintes pontos quando começar a planejar a criação de uma estrutura de pastas no repositório do Assets Essentials:

* Governança futura: as pastas controladas pelos administradores e as pastas [delegadas por permissões a outros usuários como proprietários](manage-permissions.md##manage-permissions-folders).

* Escalável: a estrutura de pastas deve atender às necessidades futuras de sua organização e deve ser facilmente escalável.

* Tamanho: uma pasta não deve conter muitos ativos. Isso pode levar a problemas de usabilidade, tornando-a difícil de gerenciar.

* Intuitiva: a estrutura de pastas deve ser fácil de navegar e intuitiva para os usuários finais. Os usuários devem ser capazes de identificar facilmente onde fazer upload de um novo ativo na estrutura de pastas.

Há vários tipos possíveis de estruturas de pastas que podem ser usados na sua organização. Veja a seguir alguns exemplos de estruturas de pastas típicas:

![Estruturas de pastas típicas](assets/folder-structure.svg)

### Gerenciar permissões para pastas {#manage-permissions-for-folders}

O Assets Essentials permite que os administradores gerenciem os níveis de acesso para pastas disponíveis no repositório. Como administrador, você pode criar grupos de usuários e atribuir permissões a esses grupos para gerenciar níveis de acesso. Você também pode delegar os privilégios de gerenciamento de permissões a grupos de usuários no nível da pasta.

>[!VIDEO](https://video.tv.adobe.com/v/341104)

Para obter mais informações, consulte [Gerenciar permissões para pastas](manage-permissions.md).

### Configurar o Forms de metadados {#metadata-forms}

Por padrão, o Assets Essentials fornece vários campos de metadados padrão. As organizações têm necessidades adicionais de metadados e precisam de mais campos para adicionar metadados específicos de negócios. Os formulários de metadados permitem que as empresas adicionem campos de metadados personalizados à página [!UICONTROL Detalhes] de um ativo. Os metadados específicos de negócios melhoram a governança e a descoberta de ativos. É possível criar formulários do zero ou redefinir a finalidade de um formulário existente.

É possível configurar formulários de metadados para diferentes tipos de ativos (diferentes tipos de MIME). Use o mesmo nome de formulário como o tipo de MIME do arquivo. O Essentials corresponde automaticamente os ativos carregados do tipo MIME ao nome do formulário e atualiza os metadados dos ativos carregados com base nos campos de formulário.

Por exemplo, se um formulário de metadados for usado pelo nome `PDF` ou `pdf` existir, os documentos PDF carregados contêm campos de metadados, conforme definido no formulário.

O Assets Essentials usa a seguinte sequência para procurar nomes de formulário de metadados existentes para aplicar os campos de metadados aos ativos carregados de um tipo específico:

Subtipo MIME > tipo MIME > `default` formulário > Formulário pronto para uso

Por exemplo, se um formulário de metadados chamado `PDF` ou `pdf` existir, os documentos PDF carregados contêm campos de metadados conforme definidos no formulário. Se um formulário de metadados for usado pelo nome `PDF` ou `pdf` não existe, o Assets Essentials corresponde se houver um formulário de metadados pelo nome `application`. Se houver um formulário de metadados pelo nome `application`, os documentos PDF carregados contêm campos de metadados, conforme definido no formulário. Se o Assets Essentials ainda não encontrar um formulário de metadados correspondente, ele pesquisará a variável `default` formulário de metadados para aplicar campos de metadados definidos no formulário aos documentos PDF carregados. Se nenhuma dessas etapas funcionar, o Assets Essentials aplica campos de metadados definidos no formulário pronto para uso a todos os documentos PDF carregados.

>[!IMPORTANT]
>
>O novo formulário de metadados para um tipo de arquivo específico substitui completamente o formulário de metadados padrão que o [!DNL Assets Essentials] fornece. Se você excluir ou renomear um formulário de metadados, os campos de metadados padrão estarão disponíveis novamente para novos ativos.

>[!VIDEO](https://video.tv.adobe.com/v/341275)

Para obter mais informações sobre o Forms de metadados, consulte [Forms de metadados no Assets Essentials](metadata.md#metadata-forms).

## O que vem a seguir

Agora que você configurou e gerenciou o aplicativo Assets Essentials, [integrar aplicativos Creative Cloud com o aplicativo Experience Manager Assets Essentials](integrate-assets-essentials-creative-cloud.md).

