---
title: Como gerenciar permissões para pastas no AEM Assets Essentials?
description: O Assets Essentials permite que os administradores gerenciem os níveis de acesso para pastas disponíveis no repositório. Crie grupos de usuários e atribua permissões a esses grupos para gerenciar níveis de acesso. Como administrador, você também pode delegar os privilégios de gerenciamento de permissões a grupos de usuários no nível da pasta.
exl-id: 5ef01dbc-87c0-4013-9367-5da3774f4f20
source-git-commit: 94435a9fc17ab02c6872bb165a4cb697b56d5602
workflow-type: tm+mt
source-wordcount: '1580'
ht-degree: 0%

---

# Gerenciar permissões para pastas

O Assets Essentials permite que os administradores gerenciem os níveis de acesso para pastas disponíveis no repositório. Como administrador, você pode criar grupos de usuários e atribuir permissões a esses grupos para gerenciar níveis de acesso. Você também pode delegar os privilégios de gerenciamento de permissões a grupos de usuários no nível da pasta.

O diagrama de fluxo de dados a seguir ilustra a sequência de tarefas que você executa para configurar e gerenciar permissões em pastas disponíveis no repositório Assets Essentials:

![Opções da barra de ferramentas ao selecionar um ativo](assets/permissions-management-new.png)

## Antes de gerenciar permissões para pastas {#before-managing-permissions}

Antes de começar a gerenciar permissões para pastas no repositório Assets Essentials, você deve realizar determinadas tarefas, como adicionar administradores que podem criar uma estrutura de pastas lógica, criar grupos de usuários e gerenciar permissões de pastas para vários grupos de usuários.

### Adicionar administradores {#add-admin-users}

Adicione administradores para o aplicativo Assets Essentials para que eles possam gerenciar permissões de pastas para outros grupos de usuários.

Para adicionar administradores:

