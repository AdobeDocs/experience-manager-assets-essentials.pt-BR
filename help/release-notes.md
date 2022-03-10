---
title: Notas de versão
description: Notas de versão e problemas conhecidos de [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 4cced7aba92fd0f041842e5ef78d02f0a4f7ffe0
workflow-type: tm+mt
source-wordcount: '549'
ht-degree: 0%

---

# Notas de versão de [!DNL Assets Essentials] {#release-notes}

A versão atual do [!DNL Assets Essentials] foi lançado em 9 de março de 2022. Esta versão fornece:

* [!DNL Assets Essentials] O agora permite [gerar um link e compartilhar ativos com os participantes externos](share-links-for-assets.md), que não têm acesso ao [!DNL Assets Essentials] aplicativo. Você pode definir uma data de expiração para o link e, em seguida, compartilhá-la com outras pessoas usando o método de comunicação preferido, como email ou serviços de mensagens. Os recipients do link podem visualizar ativos e baixá-los.

* O [!DNL Assets Essentials] agora inclui [um perfil de produto de administrador](deploy-administer.md#add-users-to-essentials) no Admin Console, além dos perfis de produtos do usuário regulares e do consumidor existentes. Um administrador agora pode atribuir outros usuários ao perfil de produto do administrador.

* O Assets Essentials agora permite que os administradores [gerenciar os níveis de acesso para pastas disponíveis no repositório](manage-permissions.md). Como administrador, você pode criar grupos de usuários e atribuir permissões a esses grupos para gerenciar níveis de acesso. Você também pode delegar os privilégios de gerenciamento de permissões a grupos de usuários no nível da pasta.

* Aprimoramentos e correções de erros com base no feedback do cliente.

Além disso, [!DNL Adobe Asset Link] extensão para Creative Cloud (Photoshop, Illustrator e InDesign) lançada como [nova versão 3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html), com melhorias de desempenho no tempo de inicialização do painel e na velocidade de download.


## Problemas conhecidos {#known-issues}

A lista de problemas conhecidos de [!DNL Assets Essentials] A oferta é revista e atualizada continuamente:

* Nenhum

Se você encontrar problemas ou até solicitações de aprimoramento, [fornecer feedback](#provide-feedback) à equipe.

## Versões anteriores {#past-release}

### Versão 2022.1.0 {#january-2022}

[!DNL Assets Essentials] O foi lançado em 30 de fevereiro de 2022 com as seguintes atualizações:

* Melhorias de desempenho para a [!UICONTROL Criar pasta] operação. <!-- CQ-4338818 -->

### Versão 2021.11.0 {#november-2021}

[!DNL Assets Essentials] O foi lançado em 16 de dezembro de 2021, com as seguintes atualizações:

* O Adobe implanta o Assets Essentials automaticamente após concluir o processo de provisionamento. Os administradores não precisam executar etapas adicionais para implantar o Assets Essentials usando [!DNL Cloud Manager] interface do usuário. Essa implantação automática estará disponível para ambientes provisionados após 6 de janeiro de 2022.
* Novas versões de plug-ins do Creative Cloud que funcionam com o Assets Essentials estão disponíveis no Adobe Exchange - [Adobe Asset Link para Adobe XD v 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) e [Adobe Asset Link para Photoshop / InDesign / Illustrator v 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* Vários bugfixes e aprimoramentos de produtos, incluindo problemas conhecidos anteriores (as pastas agora são exibidas corretamente na árvore de navegação esquerda após o upload<!-- CQ-4337638 -->, arrastar e soltar upload permite que o usuário selecione a pasta atual ou qualquer subpasta ao soltar para upload<!-- CQ-4327753 -->).

### Versão 2021.8.0 {#august2021}

[!DNL Assets Essentials] O 2021.8.0 foi lançado em 30 de agosto de 2021, com as seguintes atualizações:

* Integrações com [!DNL Adobe Workfront] que permite [!DNL Workfront] Os usuários do gerenciam seus ativos digitais no contexto do gerenciamento de seu trabalho. Para obter mais informações, consulte [integrações com outras soluções do Adobe](/help/integration.md).

### Versão 2021.7.0 {#july2021}

[!DNL Assets Essentials] O 2021.7.0 foi lançado em 29 de julho de 2021, com as seguintes atualizações:

* Você pode criar e gerenciar formulários de metadados personalizados a serem usados para exibir propriedades de metadados aos usuários na tela de detalhes do ativo em [!UICONTROL Forms de metadados] opção em [!DNL Settings]. Consulte [formulários de metadados](metadata.md#metadata-forms).
* Várias correções de erros e aprimoramentos de produtos, incluindo melhor desempenho ao fazer upload de uma pasta aninhada com muitas subpastas.

### Versão 2021.6.0 {#june2021}

A primeira versão do [!DNL Assets Essentials], disponibilizado em 21 de junho de 2021, oferece recursos leves de gerenciamento de ativos. Ele oferece suporte aos seguintes principais recursos e operações de CRUD (criar, ler, atualizar e excluir):

* Faça upload e adicione ativos, incluindo pastas aninhadas. Visualize os ativos e as versões.
* Pesquisa de texto completo, filtros de pesquisa aprimorados e pesquisas salvas para detecção rápida de ativos.
* Operações básicas de gerenciamento de ativos como atualizar, excluir, baixar e gerenciar metadados.
* [!DNL Assets Essentials] está disponível para [!DNL Adobe Journey Optimizer] usuários para gerenciar os ativos ao criar mensagens. Para obter mais informações, consulte [integrações com outras soluções do Adobe](/help/integration.md).
