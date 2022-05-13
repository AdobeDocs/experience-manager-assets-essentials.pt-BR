---
title: Notas de versão
description: Notas de versão e problemas conhecidos do [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 7c4bc88e2110ff1dd7442af303bdd2c586ba5a6f
workflow-type: tm+mt
source-wordcount: '786'
ht-degree: 69%

---

# Notas de versão do [!DNL Assets Essentials] {#release-notes}

A versão atual do [!DNL Assets Essentials] foi lançado em 12 de maio de 2022. Esta versão fornece:

* [!DNL Assets Essentials] agora suporta [criação de coleções](manage-collections.md). Uma coleção é um conjunto de ativos no Experience Manager Assets Essentials. Use coleções para compartilhar ativos entre usuários. Diferente de pastas, uma coleção pode incluir ativos de locais diferentes.

* O Assets Essentials agora também permite [adicionar filtros personalizados](search.md#custom-filters) à interface do usuário. Em seguida, você pode aplicar esses filtros personalizados, além dos filtros padrão para refinar seus resultados de pesquisa.

* O Assets Essentials agora permite [definir status](manage-organize.md#set-asset-status) em ativos disponíveis no repositório. Defina um status de ativo para melhor administrar e gerenciar o consumo downstream de ativos digitais.

* Aprimoramentos e correções de erros com base no feedback do cliente.

## Modo incógnito no Chrome {#incognito-mode}

Com esta versão, estamos otimizando o desempenho do delivery da interface do usuário e os recursos específicos no Assets Essentials - comentários em ativos e edição de imagens - dependem do armazenamento local do navegador e da ativação de cookies de terceiros. O modo incógnito no navegador da Web Chrome bloqueia cookies de terceiros por padrão - os usuários têm várias opções para continuar a acessar todos os recursos:

* Use os perfis do Chrome em vez do modo Incógnito, quando o usuário precisar separar as sessões do navegador

* Desligue o `Block third-party cookies` na tela do modo Incógnito no Chrome

## Problemas conhecidos {#known-issues}

A lista de problemas conhecidos do [!DNL Assets Essentials] é revisada e atualizada continuamente:

* Não é possível filtrar ativos usando a variável `No Status` status do ativo.

* Não é possível procurar ou procurar um ativo com uma `Expired` status. Você só pode acessar o ativo usando um deep link ou URL.

* O Assets Essentials não oferece suporte à criação de coleções privadas.

Se você encontrar problemas ou quiser fazer solicitações de aprimoramento, [forneça feedback](#provide-feedback) à equipe.

## Versões anteriores {#past-release}

### 2022.2.0 {#march-2022}

[!DNL Assets Essentials] O foi lançado em 9 de março de 2022, com as seguintes atualizações:

* O [!DNL Assets Essentials] agora permite [gerar um link e compartilhar ativos com os participantes externos](share-links-for-assets.md), que não têm acesso ao aplicativo do [!DNL Assets Essentials]. Você pode definir uma data de expiração para o link e, em seguida, compartilhá-la com outras pessoas usando o método de comunicação preferido, como email ou serviços de mensagens. Os recipients do link podem visualizar ativos e baixá-los.

* O [!DNL Assets Essentials] agora inclui [um perfil de administrador de produto](deploy-administer.md#add-users-to-essentials) no Admin Console, além dos perfis de produtos do usuário regular e do consumidor existentes. Agora, um administrador pode atribuir outros usuários ao perfil de administrador de produto.

* O Assets Essentials agora permite que os administradores [gerenciem os níveis de acesso para pastas disponíveis no repositório](manage-permissions.md). Como administrador, você pode criar grupos de usuários e atribuir permissões a esses grupos para gerenciar níveis de acesso. Você também pode delegar os privilégios de gerenciamento de permissões a grupos de usuários no nível da pasta.

* Aprimoramentos e correções de erros com base no feedback do cliente.

Além disso, a extensão [!DNL Adobe Asset Link] para Creative Cloud (Photoshop, Illustrator e InDesign), recebeu uma [nova versão (3.2)](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html), com melhorias de desempenho no tempo de inicialização do painel e na velocidade de download.


### Versão 2022.1.0 {#january-2022}

O [!DNL Assets Essentials] foi lançado em 03 de fevereiro de 2022 com as seguintes atualizações:

* Melhorias de desempenho para a operação [!UICONTROL Criar pasta]. <!-- CQ-4338818 -->

### Versão 2021.11.0 {#november-2021}

O [!DNL Assets Essentials] foi lançado em 16 de dezembro de 2021 com as seguintes atualizações:

* A Adobe implanta o Assets Essentials automaticamente após concluir o processo de provisionamento. Os administradores não precisam executar etapas adicionais para implantar o Assets Essentials usando a interface do usuário do [!DNL Cloud Manager]. Essa implantação automática estará disponível para ambientes provisionados após 6 de janeiro de 2022.
* Novas versões de plug-ins da Creative Cloud que funcionam com o Assets Essentials estão disponíveis no Adobe Exchange - [Adobe Asset Link para Adobe XD v 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) e [Adobe Asset Link para Photoshop / InDesign / Illustrator v 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* Várias correções de erros e aprimoramentos de produtos, incluindo problemas conhecidos anteriores (as pastas agora são exibidas corretamente na árvore de navegação esquerda após o upload<!-- CQ-4337638 -->, arrastar e soltar upload permite que o usuário selecione a pasta atual ou qualquer subpasta ao soltar para fazer upload<!-- CQ-4327753 -->).

### Versão 2021.8.0 {#august2021}

O [!DNL Assets Essentials] 2021.8.0 foi lançado em 30 de agosto de 2021, com as seguintes atualizações:

* Integrações com o [!DNL Adobe Workfront] que permite que usuários do [!DNL Workfront] gerenciam os ativos digitais no contexto do gerenciamento do próprio trabalho. Para obter mais informações, consulte [integrações com outras soluções da Adobe](/help/integration.md).

### Versão 2021.7.0 {#july2021}

O [!DNL Assets Essentials] 2021.7.0 foi lançado em 29 de julho de 2021, com as seguintes atualizações:

* Você pode criar e gerenciar formulários de metadados personalizados que serão usados para exibir propriedades de metadados aos usuários na tela de detalhes do ativo, por meio da opção [!UICONTROL Formulários de metadados] em [!DNL Settings]. Consulte [formulários de metadados](metadata.md#metadata-forms).
* Várias correções de erros e aprimoramentos de produtos, incluindo melhor desempenho ao fazer upload de uma pasta aninhada com muitas subpastas.

### Versão 2021.6.0 {#june2021}

A primeira versão do [!DNL Assets Essentials], disponibilizada em 21 de junho de 2021, oferece recursos leves de gerenciamento de ativos. Ela oferece suporte aos seguintes principais recursos e operações de CRUD (criar, ler, atualizar e excluir):

* Faça upload e adicione ativos, inclusive pastas aninhadas. Visualize os ativos e as versões.
* Pesquisa de texto completo, filtros de pesquisa aprimorados e pesquisas salvas para detecção rápida de ativos.
* Operações básicas de gerenciamento de ativos, como atualizar, excluir, baixar e gerenciar metadados.
* O [!DNL Assets Essentials] está disponível a usuários do [!DNL Adobe Journey Optimizer] para gerenciar os ativos ao criar mensagens. Para obter mais informações, consulte [integrações com outras soluções da Adobe](/help/integration.md).