1. Acesso [Admin Console](https://adminconsole.adobe.com) para sua organização, clique em **[!UICONTROL Produtos]** na barra superior, clique em **[!UICONTROL AEM Assets Essentials]** e, em seguida, clique em [!DNL Assets Essentials] ambiente. [!DNL Assets Essentials] O tem três perfis de produto que representam o acesso de administradores, usuários regulares e consumidores.

   ![Perfil de administrador do Admin Console](assets/admin-console-admin-profile.png)

1. Para adicionar um usuário a um grupo, clique no grupo Administradores do Assets Essentials e selecione **[!UICONTROL Adicionar usuário]**, forneça os detalhes do usuário e clique em **[!UICONTROL Salvar]**.

   ![Adicionar perfil de administrador de usuários](assets/add-users-admin-profile.png)

   Quando você adiciona um usuário, ele recebe um convite por email para começar. Você pode desativar os convites por email nas configurações do perfil de produto em [!DNL Admin Console].

1. Para remover um usuário de um grupo, clique no grupo, selecione um usuário existente e selecione **[!UICONTROL Remover usuário]**.

### Adicionar grupos de usuários {#add-user-groups}

Crie grupos de usuários e atribua permissões a esses grupos para gerenciar os níveis de acesso às pastas no repositório do Assets Essentials. Em seguida, você pode atribuir seus usuários aos grupos de usuários.

![Adicionar usuários a grupos e perfis de produtos](assets/user-groups-product-profiles-updated.png)

Você pode adicionar usuários a grupos de usuários (1) e [usuários dos Perfis de produto do Assets Essentials (2)](#add-admin-users). No entanto, não é possível adicionar grupos de usuários diretamente aos Perfis de produto do Assets Essentials (3).

Para obter informações sobre como gerenciar grupos de usuários, consulte `Create user groups` e `Edit user groups` disponível em [Gerenciar grupos de usuários](https://helpx.adobe.com/enterprise/using/user-groups.html).

>[!NOTE]
>
>Se o Admin Console estiver configurado para usar um sistema externo para gerenciar atribuições de usuários/grupos, como conectores do Azure ou do Google, ferramenta de sincronização de usuários ou API do User Management Rest, seus grupos e atribuições de usuários serão configuradas automaticamente. Para obter mais informações, consulte [Usuários do Adobe Admin Console](https://helpx.adobe.com/enterprise/using/users.html).


### Adicionar usuários a grupos {#add-users-to-uesr-groups}

Depois de criar grupos de usuários, você pode começar a adicionar usuários aos grupos de usuários.

Para obter informações sobre como gerenciar a adição de usuários a grupos de usuários, consulte `Add users to groups` disponível em [Gerenciar grupos de usuários](https://helpx.adobe.com/in/enterprise/using/user-groups.html#add-users-to-groups).

### Criar estrutura de pastas {#create-folder-structure}

Você pode usar os seguintes métodos para criar uma estrutura de pastas no repositório do Assets Essentials:

* Clique no botão **[!UICONTROL Criar pasta]** opção disponível na barra de ferramentas para criar uma pasta vazia.

* Clique em **[!UICONTROL Adicionar ativos]** opção disponível na barra de ferramentas para [fazer upload de uma estrutura de pastas disponível em seu computador local](add-delete.md).

Crie uma estrutura de pastas que funcione bem com os objetivos de negócios da organização. Se estiver carregando uma estrutura de pastas existente no repositório do Assets Essentials, você deverá revisar a estrutura. Para obter mais informações, consulte [Práticas recomendadas para o gerenciamento eficaz de permissões](permission-management-best-practices.md).

## Gerenciar permissões em pastas {#manage-permissions-folders}

Você pode atribuir as seguintes permissões aos grupos de usuários ou usuários. O Adobe não recomenda atribuir permissões a usuários.

| Nome da permissão | Descrição |
|-----|------|
| Pode visualizar | <ul><li>Acesso de leitura para exibir e navegar pelas pastas </li><li>Visualizar ativos</li><li>Baixar ativos</li><li>Copiar ativos</li><li>Compartilhar links para ativos</li><ul> |
| Pode editar | <ul><li>Todos os privilégios disponíveis para as permissões Pode Visualizar </li><li>Criar pastas</li><li>Remover pastas</li><li>Renomear pastas</li><li>Criar ativos</li><li>Atualizar ativos</li><li>Remover ativos</li><li>Mover ativos</li><li>Renomear ativos</li><ul> |
| Proprietário | <ul><li>Todos os privilégios disponíveis para as permissões Pode editar</li><li>Gerenciar permissões em uma pasta e em suas subpastas</li>Essa permissão permite que os administradores deleguem os privilégios de administrador a outras pessoas para uma pasta e suas subpastas.<ul> |
| Negar acesso | Remova as permissões Pode visualizar, Pode editar e Proprietário de uma pasta e suas subpastas. |

**Permissões padrão**

Todos os usuários autenticados e que podem fazer logon no aplicativo Assets Essentials têm `Can Edit` permissões para o repositório do Assets Essentials inicialmente. O administrador pode ajustar as permissões padrão ao [editar permissões para todo o repositório Assets Essentials](#edit-permissions-entire-repository).

**Sequência para atribuir permissões de pasta a grupos de usuários**

Crie regras para atribuir permissões de pasta a grupos de usuários. A sequência usada para atribuir permissões a uma pasta é importante e decide o acesso disponível aos grupos de usuários e eventualmente aos usuários.

Por exemplo, se você atribuir a variável `Can View` permissões de uma pasta para um supergrupo e, em seguida, atribuir `Can Edit` Permissões para o subgrupo, somente os membros do subgrupo têm permissões de edição para a pasta. Os usuários do supergrupo têm acesso de visualização à pasta.

Se precisar fornecer permissões de edição ao `Marketing` somente para o departamento de marketing de sua organização e permissões de visualização para outras pessoas, atribua `Can View` permissões para super grupo `All Authenticated Users` e `Can Edit` permissões para seu subgrupo `Marketing`.

![Atribuir permissões](assets/permissions-management-groups-new.png)

**Herança da permissão**

O Assets Essentials usa a herança de permissão, que permite herdar as permissões definidas para a pasta pai na pasta filho. Por exemplo, se a pasta principal tiver `Can View` permissões para o `All Authenticated Users` e a pasta filho tiver `Can Edit` permissões para o `Marketing` grupo de usuários, permite que todos os usuários autenticados tenham permissões de exibição para a pasta filho e para o `Marketing` grupo de usuários para ter permissões de edição para a pasta filho. O `Marketing` o grupo de usuários tem permissões de edição para outros níveis de pastas na pasta filho (Marketing).

![Atribuir permissões](assets/permissions-inheritance-new.png)

>[!NOTE]
>
> Configurar um `Deny Access` permissões para um grupo em uma pasta de nível superior e, em seguida, restaurar o acesso (`Can view`, `Can edit` ou `Owner`) para esse grupo ou seu membro não é suportado. Use `Deny Access` com moderação.

### Adicionar permissões a grupos de usuários {#add-permissions}

Para atribuir permissões de grupo em pastas:

1. Selecione a pasta e clique em **[!UICONTROL Gerenciar permissões]**.

1. No **[!UICONTROL Gerenciar permissões]** , especifique o nome do grupo ou de um usuário no **[!UICONTROL Grupos e usuários]** campo.

1. Selecione o [nível de acesso](#manage-permissions-folders) do **[!UICONTROL Acesso]** lista suspensa.

1. Clique em **[!UICONTROL Adicionar]** para fazer uma alteração imediata nas permissões para o usuário ou grupo de usuários.

1. Repita as etapas 1 a 3 para adicionar mais regras ao **[!UICONTROL Gerenciar permissões]** caixa de diálogo.

   ![Adicionar permissões](assets/add-permissions.png)

   >[!NOTE]
   >
   > A ordem usada para atribuir permissões a uma pasta é importante e decide o acesso disponível aos grupos de usuários e, eventualmente, aos usuários adicionados aos grupos.

   Se você estiver gerenciando permissões para várias pastas, também poderá selecionar qualquer outra pasta no painel esquerdo e começar a gerenciar permissões para essa pasta.

1. Clique em **[!UICONTROL Fechar]**.

>[!CAUTION]
>
> É recomendável gerenciar permissões para grupos de usuários, em vez de usuários individuais. Definir a `Deny access` só há suporte para grupos de usuários, mas não para usuários individuais.

### Editar permissões atribuídas a grupos de usuários {#edit-permissions}

Para editar permissões atribuídas a grupos de usuários em pastas:

1. Selecione a pasta e clique em **[!UICONTROL Gerenciar permissões]**.

1. No **[!UICONTROL Gerenciar permissões]** , edite o [nível de acesso](#manage-permissions-folders) do **[!UICONTROL Acesso]** lista suspensa.

1. [Adicionar mais grupos de usuários ou usuários](#add-permissions) às regras de permissão existentes, se necessário.

1. Clique em X para remover as permissões atribuídas a um grupo de usuários.

### Editar permissões para todo o repositório Assets Essentials {#edit-permissions-entire-repository}

Um administrador de aplicativos pode editar permissões para todo o repositório Assets Essentials a partir de um padrão `Can Edit` para qualquer outro nível de acesso.

Para editar permissões para todo o repositório Assets Essentials:

1. Selecione qualquer pasta e clique em **[!UICONTROL Gerenciar permissões]**.

1. No **[!UICONTROL Gerenciar permissões]** , clique em **[!UICONTROL Todos os ativos]** no painel esquerdo.

1. [Editar as permissões](#edit-permissions) e feche a caixa de diálogo.

>[!NOTE]
>
>Um administrador não pode selecionar a variável `Deny Access` nível de permissão para todo o repositório Assets Essentials para garantir que os usuários tenham pelo menos acesso de leitura ao aplicativo. Da mesma forma, `All Authenticated Users` tenha pelo menos permissões de leitura no repositório, mesmo que o administrador remova explicitamente o `Can Edit` nas [!UICONTROL Gerenciar permissões] caixa de diálogo.


## Exemplos para o gerenciamento eficaz de permissões {#example-permission-management}

**Caso de uso**

* Todos os grupos Usuários Autenticados têm acesso de exibição ao repositório.
* Grupos de usuários específicos da equipe têm permissões de edição para suas próprias pastas específicas da função.
* A pasta legal não está disponível para visualização para qualquer usuário autenticado, exceto para a equipe Jurídica.

Crie os seguintes grupos de usuários no Admin Console:

* Equipe de marketing

* Equipe de aprovadores da marca

* Equipe de gerentes de projeto

* Equipe X do projeto

* Equipe Legal

O diagrama a seguir ilustra a hierarquia de pastas e as permissões atribuídas a cada grupo de usuários:
![Atribuir permissões](assets/use-case-permissions-management.png)

A seguir estão os níveis de acesso para todos os grupos de usuários na hierarquia de pastas:

* /Todos os ativos: Administrador modifica as permissões no nível raiz do padrão `Can Edit` para `Can View`. Todos os usuários podem exibir pastas e ativos, mas não podem editá-los.

* /marketing: Todos os usuários podem exibir as pastas e suas subpastas com base na herança da permissão. No entanto, o grupo de usuários da Equipe de marketing tem permissões de edição para a pasta.

* /marca: Todos os usuários podem exibir as pastas e suas subpastas com base na herança da permissão. No entanto, o grupo de usuários da Equipe de aprovadores da marca tem permissões de edição para a pasta.

* /projetos: Todos os usuários podem exibir as pastas e suas subpastas com base na herança da permissão. O grupo de usuários da Equipe de Gerentes de Projeto tem:

   * Editar permissões

   * Permissões do proprietário: Gerencie permissões em uma pasta e em suas subpastas.

* /projects/project-x: Todos os usuários podem exibir as pastas e suas subpastas. O grupo de usuários Equipe de gerentes de projeto tem permissões de edição e pode gerenciar permissões em uma pasta e em suas subpastas (permissões de proprietário). O grupo de usuários Equipe do Project X tem permissões de edição.

* /legal: Nenhum dos usuários pode acessar a pasta com base no `Deny Access` permissões para `All Authenticated Users` grupo. O grupo de usuários Equipe Jurídica tem permissões de edição.
