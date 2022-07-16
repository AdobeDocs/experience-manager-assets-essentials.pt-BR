---
title: Notas de versão
description: Notas de versão e problemas conhecidos do [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: f273e1e3c8a290e0beee0423da00c63013062c43
workflow-type: tm+mt
source-wordcount: '1117'
ht-degree: 80%

---

# Notas de versão do [!DNL Assets Essentials] {#release-notes}

A versão atual do [!DNL Assets Essentials] foi lançado em 14 de julho de 2022.

Esta versão fornece:

**Coleções inteligentes**

Salve os resultados da pesquisa como uma coleção inteligente para atualizar dinamicamente o conteúdo da coleção. Se houver ativos adicionados ao repositório do Assets Essentials que se encaixem nos critérios de pesquisa definidos ao [criação da coleção inteligente](manage-collections.md#create-smart-collection), o conteúdo da coleção inteligente é atualizado automaticamente.

**Notificações**

As notificações do Assets Essentials permitem [monitorar as operações executadas nos ativos ou pastas disponíveis no repositório](manage-notifications.md). É necessário selecionar e assinar o conteúdo para o qual as notificações são enviadas. Também é possível configurar as categorias para as quais as notificações são enviadas.

**Relatório**

Os relatórios de ativos permitem que os administradores avaliem a atividade do usuário no Adobe Experience Manager Assets Essentials. Os relatórios e o painel de estatísticas ao vivo fornecem informações úteis sobre como os usuários interagem com ativos disponíveis na implantação. [Use as informações nos relatórios](manage-reports.md) derivar métricas de sucesso importantes para medir a adoção de Ativos na empresa e por clientes.

Visualize relatórios de download de ativos e o módulo do painel de estatísticas ao vivo para ver quais ativos estão sendo baixados e a frequência de downloads.

**Aprimoramentos com base no feedback dos clientes**

Aprimoramentos e correções de erros com base no feedback do cliente.


## Problemas conhecidos {#known-issues}

A lista de problemas conhecidos do [!DNL Assets Essentials] é revisada e atualizada continuamente:

<!--

* Assets Essentials does not support creating Private collections.

-->


* O Assets Essentials não oferece suporte à edição de uma coleção inteligente.

* As coleções privadas estão disponíveis para o criador e para os usuários com privilégios de administrador. Como administrador, não é possível delegar as permissões para acessar a coleção a outros usuários.

Se você encontrar problemas ou quiser fazer solicitações de aprimoramento, [forneça feedback](#provide-feedback) à equipe.

## Versões anteriores {#past-release}

### 2022.5.0 {#may-2022}

A versão atual do [!DNL Assets Essentials] foi lançada em 16 de junho de 2022.

Esta versão fornece:

**Aprimoramentos no status do ativo**

* O Assets Essentials agora permite [definir uma data de expiração para um ativo](manage-organize.md#set-asset-status). Além disso, você pode [filtrar ativos](search.md#refine-search-results) com base no status `Expired` do ativo e em um intervalo de datas de expiração.

* Agora é possível visualizar o indicador de status do ativo de todos os ativos disponíveis na Lixeira. Assim, você pode decidir se deve restaurar um ativo com base em seu status.

**Aprimoramentos nos filtros de pesquisa**

* O Assets Essentials agora permite [filtrar ativos](search.md#refine-search-results) usando o status `No Status` do ativo.

<!--

* Assets Essentials now supports [using a wildcard operator (*) while using custom filters](search.md#custom-filters) to enable Assets Essentials to display assets in the results that partially match the search criteria.

-->

**Aprimoramentos nas coleções**

<!--

* Assets Essentials now enables you to [create Private collections](manage-collections.md#create-collection).

-->

* O Assets Essentials agora permite fazer o [download de uma coleção](manage-collections.md).

* Agora é possível editar o campo de metadados Descrição de uma coleção.

**Aprimoramentos na documentação**

* Uma nova versão da [documentação de visão geral do Assets Essentials](introduction.md) agora está disponível.

**Aprimoramentos com base no feedback dos clientes**

* Aprimoramentos e correções de erros com base no feedback do cliente.

### 2022.4.0 {#april-2022}

A versão atual do [!DNL Assets Essentials] foi lançada em 12 de maio de 2022. Esta versão fornece:

* O [!DNL Assets Essentials] agora permite a [criação de coleções](manage-collections.md). Uma coleção é um conjunto de ativos no Experience Manager Assets Essentials. Use coleções para compartilhar ativos entre usuários. Diferente de pastas, uma coleção pode incluir ativos de locais diferentes.

* O Assets Essentials agora também permite [adicionar filtros personalizados](search.md#custom-filters) à interface. É possível aplicar esses filtros personalizados além dos filtros padrão para refinar os resultados da pesquisa.

* O Assets Essentials agora permite [definir status](manage-organize.md#set-asset-status) em ativos disponíveis no repositório. Defina um status de ativo para melhor administrar e gerenciar o consumo downstream de ativos digitais.

* Aprimoramentos e correções de erros com base no feedback do cliente.

#### Modo incógnito no Chrome {#incognito-mode}

Com esta versão, estamos otimizando o desempenho do delivery da interface. Recursos específicos no Assets Essentials - comentários em ativos e edição de imagens - dependem do armazenamento local do navegador e da ativação de cookies de terceiros. O modo incógnito no navegador Chrome bloqueia cookies de terceiros por padrão. Os usuários têm várias opções para continuar a acessar todos os recursos:

* Uso dos perfis do Chrome em vez do modo Incógnito, quando o usuário precisar separar as sessões do navegador

* Desativação de `Block third-party cookies` na tela do modo Incógnito no Chrome

### 2022.2.0 {#march-2022}

O [!DNL Assets Essentials] foi lançado em 9 de março de 2022 com as seguintes atualizações:

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
